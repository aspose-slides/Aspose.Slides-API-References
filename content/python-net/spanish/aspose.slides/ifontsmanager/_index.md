---
title: IFontsManager class
second_title: Aspose.Slides para Python mediante .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides/ifontsmanager/
---
## Clase IFontsManager

Manages fonts across the presentation.

The IFontsManager type exposes the following members:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/es/aspose.slides/ifontsmanager/font_subst_rule_list/) | Font substitutions to use when rendering<br/>            Read/write [`IFontSubstRuleCollection`](/slides/python-net/es/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/es/aspose.slides/ifontsmanager/font_fall_back_rules_collection/) | Represents a user's collection of FontFallBack rules for managing of collections of fonts for proper substitutions by fallback functionality<br/>            Read/write [`IFontFallBackRulesCollection`](/slides/python-net/es/aspose.slides/ifontfallbackrulescollection). |

## Métodos

| Método | Descripción |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/es/aspose.slides/ifontsmanager/get_substitutions/#) | Obtiene la información sobre las fuentes que serán reemplazadas en el renderizado de la presentación. |
| [`get_substitutions(self, slides)`](/slides/python-net/es/aspose.slides/ifontsmanager/get_substitutions/#listint) | Obtiene la información sobre las fuentes que serán reemplazadas durante el renderizado de las diapositivas especificadas. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/es/aspose.slides/ifontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Añade la fuente incrustada.<br/>            Keep in mind when copying any fonts that most fonts are copyrighted. First locate the license of <br/>            a font before hand and verify they can be freely transferred to another machine.An ArgumentException can be thrown if font data is None or this font is already embedded |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/es/aspose.slides/ifontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Añade la fuente incrustada<br/>            Keep in mind when adding any fonts that most fonts are copyrighted. First locate the license of <br/>            a font before hand and verify they can be freely transferred to another machine.An ArgumentException can be thrown if font data is None or this font is already embedded |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/es/aspose.slides/ifontsmanager/replace_font/#ifontdata-ifontdata) | Reemplaza la fuente en la presentación |
| [`replace_font(self, subst_rule)`](/slides/python-net/es/aspose.slides/ifontsmanager/replace_font/#ifontsubstrule) | Reemplaza la fuente en la presentación usando la información proporcionada en [`IFontSubstRule`](/slides/python-net/es/aspose.slides/ifontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/es/aspose.slides/ifontsmanager/replace_font/#ifontsubstrulecollection) | Reemplaza la fuente en la presentación usando la información proporcionada en la colección de [`IFontSubstRule`](/slides/python-net/es/aspose.slides/ifontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/es/aspose.slides/ifontsmanager/get_fonts/#) | Devuelve las fuentes usadas en la presentación |
| [`get_embedded_fonts(self)`](/slides/python-net/es/aspose.slides/ifontsmanager/get_embedded_fonts/#) | Devuelve las fuentes incrustadas en la presentación |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/es/aspose.slides/ifontsmanager/remove_embedded_font/#ifontdata) | Elimina la fuente incrustada |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/es/aspose.slides/ifontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Recupera el arreglo de bytes que representa los datos de la fuente para un estilo de fuente y datos de fuente especificados. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/es/aspose.slides/ifontsmanager/get_font_embedding_level/#bytes-str) | Determina el nivel de incrustación de una fuente a partir del arreglo de bytes y el nombre de la fuente proporcionados. |

### Ver también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)