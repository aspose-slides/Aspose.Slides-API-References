---
title: to_jpeg method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.lowcode/convert/to_jpeg/
weight: 20
---
## to_jpeg(pres, output_file_name) {#presentation-str}
Converte a apresentação de entrada em um conjunto de imagens no formato JPEG.  
Se o nome do arquivo de saída for fornecido como "myPath/myFilename.jpeg", o resultado será salvo como um conjunto de arquivos "myPath/myFilename_N.jpeg", onde N é o número do slide.

```python
@staticmethod
def to_jpeg(pres, output_file_name):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/pt/aspose.slides/presentation) | A apresentação de entrada. |
| output_file_name | **str** | O nome do arquivo de saída. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |

## to_jpeg(pres, output_file_name, image_size) {#presentation-str-asposepydrawingsize}
Converte a apresentação de entrada em um conjunto de imagens no formato JPEG.  
Se o nome do arquivo de saída for fornecido como "myPath/myFilename.jpeg", o resultado será salvo como um conjunto de arquivos "myPath/myFilename_N.jpeg", onde N é o número do slide.

```python
@staticmethod
def to_jpeg(pres, output_file_name, image_size):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/pt/aspose.slides/presentation) | A apresentação de entrada |
| output_file_name | **str** | O nome do arquivo de saída. |
| image_size | **aspose.slides.Size** | O tamanho de cada imagem gerada. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |

## to_jpeg(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
Converte a apresentação de entrada em um conjunto de imagens no formato JPEG.  
Se o nome do arquivo de saída for fornecido como "myPath/myFilename.jpeg", o resultado será salvo como um conjunto de arquivos "myPath/myFilename_N.jpeg", onde N é o número do slide.

```python
@staticmethod
def to_jpeg(pres, output_file_name, scale, options):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/pt/aspose.slides/presentation) | A apresentação de entrada. |
| output_file_name | **str** | O nome do arquivo de saída. |
| scale | **float** | O fator de escala aplicado às imagens de saída em relação ao tamanho original do slide. |
| options | [`IRenderingOptions`](/slides/python-net/pt/aspose.slides.export/irenderingoptions) | As opções de renderização. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |

### Ver Também
* classe [`Convert`](/slides/python-net/pt/aspose.slides.lowcode/convert)
* classe [`IRenderingOptions`](/slides/python-net/pt/aspose.slides.export/irenderingoptions)
* classe [`Presentation`](/slides/python-net/pt/aspose.slides/presentation)
* módulo [`aspose.slides.lowcode`](/slides/python-net/pt/aspose.slides.lowcode)
* biblioteca [`Aspose.Slides`](/slides/python-net)