---
title: idx_set()
second_title: Aspose.Slides für C++ API-Referenz
description: Element der Matrix
type: docs
weight: 222
url: /de/aspose.slides.mathtext/mathmatrix/idx_set/
---
## MathMatrix::idx_set(int32_t, int32_t, System::SharedPtr\<IMathElement\>) Methode


Element der Matrix

```cpp
void Aspose::Slides::MathText::MathMatrix::idx_set(int32_t row, int32_t column, System::SharedPtr<IMathElement> value) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| row | **int32_t** | Der nullbasierte Index der Zeile, um das Element abzurufen |
| column | **int32_t** | Der nullbasierte Index der Spalte, um das Element abzurufen |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> |  |
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