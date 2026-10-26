---
title: BulletFormat class
second_title: Aspose.Slides para Python via referência de API .NET
description: 
type: docs
url: /pt/aspose.slides/bulletformat/
---
## BulletFormat classe

Representa as propriedades de formatação de marcadores de parágrafo.

**Herança:**[`BulletFormat`](/slides/python-net/pt/aspose.slides/bulletformat) → [`PVIObject`](/slides/python-net/pt/aspose.slides/pviobject)

O tipo BulletFormat expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`type`](/slides/python-net/pt/aspose.slides/bulletformat/type/) | Retorna ou define o tipo de marcador de um parágrafo sem herança.<br/>            Leitura/gravação [`BulletType`](/slides/python-net/pt/aspose.slides/bullettype). |
| [`char`](/slides/python-net/pt/aspose.slides/bulletformat/char/) | Retorna ou define o caractere de marcador de um parágrafo sem herança.<br/>            Leitura/gravação **System.Char**. |
| [`font`](/slides/python-net/pt/aspose.slides/bulletformat/font/) | Retorna ou define a fonte do marcador de um parágrafo sem herança.<br/>            Leitura/gravação [`IFontData`](/slides/python-net/pt/aspose.slides/ifontdata). |
| [`height`](/slides/python-net/pt/aspose.slides/bulletformat/height/) | Retorna ou define a altura do marcador de um parágrafo sem herança.<br/>            O valor float.NaN determina que o marcador herda a altura da primeira porção no parágrafo.<br/>            Leitura/gravação **float**. |
| [`color`](/slides/python-net/pt/aspose.slides/bulletformat/color/) | Retorna o formato de cor de um marcador de um parágrafo sem herança.<br/>            Somente leitura [`IColorFormat`](/slides/python-net/pt/aspose.slides/icolorformat). |
| [`numbered_bullet_start_with`](/slides/python-net/pt/aspose.slides/bulletformat/numbered_bullet_start_with/) | Retorna ou define o primeiro número usado para o grupo de marcadores numerados sem herança.<br/>            Leitura/gravação **int**. |
| [`numbered_bullet_style`](/slides/python-net/pt/aspose.slides/bulletformat/numbered_bullet_style/) | Retorna ou define o estilo de um marcador numerado sem herança.<br/>            Leitura/gravação [`NumberedBulletStyle`](/slides/python-net/pt/aspose.slides/numberedbulletstyle). |
| [`is_bullet_hard_color`](/slides/python-net/pt/aspose.slides/bulletformat/is_bullet_hard_color/) | Determina se o marcador tem cor própria ou a herda da primeira porção no parágrafo.<br/>            **NullableBool.True**  se o marcador tem cor própria e **NullableBool.False**  se o marcador<br/>            herda a cor da primeira porção no parágrafo.<br/>            Leitura/gravação [`NullableBool`](/slides/python-net/pt/aspose.slides/nullablebool). |
| [`is_bullet_hard_font`](/slides/python-net/pt/aspose.slides/bulletformat/is_bullet_hard_font/) | Determina se o marcador tem fonte própria ou a herda da primeira porção no parágrafo.<br/>            **NullableBool.True**  se o marcador tem fonte própria e **NullableBool.False**  se o marcador<br/>            herda a fonte da primeira porção no parágrafo.<br/>            Leitura/gravação [`NullableBool`](/slides/python-net/pt/aspose.slides/nullablebool). |
| [`picture`](/slides/python-net/pt/aspose.slides/bulletformat/picture/) | Retorna a imagem usada como marcador em um parágrafo sem herança.<br/>            Somente leitura [`ISlidesPicture`](/slides/python-net/pt/aspose.slides/islidespicture). |
| [`slide`](/slides/python-net/pt/aspose.slides/bulletformat/slide/) |  |
| [`presentation`](/slides/python-net/pt/aspose.slides/bulletformat/presentation/) |  |

## Métodos

| Método | Descrição |
| :- | :- |
| [`apply_default_paragraph_indents_shifts(self)`](/slides/python-net/pt/aspose.slides/bulletformat/apply_default_paragraph_indents_shifts/#) | Define os deslocamentos padrão diferentes de zero para Indent e MarginLeft efetivos do parágrafo quando marcadores estão habilitados (como o PowerPoint faz se habilitar marcadores/numerção de parágrafo nele). Se marcadores estiverem desabilitados, então apenas redefina Indent e MarginLeft do parágrafo (como o PowerPoint faz se desabilitar marcadores/numerção de parágrafo nele). Os deslocamentos de recuo são aplicados em relação ao contexto atual do marcador - IBulletFormat.Type, .NumberedBulletStyle e FontHeight da primeira porção. Deslocamentos de recuo diferentes de zero são aplicados ao Indent e MarginLeft efetivos do parágrafo atual (fazendo com que os valores resultantes sejam valores locais). |
| [`get_effective(self)`](/slides/python-net/pt/aspose.slides/bulletformat/get_effective/#) | Obtém os dados de formatação de marcador efetivos com a herança aplicada. |


### Veja Também
* classe [`BulletFormat`](/slides/python-net/pt/aspose.slides/bulletformat)
* classe [`PVIObject`](/slides/python-net/pt/aspose.slides/pviobject)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)