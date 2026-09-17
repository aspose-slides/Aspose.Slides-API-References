---
title: VbaProject class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.vba/vbaproject/
---
## VbaProject clase

Representa un proyecto VBA con macros de presentación.

El tipo VbaProject expone los siguientes miembros:

## Constructores

| Constructor | Descripción |
| :- | :- |
| [`__init__(self)`](/slides/python-net/es/aspose.slides.vba/vbaproject/__init__/#) | Este constructor crea un nuevo proyecto VBA desde cero.<br/>            El proyecto se creará en la página de códigos 1252 Windows Latin 1 (ANSI) |
| [`__init__(self, data)`](/slides/python-net/es/aspose.slides.vba/vbaproject/__init__/#bytes) | Este constructor carga el proyecto VBA a partir de la representación binaria del contenedor OLE. |

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`name`](/slides/python-net/es/aspose.slides.vba/vbaproject/name/) | Devuelve el nombre del proyecto VBA.<br/>            Solo lectura **str**. |
| [`modules`](/slides/python-net/es/aspose.slides.vba/vbaproject/modules/) | Devuelve la lista de todos los módulos que contiene el proyecto VBA.<br/>            Solo lectura [`IVbaModuleCollection`](/slides/python-net/es/aspose.slides.vba/ivbamodulecollection). |
| [`references`](/slides/python-net/es/aspose.slides.vba/vbaproject/references/) | Devuelve la lista de todas las referencias que contiene el proyecto VBA.<br/>            Solo lectura [`IVbaReferenceCollection`](/slides/python-net/es/aspose.slides.vba/ivbareferencecollection). |
| [`is_password_protected`](/slides/python-net/es/aspose.slides.vba/vbaproject/is_password_protected/) | Indica si el VBAProject está protegido por una contraseña para ver las propiedades del proyecto.<br/>            Solo lectura **bool**. |

## Métodos

| Método | Descripción |
| :- | :- |
| [`to_binary(self)`](/slides/python-net/es/aspose.slides.vba/vbaproject/to_binary/#) | Devuelve la representación binaria del proyecto VBA como contenedor OLE |


### Ver también
* módulo [`aspose.slides.vba`](/slides/python-net/es/aspose.slides.vba)
* biblioteca [`Aspose.Slides`](/slides/python-net)