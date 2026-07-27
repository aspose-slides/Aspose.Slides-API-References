---
title: OperatingSystem
second_title: Referencia de API de Aspose.Slides para C++
description: "Representa un sistema operativo particular y proporciona información sobre él. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento."
type: docs
weight: 1171
url: /es/system/operatingsystem/
---
## OperatingSystem clase

Representa un sistema operativo particular y proporciona información sobre él. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class OperatingSystem
```

## Métodos

| Método | Descripción |
| --- | --- |
| [PlatformID](../platformid/) [get_Platform](./get_platform/)() const | Devuelve el identificador de plataforma del sistema operativo representado por el objeto actual. |
| [String](../string/) [get_ServicePack](./get_servicepack/)() const | Devuelve el nombre del service pack del sistema operativo representado por el objeto actual. |
| const [Version](../version/)\& [get_Version](./get_version/)() const | Devuelve una referencia constante a un objeto [Version](../version/) que representa la versión del sistema operativo representado por el objeto actual. |
| [String](../string/) [get_VersionString](./get_versionstring/)() const | Devuelve la representación en cadena de la versión del sistema operativo representado por el objeto actual. |
| static **bool** [IsFreeBSD](./isfreebsd/)() | Indica si la aplicación actual se está ejecutando en FreeBSD. |
| static **bool** [IsLinux](./islinux/)() | Indica si la aplicación actual se está ejecutando en Linux. |
| static **bool** [IsMacOS](./ismacos/)() | Indica si la aplicación actual se está ejecutando en MacOS. |
| static **bool** [IsOSPlatform](./isosplatform/)(const [String](../string/)\&) | Indica si la aplicación actual se está ejecutando en la plataforma especificada. |
| static **bool** [IsWindows](./iswindows/)() | Indica si la aplicación actual se está ejecutando en [Windows](../../system.windows/). |
|  [OperatingSystem](./operatingsystem/)([PlatformID](../platformid/), const [Version](../version/)\&) | Construye una instancia que representa un sistema operativo especificado como un identificador de plataforma y versión particulares. |
|  [OperatingSystem](./operatingsystem/)([PlatformID](../platformid/), const [Version](../version/)\&, const [String](../string/)\&) | Construye una instancia que representa un sistema operativo especificado como un identificador de plataforma, versión y service pack particulares. |
| [String](../string/) [ToString](./tostring/)() const | Devuelve la representación en cadena de la versión del sistema operativo representado por el objeto actual. |

## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)