---
title: NotesSlide class
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides/notesslide/
---
## NotesSlide classe

Representa um slide de notas em uma apresentação.

**Herança:**[`NotesSlide`](/slides/python-net/pt/aspose.slides/notesslide) → [`BaseSlide`](/slides/python-net/pt/aspose.slides/baseslide)

O tipo NotesSlide expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`shapes`](/slides/python-net/pt/aspose.slides/notesslide/shapes/) | Retorna as formas de um slide.<br/>            Somente leitura [`IShapeCollection`](/slides/python-net/pt/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/pt/aspose.slides/notesslide/controls/) | Retorna a coleção de controles ActiveX em um slide.<br/>            Somente leitura [`IControlCollection`](/slides/python-net/pt/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/pt/aspose.slides/notesslide/name/) | Retorna ou define o nome de um slide.<br/>            Leitura/gravação **str**. |
| [`slide_id`](/slides/python-net/pt/aspose.slides/notesslide/slide_id/) | Retorna o ID de um slide.<br/>            Somente leitura **int**. |
| [`custom_data`](/slides/python-net/pt/aspose.slides/notesslide/custom_data/) | Retorna os dados personalizados do slide.<br/>            Somente leitura [`ICustomData`](/slides/python-net/pt/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/pt/aspose.slides/notesslide/timeline/) | Retorna o objeto de linha do tempo de animação.<br/>            Somente leitura [`IAnimationTimeLine`](/slides/python-net/pt/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/pt/aspose.slides/notesslide/slide_show_transition/) | Retorna o objeto Transition que contém informações sobre<br/>            como o slide especificado avança durante a apresentação.<br/>            Somente leitura [`ISlideShowTransition`](/slides/python-net/pt/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/pt/aspose.slides/notesslide/background/) | Retorna o plano de fundo do slide.<br/>            Somente leitura [`IBackground`](/slides/python-net/pt/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/pt/aspose.slides/notesslide/hyperlink_queries/) | Fornece acesso fácil a hyperlinks contidos.<br/>            Somente leitura [`IHyperlinkQueries`](/slides/python-net/pt/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/pt/aspose.slides/notesslide/show_master_shapes/) | Especifica se as formas no slide mestre devem ser mostradas nos slides ou não.<br/>            Leitura/gravação **bool**. |
| [`presentation`](/slides/python-net/pt/aspose.slides/notesslide/presentation/) | Retorna a interface IPresentation.<br/>            Somente leitura [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/pt/aspose.slides/notesslide/header_footer_manager/) | Retorna o gerenciador HeaderFooter do slide de notas.<br/>            Somente leitura [`INotesSlideHeaderFooterManager`](/slides/python-net/pt/aspose.slides/inotesslideheaderfootermanager). |
| [`notes_text_frame`](/slides/python-net/pt/aspose.slides/notesslide/notes_text_frame/) | Retorna um TextFrame com o texto das notas, se houver.<br/>            Somente leitura [`ITextFrame`](/slides/python-net/pt/aspose.slides/itextframe). |
| [`theme_manager`](/slides/python-net/pt/aspose.slides/notesslide/theme_manager/) | Retorna o gerenciador de tema sobrescrito.<br/>            Somente leitura [`IOverrideThemeManager`](/slides/python-net/pt/aspose.slides.theme/ioverridethememanager). |
| [`parent_slide`](/slides/python-net/pt/aspose.slides/notesslide/parent_slide/) | Retorna o slide pai.<br/>            Somente leitura [`ISlide`](/slides/python-net/pt/aspose.slides/islide). |
| [`slide`](/slides/python-net/pt/aspose.slides/notesslide/slide/) |  |

## Métodos

| Método | Descrição |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/pt/aspose.slides/notesslide/join_portions_with_same_formatting/#) | Une sequências com a mesma formatação em todos os parágrafos de todas as formas aceitáveis. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/pt/aspose.slides/notesslide/join_portions_with_same_formatting/#ishapecollection) | Une sequências com a mesma formatação em todos os parágrafos em todas as formas aceitáveis. |
| [`equals(self, slide)`](/slides/python-net/pt/aspose.slides/notesslide/equals/#ibaseslide) | Determina se duas instâncias de IBaseSlide são iguais.<br/>            O valor retornado é calculado com base na estrutura do slide e no conteúdo estático.<br/>            Dois slides são iguais se todas as formas, estilos, textos, animações e outras configurações, etc., forem iguais. A comparação não leva em conta valores de identificadores únicos, como SlideId, e conteúdo dinâmico, como o valor da data atual em Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/pt/aspose.slides/notesslide/create_theme_effective/#) | Retorna um tema efetivo para este slide. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/pt/aspose.slides/notesslide/find_shape_by_alt_text/#str) | Encontra a primeira ocorrência de uma forma com o texto alternativo especificado. |

### Veja Também
* classe [`BaseSlide`](/slides/python-net/pt/aspose.slides/baseslide)
* classe [`NotesSlide`](/slides/python-net/pt/aspose.slides/notesslide)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)