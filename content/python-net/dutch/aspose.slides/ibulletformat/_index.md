---
title: IBulletFormat class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/ibulletformat/
---
## IBulletFormat klasse

Representeert alinea-bullet-opmaak-eigenschappen.

Het IBulletFormat-type biedt de volgende leden:

## Eigenschappen

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/nl/aspose.slides/ibulletformat/type/) | Geeft het bullet-type van een alinea terug of stelt dit in zonder overerving.<br/>            Lezen/schrijven [`BulletType`](/slides/python-net/nl/aspose.slides/bullettype). |
| [`char`](/slides/python-net/nl/aspose.slides/ibulletformat/char/) | Geeft het bullet-teken van een alinea terug of stelt dit in zonder overerving.<br/>            Lezen/schrijven **System.Char**. |
| [`font`](/slides/python-net/nl/aspose.slides/ibulletformat/font/) | Geeft het bullet-lettertype van een alinea terug of stelt dit in zonder overerving.<br/>            Lezen/schrijven [`IFontData`](/slides/python-net/nl/aspose.slides/ifontdata). |
| [`height`](/slides/python-net/nl/aspose.slides/ibulletformat/height/) | Geeft de bullet-hoogte van een alinea terug of stelt deze in zonder overerving.<br/>            De waarde float.NaN bepaalt dat de bullet de hoogte erft van het eerste gedeelte in de alinea.<br/>            Lezen/schrijven **float**. |
| [`color`](/slides/python-net/nl/aspose.slides/ibulletformat/color/) | Geeft het kleurformaat van een bullet van een alinea terug zonder overerving.<br/>            Alleen-lezen [`IColorFormat`](/slides/python-net/nl/aspose.slides/icolorformat). |
| [`picture`](/slides/python-net/nl/aspose.slides/ibulletformat/picture/) | Geeft de afbeelding die als bullet wordt gebruikt in een alinea terug zonder overerving.<br/>            Alleen-lezen [`ISlidesPicture`](/slides/python-net/nl/aspose.slides/islidespicture). |
| [`numbered_bullet_start_with`](/slides/python-net/nl/aspose.slides/ibulletformat/numbered_bullet_start_with/) | Geeft het eerste getal dat wordt gebruikt voor een groep genummerde bullets terug of stelt dit in zonder overerving.<br/>            Lezen/schrijven **int**. |
| [`numbered_bullet_style`](/slides/python-net/nl/aspose.slides/ibulletformat/numbered_bullet_style/) | Geeft de stijl van een genummerde bullet terug of stelt deze in zonder overerving.<br/>            Lezen/schrijven [`IBulletFormat.numbered_bullet_style`](/slides/python-net/nl/aspose.slides/ibulletformat/numbered_bullet_style). |
| [`is_bullet_hard_color`](/slides/python-net/nl/aspose.slides/ibulletformat/is_bullet_hard_color/) | Bepaalt of de bullet een eigen kleur heeft of deze erft van het eerste gedeelte in de alinea.<br/>            **NullableBool.True** als de bullet een eigen kleur heeft en **NullableBool.False** als de bullet de kleur erft van het eerste gedeelte in de alinea.<br/>            Lezen/schrijven [`NullableBool`](/slides/python-net/nl/aspose.slides/nullablebool). |
| [`is_bullet_hard_font`](/slides/python-net/nl/aspose.slides/ibulletformat/is_bullet_hard_font/) | Bepaalt of de bullet een eigen lettertype heeft of dit erft van het eerste gedeelte in de alinea.<br/>            **NullableBool.True** als de bullet een eigen lettertype heeft en **NullableBool.False** als de bullet het lettertype erft van het eerste gedeelte in de alinea.<br/>            Lezen/schrijven [`NullableBool`](/slides/python-net/nl/aspose.slides/nullablebool). |

## Methoden

| Method | Description |
| :- | :- |
| [`apply_default_paragraph_indents_shifts(self)`](/slides/python-net/nl/aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/#) | Stelt standaard niet-nul verschuivingen in voor de effectieve alinea-Indent en MarginLeft wanneer bullets ingeschakeld zijn (zoals PowerPoint doet als alinea-bullets/nummers worden ingeschakeld). Als bullets uitgeschakeld zijn, worden de alinea-Indent en MarginLeft gewoon gereset (zoals PowerPoint doet als alinea-bullets/nummers worden uitgeschakeld). Indent-verschuivingen worden toegepast met betrekking tot de huidige bullet-context - IBulletFormat.Type, .NumberedBulletStyle en FontHeight van het eerste gedeelte. Niet-nul indent-verschuivingen worden toegepast op de effectieve Indent en MarginLeft van de huidige alinea (zodat resulterende waarden lokale waarden worden). |
| [`get_effective(self)`](/slides/python-net/nl/aspose.slides/ibulletformat/get_effective/#) | Haalt de effectieve bullet-opmaakgegevens op met de toegepaste overerving. |

### Zie ook
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)