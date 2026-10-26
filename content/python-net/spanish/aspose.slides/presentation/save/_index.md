---
title: save method
second_title: Referencia de API de Aspose.Slides para Python mediante .NET
description: 
type: docs
url: /es/aspose.slides/presentation/save/
weight: 90
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
Guarda todas las diapositivas de una presentación en un conjunto de archivos que representan marcado XAML.

```python
def save(self, options):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/es/aspose.slides.export.xaml/ixamloptions) | Las opciones de formato XAML. |


## save(self, fname, format) {#str-asposeslidesexportsaveformat}
Guarda todas las diapositivas de una presentación en un archivo con el formato especificado.

```python
def save(self, fname, format):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| fname | **str** | Ruta al archivo creado. |
| format | [`SaveFormat`](/slides/python-net/es/aspose.slides.export/saveformat) | Formato de los datos exportados. |


## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
Guarda todas las diapositivas de una presentación en un flujo con el formato especificado.

```python
def save(self, stream, format):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream | **io.RawIOBase** | Flujo de salida. |
| format | [`SaveFormat`](/slides/python-net/es/aspose.slides.export/saveformat) | Formato de los datos exportados. |


## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}

```python
def save(self, fname, format, options):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| fname | **str** |  |
| format | [`SaveFormat`](/slides/python-net/es/aspose.slides.export/saveformat) |  |
| options | [`ISaveOptions`](/slides/python-net/es/aspose.slides.export/isaveoptions) |  |


## save(self, stream, format, options) {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Guarda todas las diapositivas de una presentación en un flujo con el formato especificado y con opciones adicionales.

```python
def save(self, stream, format, options):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream | **io.RawIOBase** | Flujo de salida. |
| format | [`SaveFormat`](/slides/python-net/es/aspose.slides.export/saveformat) | Formato de los datos exportados. |
| options | [`ISaveOptions`](/slides/python-net/es/aspose.slides.export/isaveoptions) | Opciones de formato adicionales. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | Si intentas guardar un archivo cifrado en <br/>            none Office 2007-2010 format |


## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
Guarda las diapositivas especificadas de una presentación en un archivo con el formato indicado manteniendo la numeración de páginas.

```python
def save(self, fname, slides, format):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| fname | **str** | Ruta al archivo creado. |
| slides | **List[int]** | Matriz con las posiciones de las diapositivas, comenzando en 1. |
| format | [`SaveFormat`](/slides/python-net/es/aspose.slides.export/saveformat) | Formato de los datos exportados. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Cuando el parámetro stream o slides es None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Cuando el parámetro slides contiene números de página incorrectos. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Cuando se utiliza un SaveFormat no compatible, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
Guarda las diapositivas especificadas de una presentación en un flujo con el formato indicado manteniendo la numeración de páginas.

```python
def save(self, stream, slides, format):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream | **io.RawIOBase** | Flujo de salida. |
| slides | **List[int]** | Matriz con las posiciones de las diapositivas, comenzando en 1. |
| format | [`SaveFormat`](/slides/python-net/es/aspose.slides.export/saveformat) | Formato de los datos exportados. |


## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Guarda las diapositivas especificadas de una presentación en un archivo con el formato indicado manteniendo la numeración de páginas.

```python
def save(self, fname, slides, format, options):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| fname | **str** | Ruta al archivo creado. |
| slides | **List[int]** | Matriz con las posiciones de las diapositivas, comenzando en 1. |
| format | [`SaveFormat`](/slides/python-net/es/aspose.slides.export/saveformat) | Formato de los datos exportados. |
| options | [`ISaveOptions`](/slides/python-net/es/aspose.slides.export/isaveoptions) | Opciones de formato adicionales. |


## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Guarda las diapositivas especificadas de una presentación en un flujo con el formato indicado manteniendo la numeración de páginas.

```python
def save(self, stream, slides, format, options):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream | **io.RawIOBase** | Flujo de salida. |
| slides | **List[int]** | Matriz con las posiciones de las diapositivas, comenzando en 1. |
| format | [`SaveFormat`](/slides/python-net/es/aspose.slides.export/saveformat) | Formato de los datos exportados. |
| options | [`ISaveOptions`](/slides/python-net/es/aspose.slides.export/isaveoptions) | Opciones de formato adicionales. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Cuando el parámetro stream o slides es None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Cuando el parámetro slides contiene números de página incorrectos. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Cuando se utiliza un SaveFormat no compatible, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |



### Ver también
* clase [`ISaveOptions`](/slides/python-net/es/aspose.slides.export/isaveoptions)
* clase [`IXamlOptions`](/slides/python-net/es/aspose.slides.export.xaml/ixamloptions)
* clase [`Presentation`](/slides/python-net/es/aspose.slides/presentation)
* enumeración [`SaveFormat`](/slides/python-net/es/aspose.slides.export/saveformat)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)