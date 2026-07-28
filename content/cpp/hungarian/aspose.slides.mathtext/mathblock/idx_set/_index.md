---
title: idx_set()
second_title: Aspose.Slides C++ API Referencia
description: Beállítja az IMathElement-et a megadott indexen.
type: docs
weight: 40
url: /hu/aspose.slides.mathtext/mathblock/idx_set/
---
## MathBlock::idx_set(int32_t, System::SharedPtr\<IMathElement\>) metódus


Beállítja a(z) [IMathElement](../../imathelement/) a megadott indexen.

```cpp
void Aspose::Slides::MathText::MathBlock::idx_set(int32_t index, System::SharedPtr<IMathElement> value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | Az elem nulláralapú indexe |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | A matematikai elem. |
## Megjegyzések



Példa: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto firstElem = mathBlock->idx_get(0);
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [MathBlock](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)