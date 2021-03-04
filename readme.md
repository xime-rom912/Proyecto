# Odyssey-Space

Este proyecto es un juego de decisiones en el cual tendras que peliar por ti vida hasta llegar al final

## Empezando

void g_over(){
    system("cls");
    system("color 0C");
    cout<<"                          GAME OVER";
}
/**
*@brief En esta función se desarrolla la trama en la armeria.
*@param no recibe parámetros
*@return retorna void
*/
void armeria(){
    system("cls");
    carac.puntos += 40;
    cout<<"Sales del cuartel armado hasta las chanclas"
        <<"\nQue decides?"
        <<"\n1.Subes a tu nave" << "\n2.Subes a la nave alienigena"
        << "\n\nTu desicion: ";
    acceso = ValidarEntrada();
    if (acceso == 1) {
        system("cls");
        carac.puntos -= 90;
        cout<<"Te diriges a la base, descubren tu nave, abren fuego y mueres"
            <<"\n\n-Presiona cualquier tecla para seguir-"<<endl;
        if(getch())
            g_over();
    }
    else {
        nave_alienigena();
    }
}

### Prerequisitos

Instalar un IDE para C++

### Instalacion

Solo se necesita abrir el codigo fuente con el IDE elegido o ejecutar el archivo exe

## Corriendo la prueba

Mientras ejecutamos el programa no se encontro ningun error, la prueba salio bien

### Desglosando la prueba

Para checarla se utilizaron entradas para ver si se rompia, todo salio correcto gracias a las validaciones

### Y prueba de estilo de codificacion 



## Despliegue

Solo tiene que ejecutarse el archivo exe o abrir el codigo fuente para generarlo

## Construido por

* [CodeBlocks]

## Contribuciones

Sin contribuciones exteriores

## Versiones

Version 1.0.0.1

## Autores

* **Javier Tarango Fierro**
* **Daniel Villegas Terrazas**
* **Ricardo Corral Sanchez**
* **Luis Fernandez Reza**
* **Ximena Romero Chavez**

## Licencia

Este proyexto no tiene licencia

## Expresiones de gratitud

* Fue un proyecyo para nuestra clase de Conceptos Avanzados de Programacion
* Simpre nos gustaron los videojuegos de decisiones
