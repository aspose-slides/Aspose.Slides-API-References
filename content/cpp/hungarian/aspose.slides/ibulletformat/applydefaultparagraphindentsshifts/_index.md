---
title: ApplyDefaultParagraphIndentsShifts()
second_title: Aspose.Slides C++ API Referenciája
description: "Alapértelmezett nem nulla eltolásokat állít be a hatékony bekezdés Indent és MarginLeft értékeihez, ha a bullets engedélyezve van (akárcsak a PowerPoint teszi, ha engedélyezi a bekezdés bullets/ számozását). Ha a bullets le van tiltva, akkor egyszerűen visszaállítja a bekezdés Indent és MarginLeft értékeit (akárcsak a PowerPoint teszi, ha letiltja a bekezdés bullets/ számozását). Az Indents eltolásokat a jelenlegi bullet kontextusra - IBulletFormat::get(set)_Type, .NumberedBulletStyle és az első rész FontHeight - tekintettel alkalmazzák. A nem nulla Indents eltolásokat a jelenlegi bekezdés hatékony Indent és MarginLeft értékeire alkalmazzák (az eredményértékek helyi értékek lesznek)."
type: docs
weight: 235
url: /hu/aspose.slides/ibulletformat/applydefaultparagraphindentsshifts/
---
## IBulletFormat::ApplyDefaultParagraphIndentsShifts() metódus

Alapértelmezett nem nulla eltolásokat állít be a hatékony bekezdés Indent és MarginLeft értékekhez, ha a bullets engedélyezve van (akárcsak a PowerPoint teszi, ha engedélyezi a bekezdés bullets/számozását benne). Ha a bullets le van tiltva, akkor csak visszaállítja a bekezdés Indent és MarginLeft értékét (akárcsak a PowerPoint teszi, ha letiltja a bekezdés bullets/számozását benne). Az eltolások a jelenlegi bullet kontextushoz – IBulletFormat::get(set)_Type, .NumberedBulletStyle és az első rész FontHeight-ja – viszonyítva kerülnek alkalmazásra. A nem nulla eltolások a jelenlegi bekezdés hatékony Indent és MarginLeft értékeire vonatkoznak (az eredményértékek helyi értékek lesznek).

```cpp
virtual void Aspose::Slides::IBulletFormat::ApplyDefaultParagraphIndentsShifts()=0
```

## Lásd még

* Osztály [IBulletFormat](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)