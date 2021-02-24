
# Códigoel video  Sidbar Menu using HTML & CSS

### Medios de contacto del autor del video:

+ https://youtu.be/V0O4pY2xX10

### Lessons Learned: Menu con HTML y CSS sin JavaScript.

0.- Entre <body> y div .sidebar, input checkbox:

	<input type="checkbox" id="check">
  <label for="check">
    <i class="fas fa-bars" id="btn"></i>
    <i class="fas fa-times" id="cancel"></i>
  </label>

1.- Crear div .sidebar, con:

			<header>
				ul
					li > a > i 

2.- Se coloca .sidebar con:

			.sidebar {
				position: fixed;
				left: 0;
				width: 250px;
				height: 100%;
				background-color: #042331;
			}

3.- CSS para .sidebar header y .sidebar ul a

4.- El aspecto de botón "alto" se da con line-height y no con padding.

5.- Efecto de mover botón en hover, se hace al agregar 10px a padding-left existente.


6.- El efecto de aparecer el menu se logra:

		6.1 Al inicio .sidebar se posiciona cn left: -250px

		6.2.- Al hacer click en checkbox, se reposiciona el elemento en:

				#check:checked~.sidebar {
					left: 0;
				}

_Febrero 2021 Omar Rosas_