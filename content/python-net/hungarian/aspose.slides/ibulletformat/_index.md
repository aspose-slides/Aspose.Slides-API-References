---
title: IBulletFormat class
second_title: Aspose.Slides a Pythonhoz .NET-en keresztül API referencia
description: 
type: docs
url: /hu/aspose.slides/ibulletformat/
---
## IBulletFormat osztály

A bekezdés felsorolási formázási tulajdonságait reprezentálja.

Az IBulletFormat típus a következő tagokat teszi közzé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`type`](/slides/python-net/hu/aspose.slides/ibulletformat/type/) | Visszaadja vagy beállítja egy bekezdés felsorolási típusát öröklődés nélkül.<br/>            Olvasás/írás [`BulletType`](/slides/python-net/hu/aspose.slides/bullettype). |
| [`char`](/slides/python-net/hu/aspose.slides/ibulletformat/char/) | Visszaadja vagy beállítja egy bekezdés felsorolási karakterét öröklődés nélkül.<br/>            Olvasás/írás **System.Char**. |
| [`font`](/slides/python-net/hu/aspose.slides/ibulletformat/font/) | Visszaadja vagy beállítja egy bekezdés felsorolási betűtípusát öröklődés nélkül.<br/>            Olvasás/írás [`IFontData`](/slides/python-net/hu/aspose.slides/ifontdata). |
| [`height`](/slides/python-net/hu/aspose.slides/ibulletformat/height/) | Visszaadja vagy beállítja egy bekezdés felsorolási magasságát öröklődés nélkül.<br/>            A float.NaN érték azt határozza meg, hogy a felsorolás a magasságot a bekezdés első részéből örökli.<br/>            Olvasás/írás **float**. |
| [`color`](/slides/python-net/hu/aspose.slides/ibulletformat/color/) | Visszaadja egy bekezdés felsorolás színformátumát öröklődés nélkül.<br/>            Csak olvasható [`IColorFormat`](/slides/python-net/hu/aspose.slides/icolorformat). |
| [`picture`](/slides/python-net/hu/aspose.slides/ibulletformat/picture/) | Visszaadja a bekezdésben felsorolásként használt képet öröklődés nélkül.<br/>            Csak olvasható [`ISlidesPicture`](/slides/python-net/hu/aspose.slides/islidespicture). |
| [`numbered_bullet_start_with`](/slides/python-net/hu/aspose.slides/ibulletformat/numbered_bullet_start_with/) | Visszaadja vagy beállítja az első számot, amely a számozott felsorolások csoportjában használatos öröklődés nélkül.<br/>            Olvasás/írás **int**. |
| [`numbered_bullet_style`](/slides/python-net/hu/aspose.slides/ibulletformat/numbered_bullet_style/) | Visszaadja vagy beállítja a számozott felsorolás stílusát öröklődés nélkül.<br/>            Olvasás/írás [`IBulletFormat.numbered_bullet_style`](/slides/python-net/hu/aspose.slides/ibulletformat/numbered_bullet_style). |
| [`is_bullet_hard_color`](/slides/python-net/hu/aspose.slides/ibulletformat/is_bullet_hard_color/) | Meghatározza, hogy a felsorolás saját színnel rendelkezik-e, vagy a bekezdés első részéből örökli azt.<br/>            **NullableBool.True**  ha a felsorolás saját színnel rendelkezik, és **NullableBool.False**  ha a felsorolás<br/>            a színt a bekezdés első részéből örökli.<br/>            Olvasás/írás [`NullableBool`](/slides/python-net/hu/aspose.slides/nullablebool). |
| [`is_bullet_hard_font`](/slides/python-net/hu/aspose.slides/ibulletformat/is_bullet_hard_font/) | Meghatározza, hogy a felsorolás saját betűtípussal rendelkezik-e, vagy a bekezdés első részéből örökli azt.<br/>            **NullableBool.True**  ha a felsorolás saját betűtípussal rendelkezik, és **NullableBool.False**  ha a felsorolás<br/>            a betűtípust a bekezdés első részéből örökli.<br/>            Olvasás/írás [`NullableBool`](/slides/python-net/hu/aspose.slides/nullablebool). |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`apply_default_paragraph_indents_shifts(self)`](/slides/python-net/hu/aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/#) | Alapértelmezett nem nulla eltolásokat állít be a hatékony bekezdés Indent és MarginLeft értékekhez, amikor a felsorolások engedélyezve vannak (ahogy a PowerPoint is tesz, ha engedélyezi a bekezdés felsorolásait/számozását). Ha a felsorolások le vannak tiltva, akkor csak visszaállítja a bekezdés Indent és MarginLeft értékét (ahogy a PowerPoint is tesz, ha letiltja a bekezdés felsorolásait/számozását). Az eltolások a jelenlegi felsorolási kontextusra vonatkoznak – IBulletFormat.Type, .NumberedBulletStyle és az első rész betűmagassága. A nem nulla bekezdési eltolások a jelenlegi bekezdés hatékony Indent és MarginLeft értékeire vonatkoznak (az eredmény értékek helyi értékekké válnak). |
| [`get_effective(self)`](/slides/python-net/hu/aspose.slides/ibulletformat/get_effective/#) | Lekéri a hatékony felsorolási formázási adatokat az alkalmazott öröklődéssel. |

### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)