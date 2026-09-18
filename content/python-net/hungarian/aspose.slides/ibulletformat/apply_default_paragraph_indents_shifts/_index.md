---
title: apply_default_paragraph_indents_shifts method
second_title: Aspose.Slides Python számára .NET API referenciája
description: 
type: docs
url: /hu/aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
Alapértelmezett nem nulla eltolásokat állít be a hatékony paragrafus Indent és MarginLeft értékekhez, ha a bullets engedélyezve van (akárcsak a PowerPoint teszi, ha engedélyezi a paragrafus bullet/numbering-et). Ha a bullets le van tiltva, akkor csak a paragrafus Indent és MarginLeft értékeket állítja vissza (akárcsak a PowerPoint teszi, ha letiltja a paragrafus bullet/numbering-et). A behúzás eltolásokat az aktuális bullet kontextusra vonatkozóan alkalmazzák – IBulletFormat.Type, .NumberedBulletStyle és a első rész FontHeight értéke alapján. A nem nulla behúzás eltolásokat az aktuális paragrafus hatékony Indent és MarginLeft értékeire alkalmazzák (az eredményértékek helyi értékekké válnak).


```python
def apply_default_paragraph_indents_shifts(self):
    ...
```


### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | A metódus hívása nem számít, és **System.InvalidOperationException**-t dob a következő esetekben:<br/>            ha a szülő formázott objektum nem paragrafus (például az ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() hívása kivételt dob);<br/>            vagy ha a paragrafus nem lett hozzáadva egy ITextFrame.Paragraphs gyűjteményhez (előbb adja hozzá); |



### Lásd még
* osztály [`IBulletFormat`](/slides/python-net/hu/aspose.slides/ibulletformat)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)