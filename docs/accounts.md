# Verificar las identidades

Este laboratorio utiliza dos cuentas del mismo propietario: `tears-mysthrala` y `tearsmysthrala-ci`. No representa una revision independiente entre personas.

- En la terminal, `gh api user --jq .login` identifica la cuenta que ejecuta las peticiones.
- `gh auth status` enumera las cuentas guardadas en GitHub CLI; no enumera las sesiones del navegador.
- En la web, el menu del avatar permite comprobar la identidad activa antes de publicar o fusionar.
- Una organizacion no es una segunda cuenta personal.
- No copie cookies ni tokens del navegador a scripts o documentos.

Una sesion web iniciada no autentica automaticamente GitHub CLI. Este ejercicio mantiene la cuenta principal en CLI y la cuenta de pruebas en Chrome.
