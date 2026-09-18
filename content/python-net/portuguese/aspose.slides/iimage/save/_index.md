---
title: save method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/iimage/save/
weight: 10
---
## save(self, filename) {#str}
Salva a imagem em um arquivo.

```python
def save(self, filename):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| filename | **str** | O caminho para o arquivo onde a imagem será salva. |

## save(self, filename, format) {#str-imageformat}
Salva a imagem em um arquivo no formato especificado.

```python
def save(self, filename, format):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| filename | **str** | O caminho para o arquivo onde a imagem será salva. |
| format | [`ImageFormat`](/slides/python-net/pt/aspose.slides/imageformat) | O formato da imagem. |

## save(self, stream, format) {#iorawiobase-imageformat}
Salva a imagem em um fluxo no formato especificado.

```python
def save(self, stream, format):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| stream | **io.RawIOBase** | O fluxo onde a imagem será salva. |
| format | [`ImageFormat`](/slides/python-net/pt/aspose.slides/imageformat) | O formato da imagem. |

## save(self, filename, format, quality) {#str-imageformat-int}
Salva a imagem em um arquivo no formato e qualidade especificados.

```python
def save(self, filename, format, quality):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| filename | **str** | O caminho para o arquivo onde a imagem será salva. |
| format | [`ImageFormat`](/slides/python-net/pt/aspose.slides/imageformat) | O formato da imagem. |
| quality | **int** | A qualidade da imagem salva (0 a 100).  <br/><br/>            Este parâmetro afeta apenas a gravação em [`ImageFormat.JPEG`](/slides/python-net/pt/aspose.slides/imageformat/JPEG); para todos os outros formatos, é ignorado. |

## save(self, stream, format, quality) {#iorawiobase-imageformat-int}
Salva a imagem em um fluxo no formato e qualidade especificados.

```python
def save(self, stream, format, quality):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| stream | **io.RawIOBase** | O fluxo onde a imagem será salva. |
| format | [`ImageFormat`](/slides/python-net/pt/aspose.slides/imageformat) | O formato da imagem. |
| quality | **int** | A qualidade da imagem salva (0 a 100).  <br/><br/>            Este parâmetro afeta apenas a gravação em [`ImageFormat.JPEG`](/slides/python-net/pt/aspose.slides/imageformat/JPEG); para todos os outros formatos, é ignorado. |

### Veja Também
* classe [`IImage`](/slides/python-net/pt/aspose.slides/iimage)
* enumeração [`ImageFormat`](/slides/python-net/pt/aspose.slides/imageformat)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)