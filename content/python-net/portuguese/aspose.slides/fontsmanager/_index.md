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

| Propriedade | Descrição |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/pt/aspose.slides/fontsmanager/font_subst_rule_list/) | Substituições de fonte a serem usadas ao renderizar.<br/>            Leitura/escrita [`IFontSubstRuleCollection`](/slides/python-net/pt/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/pt/aspose.slides/fontsmanager/font_fall_back_rules_collection/) | Representa a coleção de regras FontFallBack de um usuário para gerenciar coleções de fontes para substituições adequadas pela funcionalidade de fallback<br/>            Leitura/escrita [`IFontFallBackRulesCollection`](/slides/python-net/pt/aspose.slides/ifontfallbackrulescollection). |

## Métodos

| Método | Descrição |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/pt/aspose.slides/fontsmanager/get_substitutions/#) | Obtém as informações sobre as fontes que serão substituídas ao renderizar a apresentação. |
| [`get_substitutions(self, slides)`](/slides/python-net/pt/aspose.slides/fontsmanager/get_substitutions/#listint) | Obtém as informações sobre as fontes que serão substituídas durante a renderização dos slides especificados. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/pt/aspose.slides/fontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Adiciona a fonte incorporada<br/>            Tenha em mente ao copiar quaisquer fontes que a maioria das fontes é protegida por direitos autorais. Primeiro localize a licença de <br/>            uma fonte antecipadamente e verifique se pode ser transferida livremente para outra máquina. Uma ArgumentException pode ser lançada se os dados da fonte forem None ou se esta fonte já estiver incorporada |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/pt/aspose.slides/fontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Adiciona a fonte incorporada<br/>            Tenha em mente ao copiar quaisquer fontes que a maioria das fontes é protegida por direitos autorais. Primeiro localize a licença de <br/>            uma fonte antecipadamente e verifique se pode ser transferida livremente para outra máquina. Uma ArgumentException pode ser lançada se os dados da fonte forem None ou se esta fonte já estiver incorporada |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/pt/aspose.slides/fontsmanager/replace_font/#ifontdata-ifontdata) | Substitui fonte na apresentação |
| [`replace_font(self, subst_rule)`](/slides/python-net/pt/aspose.slides/fontsmanager/replace_font/#ifontsubstrule) | Substitui fonte na apresentação usando as informações fornecidas em [`FontSubstRule`](/slides/python-net/pt/aspose.slides/fontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/pt/aspose.slides/fontsmanager/replace_font/#ifontsubstrulecollection) | Substitui fonte na apresentação usando as informações fornecidas na coleção de [`FontSubstRule`](/slides/python-net/pt/aspose.slides/fontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/pt/aspose.slides/fontsmanager/get_fonts/#) | Retorna as fontes usadas na apresentação |
| [`get_embedded_fonts(self)`](/slides/python-net/pt/aspose.slides/fontsmanager/get_embedded_fonts/#) | Retorna as fontes incorporadas na apresentação |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/pt/aspose.slides/fontsmanager/remove_embedded_font/#ifontdata) | Remove a fonte incorporada |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/pt/aspose.slides/fontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Recupera o array de bytes que representa os dados da fonte para um estilo de fonte e dados de fonte especificados. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/pt/aspose.slides/fontsmanager/get_font_embedding_level/#bytes-str) | Determina o nível de incorporação de uma fonte a partir do array de bytes e do nome da fonte fornecidos. |

### Ver também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)