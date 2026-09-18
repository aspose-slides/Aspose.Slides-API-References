---
title: add_image method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/imagecollection/add_image/
weight: 10
---
## add_image(self, image_source) {#ippimage}
Adiciona uma cópia de uma imagem de outra apresentação.

### Retorna
Imagem adicionada.



```python
def add_image(self, image_source):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| image_source | [`IPPImage`](/slides/python-net/pt/aspose.slides/ippimage) | Imagem de origem. |


## add_image(self, image) {#iimage}
Adiciona uma imagem a uma apresentação.

### Retorna
Imagem adicionada.



```python
def add_image(self, image):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| image | [`IImage`](/slides/python-net/pt/aspose.slides/iimage) | Imagem a ser adicionada. |

### Observações
Este método converte arquivos metafile WMF/EMF em imagem raster PNG antes de inseri-los em uma apresentação.


## add_image(self, stream) {#iorawiobase}
Adiciona uma imagem a uma apresentação a partir de um fluxo.

### Retorna
Imagem adicionada.



```python
def add_image(self, stream):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| stream | **io.RawIOBase** | Fluxo de onde adicionar a imagem. |

### Observações
Este método pode adicionar arquivos metafile WMF/EMF a uma apresentação sem convertê-los em imagem raster PNG.


## add_image(self, buffer) {#bytes}
Adiciona uma imagem a uma apresentação a partir de um buffer especificado.

### Retorna
Imagem adicionada.



```python
def add_image(self, buffer):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| buffer | **bytes** | Buffer. |


## add_image(self, svg_image) {#isvgimage}
Adiciona uma imagem a uma apresentação a partir de um objeto Svg.

### Retorna
Imagem adicionada.



```python
def add_image(self, svg_image):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/pt/aspose.slides/isvgimage) | Objeto de imagem Svg [`ISvgImage`](/slides/python-net/pt/aspose.slides/isvgimage) |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Quando o parâmetro svgImage for None. |


## add_image(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Cria e adiciona uma imagem a uma apresentação a partir de um fluxo.

### Retorna
Adicionado [`IPPImage`](/slides/python-net/pt/aspose.slides/ippimage).



```python
def add_image(self, stream, loading_stream_behavior):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| stream | **io.RawIOBase** | Fluxo de onde adicionar o arquivo de imagem. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/pt/aspose.slides/loadingstreambehavior) | O comportamento que será aplicado ao fluxo. |



### Veja Também
* classe [`IImage`](/slides/python-net/pt/aspose.slides/iimage)
* classe [`ImageCollection`](/slides/python-net/pt/aspose.slides/imagecollection)
* classe [`IPPImage`](/slides/python-net/pt/aspose.slides/ippimage)
* classe [`ISvgImage`](/slides/python-net/pt/aspose.slides/isvgimage)
* enumeração [`LoadingStreamBehavior`](/slides/python-net/pt/aspose.slides/loadingstreambehavior)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)