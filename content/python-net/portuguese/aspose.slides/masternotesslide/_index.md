---
title: MasterNotesSlide class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/masternotesslide/
---
## MasterNotesSlide classe

Representa o slide mestre para notas.

**Herança:**[`MasterNotesSlide`](/slides/python-net/pt/aspose.slides/masternotesslide) → [`BaseSlide`](/slides/python-net/pt/aspose.slides/baseslide)

O tipo MasterNotesSlide expõe os seguintes membros:

## Propriedades

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/pt/aspose.slides/masternotesslide/shapes/) | Retorna as formas de um slide.<br/>            Somente leitura [`IShapeCollection`](/slides/python-net/pt/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/pt/aspose.slides/masternotesslide/controls/) | Retorna a coleção de controles ActiveX em um slide.<br/>            Somente leitura [`IControlCollection`](/slides/python-net/pt/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/pt/aspose.slides/masternotesslide/name/) | Retorna ou define o nome de um slide.<br/>            Leitura/gravação **str**. |
| [`slide_id`](/slides/python-net/pt/aspose.slides/masternotesslide/slide_id/) | Retorna o ID de um slide.<br/>            Somente leitura **int**. |
| [`custom_data`](/slides/python-net/pt/aspose.slides/masternotesslide/custom_data/) | Retorna os dados personalizados do slide.<br/>            Somente leitura [`ICustomData`](/slides/python-net/pt/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/pt/aspose.slides/masternotesslide/timeline/) | Retorna o objeto de linha do tempo de animação.<br/>            Somente leitura [`IAnimationTimeLine`](/slides/python-net/pt/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/pt/aspose.slides/masternotesslide/slide_show_transition/) | Retorna o objeto Transition que contém informações sobre<br/>            como o slide especificado avança durante uma apresentação de slides.<br/>            Somente leitura [`ISlideShowTransition`](/slides/python-net/pt/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/pt/aspose.slides/masternotesslide/background/) | Retorna o plano de fundo do slide.<br/>            Somente leitura [`IBackground`](/slides/python-net/pt/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/pt/aspose.slides/masternotesslide/hyperlink_queries/) | Fornece acesso fácil a hiperlinks contidos.<br/>            Somente leitura [`IHyperlinkQueries`](/slides/python-net/pt/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/pt/aspose.slides/masternotesslide/show_master_shapes/) | Especifica se as formas no slide mestre devem ser mostradas nos slides ou não.<br/>            Para o próprio slide mestre, esta propriedade sempre retorna `false`.<br/>            Leitura/gravação **bool**. |
| [`presentation`](/slides/python-net/pt/aspose.slides/masternotesslide/presentation/) | Retorna a interface IPresentation.<br/>            Somente leitura [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/pt/aspose.slides/masternotesslide/header_footer_manager/) | Retorna o gerenciador HeaderFooter do slide mestre de notas.<br/>            Somente leitura [`IMasterHandoutSlideHeaderFooterManager`](/slides/python-net/pt/aspose.slides/imasterhandoutslideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/pt/aspose.slides/masternotesslide/theme_manager/) | Retorna o gerenciador de tema.<br/>            Somente leitura [`IMasterThemeManager`](/slides/python-net/pt/aspose.slides.theme/imasterthememanager). |
| [`notes_style`](/slides/python-net/pt/aspose.slides/masternotesslide/notes_style/) | Retorna o estilo de um texto de notas.<br/>            Somente leitura [`ITextStyle`](/slides/python-net/pt/aspose.slides/itextstyle). |
| [`drawing_guides`](/slides/python-net/pt/aspose.slides/masternotesslide/drawing_guides/) | Retorna uma coleção de guias de desenho para o slide mestre de notas.<br/>            Somente leitura [`IDrawingGuidesCollection`](/slides/python-net/pt/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/pt/aspose.slides/masternotesslide/slide/) |  |

## Métodos

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/pt/aspose.slides/masternotesslide/join_portions_with_same_formatting/#) | Une runs com a mesma formatação em todos os parágrafos de todas as formas aceitáveis. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/pt/aspose.slides/masternotesslide/join_portions_with_same_formatting/#ishapecollection) | Une runs com a mesma formatação em todos os parágrafos em todas as formas aceitáveis. |
| [`equals(self, slide)`](/slides/python-net/pt/aspose.slides/masternotesslide/equals/#ibaseslide) | Determina se as duas instâncias de IBaseSlide são iguais.<br/>            O valor retornado é calculado com base na estrutura do slide e no conteúdo estático.<br/>            Dois slides são iguais se todas as formas, estilos, textos, animações e outras configurações, etc., forem iguais. A comparação não leva em conta valores de identificadores únicos, por exemplo SlideId, e conteúdo dinâmico, por exemplo o valor da data atual em um Marcador de data. |
| [`create_theme_effective(self)`](/slides/python-net/pt/aspose.slides/masternotesslide/create_theme_effective/#) | Retorna um tema efetivo para este slide. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/pt/aspose.slides/masternotesslide/find_shape_by_alt_text/#str) | Encontra a primeira ocorrência de uma forma com o texto alternativo especificado. |

### Veja Também
* classe [`BaseSlide`](/slides/python-net/pt/aspose.slides/baseslide)
* classe [`MasterNotesSlide`](/slides/python-net/pt/aspose.slides/masternotesslide)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)