---
title: IFontsManager class
second_title: Referencia de API de Aspose.Slides para Python mediante .NET
description: 
type: docs
url: /es/aspose.slides/ifontsmanager/
---
## IFontsManager clase

Gestiona fuentes en toda la presentación.

El tipo IFontsManager expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/es/aspose.slides/ifontsmanager/font_subst_rule_list/) | Sustituciones de fuentes a usar al renderizar<br/>            Lectura/escritura [`IFontSubstRuleCollection`](/slides/python-net/es/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/es/aspose.slides/ifontsmanager/font_fall_back_rules_collection/) | Representa la colección de reglas FontFallBack de un usuario para gestionar colecciones de fuentes y permitir sustituciones adecuadas mediante la funcionalidad de reserva<br/>            Lectura/escritura [`IFontFallBackRulesCollection`](/slides/python-net/es/aspose.slides/ifontfallbackrulescollection). |
| [`prefer_registered_fonts_over_embedded`](/slides/python-net/es/aspose.slides/ifontsmanager/prefer_registered_fonts_over_embedded/) | Especifica si las fuentes registradas deben tener prioridad sobre las fuentes incrustadas con el mismo nombre y estilo.<br/>            Cuando está habilitado, las fuentes incrustadas coincidentes se reemplazan temporalmente por las fuentes registradas correspondientes durante la exportación. |

## Métodos

| Método | Descripción |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/es/aspose.slides/ifontsmanager/get_substitutions/#) | Obtiene la información sobre las fuentes que serán reemplazadas al renderizar la presentación. |
| [`get_substitutions(self, slides)`](/slides/python-net/es/aspose.slides/ifontsmanager/get_substitutions/#listint) | Obtiene la información sobre las fuentes que serán reemplazadas al renderizar las diapositivas especificadas. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/es/aspose.slides/ifontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Agrega la fuente incrustada.<br/>            Tenga en cuenta que la mayoría de las fuentes están protegidas por derechos de autor al copiar cualquier fuente. Primero localice la licencia de <br/>            una fuente y verifique que pueda transferirse libremente a otra máquina. Se puede lanzar una ArgumentException si los datos de la fuente son None o si esta fuente ya está incrustada |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/es/aspose.slides/ifontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Agrega la fuente incrustada<br/>            Tenga en cuenta que la mayoría de las fuentes están protegidas por derechos de autor al agregar cualquier fuente. Primero localice la licencia de <br/>            una fuente y verifique que pueda transferirse libremente a otra máquina. Se puede lanzar una ArgumentException si los datos de la fuente son None o si esta fuente ya está incrustada |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/es/aspose.slides/ifontsmanager/replace_font/#ifontdata-ifontdata) | Reemplaza la fuente en la presentación |
| [`replace_font(self, subst_rule)`](/slides/python-net/es/aspose.slides/ifontsmanager/replace_font/#ifontsubstrule) | Reemplaza la fuente en la presentación usando la información proporcionada en [`IFontSubstRule`](/slides/python-net/es/aspose.slides/ifontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/es/aspose.slides/ifontsmanager/replace_font/#ifontsubstrulecollection) | Reemplaza la fuente en la presentación usando la información proporcionada en la colección de [`IFontSubstRule`](/slides/python-net/es/aspose.slides/ifontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/es/aspose.slides/ifontsmanager/get_fonts/#) | Devuelve las fuentes usadas en la presentación |
| [`get_embedded_fonts(self)`](/slides/python-net/es/aspose.slides/ifontsmanager/get_embedded_fonts/#) | Devuelve las fuentes incrustadas en la presentación |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/es/aspose.slides/ifontsmanager/remove_embedded_font/#ifontdata) | Elimina la fuente incrustada |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/es/aspose.slides/ifontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Recupera la matriz de bytes que representa los datos de la fuente para un estilo y datos de fuente especificados. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/es/aspose.slides/ifontsmanager/get_font_embedding_level/#bytes-str) | Determina el nivel de incrustación de una fuente a partir de la matriz de bytes y el nombre de fuente proporcionados. |


### Ver también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)