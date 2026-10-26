---
title: LoadingStreamBehavior
second_title: Aspose.Slides para C++ Referencia de API
description: "El System::IO::Stream pasado a un método se considera como un Binary Large Object (BLOB) (ver la descripción de IBlobManagementOptions). Los valores de esta enumeración identifican cómo debe tratarse el System::IO::Stream cuando se pasa al método. Dependiendo de los requisitos, se pueden tomar diferentes decisiones para proporcionar el comportamiento más eficiente."
type: docs
weight: 6735
url: /es/aspose.slides/loadingstreambehavior/
---
## LoadingStreamBehavior enum

El [System::IO::Stream](../../system.io/stream/) pasado a un método se considera como un Binary Large Object (BLOB) (ver la descripción de [IBlobManagementOptions](../iblobmanagementoptions/)). Los valores de esta enumeración identifican cómo debe tratarse el [System::IO::Stream](../../system.io/stream/) cuando se pasa al método. Dependiendo de los requisitos, se pueden tomar diferentes decisiones para proporcionar el comportamiento más eficiente.

```cpp
enum class LoadingStreamBehavior
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| ReadStreamAndRelease | 0 | El flujo se leerá hasta el final y luego se liberará - es decir, se garantizará que este flujo no será usado por la instancia [IPresentation](../ipresentation/) en el futuro. Puede ser cerrado por el código del cliente o usado de cualquier otra manera. |
| KeepLocked | 1 | El flujo quedará bloqueado dentro del objeto [IPresentation](../ipresentation/), es decir, la propiedad del flujo será transferida. El objeto [IPresentation](../ipresentation/) será responsable de disponer correctamente del flujo cuando este objeto se disponga a sí mismo. Este comportamiento es extremadamente útil cuando necesitas serializar un archivo BLOB grande (como un video o audio grande - ver la descripción de [IBlobManagementOptions](../iblobmanagementoptions/)) y deseas evitar cargar este archivo en memoria u otros problemas de rendimiento. Simplemente puedes abrir el [System::IO::FileStream](../../system.io/filestream/) para este archivo y pasarlo a un método, eligiendo [LoadingStreamBehavior::KeepLocked](./) LoadingStreamBehavior. |

## Ver también

* Espacio de nombres [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)