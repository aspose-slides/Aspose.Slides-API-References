---
title: idx_get()
second_title: Aspose.Slides für C++ API-Referenz
description: Elemente der Matrix
type: docs
weight: 209
url: /de/aspose.slides.mathtext/imathmatrix/idx_get/
---
## IMathMatrix::idx_get(int32_t, int32_t) method


Elemente der Matrix

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathMatrix::idx_get(int32_t row, int32_t column)=0
```


### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| row | **int32_t** | Der nullbasierte Index der Zeile, um das Element abzurufen |
| column | **int32_t** | Der nullbasierte Index der Spalte, um das Element abzurufen |

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
* Klasse [IMathMatrix](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)