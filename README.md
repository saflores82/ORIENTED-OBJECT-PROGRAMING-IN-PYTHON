# ORIENTED-OBJECT-PROGRAMING-IN-PYTHON
ORIENTED OBJECT PROGRAMING IN PYTHON (FLASK)

PASOS

1-Crear una EC2 en AWS

Crear la clave para enlazar al git en la ec2

ssh-keygen -t ed25519 -C "your_email@example.com"

INTRO x 4

2-Instalar git

sudo yum update -y

sudo yum install git -y

git –versión

3-Hacer el git clone con el SSH

Debemos ir al git en Deploy keys e introducir la clave del archivo 

/home/ec2-user/.ssh/ id_ed25519.pub

cat id_ed25519.pub

Recordar marcar el CHECK de Allow write Access y pulsar el botón Add Key

Después vamos a Codes y copiamos el SSH

Vamos a la ec2 y hacemos el git clone [clave SSH]

4- Instalar pip y Flask (En la raíz del poyecto)

sudo yum install python3-pip -y

sudo pip3 install Flask

5-Ejecuta tu aplicación Flask (en la raíz del proyecto)

python3 app.py 

# Oriented Object Programming in Python (Flask)

## Pasos

1. **Crear una EC2 en AWS**

   - Crea la clave para enlazar al git en la EC2:

     ```sh
     ssh-keygen -t ed25519 -C "your_email@example.com"
     ```

   - **INTRO x 4**

2. **Instalar git**

   ```sh
   sudo yum update -y
   sudo yum install git -y
   git --version
