---
title: IBulletFormat class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/ibulletformat/
---
## IBulletFormat klass

Representerar formateringsinställningar för styckepunkter.

IBulletFormat-typen exponerar följande medlemmar:

## Egenskaper

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/sv/aspose.slides/ibulletformat/type/) | Returnerar eller anger punkttypen för ett stycke utan arv.<br/>            Läs/skriv [`BulletType`](/slides/python-net/sv/aspose.slides/bullettype). |
| [`char`](/slides/python-net/sv/aspose.slides/ibulletformat/char/) | Returnerar eller anger punkttecknet för ett stycke utan arv.<br/>            Läs/skriv **System.Char**. |
| [`font`](/slides/python-net/sv/aspose.slides/ibulletformat/font/) | Returnerar eller anger punktfonten för ett stycke utan arv.<br/>            Läs/skriv [`IFontData`](/slides/python-net/sv/aspose.slides/ifontdata). |
| [`height`](/slides/python-net/sv/aspose.slides/ibulletformat/height/) | Returnerar eller anger punktens höjd för ett stycke utan arv.<br/>            Värdet float.NaN bestämmer att punkten ärver höjden från den första delen i stycket.<br/>            Läs/skriv **float**. |
| [`color`](/slides/python-net/sv/aspose.slides/ibulletformat/color/) | Returnerar färgformatet för en punkt i ett stycke utan arv.<br/>            Endast läs [`IColorFormat`](/slides/python-net/sv/aspose.slides/icolorformat). |
| [`picture`](/slides/python-net/sv/aspose.slides/ibulletformat/picture/) | Returnerar bilden som används som punkt i ett stycke utan arv.<br/>            Endast läs [`ISlidesPicture`](/slides/python-net/sv/aspose.slides/islidespicture). |
| [`numbered_bullet_start_with`](/slides/python-net/sv/aspose.slides/ibulletformat/numbered_bullet_start_with/) | Returnerar eller anger det första talet som används för en grupp numrerade punkter utan arv.<br/>            Läs/skriv **int**. |
| [`numbered_bullet_style`](/slides/python-net/sv/aspose.slides/ibulletformat/numbered_bullet_style/) | Returnerar eller anger stilen för en numrerad punkt utan arv.<br/>            Läs/skriv [`IBulletFormat.numbered_bullet_style`](/slides/python-net/sv/aspose.slides/ibulletformat/numbered_bullet_style). |
| [`is_bullet_hard_color`](/slides/python-net/sv/aspose.slides/ibulletformat/is_bullet_hard_color/) | Bestämmer om punkten har egen färg eller ärver den från den första delen i stycket.<br/>            **NullableBool.True**  om punkten har egen färg och **NullableBool.False**  om punkten<br/>            ärver färg från den första delen i stycket.<br/>            Läs/skriv [`NullableBool`](/slides/python-net/sv/aspose.slides/nullablebool). |
| [`is_bullet_hard_font`](/slides/python-net/sv/aspose.slides/ibulletformat/is_bullet_hard_font/) | Bestämmer om punkten har egen font eller ärver den från den första delen i stycket.<br/>            **NullableBool.True**  om punkten har egen font och **NullableBool.False**  om punkten<br/>            ärver font från den första delen i stycket.<br/>            Läs/skriv [`NullableBool`](/slides/python-net/sv/aspose.slides/nullablebool). |

## Metoder

| Method | Description |
| :- | :- |
| [`apply_default_paragraph_indents_shifts(self)`](/slides/python-net/sv/aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/#) | Ställer in standard icke-noll förskjutningar för effektiv stycke-Indent och MarginLeft när punkter är aktiverade (som PowerPoint gör när man aktiverar styckepunkter/numrering). Om punkter är inaktiverade återställs bara stycke-Indent och MarginLeft (som PowerPoint gör när man inaktiverar styckepunkter/numrering). Indent-förskjutningar tillämpas i förhållande till aktuell punktkontext – IBulletFormat.Type, .NumberedBulletStyle och FontHeight för första delen. Icke-noll indentsförskjutningar tillämpas på effektiv Indent och MarginLeft för aktuellt stycke (gör resultatvärdena lokala). |
| [`get_effective(self)`](/slides/python-net/sv/aspose.slides/ibulletformat/get_effective/#) | Hämtar effektiv formateringsdata för punkter med ärvd egenskap tillämpad. |


### Se även
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)