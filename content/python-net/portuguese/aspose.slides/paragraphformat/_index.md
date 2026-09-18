---
title: ParagraphFormat class
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides/paragraphformat/
---
## classe ParagraphFormat

Esta classe contém as propriedades de formatação de parágrafo. Ao contrário de [`IParagraphFormatEffectiveData`](/slides/python-net/pt/aspose.slides/iparagraphformateffectivedata), todas as propriedades desta classe são graváveis.

**Herança:**[`ParagraphFormat`](/slides/python-net/pt/aspose.slides/paragraphformat) → [`PVIObject`](/slides/python-net/pt/aspose.slides/pviobject)

O tipo ParagraphFormat expõe os seguintes membros:

## Construtores

| Construtor | Descrição |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pt/aspose.slides/paragraphformat/__init__/#) | Inicializa uma nova instância da classe [`ParagraphFormat`](/slides/python-net/pt/aspose.slides/paragraphformat). |

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`alignment`](/slides/python-net/pt/aspose.slides/paragraphformat/alignment/) | Retorna ou define o alinhamento de texto em um parágrafo sem herança.<br/>            Leitura/gravação [`TextAlignment`](/slides/python-net/pt/aspose.slides/textalignment). |
| [`space_within`](/slides/python-net/pt/aspose.slides/paragraphformat/space_within/) | Retorna ou define a quantidade de espaço entre linhas de base em um parágrafo. Valor positivo significa porcentagem, negativo - tamanho em pontos. Nenhuma herança aplicada.<br/>            Leitura/gravação **float**. |
| [`space_before`](/slides/python-net/pt/aspose.slides/paragraphformat/space_before/) | Retorna ou define a quantidade de espaço antes da primeira linha em um parágrafo sem herança.<br/>            Um valor positivo especifica a porcentagem do tamanho da fonte que o espaço em branco deve ter.<br/>            Um valor negativo especifica o tamanho do espaço em branco em pontos.<br/>            Leitura/gravação **float**. |
| [`space_after`](/slides/python-net/pt/aspose.slides/paragraphformat/space_after/) | Retorna ou define a quantidade de espaço após a última linha em um parágrafo sem herança.<br/>            Um valor positivo especifica a porcentagem do tamanho da fonte que o espaço em branco deve ter.<br/>            Um valor negativo especifica o tamanho do espaço em branco em pontos.<br/>            Leitura/gravação **float**. |
| [`east_asian_line_break`](/slides/python-net/pt/aspose.slides/paragraphformat/east_asian_line_break/) | Determina se a quebra de linha Oriental (East Asian) é usada em um parágrafo. Nenhuma herança aplicada.<br/>            Leitura/gravação [`NullableBool`](/slides/python-net/pt/aspose.slides/nullablebool). |
| [`right_to_left`](/slides/python-net/pt/aspose.slides/paragraphformat/right_to_left/) | Determina se a escrita da direita para a esquerda é usada em um parágrafo. Nenhuma herança aplicada.<br/>            Leitura/gravação [`NullableBool`](/slides/python-net/pt/aspose.slides/nullablebool). |
| [`latin_line_break`](/slides/python-net/pt/aspose.slides/paragraphformat/latin_line_break/) | Determina se a quebra de linha Latina é usada em um parágrafo. Nenhuma herança aplicada.<br/>            Leitura/gravação [`NullableBool`](/slides/python-net/pt/aspose.slides/nullablebool). |
| [`hanging_punctuation`](/slides/python-net/pt/aspose.slides/paragraphformat/hanging_punctuation/) | Determina se a pontuação suspensa é usada em um parágrafo. Nenhuma herança aplicada.<br/>            Leitura/gravação [`NullableBool`](/slides/python-net/pt/aspose.slides/nullablebool). |
| [`margin_left`](/slides/python-net/pt/aspose.slides/paragraphformat/margin_left/) | Retorna ou define a margem esquerda em um parágrafo sem herança.<br/>            Leitura/gravação **float**. |
| [`margin_right`](/slides/python-net/pt/aspose.slides/paragraphformat/margin_right/) | Retorna ou define a margem direita em um parágrafo sem herança.<br/>            Leitura/gravação **float**. |
| [`indent`](/slides/python-net/pt/aspose.slides/paragraphformat/indent/) | Retorna ou define o recuo da primeira linha/recuo suspenso do parágrafo sem herança. O recuo suspenso pode ser definido com valores negativos.<br/>            Leitura/gravação **float**. |
| [`default_tab_size`](/slides/python-net/pt/aspose.slides/paragraphformat/default_tab_size/) | Retorna ou define o tamanho padrão de tabulação sem herança.<br/>            Leitura/gravação **float**. |
| [`tabs`](/slides/python-net/pt/aspose.slides/paragraphformat/tabs/) | Retorna as tabulações de um parágrafo. Nenhuma herança aplicada.<br/>            Somente leitura [`ITabCollection`](/slides/python-net/pt/aspose.slides/itabcollection). |
| [`font_alignment`](/slides/python-net/pt/aspose.slides/paragraphformat/font_alignment/) | Retorna ou define um alinhamento de fonte em um parágrafo sem herança.<br/>            Leitura/gravação [`FontAlignment`](/slides/python-net/pt/aspose.slides/fontalignment). |
| [`slide`](/slides/python-net/pt/aspose.slides/paragraphformat/slide/) |  |
| [`presentation`](/slides/python-net/pt/aspose.slides/paragraphformat/presentation/) |  |
| [`bullet`](/slides/python-net/pt/aspose.slides/paragraphformat/bullet/) |  |
| [`depth`](/slides/python-net/pt/aspose.slides/paragraphformat/depth/) |  |
| [`default_portion_format`](/slides/python-net/pt/aspose.slides/paragraphformat/default_portion_format/) |  |

## Métodos

| Método | Descrição |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/pt/aspose.slides/paragraphformat/get_effective/#) | Obtém os dados de formatação de parágrafo efetivos com a herança aplicada. |

### Observações

Esta classe é usada para retornar e manipular propriedades de formatação de parágrafo definidas para o parágrafo específico. Isso significa que nenhuma herança é aplicada ao obter valores, portanto, na maioria dos casos você receberá valores significando "indefinido".

Para obter os valores dos parâmetros de formatação efetivos, incluindo os herdados, você precisa usar o método [`ParagraphFormat.get_effective`](/slides/python-net/pt/aspose.slides/paragraphformat/get_effective) que retorna uma instância [`IParagraphFormatEffectiveData`](/slides/python-net/pt/aspose.slides/iparagraphformateffectivedata).

### Ver também
* classe [`IParagraphFormatEffectiveData`](/slides/python-net/pt/aspose.slides/iparagraphformateffectivedata)
* classe [`ParagraphFormat`](/slides/python-net/pt/aspose.slides/paragraphformat)
* classe [`PVIObject`](/slides/python-net/pt/aspose.slides/pviobject)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)