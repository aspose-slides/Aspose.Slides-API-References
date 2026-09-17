---
title: IBasePortionFormat class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat classe

Cette classe contient les propriétés de formatage des portions de texte. Contrairement à [`IPortionFormatEffectiveData`](/slides/python-net/fr/aspose.slides/iportionformateffectivedata), toutes les propriétés de cette classe sont modifiables.

Le type IBasePortionFormat expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`line_format`](/slides/python-net/fr/aspose.slides/ibaseportionformat/line_format/) | Renvoie les propriétés LineFormat pour le contour du texte. Aucun héritage appliqué.<br/>            Lecture seule [`ILineFormat`](/slides/python-net/fr/aspose.slides/ilineformat). |
| [`fill_format`](/slides/python-net/fr/aspose.slides/ibaseportionformat/fill_format/) | Renvoie les propriétés FillFormat du texte. Aucun héritage appliqué.<br/>            Lecture seule [`IFillFormat`](/slides/python-net/fr/aspose.slides/ifillformat). |
| [`effect_format`](/slides/python-net/fr/aspose.slides/ibaseportionformat/effect_format/) | Renvoie les propriétés EffectFormat du texte. Aucun héritage appliqué.<br/>            Lecture seule [`IEffectFormat`](/slides/python-net/fr/aspose.slides/ieffectformat). |
| [`highlight_color`](/slides/python-net/fr/aspose.slides/ibaseportionformat/highlight_color/) | Renvoie la couleur utilisée pour mettre en évidence un texte. Aucun héritage appliqué.<br/>            Lecture seule [`IColorFormat`](/slides/python-net/fr/aspose.slides/icolorformat). |
| [`underline_line_format`](/slides/python-net/fr/aspose.slides/ibaseportionformat/underline_line_format/) | Renvoie les propriétés LineFormat utilisées pour le contour de la ligne de soulignement. Aucun héritage appliqué.<br/>            Lecture seule [`ILineFormat`](/slides/python-net/fr/aspose.slides/ilineformat). |
| [`underline_fill_format`](/slides/python-net/fr/aspose.slides/ibaseportionformat/underline_fill_format/) | Renvoie les propriétés FillFormat de la ligne de soulignement. Aucun héritage appliqué.<br/>            Lecture seule [`IFillFormat`](/slides/python-net/fr/aspose.slides/ifillformat). |
| [`font_bold`](/slides/python-net/fr/aspose.slides/ibaseportionformat/font_bold/) | Détermine si la police est en gras. Aucun héritage appliqué.<br/>            Lecture/écriture [`NullableBool`](/slides/python-net/fr/aspose.slides/nullablebool). |
| [`font_italic`](/slides/python-net/fr/aspose.slides/ibaseportionformat/font_italic/) | Détermine si la police est en italique. Aucun héritage appliqué.<br/>            Lecture/écriture [`NullableBool`](/slides/python-net/fr/aspose.slides/nullablebool). |
| [`kumimoji`](/slides/python-net/fr/aspose.slides/ibaseportionformat/kumimoji/) | Détermine si les nombres doivent ignorer la disposition verticale du texte propre aux langues orientales. Aucun héritage appliqué.<br/>            Lecture/écriture [`NullableBool`](/slides/python-net/fr/aspose.slides/nullablebool). |
| [`normalise_height`](/slides/python-net/fr/aspose.slides/ibaseportionformat/normalise_height/) | Détermine si la hauteur du texte doit être normalisée. Aucun héritage appliqué.<br/>            Lecture/écriture [`NullableBool`](/slides/python-net/fr/aspose.slides/nullablebool). |
| [`proof_disabled`](/slides/python-net/fr/aspose.slides/ibaseportionformat/proof_disabled/) | Détermine si le texte ne doit pas être révisé. Aucun héritage appliqué.<br/>            Lecture/écriture [`NullableBool`](/slides/python-net/fr/aspose.slides/nullablebool). |
| [`font_underline`](/slides/python-net/fr/aspose.slides/ibaseportionformat/font_underline/) | Renvoie ou définit le type de soulignement du texte. Aucun héritage appliqué.<br/>            Lecture/écriture [`TextUnderlineType`](/slides/python-net/fr/aspose.slides/textunderlinetype). |
| [`text_cap_type`](/slides/python-net/fr/aspose.slides/ibaseportionformat/text_cap_type/) | Renvoie ou définit le type de capitalisation du texte. Aucun héritage appliqué.<br/>            Lecture/écriture [`TextCapType`](/slides/python-net/fr/aspose.slides/textcaptype). |
| [`strikethrough_type`](/slides/python-net/fr/aspose.slides/ibaseportionformat/strikethrough_type/) | Renvoie ou définit le type de barré du texte. Aucun héritage appliqué.<br/>            Lecture/écriture [`TextStrikethroughType`](/slides/python-net/fr/aspose.slides/textstrikethroughtype). |
| [`is_hard_underline_line`](/slides/python-net/fr/aspose.slides/ibaseportionformat/is_hard_underline_line/) | Détermine si le style de soulignement possède ses propres propriétés LineFormat ou les hérite des propriétés LineFormat du texte.<br/>            Lecture/écriture [`NullableBool`](/slides/python-net/fr/aspose.slides/nullablebool). |
| [`is_hard_underline_fill`](/slides/python-net/fr/aspose.slides/ibaseportionformat/is_hard_underline_fill/) | Détermine si le style de soulignement possède ses propres propriétés FillFormat ou les hérite des propriétés FillFormat du texte.<br/>            Lecture/écriture [`NullableBool`](/slides/python-net/fr/aspose.slides/nullablebool). |
| [`font_height`](/slides/python-net/fr/aspose.slides/ibaseportionformat/font_height/) | Renvoie ou définit la hauteur de police d'une portion.<br/>            **float.NaN**  signifie que la hauteur n'est pas définie et doit être héritée du Maître.<br/>            Lecture/écriture **float**. |
| [`latin_font`](/slides/python-net/fr/aspose.slides/ibaseportionformat/latin_font/) | Renvoie ou définit les informations de police Latin.<br/>            Null signifie que la police n'est pas définie et doit être héritée du Maître.<br/>            Lecture/écriture [`IFontData`](/slides/python-net/fr/aspose.slides/ifontdata). |
| [`east_asian_font`](/slides/python-net/fr/aspose.slides/ibaseportionformat/east_asian_font/) | Renvoie ou définit les informations de police Est-asiatique.<br/>            Null signifie que la police n'est pas définie et doit être héritée du Maître.<br/>            Lecture/écriture [`IFontData`](/slides/python-net/fr/aspose.slides/ifontdata). |
| [`complex_script_font`](/slides/python-net/fr/aspose.slides/ibaseportionformat/complex_script_font/) | Renvoie ou définit les informations de police d'écriture complexe.<br/>            Null signifie que la police n'est pas définie et doit être héritée du Maître.<br/>            Lecture/écriture [`IFontData`](/slides/python-net/fr/aspose.slides/ifontdata). |
| [`symbol_font`](/slides/python-net/fr/aspose.slides/ibaseportionformat/symbol_font/) | Renvoie ou définit les informations de police symbolique.<br/>            Null signifie que la police n'est pas définie et doit être héritée du Maître.<br/>            Lecture/écriture [`IFontData`](/slides/python-net/fr/aspose.slides/ifontdata). |
| [`escapement`](/slides/python-net/fr/aspose.slides/ibaseportionformat/escapement/) | Renvoie ou définit le texte en exposant ou indice.<br/>            Valeur de -100% (indice) à 100% (exposant).<br/>            **float.NaN**  signifie que la valeur n'est pas définie et doit être héritée du Maître.<br/>            Lecture/écriture **float**. |
| [`kerning_minimal_size`](/slides/python-net/fr/aspose.slides/ibaseportionformat/kerning_minimal_size/) | Renvoie ou définit la taille de police minimale, à partir de laquelle le crénage doit être activé.<br/>            **float.NaN**  signifie que la valeur n'est pas définie et doit être héritée du Maître.<br/>            Lecture/écriture **float**. |
| [`language_id`](/slides/python-net/fr/aspose.slides/ibaseportionformat/language_id/) | Renvoie ou définit l'Id d'une langue de révision. Utilisé pour la vérification orthographique et grammaticale.<br/>            Lecture/écriture **str**. |
| [`alternative_language_id`](/slides/python-net/fr/aspose.slides/ibaseportionformat/alternative_language_id/) | Renvoie ou définit l'Id d'une langue alternative.<br/>            Lecture/écriture **str**. |
| [`spacing`](/slides/python-net/fr/aspose.slides/ibaseportionformat/spacing/) | Renvoie ou définit l'incrément de l'espacement intercaractères.<br/>            **float.NaN**  signifie que la valeur n'est pas définie et doit être héritée du Maître.<br/>            Lecture/écriture **float**. |
| [`spell_check`](/slides/python-net/fr/aspose.slides/ibaseportionformat/spell_check/) | Obtient ou définit une valeur indiquant si la vérification orthographique est activée pour la portion de texte.<br/>            Lorsque cette propriété est définie sur false, les vérifications orthographiques des éléments texte sont supprimées.<br/>            Lorsqu'elle est définie sur true, la vérification orthographique est autorisée.<br/>            La valeur par défaut est `false`. |

### Remarques

Cette classe est utilisée pour renvoyer et manipuler les propriétés de formatage de portion de texte définies pour la portion particulière. Cela signifie que
            aucun héritage n'est appliqué lors de l'obtention des valeurs, donc dans la plupart des cas vous obtiendrez des valeurs signifiant « indéfini ».

Afin d'obtenir les valeurs effectives des paramètres de formatage, y compris héritées, vous devez utiliser la méthode [`IPortionFormat.get_effective`](/slides/python-net/fr/aspose.slides/iportionformat/get_effective) 
            qui renvoie une instance [`IPortionFormatEffectiveData`](/slides/python-net/fr/aspose.slides/iportionformateffectivedata).

### Voir aussi
* classe [`IPortionFormatEffectiveData`](/slides/python-net/fr/aspose.slides/iportionformateffectivedata)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)