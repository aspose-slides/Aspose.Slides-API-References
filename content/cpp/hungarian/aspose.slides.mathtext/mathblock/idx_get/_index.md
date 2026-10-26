---
title: idx_get()
second_title: Aspose.Slides C++ API hivatkozás
description: Lekéri az IMathElement-et a megadott indexnél.
type: docs
weight: 27
url: /hu/aspose.slides.mathtext/mathblock/idx_get/
---
## MathBlock::idx_get(int32_t) metódus

Megkapja a megadott indexnél lévő [IMathElement](../../imathelement/).

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBlock::idx_get(int32_t index) override
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Az elem nullától számított indexe |

### Visszatérési érték

A matematikai elem.
## Megjegyzések



Példa: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto firstElem = mathBlock->idx_get(0);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [MathBlock](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)