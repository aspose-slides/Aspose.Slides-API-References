---
title: to_tiff method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.lowcode/convert/to_tiff/
weight: 60
---
## to_tiff(pres, output_file_name) {#presentation-str}
Convierte la presentación de entrada en un conjunto de imágenes en formato TIFF.  
            Si el nombre del archivo de salida se proporciona como "myPath/myFilename.tiff", 
            el resultado se guardará como un conjunto de archivos "myPath/myFilename_N.tiff", donde N es el número de diapositiva.


```python
@staticmethod
def to_tiff(pres, output_file_name):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/es/aspose.slides/presentation) | La presentación de entrada. |
| output_file_name | **str** | El nombre del archivo de salida. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_tiff(pres, output_file_name, options, multipage) {#presentation-str-asposeslidesexportitiffoptions-bool}
Convierte la presentación de entrada a formato TIFF con opciones personalizadas.
            Si el nombre del archivo de salida se proporciona como "myPath/myFilename.tiff" y `multipage` es `false`, 
            el resultado se guardará como un conjunto de archivos "myPath/myFilename_N.tiff", donde N es el número de diapositiva.
            De lo contrario, si `multipage` es `true`, el resultado será un documento multipágina "myPath/myFilename.tiff".


```python
@staticmethod
def to_tiff(pres, output_file_name, options, multipage):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/es/aspose.slides/presentation) | La presentación de entrada. |
| output_file_name | **str** | El nombre del archivo de salida. |
| options | [`ITiffOptions`](/slides/python-net/es/aspose.slides.export/itiffoptions) | Las opciones de guardado en TIFF. |
| multipage | **bool** | Especifica si el documento TIFF generado debe ser multipágina. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### Ver también
* clase [`Convert`](/slides/python-net/es/aspose.slides.lowcode/convert)
* clase [`ITiffOptions`](/slides/python-net/es/aspose.slides.export/itiffoptions)
* clase [`Presentation`](/slides/python-net/es/aspose.slides/presentation)
* módulo [`aspose.slides.lowcode`](/slides/python-net/es/aspose.slides.lowcode)
* biblioteca [`Aspose.Slides`](/slides/python-net)