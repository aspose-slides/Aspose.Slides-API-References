---
title: FontsManager class
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides/fontsmanager/
---
## FontsManager clase

Administra fuentes en toda la presentación.

El tipo FontsManager expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/es/aspose.slides/fontsmanager/font_subst_rule_list/) | Sustituciones de fuentes para usar al renderizar.<br/>            Lectura/escritura [`IFontSubstRuleCollection`](/slides/python-net/es/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/es/aspose.slides/fontsmanager/font_fall_back_rules_collection/) | Representa la colección de reglas FontFallBack de un usuario para gestionar colecciones de fuentes y permitir sustituciones adecuadas mediante la funcionalidad de reserva.<br/>            Lectura/escritura [`IFontFallBackRulesCollection`](/slides/python-net/es/aspose.slides/ifontfallbackrulescollection). |

## Métodos

| Método | Descripción |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/es/aspose.slides/fontsmanager/get_substitutions/#) | Obtiene la información sobre las fuentes que serán sustituidas en el renderizado de la presentación. |
| [`get_substitutions(self, slides)`](/slides/python-net/es/aspose.slides/fontsmanager/get_substitutions/#listint) | Obtiene la información sobre las fuentes que serán sustituidas durante el renderizado de las diapositivas especificadas. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/es/aspose.slides/fontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Añade la fuente incrustada<br/>            Tenga en cuenta que la mayoría de las fuentes están protegidas por derechos de autor al copiar cualquier fuente. Primero localice la licencia de <br/>            una fuente de antemano y verifique que pueda transferirse libremente a otra máquina. Se puede lanzar una ArgumentException si los datos de la fuente son None o si esta fuente ya está incrustada |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/es/aspose.slides/fontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Añade la fuente incrustada<br/>            Tenga en cuenta que la mayoría de las fuentes están protegidas por derechos de autor al copiar cualquier fuente. Primero localice la licencia de <br/>            una fuente de antemano y verifique que pueda transferirse libremente a otra máquina. Se puede lanzar una ArgumentException si los datos de la fuente son None o si esta fuente ya está incrustada |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/es/aspose.slides/fontsmanager/replace_font/#ifontdata-ifontdata) | Reemplaza la fuente en la presentación |
| [`replace_font(self, subst_rule)`](/slides/python-net/es/aspose.slides/fontsmanager/replace_font/#ifontsubstrule) | Reemplaza la fuente en la presentación utilizando la información proporcionada en [`FontSubstRule`](/slides/python-net/es/aspose.slides/fontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/es/aspose.slides/fontsmanager/replace_font/#ifontsubstrulecollection) | Reemplaza la fuente en la presentación utilizando la información proporcionada en la colección de [`FontSubstRule`](/slides/python-net/es/aspose.slides/fontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/es/aspose.slides/fontsmanager/get_fonts/#) | Devuelve las fuentes usadas en la presentación |
| [`get_embedded_fonts(self)`](/slides/python-net/es/aspose.slides/fontsmanager/get_embedded_fonts/#) | Devuelve las fuentes incrustadas en la presentación |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/es/aspose.slides/fontsmanager/remove_embedded_font/#ifontdata) | Elimina la fuente incrustada |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/es/aspose.slides/fontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Recupera la matriz de bytes que representa los datos de la fuente para un estilo de fuente y datos de fuente especificados. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/es/aspose.slides/fontsmanager/get_font_embedding_level/#bytes-str) | Determina el nivel de incrustación de una fuente a partir de la matriz de bytes y el nombre de la fuente proporcionados. |

### Ver también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)