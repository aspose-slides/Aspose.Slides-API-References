---
title: to_tiff method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.lowcode/convert/to_tiff/
weight: 60
---
## to_tiff(pres, output_file_name) {#presentation-str}
Converte a apresentação de entrada em um conjunto de imagens no formato TIFF.  
Se o nome do arquivo de saída for fornecido como "myPath/myFilename.tiff", o resultado será salvo como um conjunto de "myPath/myFilename_N.tiff" arquivos, onde N é o número do slide.

```python
@staticmethod
def to_tiff(pres, output_file_name):
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

## to_tiff(pres, output_file_name, options, multipage) {#presentation-str-asposeslidesexportitiffoptions-bool}
Converte a apresentação de entrada para o formato TIFF com opções personalizadas.  
Se o nome do arquivo de saída for fornecido como "myPath/myFilename.tiff" e `multipage` for `false`, o resultado será salvo como um conjunto de "myPath/myFilename_N.tiff" arquivos, onde N é o número do slide.  
Caso contrário, se `multipage` for `true`, o resultado será um documento de múltiplas páginas "myPath/myFilename.tiff".

```python
@staticmethod
def to_tiff(pres, output_file_name, options, multipage):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/pt/aspose.slides/presentation) | A apresentação de entrada. |
| output_file_name | **str** | O nome do arquivo de saída. |
| options | [`ITiffOptions`](/slides/python-net/pt/aspose.slides.export/itiffoptions) | As opções de salvamento TIFF. |
| multipage | **bool** | Especifica se o documento TIFF gerado deve ser de múltiplas páginas. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |

### Veja Também
* classe [`Convert`](/slides/python-net/pt/aspose.slides.lowcode/convert)
* classe [`ITiffOptions`](/slides/python-net/pt/aspose.slides.export/itiffoptions)
* classe [`Presentation`](/slides/python-net/pt/aspose.slides/presentation)
* módulo [`aspose.slides.lowcode`](/slides/python-net/pt/aspose.slides.lowcode)
* biblioteca [`Aspose.Slides`](/slides/python-net)