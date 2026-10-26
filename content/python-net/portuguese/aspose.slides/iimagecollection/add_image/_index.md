---
title: add_image method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/iimagecollection/add_image/
weight: 10
---
## add_image(self, image) {#iimage}
Adiciona uma imagem a uma apresentação.

### Retorno

Imagem adicionada.



```python
def add_image(self, image):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| image | [`IImage`](/slides/python-net/pt/aspose.slides/iimage) | Imagem a ser adicionada. |

### Observações

Este método converte metafiles WMF/EMF em imagem PNG raster antes de inseri-la em uma apresentação.


## add_image(self, stream) {#iorawiobase}
Adiciona uma imagem a uma apresentação a partir de um fluxo.

### Retorno

Imagem adicionada.



```python
def add_image(self, stream):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| stream | **io.RawIOBase** | Fluxo de onde a imagem será adicionada. |

### Observações

Este método pode adicionar metafiles WMF/EMF a uma apresentação sem convertê-los para imagem PNG raster.


## add_image(self, buffer) {#bytes}
Adiciona uma imagem a uma apresentação a partir de um buffer especificado.

### Retorno

Imagem adicionada.



```python
def add_image(self, buffer):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| buffer | **bytes** | Buffer. |


## add_image(self, image_source) {#ippimage}
Adiciona uma cópia de uma imagem de outra apresentação.

### Retorno

Imagem adicionada.



```python
def add_image(self, image_source):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| image_source | [`IPPImage`](/slides/python-net/pt/aspose.slides/ippimage) | Imagem de origem. |


## add_image(self, svg_image) {#isvgimage}
Adiciona uma imagem a uma apresentação a partir de um objeto SVG.

### Retorno

Imagem adicionada.



```python
def add_image(self, svg_image):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/pt/aspose.slides/isvgimage) | Objeto de imagem SVG [`ISvgImage`](/slides/python-net/pt/aspose.slides/isvgimage) |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Lançado quando o parâmetro svgImage for None. |


## add_image(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Cria e adiciona uma imagem a uma apresentação a partir de um fluxo.

### Retorno

Adicionado [`IPPImage`](/slides/python-net/pt/aspose.slides/ippimage).



```python
def add_image(self, stream, loading_stream_behavior):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| stream | **io.RawIOBase** | Fluxo de onde o arquivo de imagem será adicionado. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/pt/aspose.slides/loadingstreambehavior) | O comportamento que será aplicado ao fluxo. |



### Veja Também
* classe [`IImage`](/slides/python-net/pt/aspose.slides/iimage)
* classe [`IImageCollection`](/slides/python-net/pt/aspose.slides/iimagecollection)
* classe [`IPPImage`](/slides/python-net/pt/aspose.slides/ippimage)
* classe [`ISvgImage`](/slides/python-net/pt/aspose.slides/isvgimage)
* enumeração [`LoadingStreamBehavior`](/slides/python-net/pt/aspose.slides/loadingstreambehavior)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)