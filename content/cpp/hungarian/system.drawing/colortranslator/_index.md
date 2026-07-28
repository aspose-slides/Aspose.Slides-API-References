---
title: ColorTranslator
second_title: Aspose.Slides C++ API Referencia
description: "Színátalakításokat hajt végre. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new használatával, mert ez futásidejű hibákat és/vagy állítási hibákat okozhat. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót, hogy argumentumként átadja a függvényeknek."
type: docs
weight: 66
url: /hu/system.drawing/colortranslator/
---
## ColorTranslator osztály

Színátalakításokat hajt végre. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvénnyel szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new használatával, mert ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót, hogy argumentumként átadja a függvényeknek.

```cpp
class ColorTranslator
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| static [Color](../color/) [FromHtml](./fromhtml/)(const [System::String](../../system/string/)\&) | Átalakítja a megadott HTML színábrázolást az ekvivalens [Color](../color/) objektummá. |
| static [Color](../color/) [FromWin32](./fromwin32/)(int) | Átalakítja a megadott [Windows](../../system.windows/) színt az ekvivalens [Color](../color/) objektummá. |
| static [String](../../system/string/) [ToHtml](./tohtml/)(const [Color](../color/)\&) | Átalakítja a megadott [Color](../color/) objektumot az ekvivalens HTML szín karakterláncábrázolásává. |
## Lásd még

* Névtér [System::Drawing](../)
* Könyvtár [Aspose.Slides](../../)