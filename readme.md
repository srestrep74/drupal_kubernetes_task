# Tópicos Especiales en Telemática: Proyecto 2
### Estudiantes:
- Luisa María Álvarez García, lmalvarez8@eafit.edu.co
- Juan Manuel Gómez Piedrahita, jmgomezp@eafit.edu.co
- Miguel Ángel Hoyos Velázquez, mahoyosv@eafit.edu.co
- Santiago Neusa Ruiz, sneusar@eafit.edu.co
- Sebastián Restrepo Ortiz, srestrep74@eafit.edu.co

### Profesor:
- Edwin Nelson Montoya Múnera, emontoya@eafit.edu.co

# 1. Descripción del proyecto
El Proyecto 2 consiste en la implementación de una aplicación web utilizando Drupal, que será desplegada en un clúster de Kubernetes en la nube. Además, se implementarán diferentes servicios para cumplir con los requisitos del proyecto, como un motor de base de datos externo, un servidor de archivos, una capa de acceso al clúster (Ingress) y un servidor de almacenamiento de archivos.

### Aspectos cumplidos
- Desplegar un clúster de k8s en la nube.
- Utilizar un motor de base de datos externo.
- Montar un servidor NFS para almacenar los archivos.
- Implementar una capa de acceso al clúster (Ingress)
- Emplear diferentes máquinas virtuales tipo EC2 en AWS
- Instalar el clúster en por lo menos 3 máquinas virtuales
- Cumplir con alta disponibilidad en los servicios de base de datos y archivos

### Aspectos no cumplidos
- Ninguno. Todos los aspectos fueron cumplidos satisfactoriamente.

# 2. Diagramas
- Diagrama de arquitectura

# 3. Ambiente de desarrollo
## 3.1. Detalles técnicos
Descripción y como se configura los parámetros del proyecto (ej: ip, puertos, conexión a bases de datos, variables de ambiente, parámetros, etc)

## 3.2. Compilación y ejecución
- Recuerde tener instalado kubectl y mysql en su máquina.
- Seguir las instrucciones del tutorial para la creación de clústers con microk8s.
- Git clone del repositorio.
```bash
git clone https://github.com/srestrep74/drupal_kubernetes_task.git
```
- Ejecutar el siguiente comando para desplegar los servicios.
```bash
cd drupal_kubernetes_task
./kuztomization.yaml
```

# 4. Resultados


# 5. Referencias
- [The simplest way to get K8s anywhere](https://microk8s.io/)
- [Create a MicroK8s cluster](https://microk8s.io/docs/clustering)
- [Configuring MySQL Instances for High Availability](https://docs.vmware.com/en/VMware-SQL-with-MySQL-for-Kubernetes/1.10/vmware-mysql-k8s/high-availability.html)
- [Deploying Drupal with MySQL database on Amazon EKS cluster using Amazon EFS](https://medium.com/@srank2000/deploying-drupal-with-mysql-database-on-amazon-eks-cluster-using-amazon-efs-150b6c36e183)