---
title: LoadingStreamBehavior enumeration
second_title: Aspose.Slides Pythonhoz .NET API-n keresztül
description: 
type: docs
url: /hu/aspose.slides/loadingstreambehavior/
---
## LoadingStreamBehavior enumeráció

A **io.RawIOBase** metódusnak átadva bináris nagy objektumnak (BLOB) tekinthető (lásd [`IBlobManagementOptions`](/slides/python-net/hu/aspose.slides/iblobmanagementoptions) leírását). Ennek az enumerációnak az értékei azt határozzák meg, hogyan kell kezelni a **io.RawIOBase**-t, amikor átadjuk a metódusnak. A követelményektől függően különböző döntéseket hozhatunk a leghatékonyabb viselkedés biztosítása érdekében.

A LoadingStreamBehavior típus a következő tagokat tartalmazza:

## Mezők

| Mező | Leírás |
| :- | :- |
| READ_STREAM_AND_RELEASE | A stream a végéig lesz olvasva, majd felszabadítva – azaz garantált, hogy ezt a stream-et <br/> nem fogja jövőben használni a [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation) példány. Lezárható a kliens <br/> kódból vagy bármilyen más módon használható. |
| KEEP_LOCKED | A stream a [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation) objektumon belül lesz zárolva, azaz a stream tulajdonjoga <br/> átkerül. A [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation) objektum felelős lesz a <br/> stream helyes felszabadításáért, amikor ez az objektum maga is felszabadul. <br/> Ez a viselkedés rendkívül hasznos, ha egy nagy BLOB fájlt (például nagy <br/> videót vagy audiót – lásd [`IBlobManagementOptions`](/slides/python-net/hu/aspose.slides/iblobmanagementoptions) leírását) szeretnénk sorosítani, és meg akarjuk akadályozni, hogy <br/> ez a fájl memóriába kerüljön vagy más teljesítményproblémákat okozzon. Egyszerűen megnyithatja a **System.IO.FileStream** <br/> ezt a fájlt, és átadhatja egy metódusnak, a [`LoadingStreamBehavior.KEEP_LOCKED`](/slides/python-net/hu/aspose.slides/loadingstreambehavior/KEEP_LOCKED) LoadingStreamBehavior-t választva. |

### Lásd még
* osztály [`IBlobManagementOptions`](/slides/python-net/hu/aspose.slides/iblobmanagementoptions)
* osztály [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)