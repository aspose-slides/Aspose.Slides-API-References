---
title: idx_get()
second_title: Aspose.Slides für C++ API-Referenz
description: Element der Matrix
type: docs
weight: 209
url: /de/aspose.slides.mathtext/mathmatrix/idx_get/
---
## MathMatrix::idx_get(int32_t, int32_t) Methode


Element der Matrix

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathMatrix::idx_get(int32_t row, int32_t column) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| row | **int32_t** | Der nullbasierte Index der Zeile, um das Element zu erhalten |
| column | **int32_t** | Der nullbasierte Index der Spalte, um das Element zu erhalten |

### Rückgabewert


## Bemerkungen



Beispiel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathMatrix](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)