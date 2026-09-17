---
title: PortionFormat class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/portionformat/
---
## PortionFormat classe

Cette classe contient les propriétés de formatage des portions de texte. Contrairement à [`IPortionFormatEffectiveData`](/slides/python-net/fr/aspose.slides/iportionformateffectivedata), toutes les propriétés de cette classe sont modifiables.

**Héritage:**[`PortionFormat`](/slides/python-net/fr/aspose.slides/portionformat) → [`BasePortionFormat`](/slides/python-net/fr/aspose.slides/baseportionformat) → [`PVIObject`](/slides/python-net/fr/aspose.slides/pviobject)

Le type PortionFormat expose les membres suivants :

## Constructeurs

| Constructeur | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fr/aspose.slides/portionformat/__init__/#) | Initialise une nouvelle instance de la classe [`PortionFormat`](/slides/python-net/fr/aspose.slides/portionformat). |

## Propriétés

| Propriété | Description |
| :- | :- |
| [`line_format`](/slides/python-net/fr/aspose.slides/portionformat/line_format/) | Renvoie les propriétés LineFormat pour le contour du texte. Aucun héritage appliqué.<br/>            Lecture seule [`ILineFormat`](/slides/python-net/fr/aspose.slides/ilineformat). |
| [`fill_format`](/slides/python-net/fr/aspose.slides/portionformat/fill_format/) | Renvoie les propriétés FillFormat du texte. Aucun héritage appliqué.<br/>            Lecture seule [`IFillFormat`](/slides/python-net/fr/aspose.slides/ifillformat). |
| [`effect_format`](/slides/python-net/fr/aspose.slides/portionformat/effect_format/) | Renvoie les propriétés EffectFormat du texte. Aucun héritage appliqué.<br/>            Lecture seule [`IEffectFormat`](/slides/python-net/fr/aspose.slides/ieffectformat). |
| [`highlight_color`](/slides/python-net/fr/aspose.slides/portionformat/highlight_color/) | Renvoie la couleur utilisée pour mettre en évidence un texte. Aucun héritage appliqué.<br/>            Lecture seule [`IColorFormat`](/slides/python-net/fr/aspose.slides/icolorformat). |
| [`underline_line_format`](/slides/python-net/fr/aspose.slides/portionformat/underline_line_format/) | Renvoie les propriétés LineFormat utilisées pour le contour de la ligne de soulignement. Aucun héritage appliqué.<br/>            Lecture seule [`ILineFormat`](/slides/python-net/fr/aspose.slides/ilineformat). |
| [`underline_fill_format`](/slides/python-net/fr/aspose.slides/portionformat/underline_fill_format/) | Renvoie les propriétés FillFormat de la ligne de soulignement. Aucun héritage appliqué.<br/>            Lecture seule [`IFillFormat`](/slides/python-net/fr/aspose.slides/ifillformat). |
| [`font_bold`](/slides/python-net/fr/aspose.slides/portionformat/font_bold/) | Détermine si la police est en gras. Aucun héritage appliqué.<br/>            Lecture/écriture [`NullableBool`](/slides/python-net/fr/aspose.slides/nullablebool). |
| [`font_italic`](/slides/python-net/fr/aspose.slides/portionformat/font_italic/) | Détermine si la police est en italique. Aucun héritage appliqué.<br/>            Lecture/écriture [`NullableBool`](/slides/python-net/fr/aspose.slides/nullablebool). |
| [`kumimoji`](/slides/python-net/fr/aspose.slides/portionformat/kumimoji/) | Détermine si les nombres doivent ignorer la disposition verticale du texte propre aux langues orientales. Aucun héritage appliqué.<br/>            Lecture/écriture [`NullableBool`](/slides/python-net/fr/aspose.slides/nullablebool). |
| [`normalise_height`](/slides/python-net/fr/aspose.slides/portionformat/normalise_height/) | Détermine si la hauteur d’un texte doit être normalisée. Aucun héritage appliqué.<br/>            Lecture/écriture [`NullableBool`](/slides/python-net/fr/aspose.slides/nullablebool). |
| [`proof_disabled`](/slides/python-net/fr/aspose.slides/portionformat/proof_disabled/) | Détermine si le texte ne doit pas être vérifié. Aucun héritage appliqué.<br/>            Lecture/écriture [`NullableBool`](/slides/python-net/fr/aspose.slides/nullablebool). |
| [`font_underline`](/slides/python-net/fr/aspose.slides/portionformat/font_underline/) | Renvoie ou définit le type de soulignement du texte. Aucun héritage appliqué.<br/>            Lecture/écriture [`TextUnderlineType`](/slides/python-net/fr/aspose.slides/textunderlinetype). |
| [`text_cap_type`](/slides/python-net/fr/aspose.slides/portionformat/text_cap_type/) | Renvoie ou définit le type de capitalisation du texte. Aucun héritage appliqué.<br/>            Lecture/écriture [`TextCapType`](/slides/python-net/fr/aspose.slides/textcaptype). |
| [`strikethrough_type`](/slides/python-net/fr/aspose.slides/portionformat/strikethrough_type/) | Renvoie ou définit le type de barré d’un texte. Aucun héritage appliqué.<br/>            Lecture/écriture [`TextStrikethroughType`](/slides/python-net/fr/aspose.slides/textstrikethroughtype). |
| [`is_hard_underline_line`](/slides/python-net/fr/aspose.slides/portionformat/is_hard_underline_line/) | Détermine si le style de soulignement possède ses propres propriétés LineFormat ou les hérite<br/>            des propriétés LineFormat du texte.<br/>            Lecture/écriture [`NullableBool`](/slides/python-net/fr/aspose.slides/nullablebool). |
| [`is_hard_underline_fill`](/slides/python-net/fr/aspose.slides/portionformat/is_hard_underline_fill/) | Détermine si le style de soulignement possède ses propres propriétés FillFormat ou les hérite<br/>            des propriétés FillFormat du texte.<br/>            Lecture/écriture [`NullableBool`](/slides/python-net/fr/aspose.slides/nullablebool). |
| [`font_height`](/slides/python-net/fr/aspose.slides/portionformat/font_height/) | Renvoie ou définit la hauteur de police d’une portion.<br/>            **float.NaN** signifie que la hauteur est indéfinie et doit être héritée du maître.<br/>            Lecture/écriture **float**. |
| [`latin_font`](/slides/python-net/fr/aspose.slides/portionformat/latin_font/) | Renvoie ou définit les informations de police latine.<br/>            Null signifie que la police est indéfinie et doit être héritée du maître.<br/>            Lecture/écriture [`IFontData`](/slides/python-net/fr/aspose.slides/ifontdata). |
| [`east_asian_font`](/slides/python-net/fr/aspose.slides/portionformat/east_asian_font/) | Renvoie ou définit les informations de police Est-Asiatique.<br/>            Null signifie que la police est indéfinie et doit être héritée du maître.<br/>            Lecture/écriture [`IFontData`](/slides/python-net/fr/aspose.slides/ifontdata). |
| [`complex_script_font`](/slides/python-net/fr/aspose.slides/portionformat/complex_script_font/) | Renvoie ou définit les informations de police script complexe.<br/>            Null signifie que la police est indéfinie et doit être héritée du maître.<br/>            Lecture/écriture [`IFontData`](/slides/python-net/fr/aspose.slides/ifontdata). |
| [`symbol_font`](/slides/python-net/fr/aspose.slides/portionformat/symbol_font/) | Renvoie ou définit les informations de police symbolique.<br/>            Null signifie que la police est indéfinie et doit être héritée du maître.<br/>            Lecture/écriture [`IFontData`](/slides/python-net/fr/aspose.slides/ifontdata). |
| [`escapement`](/slides/python-net/fr/aspose.slides/portionformat/escapement/) | Renvoie ou définit le texte en exposant ou indice.<br/>            Valeur de -100 % (indice) à 100 % (exposant).<br/>            **float.NaN** signifie que la valeur est indéfinie et doit être héritée du maître.<br/>            Lecture/écriture **float**. |
| [`kerning_minimal_size`](/slides/python-net/fr/aspose.slides/portionformat/kerning_minimal_size/) | Renvoie ou définit la taille minimale de police, pour laquelle le crénage doit être activé.<br/>            **float.NaN** signifie que la valeur est indéfinie et doit être héritée du maître.<br/>            Lecture/écriture **float**. |
| [`language_id`](/slides/python-net/fr/aspose.slides/portionformat/language_id/) | Renvoie ou définit l’identifiant d’une langue de vérification. Utilisé pour la vérification orthographique et grammaticale.<br/>            Lecture/écriture **str**. |
| [`alternative_language_id`](/slides/python-net/fr/aspose.slides/portionformat/alternative_language_id/) | Renvoie ou définit l’identifiant d’une langue alternative.<br/>            Lecture/écriture **str**. |
| [`spacing`](/slides/python-net/fr/aspose.slides/portionformat/spacing/) | Renvoie ou définit l’incrément d’espacement intercaractères.<br/>            **float.NaN** signifie que la valeur est indéfinie et doit être héritée du maître.<br/>            Lecture/écriture **float**. |
| [`spell_check`](/slides/python-net/fr/aspose.slides/portionformat/spell_check/) | Obtient ou définit une valeur indiquant si la vérification orthographique est activée pour la portion de texte.<br/>            Lorsque cette propriété est définie sur false, les vérifications orthographiques des éléments de texte sont supprimées.<br/>            Lorsqu’elle est définie sur true, la vérification orthographique est autorisée.<br/>            La valeur par défaut est `false`. |
| [`bookmark_id`](/slides/python-net/fr/aspose.slides/portionformat/bookmark_id/) | Renvoie ou définit l’identifiant du signet.<br/>            Lecture/écriture **str**. |
| [`smart_tag_clean`](/slides/python-net/fr/aspose.slides/portionformat/smart_tag_clean/) | Détermine si la balise intelligente doit être nettoyée. Aucun héritage appliqué.<br/>            Lecture/écriture **bool**. |
| [`hyperlink_click`](/slides/python-net/fr/aspose.slides/portionformat/hyperlink_click/) | Renvoie ou définit le lien hypertexte défini pour le clic de souris.<br/>            Lecture/écriture [`IHyperlink`](/slides/python-net/fr/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/fr/aspose.slides/portionformat/hyperlink_mouse_over/) | Renvoie ou définit le lien hypertexte défini pour le survol de la souris.<br/>            Lecture/écriture [`IHyperlink`](/slides/python-net/fr/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/fr/aspose.slides/portionformat/hyperlink_manager/) | Gestionnaire de liens hypertexte.<br/>            Lecture seule [`IHyperlinkManager`](/slides/python-net/fr/aspose.slides/ihyperlinkmanager). |
| [`slide`](/slides/python-net/fr/aspose.slides/portionformat/slide/) |  |
| [`presentation`](/slides/python-net/fr/aspose.slides/portionformat/presentation/) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/fr/aspose.slides/portionformat/get_effective/#) | Obtient les données de formatage effectif de la portion avec l'héritage appliqué. |

### Remarques

Cette classe est utilisée pour renvoyer et manipuler les propriétés de formatage des portions de texte définies pour la portion spécifique. Cela signifie que
            aucun héritage n'est appliqué lors de la récupération des valeurs, ainsi dans la plupart des cas vous obtiendrez des valeurs signifiant "indéfini".

Afin d'obtenir les valeurs effectives des paramètres de formatage, y compris celles héritées, vous devez utiliser la méthode [`PortionFormat.get_effective`](/slides/python-net/fr/aspose.slides/portionformat/get_effective) 
            qui renvoie une instance [`IPortionFormatEffectiveData`](/slides/python-net/fr/aspose.slides/iportionformateffectivedata).

### Voir aussi
* classe [`BasePortionFormat`](/slides/python-net/fr/aspose.slides/baseportionformat)
* classe [`IPortionFormatEffectiveData`](/slides/python-net/fr/aspose.slides/iportionformateffectivedata)
* classe [`PortionFormat`](/slides/python-net/fr/aspose.slides/portionformat)
* classe [`PVIObject`](/slides/python-net/fr/aspose.slides/pviobject)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)