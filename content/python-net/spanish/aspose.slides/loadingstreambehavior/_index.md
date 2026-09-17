---
title: LoadingStreamBehavior enumeration
second_title: Referencia de API de Aspose.Slides para Python mediante .NET
description: 
type: docs
url: /es/aspose.slides/loadingstreambehavior/
---
## LoadingStreamBehavior enumeración

El **io.RawIOBase** pasado a un método se considera un Binary Large Object (BLOB) (ver la descripción de [`IBlobManagementOptions`](/slides/python-net/es/aspose.slides/iblobmanagementoptions)). Los valores de esta enumeración identifican cómo debe tratarse el **io.RawIOBase** cuando se pasa al método. Dependiendo de los requisitos, se pueden tomar diferentes decisiones para proporcionar el comportamiento más eficiente.

El tipo LoadingStreamBehavior expone los siguientes miembros:

## Campos

| Campo | Descripción |
| :- | :- |
| READ_STREAM_AND_RELEASE | La secuencia se leerá hasta el final y luego se liberará, es decir, se garantizará que esta secuencia <br/>            no será utilizada por la instancia [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation) en el futuro. Puede ser cerrada por el código del cliente <br/>            o utilizada de cualquier otra manera. |
| KEEP_LOCKED | La secuencia se bloqueará dentro del objeto [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation), es decir, la propiedad de <br/>            la secuencia se transferirá. El objeto [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation) será responsable de <br/>            disponer correctamente la secuencia cuando este objeto se disponga a sí mismo. <br/>            Este comportamiento es extremadamente útil cuando necesita serializar un archivo BLOB grande (como un <br/>            video o audio grande -ver la descripción de [`IBlobManagementOptions`](/slides/python-net/es/aspose.slides/iblobmanagementoptions)) y desea evitar cargar <br/>            este archivo en memoria u otros problemas de rendimiento. Puede simplemente abrir el **System.IO.FileStream** <br/>            para este archivo y pasarlo a un método, eligiendo LoadingStreamBehavior [`LoadingStreamBehavior.KEEP_LOCKED`](/slides/python-net/es/aspose.slides/loadingstreambehavior/KEEP_LOCKED). |

### Ver también
* clase [`IBlobManagementOptions`](/slides/python-net/es/aspose.slides/iblobmanagementoptions)
* clase [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)