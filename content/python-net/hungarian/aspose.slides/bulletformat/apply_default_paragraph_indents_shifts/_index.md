---
title: apply_default_paragraph_indents_shifts method
second_title: Aspose.Slides Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/bulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
Alapértelmezett nem nulla eltolásokat állít be a hatékony bekezdés Indent és MarginLeft értékeihez, ha a bullet-ek engedélyezettek (ahogyan a PowerPoint teszi, ha engedélyezi a bekezdés bullet/numbering funkciót). Ha a bullet-ek le vannak tiltva, akkor csak visszaállítja a bekezdés Indent és MarginLeft értékeit (ahogyan a PowerPoint teszi, ha letiltja a bekezdés bullet/numbering funkciót). Az indent eltolások a jelenlegi bullet kontextusra – IBulletFormat.Type, .NumberedBulletStyle és a első rész FontHeight értékére – vonatkoznak. A nem nulla indent eltolások a jelenlegi bekezdés hatékony Indent és MarginLeft értékeire kerülnek alkalmazásra (az eredményértékek helyi értékek lesznek).


```python
def apply_default_paragraph_indents_shifts(self):
    ...
```


### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Ennek a metódusnak a meghívása nem számít, és **System.InvalidOperationException** dob a következő esetekben:<br/>            ha a szülő formázott objektum nem bekezdés (például az ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() meghívása kivételt dob);<br/>            vagy ha a bekezdés nem lett hozzáadva semelyik ITextFrame.Paragraphs gyűjteményhez (először adja hozzá); |



### Lásd még
* osztály [`BulletFormat`](/slides/python-net/hu/aspose.slides/bulletformat)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)