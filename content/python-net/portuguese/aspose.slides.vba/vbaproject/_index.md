---
title: VbaProject class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.vba/vbaproject/
---
## VbaProject classe

Representa o projeto VBA com macros de apresentação.

O tipo VbaProject expõe os seguintes membros:

## Construtores

| Construtor | Descrição |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pt/aspose.slides.vba/vbaproject/__init__/#) | Este construtor cria um novo projeto VBA do zero.<br/>            O projeto será criado na página de código 1252 Windows Latin 1 (ANSI) |
| [`__init__(self, data)`](/slides/python-net/pt/aspose.slides.vba/vbaproject/__init__/#bytes) | Este construtor carrega o projeto VBA a partir da representação binária do contêiner OLE. |

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`name`](/slides/python-net/pt/aspose.slides.vba/vbaproject/name/) | Retorna o nome do projeto VBA.<br/>            Somente leitura **str**. |
| [`modules`](/slides/python-net/pt/aspose.slides.vba/vbaproject/modules/) | Retorna a lista de todos os módulos que estão contidos no projeto VBA.<br/>            Somente leitura [`IVbaModuleCollection`](/slides/python-net/pt/aspose.slides.vba/ivbamodulecollection). |
| [`references`](/slides/python-net/pt/aspose.slides.vba/vbaproject/references/) | Retorna a lista de todas as referências que estão contidas no projeto VBA.<br/>            Somente leitura [`IVbaReferenceCollection`](/slides/python-net/pt/aspose.slides.vba/ivbareferencecollection). |
| [`is_password_protected`](/slides/python-net/pt/aspose.slides.vba/vbaproject/is_password_protected/) | Indica se o VBAProject está protegido por senha para visualizar as propriedades do projeto.<br/>            Somente leitura **bool**. |

## Métodos

| Método | Descrição |
| :- | :- |
| [`to_binary(self)`](/slides/python-net/pt/aspose.slides.vba/vbaproject/to_binary/#) | Retorna a representação binária do projeto VBA como contêiner OLE |

### Veja Também
* módulo [`aspose.slides.vba`](/slides/python-net/pt/aspose.slides.vba)
* biblioteca [`Aspose.Slides`](/slides/python-net)