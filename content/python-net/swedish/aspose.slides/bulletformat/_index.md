---
title: BulletFormat class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/bulletformat/
---
## BulletFormat klass

Representerar egenskaper för punktformatering av ett stycke.

**Arv:**[`BulletFormat`](/slides/python-net/sv/aspose.slides/bulletformat) → [`PVIObject`](/slides/python-net/sv/aspose.slides/pviobject)

BulletFormat-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`type`](/slides/python-net/sv/aspose.slides/bulletformat/type/) | Returnerar eller anger punkttypen för ett stycke utan arv.<br/>            Läs/skriv [`BulletType`](/slides/python-net/sv/aspose.slides/bullettype). |
| [`char`](/slides/python-net/sv/aspose.slides/bulletformat/char/) | Returnerar eller anger punktsymbolen för ett stycke utan arv.<br/>            Läs/skriv **System.Char**. |
| [`font`](/slides/python-net/sv/aspose.slides/bulletformat/font/) | Returnerar eller anger punktfonten för ett stycke utan arv.<br/>            Läs/skriv [`IFontData`](/slides/python-net/sv/aspose.slides/ifontdata). |
| [`height`](/slides/python-net/sv/aspose.slides/bulletformat/height/) | Returnerar eller anger punktens höjd för ett stycke utan arv.<br/>            Värdet float.NaN bestämmer att punkten ärver höjden från den första delen i stycket.<br/>            Läs/skriv **float**. |
| [`color`](/slides/python-net/sv/aspose.slides/bulletformat/color/) | Returnerar färgformatet för en punkt i ett stycke utan arv.<br/>            Endast läsning [`IColorFormat`](/slides/python-net/sv/aspose.slides/icolorformat). |
| [`numbered_bullet_start_with`](/slides/python-net/sv/aspose.slides/bulletformat/numbered_bullet_start_with/) | Returnerar eller anger det första numret som används för en grupp numrerade punkter utan arv.<br/>            Läs/skriv **int**. |
| [`numbered_bullet_style`](/slides/python-net/sv/aspose.slides/bulletformat/numbered_bullet_style/) | Returnerar eller anger stilen för en numrerad punkt utan arv.<br/>            Läs/skriv [`NumberedBulletStyle`](/slides/python-net/sv/aspose.slides/numberedbulletstyle). |
| [`is_bullet_hard_color`](/slides/python-net/sv/aspose.slides/bulletformat/is_bullet_hard_color/) | Bestämmer om punkten har egen färg eller ärver den från den första delen i stycket.<br/>            **NullableBool.True**  om punkten har egen färg och **NullableBool.False**  om punkten<br/>            ärver färg från den första delen i stycket.<br/>            Läs/skriv [`NullableBool`](/slides/python-net/sv/aspose.slides/nullablebool). |
| [`is_bullet_hard_font`](/slides/python-net/sv/aspose.slides/bulletformat/is_bullet_hard_font/) | Bestämmer om punkten har eget teckensnitt eller ärver det från den första delen i stycket.<br/>            **NullableBool.True**  om punkten har eget teckensnitt och **NullableBool.False**  om punkten<br/>            ärver teckensnitt från den första delen i stycket.<br/>            Läs/skriv [`NullableBool`](/slides/python-net/sv/aspose.slides/nullablebool). |
| [`picture`](/slides/python-net/sv/aspose.slides/bulletformat/picture/) | Returnerar bilden som används som en punkt i ett stycke utan arv.<br/>            Endast läsning [`ISlidesPicture`](/slides/python-net/sv/aspose.slides/islidespicture). |
| [`slide`](/slides/python-net/sv/aspose.slides/bulletformat/slide/) |  |
| [`presentation`](/slides/python-net/sv/aspose.slides/bulletformat/presentation/) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`apply_default_paragraph_indents_shifts(self)`](/slides/python-net/sv/aspose.slides/bulletformat/apply_default_paragraph_indents_shifts/#) | Ställer in standard icke-noll förskjutningar för effektiv stycke-Indent och MarginLeft när punkter är aktiverade (som PowerPoint gör om du aktiverar stycke-punkter/numrering i det). Om punkter är inaktiverade återställs bara stycke-Indent och MarginLeft (som PowerPoint gör om du inaktiverar stycke-punkter/numrering i det). Indent-förskjutningar tillämpas med hänsyn till den aktuella punktkontexten – IBulletFormat.Type, .NumberedBulletStyle och FontHeight för den första delen. Icke-noll Indent-förskjutningar tillämpas på effektiv Indent och MarginLeft för aktuellt stycke (gör resultatvärdena lokala). |
| [`get_effective(self)`](/slides/python-net/sv/aspose.slides/bulletformat/get_effective/#) | Hämtar effektiv punktformateringsdata med ärvd egenskap tillämpad. |

### Se också
* klass [`BulletFormat`](/slides/python-net/sv/aspose.slides/bulletformat)
* klass [`PVIObject`](/slides/python-net/sv/aspose.slides/pviobject)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)