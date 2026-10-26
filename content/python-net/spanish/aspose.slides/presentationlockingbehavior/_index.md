---
title: PresentationLockingBehavior enumeration
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior enumeración

Representa el comportamiento respecto al tratamiento de la fuente [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation) (archivo o **io.RawIOBase**) al cargar y trabajar con una instancia de [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation).

El tipo PresentationLockingBehavior expone los siguientes miembros:

## Campos

| Campo | Descripción |
| :- | :- |
| LOAD_AND_RELEASE | La fuente se bloqueará solo durante la ejecución del constructor [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation).<br/>Si [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/es/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) está establecido en false, todos los BLOBs <br/>se cargarán en memoria. De lo contrario, se podrían usar otros medios como archivos temporales. Este comportamiento es más lento que [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/es/aspose.slides/presentationlockingbehavior/KEEP_LOCKED), y si es posible pasar la <br/>propiedad de la fuente a [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation), se recomienda usar [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/es/aspose.slides/presentationlockingbehavior/KEEP_LOCKED). |
| KEEP_LOCKED | La fuente se bloqueará durante toda la vida de la instancia [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation), hasta que se <br/>dispose.<br/>[`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/es/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) debe estar establecido en true para usar <br/>este comportamiento; de lo contrario se lanzará una excepción. Este comportamiento es recomendado, es más rápido y consume menos memoria que [`PresentationLockingBehavior.LOAD_AND_RELEASE`](/slides/python-net/es/aspose.slides/presentationlockingbehavior/LOAD_AND_RELEASE). |

### Comentarios

La fuente es el parámetro pasado al constructor [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation). En el 
            ejemplo a continuación, la fuente es el archivo "pres.pptx":
            
            Para este ejemplo, la fuente (archivo "pres.pptx") se bloqueará durante la vida de una instancia [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation), es decir, no podrá ser cambiada o eliminada por otro proceso.

### Ver también
* clase [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)