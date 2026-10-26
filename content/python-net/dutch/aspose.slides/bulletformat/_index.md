---
title: BulletFormat class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/bulletformat/
---
## BulletFormat klasse

Stelt de bullet-opmaak-eigenschappen van een alinea voor.

**Erfenis:**[`BulletFormat`](/slides/python-net/nl/aspose.slides/bulletformat) → [`PVIObject`](/slides/python-net/nl/aspose.slides/pviobject)

Het type BulletFormat maakt de volgende leden beschikbaar:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`type`](/slides/python-net/nl/aspose.slides/bulletformat/type/) | Retourneert of stelt het bullettype van een alinea in zonder erfelijkheid.<br/>            Lezen/Schrijven [`BulletType`](/slides/python-net/nl/aspose.slides/bullettype). |
| [`char`](/slides/python-net/nl/aspose.slides/bulletformat/char/) | Retourneert of stelt het bullet-teken van een alinea in zonder erfelijkheid.<br/>            Lezen/Schrijven **System.Char**. |
| [`font`](/slides/python-net/nl/aspose.slides/bulletformat/font/) | Retourneert of stelt het bullet-lettertype van een alinea in zonder erfelijkheid.<br/>            Lezen/Schrijven [`IFontData`](/slides/python-net/nl/aspose.slides/ifontdata). |
| [`height`](/slides/python-net/nl/aspose.slides/bulletformat/height/) | Retourneert of stelt de bullethoogte van een alinea in zonder erfelijkheid.<br/>            De waarde float.NaN bepaalt dat de bullet de hoogte erft van het eerste gedeelte in de alinea.<br/>            Lezen/Schrijven **float**. |
| [`color`](/slides/python-net/nl/aspose.slides/bulletformat/color/) | Retourneert het kleurformaat van een bullet van een alinea zonder erfelijkheid.<br/>            Alleen-lezen [`IColorFormat`](/slides/python-net/nl/aspose.slides/icolorformat). |
| [`numbered_bullet_start_with`](/slides/python-net/nl/aspose.slides/bulletformat/numbered_bullet_start_with/) | Retourneert of stelt het eerste getal in dat wordt gebruikt voor een groep genummerde bullets zonder erfelijkheid.<br/>            Lezen/Schrijven **int**. |
| [`numbered_bullet_style`](/slides/python-net/nl/aspose.slides/bulletformat/numbered_bullet_style/) | Retourneert of stelt de stijl van een genummerde bullet in zonder erfelijkheid.<br/>            Lezen/Schrijven [`NumberedBulletStyle`](/slides/python-net/nl/aspose.slides/numberedbulletstyle). |
| [`is_bullet_hard_color`](/slides/python-net/nl/aspose.slides/bulletformat/is_bullet_hard_color/) | Bepaalt of de bullet een eigen kleur heeft of deze erft van het eerste gedeelte in de alinea.<br/>            **NullableBool.True**  als de bullet een eigen kleur heeft en **NullableBool.False**  als de bullet<br/>            kleur erft van het eerste gedeelte in de alinea.<br/>            Lezen/Schrijven [`NullableBool`](/slides/python-net/nl/aspose.slides/nullablebool). |
| [`is_bullet_hard_font`](/slides/python-net/nl/aspose.slides/bulletformat/is_bullet_hard_font/) | Bepaalt of de bullet een eigen lettertype heeft of dit erft van het eerste gedeelte in de alinea.<br/>            **NullableBool.True**  als de bullet een eigen lettertype heeft en **NullableBool.False**  als de bullet<br/>            lettertype erft van het eerste gedeelte in de alinea.<br/>            Lezen/Schrijven [`NullableBool`](/slides/python-net/nl/aspose.slides/nullablebool). |
| [`picture`](/slides/python-net/nl/aspose.slides/bulletformat/picture/) | Retourneert de afbeelding die als bullet in een alinea wordt gebruikt zonder erfelijkheid.<br/>            Alleen-lezen [`ISlidesPicture`](/slides/python-net/nl/aspose.slides/islidespicture). |
| [`slide`](/slides/python-net/nl/aspose.slides/bulletformat/slide/) |  |
| [`presentation`](/slides/python-net/nl/aspose.slides/bulletformat/presentation/) |  |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`apply_default_paragraph_indents_shifts(self)`](/slides/python-net/nl/aspose.slides/bulletformat/apply_default_paragraph_indents_shifts/#) | Stelt de standaard niet-nul verschuivingen in voor de effectieve alinea-Indent en MarginLeft wanneer bullets zijn ingeschakeld (zoals PowerPoint doet als alinea-bullets/nummering is ingeschakeld). Als bullets zijn uitgeschakeld, worden de alinea-Indent en MarginLeft gewoon gereset (zoals PowerPoint doet als alinea-bullets/nummering is uitgeschakeld). Verschui ving-offsets worden toegepast ten opzichte van de huidige bullet-context – IBulletFormat.Type, .NumberedBulletStyle en FontHeight van het eerste gedeelte. Niet-nul offset-verschui ving-s worden toegepast op de effectieve Indent en MarginLeft van de huidige alinea (zodat de resulterende waarden lokale waarden worden). |
| [`get_effective(self)`](/slides/python-net/nl/aspose.slides/bulletformat/get_effective/#) | Haalt de effectieve bullet-opmaak-gegevens op met de toegepaste erfelijkheid. |


### Zie ook
* klasse [`BulletFormat`](/slides/python-net/nl/aspose.slides/bulletformat)
* klasse [`PVIObject`](/slides/python-net/nl/aspose.slides/pviobject)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)