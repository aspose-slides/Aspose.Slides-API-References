---
title: to_jpeg method
second_title: Aspose.Slides para Python a través de la referencia de API .NET
description: 
type: docs
url: /es/aspose.slides.lowcode/convert/to_jpeg/
weight: 20
---
## to_jpeg(pres, output_file_name) {#presentation-str}
Convierte la presentación de entrada en un conjunto de imágenes en formato JPEG.  
Si el nombre del archivo de salida se proporciona como "myPath/myFilename.jpeg", el resultado se guardará como un conjunto de archivos "myPath/myFilename_N.jpeg", donde N es el número de diapositiva.

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

## to_jpeg(pres, output_file_name, image_size) {#presentation-str-asposeslidessize}
Convierte la presentación de entrada en un conjunto de imágenes en formato JPEG.  
Si el nombre del archivo de salida se proporciona como "myPath/myFilename.jpeg", el resultado se guardará como un conjunto de archivos "myPath/myFilename_N.jpeg", donde N es el número de diapositiva.

```python
@staticmethod
def to_jpeg(pres, output_file_name, image_size):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/es/aspose.slides/presentation) | La presentación de entrada |
| output_file_name | **str** | El nombre del archivo de salida. |
| image_size | [`Size`](/slides/python-net/es/aspose.slides/size) | El tamaño de cada imagen generada. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |

## to_jpeg(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
Convierte la presentación de entrada en un conjunto de imágenes en formato JPEG.  
Si el nombre del archivo de salida se proporciona como "myPath/myFilename.jpeg", el resultado se guardará como un conjunto de archivos "myPath/myFilename_N.jpeg", donde N es el número de diapositiva.

```python
@staticmethod
def to_jpeg(pres, output_file_name, scale, options):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/es/aspose.slides/presentation) | La presentación de entrada. |
| output_file_name | **str** | El nombre del archivo de salida. |
| scale | **float** | El factor de escala aplicado a las imágenes de salida respecto al tamaño original de la diapositiva. |
| options | [`IRenderingOptions`](/slides/python-net/es/aspose.slides.export/irenderingoptions) | Las opciones de renderizado. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |

### Ver también
* clase [`Convert`](/slides/python-net/es/aspose.slides.lowcode/convert)
* clase [`IRenderingOptions`](/slides/python-net/es/aspose.slides.export/irenderingoptions)
* clase [`Presentation`](/slides/python-net/es/aspose.slides/presentation)
* clase [`Size`](/slides/python-net/es/aspose.slides/size)
* módulo [`aspose.slides.lowcode`](/slides/python-net/es/aspose.slides.lowcode)
* biblioteca [`Aspose.Slides`](/slides/python-net)