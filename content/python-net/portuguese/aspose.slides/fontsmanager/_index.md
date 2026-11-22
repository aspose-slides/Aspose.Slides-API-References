---
title: FontsManager class
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/fontsmanager/
---
## FontsManager classe

Gerencia fontes em toda a apresentação.

O tipo FontsManager expõe os seguintes membros:

## Propriedades

| Property | Description |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/pt/aspose.slides/fontsmanager/font_subst_rule_list/) | Substituições de fonte a serem usadas ao renderizar.<br/>            Leitura/Gravação [`IFontSubstRuleCollection`](/slides/python-net/pt/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/pt/aspose.slides/fontsmanager/font_fall_back_rules_collection/) | Representa a coleção de regras FontFallBack de um usuário para gerenciamento de coleções de fontes para substituições adequadas por funcionalidade de fallback<br/>            Leitura/Gravação [`IFontFallBackRulesCollection`](/slides/python-net/pt/aspose.slides/ifontfallbackrulescollection). |
| [`prefer_registered_fonts_over_embedded`](/slides/python-net/pt/aspose.slides/fontsmanager/prefer_registered_fonts_over_embedded/) | Especifica se fontes registradas devem ser priorizadas sobre fontes incorporadas com o mesmo nome e estilo de fonte.<br/>            Quando habilitado, fontes incorporadas correspondentes são temporariamente substituídas por fontes registradas correspondentes durante a exportação. |

## Métodos

| Method | Description |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/pt/aspose.slides/fontsmanager/get_substitutions/#) | Obtém a informação sobre fontes que serão substituídas na renderização da apresentação. |
| [`get_substitutions(self, slides)`](/slides/python-net/pt/aspose.slides/fontsmanager/get_substitutions/#listint) | Obtém a informação sobre fontes que serão substituídas durante a renderização dos slides especificados. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/pt/aspose.slides/fontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Adiciona a fonte incorporada<br/>            Tenha em mente ao copiar quaisquer fontes que a maioria das fontes é protegida por direitos autorais. Primeiro localize a licença de <br/>            uma fonte antecipadamente e verifique se ela pode ser livremente transferida para outra máquina. Uma ArgumentException pode ser lançada se os dados da fonte forem None ou se esta fonte já estiver incorporada |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/pt/aspose.slides/fontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Adiciona a fonte incorporada<br/>            Tenha em mente ao copiar quaisquer fontes que a maioria das fontes é protegida por direitos autorais. Primeiro localize a licença de <br/>            uma fonte antecipadamente e verifique se ela pode ser livremente transferida para outra máquina. Uma ArgumentException pode ser lançada se os dados da fonte forem None ou se esta fonte já estiver incorporada |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/pt/aspose.slides/fontsmanager/replace_font/#ifontdata-ifontdata) | Substituir fonte na apresentação |
| [`replace_font(self, subst_rule)`](/slides/python-net/pt/aspose.slides/fontsmanager/replace_font/#ifontsubstrule) | Substituir fonte na apresentação usando informações fornecidas em [`FontSubstRule`](/slides/python-net/pt/aspose.slides/fontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/pt/aspose.slides/fontsmanager/replace_font/#ifontsubstrulecollection) | Substituir fonte na apresentação usando informações fornecidas na coleção de [`FontSubstRule`](/slides/python-net/pt/aspose.slides/fontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/pt/aspose.slides/fontsmanager/get_fonts/#) | Retorna as fontes usadas na apresentação |
| [`get_embedded_fonts(self)`](/slides/python-net/pt/aspose.slides/fontsmanager/get_embedded_fonts/#) | Retorna as fontes incorporadas na apresentação |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/pt/aspose.slides/fontsmanager/remove_embedded_font/#ifontdata) | Remove a fonte incorporada |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/pt/aspose.slides/fontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Recupera o array de bytes que representa os dados da fonte para um estilo de fonte e dados de fonte especificados. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/pt/aspose.slides/fontsmanager/get_font_embedding_level/#bytes-str) | Determina o nível de incorporação de uma fonte a partir do array de bytes fornecido e do nome da fonte. |

### Veja Também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)