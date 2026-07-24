---
title: idx_get()
second_title: Aspose.Slides für C++ API-Referenz
description: Ruft IMathElement am angegebenen Index ab.
type: docs
weight: 27
url: /de/aspose.slides.mathtext/mathblock/idx_get/
---
## MathBlock::idx_get(int32_t) Methode


Ruft [IMathElement](../../imathelement/) am angegebenen Index ab.

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBlock::idx_get(int32_t index) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | The zero-based index of the item |

### Rückgabewert

Das mathematische Element.
## Hinweise



Beispiel: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto firstElem = mathBlock->idx_get(0);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathBlock](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)