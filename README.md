# Ayudantia-mate-3
Repositorio dedicado a la resolución de ejercicios y material didáctico para la materia **Matemática 3**. Este proyecto utiliza LaTeX para generar documentos técnicos.

## 📂 Estructura del Proyecto

* `main.tex`: Archivo principal que compila todo el documento.
* `tp.tex`: Archivo que despues podria ser incluido directamente al proyecto principal (habria que revisar tema paquetes)
* `ejercicios/`: Carpeta que contiene los archivos individuales (`.tex`) por ejercicio para facilitar el trabajo colaborativo.
* `main.pdf`: Versión compilada más reciente.

## 🛠️ Requisitos para colaborar

Para que el proyecto compile correctamente sin errores, asegúrense de tener instalado:

1.  **MiKTeX:** Configurado en "Always install missing packages on-the-fly".
2.  **Perl:** (Strawberry Perl recomendado) necesario para ejecutar `latexmk`.
3.  **VS Code:** Con la extensión **LaTeX Workshop**.

## 🚀 Instrucciones

1.  Clonar el repositorio.
2.  Para editar un ejercicio, modificar el archivo correspondiente dentro de la carpeta `/ejercicios`.
3.  Para visualizar los cambios generales, compilar desde `main.tex`.

---
*Nota: Este repositorio utiliza un archivo `.gitignore` para mantener el espacio de trabajo limpio de archivos auxiliares de compilación.*
