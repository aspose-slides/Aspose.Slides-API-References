---
title: to_jpeg method
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides.lowcode/convert/to_jpeg/
weight: 20
---
## to_jpeg(pres, output_file_name) {#presentation-str}
Convierte la presentación de entrada en un conjunto de imágenes en formato JPEG.  
            Si el nombre del archivo de salida se indica como "myPath/myFilename.jpeg", 
            el resultado se guardará como un conjunto de archivos "myPath/myFilename_N.jpeg", donde N es el número de diapositiva.


```python
@staticmethod
def to_jpeg(pres, output_file_name):
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


## to_jpeg(pres, output_file_name, image_size) {#presentation-str-asposepydrawingsize}
Convierte la presentación de entrada en un conjunto de imágenes en formato JPEG.  
            Si el nombre del archivo de salida se indica como "myPath/myFilename.jpeg", 
            el resultado se guardará como un conjunto de archivos "myPath/myFilename_N.jpeg", donde N es el número de diapositiva.


```python
@staticmethod
def to_jpeg(pres, output_file_name, image_size):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/es/aspose.slides/presentation) | La presentación de entrada |
| output_file_name | **str** | El nombre del archivo de salida. |
| image_size | **aspose.slides.Size** | El tamaño de cada imagen generada. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_jpeg(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
Convierte la presentación de entrada en un conjunto de imágenes en formato JPEG.  
            Si el nombre del archivo de salida se indica como "myPath/myFilename.jpeg", 
            el resultado se guardará como un conjunto de archivos "myPath/myFilename_N.jpeg", donde N es el número de diapositiva.


```python
@staticmethod
def to_jpeg(pres, output_file_name, scale, options):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/es/aspose.slides/presentation) | La presentación de entrada. |
| output_file_name | **str** | El nombre del archivo de salida. |
| scale | **float** | El factor de escalado aplicado a las imágenes de salida en relación con el tamaño original de la diapositiva. |
| options | [`IRenderingOptions`](/slides/python-net/es/aspose.slides.export/irenderingoptions) | Las opciones de renderizado. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### Ver también
* clase [`Convert`](/slides/python-net/es/aspose.slides.lowcode/convert)
* clase [`IRenderingOptions`](/slides/python-net/es/aspose.slides.export/irenderingoptions)
* clase [`Presentation`](/slides/python-net/es/aspose.slides/presentation)
* módulo [`aspose.slides.lowcode`](/slides/python-net/es/aspose.slides.lowcode)
* biblioteca [`Aspose.Slides`](/slides/python-net)