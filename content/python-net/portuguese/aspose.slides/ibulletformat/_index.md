---
title: IBulletFormat class
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/ibulletformat/
---
## IBulletFormat classe

Representa as propriedades de formatação de marcadores de parágrafo.

O tipo IBulletFormat expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`type`](/slides/python-net/pt/aspose.slides/ibulletformat/type/) | Retorna ou define o tipo de marcador de um parágrafo sem herança.<br/>            Leitura/Gravação [`BulletType`](/slides/python-net/pt/aspose.slides/bullettype). |
| [`char`](/slides/python-net/pt/aspose.slides/ibulletformat/char/) | Retorna ou define o caractere de marcador de um parágrafo sem herança.<br/>            Leitura/Gravação **System.Char**. |
| [`font`](/slides/python-net/pt/aspose.slides/ibulletformat/font/) | Retorna ou define a fonte de marcador de um parágrafo sem herança.<br/>            Leitura/Gravação [`IFontData`](/slides/python-net/pt/aspose.slides/ifontdata). |
| [`height`](/slides/python-net/pt/aspose.slides/ibulletformat/height/) | Retorna ou define a altura do marcador de um parágrafo sem herança.<br/>            O valor float.NaN determina que o marcador herda a altura da primeira porção no parágrafo.<br/>            Leitura/Gravação **float**. |
| [`color`](/slides/python-net/pt/aspose.slides/ibulletformat/color/) | Retorna o formato de cor de um marcador de um parágrafo sem herança.<br/>            Somente leitura [`IColorFormat`](/slides/python-net/pt/aspose.slides/icolorformat). |
| [`picture`](/slides/python-net/pt/aspose.slides/ibulletformat/picture/) | Retorna a imagem usada como marcador em um parágrafo sem herança.<br/>            Somente leitura [`ISlidesPicture`](/slides/python-net/pt/aspose.slides/islidespicture). |
| [`numbered_bullet_start_with`](/slides/python-net/pt/aspose.slides/ibulletformat/numbered_bullet_start_with/) | Retorna ou define o primeiro número usado para o grupo de marcadores numerados sem herança.<br/>            Leitura/Gravação **int**. |
| [`numbered_bullet_style`](/slides/python-net/pt/aspose.slides/ibulletformat/numbered_bullet_style/) | Retorna ou define o estilo de um marcador numerado sem herança.<br/>            Leitura/Gravação [`IBulletFormat.numbered_bullet_style`](/slides/python-net/pt/aspose.slides/ibulletformat/numbered_bullet_style). |
| [`is_bullet_hard_color`](/slides/python-net/pt/aspose.slides/ibulletformat/is_bullet_hard_color/) | Determina se o marcador tem cor própria ou a herda da primeira porção no parágrafo.<br/>            **NullableBool.True**  se o marcador tem cor própria e **NullableBool.False**  se o marcador<br/>            herda a cor da primeira porção no parágrafo.<br/>            Leitura/Gravação [`NullableBool`](/slides/python-net/pt/aspose.slides/nullablebool). |
| [`is_bullet_hard_font`](/slides/python-net/pt/aspose.slides/ibulletformat/is_bullet_hard_font/) | Determina se o marcador tem fonte própria ou a herda da primeira porção no parágrafo.<br/>            **NullableBool.True**  se o marcador tem fonte própria e **NullableBool.False**  se o marcador<br/>            herda a fonte da primeira porção no parágrafo.<br/>            Leitura/Gravação [`NullableBool`](/slides/python-net/pt/aspose.slides/nullablebool). |

## Métodos

| Método | Descrição |
| :- | :- |
| [`apply_default_paragraph_indents_shifts(self)`](/slides/python-net/pt/aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/#) | Define deslocamentos padrão diferentes de zero para o recuo efetivo do parágrafo (Indent) e MarginLeft quando os marcadores estão habilitados (como o PowerPoint faz ao habilitar marcadores/numerção de parágrafos). Se os marcadores estiverem desabilitados, apenas reinicia o recuo (Indent) e MarginLeft do parágrafo (como o PowerPoint faz ao desabilitar marcadores/numerção de parágrafos). Os deslocamentos de recuo são aplicados em relação ao contexto atual do marcador – IBulletFormat.Type, .NumberedBulletStyle e FontHeight da primeira porção. Deslocamentos de recuo diferentes de zero são aplicados ao Indent e MarginLeft efetivos do parágrafo atual (fazendo com que os valores resultantes sejam valores locais). |
| [`get_effective(self)`](/slides/python-net/pt/aspose.slides/ibulletformat/get_effective/#) | Obtém os dados de formatação de marcadores efetivos com a herança aplicada. |

### Ver também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)