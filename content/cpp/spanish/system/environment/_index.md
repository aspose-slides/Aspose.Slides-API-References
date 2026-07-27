---
title: Environment
second_title: Referencia de API de Aspose.Slides para C++
description: Servicios de Environment. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio.
type: docs
weight: 1626
url: /es/system/environment/
---
## Estructura Environment

[Environment](./) servicios. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio.

```cpp
class Environment
```

## Métodos

| Método | Descripción |
| --- | --- |
| static void [Exit](./exit/)(int) | Finaliza el proceso actual y devuelve el código de salida especificado al sistema operativo. |
| static [String](../string/) [ExpandEnvironmentVariables](./expandenvironmentvariables/)(const [String](../string/)\&) | Reemplaza los nombres de las variables de entorno encontrados en la cadena especificada con los valores de esas variables y devuelve la cadena resultante. |
| static void [FailFast](./failfast/)(const [String](../string/)\&) | Abortar el proceso actual. |
| static [String](../string/) [get_CommandLine](./get_commandline/)() | Devuelve la línea de comandos utilizada para iniciar el proceso actual. |
| static [String](../string/) [get_CurrentDirectory](./get_currentdirectory/)() | Devuelve la ruta al directorio de trabajo actual. |
| static int [get_ExitCode](./get_exitcode/)() | Devuelve el código de salida del proceso actual. |
| static **bool** [get_HasShutdownStarted](./get_hasshutdownstarted/)() | Comprueba si el apagado está en curso. No implementado. |
| static **bool** [get_Is64BitProcess](./get_is64bitprocess/)() | Devuelve true para ejecutables/bibliotecas de plataforma de 64 bits. |
| static [String](../string/) [get_MachineName](./get_machinename/)() | Devuelve el nombre NetBIOS de este equipo. |
| static [String](../string/) [get_NewLine](./get_newline/)() | Devuelve la cadena de salto de línea establecida para el entorno actual. |
| static const [OperatingSystem](../operatingsystem/)\& [get_OSVersion](./get_osversion/)() | Devuelve el objeto [OperatingSystem](../operatingsystem/) que contiene información sobre el sistema operativo actual. |
| static int [get_ProcessorCount](./get_processorcount/)() | Devuelve el número de procesadores de la máquina actual. |
| static [String](../string/) [get_StackTrace](./get_stacktrace/)() | Devuelve la cadena que contiene la información de la traza de pila actual. |
| static [String](../string/) [get_SystemDirectory](./get_systemdirectory/)() | Devuelve la ruta al directorio del sistema. |
| static int [get_TickCount](./get_tickcount/)() | Devuelve el número de milisegundos transcurridos desde que se inició el sistema. |
| static [String](../string/) [get_UserDomainName](./get_userdomainname/)() | Devuelve el nombre de dominio de red del usuario actual. |
| static **bool** [get_UserInteractive](./get_userinteractive/)() | Determina si el proceso actual se está ejecutando en modo interactivo de usuario. |
| static [String](../string/) [get_UserName](./get_username/)() | Devuelve el nombre del usuario actualmente conectado al sistema operativo [Windows](../../system.windows/). |
| static [Version](../version/) [get_Version](./get_version/)() | Devuelve el objeto [Version](../version/) que representa la información sobre la versión del tiempo de ejecución de lenguaje común. El número de versión devuelto por este método es más bien ficticio y no significa que todas las clases de la biblioteca se comporten de acuerdo con la versión devuelta. |
| static **int64_t** [get_WorkingSet](./get_workingset/)() | Devuelve la cantidad de memoria física asignada al contexto del proceso. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetCommandLineArgs](./getcommandlineargs/)() | Devuelve una matriz que contiene los argumentos de la línea de comandos utilizados para iniciar el proceso actual. |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&) | Devuelve el valor de la variable de entorno especificada asociada al proceso actual. |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | Devuelve el valor de la variable de entorno especificada desde la ubicación especificada. |
| static [String](../string/) [GetEnvironmentVariableA](./getenvironmentvariablea/)(const [String](../string/)\&) | Devuelve el valor de la variable de entorno especificada asociada al proceso actual. |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)() | Devuelve un diccionario que contiene todos los nombres de variables de entorno y sus valores asociados al proceso actual. |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)([EnvironmentVariableTarget](../environmentvariabletarget/)) | Devuelve un diccionario que contiene todos los nombres de variables de entorno y sus valores de la ubicación especificada. |
| static [String](../string/) [GetEnvironmentVariableW](./getenvironmentvariablew/)(const [String](../string/)\&) | Devuelve el valor de la variable de entorno especificada asociada al proceso actual. |
| static [String](../string/) [GetFolderPath](./getfolderpath/)([SpecialFolder](./specialfolder/)) | Devuelve la ruta completamente calificada a la carpeta del sistema especificada. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetLogicalDrives](./getlogicaldrives/)() | Devuelve una matriz que contiene los nombres de todas las unidades lógicas del equipo actual. |
| static **bool** [IsWindowsSubsystemForLinux](./iswindowssubsystemforlinux/)() | Devuelve true solo para WSL. |
| static void [set_CurrentDirectory](./set_currentdirectory/)(const [String](../string/)\&) | Establece el directorio especificado como el directorio de trabajo actual. |
| static void [set_ExitCode](./set_exitcode/)(int) | Establece el valor especificado como código de salida para el proceso actual. |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&) | NO IMPLEMENTADO. |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | NO IMPLEMENTADO. |

## Enumeraciones

| Enumeración | Descripción |
| --- | --- |
| [SpecialFolder](./specialfolder/) | Representa carpetas especiales del sistema. |

## Véase también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)