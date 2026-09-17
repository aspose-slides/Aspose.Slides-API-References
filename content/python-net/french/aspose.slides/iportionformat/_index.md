---
title: IPortionFormat class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/iportionformat/
---
## IPortionFormat classe

Cette classe contient les propriétés de mise en forme des portions de texte. Contrairement à [`IPortionFormatEffectiveData`](/slides/python-net/fr/aspose.slides/iportionformateffectivedata), toutes les propriétés de cette classe sont modifiables.

Le type IPortionFormat expose les membres suivants :

## Propriétés

| Property | Description |
| :- | :- |
| [`bookmark_id`](/slides/python-net/fr/aspose.slides/iportionformat/bookmark_id/) | Renvoie ou définit l'identifiant du signet.<br/>            Lecture/écriture **str**. |
| [`smart_tag_clean`](/slides/python-net/fr/aspose.slides/iportionformat/smart_tag_clean/) | Détermine si le smart tag doit être nettoyé. Aucun héritage appliqué.<br/>            Lecture/écriture **bool**. |
| [`line_format`](/slides/python-net/fr/aspose.slides/iportionformat/line_format/) |  |
| [`fill_format`](/slides/python-net/fr/aspose.slides/iportionformat/fill_format/) |  |
| [`effect_format`](/slides/python-net/fr/aspose.slides/iportionformat/effect_format/) |  |
| [`highlight_color`](/slides/python-net/fr/aspose.slides/iportionformat/highlight_color/) |  |
| [`underline_line_format`](/slides/python-net/fr/aspose.slides/iportionformat/underline_line_format/) |  |
| [`underline_fill_format`](/slides/python-net/fr/aspose.slides/iportionformat/underline_fill_format/) |  |
| [`font_bold`](/slides/python-net/fr/aspose.slides/iportionformat/font_bold/) |  |
| [`font_italic`](/slides/python-net/fr/aspose.slides/iportionformat/font_italic/) |  |
| [`kumimoji`](/slides/python-net/fr/aspose.slides/iportionformat/kumimoji/) |  |
| [`normalise_height`](/slides/python-net/fr/aspose.slides/iportionformat/normalise_height/) |  |
| [`proof_disabled`](/slides/python-net/fr/aspose.slides/iportionformat/proof_disabled/) |  |
| [`font_underline`](/slides/python-net/fr/aspose.slides/iportionformat/font_underline/) |  |
| [`text_cap_type`](/slides/python-net/fr/aspose.slides/iportionformat/text_cap_type/) |  |
| [`strikethrough_type`](/slides/python-net/fr/aspose.slides/iportionformat/strikethrough_type/) |  |
| [`is_hard_underline_line`](/slides/python-net/fr/aspose.slides/iportionformat/is_hard_underline_line/) |  |
| [`is_hard_underline_fill`](/slides/python-net/fr/aspose.slides/iportionformat/is_hard_underline_fill/) |  |
| [`font_height`](/slides/python-net/fr/aspose.slides/iportionformat/font_height/) |  |
| [`latin_font`](/slides/python-net/fr/aspose.slides/iportionformat/latin_font/) |  |
| [`east_asian_font`](/slides/python-net/fr/aspose.slides/iportionformat/east_asian_font/) |  |
| [`complex_script_font`](/slides/python-net/fr/aspose.slides/iportionformat/complex_script_font/) |  |
| [`symbol_font`](/slides/python-net/fr/aspose.slides/iportionformat/symbol_font/) |  |
| [`escapement`](/slides/python-net/fr/aspose.slides/iportionformat/escapement/) |  |
| [`kerning_minimal_size`](/slides/python-net/fr/aspose.slides/iportionformat/kerning_minimal_size/) |  |
| [`language_id`](/slides/python-net/fr/aspose.slides/iportionformat/language_id/) |  |
| [`alternative_language_id`](/slides/python-net/fr/aspose.slides/iportionformat/alternative_language_id/) |  |
| [`spacing`](/slides/python-net/fr/aspose.slides/iportionformat/spacing/) |  |
| [`spell_check`](/slides/python-net/fr/aspose.slides/iportionformat/spell_check/) |  |
| [`hyperlink_click`](/slides/python-net/fr/aspose.slides/iportionformat/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/fr/aspose.slides/iportionformat/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/fr/aspose.slides/iportionformat/hyperlink_manager/) |  |

## Méthodes

| Method | Description |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/fr/aspose.slides/iportionformat/get_effective/#) | Obtient les données de mise en forme de la portion effective avec l'héritage appliqué. |

### Remarques

Cette classe est utilisée pour renvoyer et manipuler les propriétés de mise en forme des portions de texte définies pour la portion particulière. Cela signifie que
            aucun héritage n'est appliqué lors de l'obtention des valeurs, donc dans la plupart des cas vous obtiendrez des valeurs signifiant « indéfini ».

Afin d'obtenir les valeurs effectives des paramètres de mise en forme, y compris celles héritées, vous devez utiliser la méthode [`IPortionFormat.get_effective`](/slides/python-net/fr/aspose.slides/iportionformat/get_effective) 
            qui renvoie une instance [`IPortionFormatEffectiveData`](/slides/python-net/fr/aspose.slides/iportionformateffectivedata).

### Voir aussi
* classe [`IPortionFormatEffectiveData`](/slides/python-net/fr/aspose.slides/iportionformateffectivedata)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)