---
title: IFontsManager class
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/ifontsmanager/
---
## IFontsManager classe

Manages fonts across the presentation.

The IFontsManager type exposes the following members:

## Propriedades

| Property | Description |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/pt/aspose.slides/ifontsmanager/font_subst_rule_list/) | Substituições de fonte a serem usadas ao renderizar<br/>            Leitura/gravação [`IFontSubstRuleCollection`](/slides/python-net/pt/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/pt/aspose.slides/ifontsmanager/font_fall_back_rules_collection/) | Representa a coleção de regras FontFallBack de um usuário para gerenciamento de coleções de fontes para substituições adequadas pela funcionalidade de fallback<br/>            Leitura/gravação [`IFontFallBackRulesCollection`](/slides/python-net/pt/aspose.slides/ifontfallbackrulescollection). |

## Métodos

| Method | Description |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/pt/aspose.slides/ifontsmanager/get_substitutions/#) | Obtém as informações sobre fontes que serão substituídas na renderização da apresentação. |
| [`get_substitutions(self, slides)`](/slides/python-net/pt/aspose.slides/ifontsmanager/get_substitutions/#listint) | Obtém as informações sobre fontes que serão substituídas durante a renderização dos slides especificados. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/pt/aspose.slides/ifontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Adiciona a fonte incorporada.<br/>            Tenha em mente ao copiar quaisquer fontes que a maioria das fontes é protegida por direitos autorais. Primeiro localize a licença de <br/>            uma fonte com antecedência e verifique se ela pode ser transferida livremente para outra máquina. Uma ArgumentException pode ser lançada se os dados da fonte forem None ou se esta fonte já estiver incorporada |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/pt/aspose.slides/ifontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Adiciona a fonte incorporada<br/>            Tenha em mente ao adicionar quaisquer fontes que a maioria das fontes é protegida por direitos autorais. Primeiro localize a licença de <br/>            uma fonte com antecedência e verifique se ela pode ser transferida livremente para outra máquina. Uma ArgumentException pode ser lançada se os dados da fonte forem None ou se esta fonte já estiver incorporada |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/pt/aspose.slides/ifontsmanager/replace_font/#ifontdata-ifontdata) | Substituir fonte na apresentação |
| [`replace_font(self, subst_rule)`](/slides/python-net/pt/aspose.slides/ifontsmanager/replace_font/#ifontsubstrule) | Substituir fonte na apresentação usando as informações fornecidas em [`IFontSubstRule`](/slides/python-net/pt/aspose.slides/ifontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/pt/aspose.slides/ifontsmanager/replace_font/#ifontsubstrulecollection) | Substituir fonte na apresentação usando as informações fornecidas na coleção de [`IFontSubstRule`](/slides/python-net/pt/aspose.slides/ifontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/pt/aspose.slides/ifontsmanager/get_fonts/#) | Retorna as fontes usadas na apresentação |
| [`get_embedded_fonts(self)`](/slides/python-net/pt/aspose.slides/ifontsmanager/get_embedded_fonts/#) | Retorna as fontes incorporadas na apresentação |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/pt/aspose.slides/ifontsmanager/remove_embedded_font/#ifontdata) | Remove a fonte incorporada |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/pt/aspose.slides/ifontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Recupera o array de bytes que representa os dados da fonte para um estilo de fonte especificado e dados de fonte. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/pt/aspose.slides/ifontsmanager/get_font_embedding_level/#bytes-str) | Determina o nível de incorporação de uma fonte a partir do array de bytes fornecido e do nome da fonte. |

### Veja Também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)