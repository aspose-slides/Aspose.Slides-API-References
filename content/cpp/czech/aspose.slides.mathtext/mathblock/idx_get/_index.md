---
title: idx_get()
second_title: Aspose.Slides pro C++ API referenci
description: Získá IMathElement na zadaném indexu.
type: docs
weight: 27
url: /cs/aspose.slides.mathtext/mathblock/idx_get/
---
## MathBlock::idx_get(int32_t) metoda


Získá [IMathElement](../../imathelement/) na zadaném indexu.

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBlock::idx_get(int32_t index) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Nulový index položky |

### Návratová hodnota

Matematický prvek.
## Poznámky



Příklad: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto firstElem = mathBlock->idx_get(0);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathElement](../../imathelement/)
* Třída [MathBlock](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)