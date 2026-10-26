---
title: PresentationLockingBehavior enumeration
second_title: Aspose.Slides a Pythonhoz .NET API Referencia
description: 
type: docs
url: /hu/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior enumeráció

A viselkedést jelöli a [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation) forrás (fájl vagy **io.RawIOBase**) kezelése tekintetében, amikor betöltünk és egy [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation) példánnyal dolgozunk.

A PresentationLockingBehavior típus a következő tagokat tartalmazza:

## Mezők

| Field | Description |
| :- | :- |
| LOAD_AND_RELEASE | A forrás csak a [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation) konstruktorának végrehajtása időtartamára lesz zárolva.<br/>            Ha [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/hu/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) false értékre van állítva, az összes BLOB <br/>            betöltődik a memóriába. Ellenkező esetben egyéb módszerek, például ideiglenes fájlok használhatók. Ez a viselkedés lassabb, mint a [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/hu/aspose.slides/presentationlockingbehavior/KEEP_LOCKED), és ha lehetséges a forrás tulajdonjogának átadása a [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation)-nek, akkor ajánlott a [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/hu/aspose.slides/presentationlockingbehavior/KEEP_LOCKED) használata. |
| KEEP_LOCKED | A forrás a teljes [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation) példány életciklusa alatt lesz zárolva, amíg le nem <br/>            lesz választva.<br/>            A [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/hu/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed)-t true értékre kell állítani ennek a viselkedésnek a használatához, ellenkező esetben kivétel lesz dobva. Ez a viselkedés ajánlott, gyorsabb és kevesebb memóriát használ, mint a [`PresentationLockingBehavior.LOAD_AND_RELEASE`](/slides/python-net/hu/aspose.slides/presentationlockingbehavior/LOAD_AND_RELEASE). |


### Megjegyzések

A forrás a [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation) konstruktorának paramétere. Az alábbi példában a forrás a "pres.pptx" fájl:

Ehhez a példához a forrás ("pres.pptx" fájl) a [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation) példány életciklusa alatt zárolva lesz, azaz a másik folyamat nem tudja módosítani vagy törölni.

### Lásd még
* osztály [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)