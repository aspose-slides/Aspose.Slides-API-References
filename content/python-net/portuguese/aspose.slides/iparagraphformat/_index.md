---
title: IParagraphFormat class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/iparagraphformat/
---
## IParagraphFormat classe

Esta classe contém as propriedades de formatação de parágrafo. Ao contrário de [`IParagraphFormatEffectiveData`](/slides/python-net/pt/aspose.slides/iparagraphformateffectivedata), todas as propriedades desta classe são graváveis.

O tipo IParagraphFormat expõe os seguintes membros:

## Propriedades

| Property | Description |
| :- | :- |
| [`bullet`](/slides/python-net/pt/aspose.slides/iparagraphformat/bullet/) | Retorna o formato de marcadores do parágrafo.<br/>            Somente leitura [`IBulletFormat`](/slides/python-net/pt/aspose.slides/ibulletformat). |
| [`depth`](/slides/python-net/pt/aspose.slides/iparagraphformat/depth/) | Retorna ou define a profundidade do parágrafo.<br/>            Valor 0 significa valor indefinido.<br/>            Leitura/gravação **int**. |
| [`alignment`](/slides/python-net/pt/aspose.slides/iparagraphformat/alignment/) | Retorna ou define o alinhamento de texto em um parágrafo sem herança.<br/>            Leitura/gravação [`TextAlignment`](/slides/python-net/pt/aspose.slides/textalignment). |
| [`space_within`](/slides/python-net/pt/aspose.slides/iparagraphformat/space_within/) | Retorna ou define a quantidade de espaço entre linhas de base em um parágrafo. Valor positivo significa porcentagem, negativo - tamanho em pontos. Nenhuma herança aplicada.<br/>            Leitura/gravação **float**. |
| [`space_before`](/slides/python-net/pt/aspose.slides/iparagraphformat/space_before/) | Retorna ou define a quantidade de espaço antes da primeira linha em um parágrafo sem herança.<br/>            Um valor positivo especifica a porcentagem do tamanho da fonte que o espaço em branco deve ter.<br/>            Um valor negativo especifica o tamanho do espaço em branco em pontos.<br/>            Leitura/gravação **float**. |
| [`space_after`](/slides/python-net/pt/aspose.slides/iparagraphformat/space_after/) | Retorna ou define a quantidade de espaço após a última linha em um parágrafo sem herança.<br/>            Um valor positivo especifica a porcentagem do tamanho da fonte que o espaço em branco deve ter.<br/>            Um valor negativo especifica o tamanho do espaço em branco em pontos.<br/>            Leitura/gravação **float**. |
| [`east_asian_line_break`](/slides/python-net/pt/aspose.slides/iparagraphformat/east_asian_line_break/) | Determina se a quebra de linha Leste-Ásia é usada em um parágrafo. Nenhuma herança aplicada.<br/>            Leitura/gravação [`NullableBool`](/slides/python-net/pt/aspose.slides/nullablebool). |
| [`right_to_left`](/slides/python-net/pt/aspose.slides/iparagraphformat/right_to_left/) | Determina se a escrita da direita para a esquerda é usada em um parágrafo. Nenhuma herança aplicada.<br/>            Leitura/gravação [`NullableBool`](/slides/python-net/pt/aspose.slides/nullablebool). |
| [`latin_line_break`](/slides/python-net/pt/aspose.slides/iparagraphformat/latin_line_break/) | Determina se a quebra de linha latina é usada em um parágrafo. Nenhuma herança aplicada.<br/>            Leitura/gravação [`NullableBool`](/slides/python-net/pt/aspose.slides/nullablebool). |
| [`hanging_punctuation`](/slides/python-net/pt/aspose.slides/iparagraphformat/hanging_punctuation/) | Determina se a pontuação suspensa é usada em um parágrafo. Nenhuma herança aplicada.<br/>            Leitura/gravação [`NullableBool`](/slides/python-net/pt/aspose.slides/nullablebool). |
| [`margin_left`](/slides/python-net/pt/aspose.slides/iparagraphformat/margin_left/) | Retorna ou define a margem esquerda em um parágrafo sem herança.<br/>            Leitura/gravação **float**. |
| [`margin_right`](/slides/python-net/pt/aspose.slides/iparagraphformat/margin_right/) | Retorna ou define a margem direita em um parágrafo sem herança.<br/>            Leitura/gravação **float**. |
| [`indent`](/slides/python-net/pt/aspose.slides/iparagraphformat/indent/) | Retorna ou define o recuo da primeira linha/recúo suspenso do parágrafo sem herança. O recuo suspenso pode ser definido com valores negativos.<br/>            Leitura/gravação **float**. |
| [`default_tab_size`](/slides/python-net/pt/aspose.slides/iparagraphformat/default_tab_size/) | Retorna ou define o tamanho padrão de tabulação sem herança.<br/>            Leitura/gravação **float**. |
| [`tabs`](/slides/python-net/pt/aspose.slides/iparagraphformat/tabs/) | Retorna as tabulações de um parágrafo. Nenhuma herança aplicada.<br/>            Somente leitura [`ITabCollection`](/slides/python-net/pt/aspose.slides/itabcollection). |
| [`font_alignment`](/slides/python-net/pt/aspose.slides/iparagraphformat/font_alignment/) | Retorna ou define um alinhamento de fonte em um parágrafo sem herança.<br/>            Leitura/gravação [`FontAlignment`](/slides/python-net/pt/aspose.slides/fontalignment). |
| [`default_portion_format`](/slides/python-net/pt/aspose.slides/iparagraphformat/default_portion_format/) | Retorna o formato padrão de porção de um parágrafo. Nenhuma herança aplicada.<br/>            Somente leitura [`IPortionFormat`](/slides/python-net/pt/aspose.slides/iportionformat). |

## Métodos

| Method | Description |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/pt/aspose.slides/iparagraphformat/get_effective/#) | Obtém os dados de formatação de parágrafo efetivos com a herança aplicada. |

### Observações

Esta classe é usada para retornar e manipular as propriedades de formatação de parágrafo definidas para o parágrafo específico. Isso significa que
            nenhuma herança é aplicada ao obter valores, portanto, na maioria dos casos você obterá valores significando "indefinido".

Para obter os valores de parâmetros de formatação efetivos, incluindo os herdados, você precisa usar o método [`IParagraphFormat.get_effective`](/slides/python-net/pt/aspose.slides/iparagraphformat/get_effective) 
            que retorna uma instância [`IParagraphFormatEffectiveData`](/slides/python-net/pt/aspose.slides/iparagraphformateffectivedata).

### Veja Também
* classe [`IParagraphFormatEffectiveData`](/slides/python-net/pt/aspose.slides/iparagraphformateffectivedata)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)