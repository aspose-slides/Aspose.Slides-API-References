---
title: FileVersionInfo
second_title: Aspose.Slides C++ API Referencia
description: "Információt biztosít a fájlverzióról. Ennek az osztálynak az objektumait csak a System::MakeObject() függvénnyel szabad lefoglalni. Soha ne hozzon létre példányt ezen típusból a stacken vagy az operator new használatával, mivel futási hibákat és/vagy állítási hibákat okozhat. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót a függvények argumentumaként való átadásra."
type: docs
weight: 1
url: /hu/system.diagnostics/fileversioninfo/
---
## FileVersionInfo osztály


Információt biztosít a fájlverzióról. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvénnyel szabad lefoglalni. Soha ne hozzon létre példányt ezen típusból a stacken vagy az operator new használatával, mivel futási hibákat és/vagy állítási hibákat okozhat. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót a függvények argumentumaként való átadásra.

```cpp
class FileVersionInfo
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [String](../../system/string/) [get_ProductVersion](./get_productversion/)() const | Visszaadja a termék verzió mezőt. |
| static [SharedPtr](../../system/sharedptr/)\<[System::Diagnostics::FileVersionInfo](./)\> [GetVersionInfo](./getversioninfo/)(const [String](../../system/string/)\&) | A fájlverzió információt adja vissza; nincs megvalósítva. |
## Lásd még

* Névtér [System::Diagnostics](../)
* Könyvtár [Aspose.Slides](../../)