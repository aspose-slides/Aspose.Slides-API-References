---
title: idx_set()
second_title: Aspose.Slides für C++ API-Referenz
description: Elemente der Matrix
type: docs
weight: 222
url: /de/aspose.slides.mathtext/imathmatrix/idx_set/
---
## IMathMatrix::idx_set(int32_t, int32_t, System::SharedPtr\<IMathElement\>) Methode

Elemente der Matrix

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::idx_set(int32_t row, int32_t column, System::SharedPtr<IMathElement> value)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| row | **int32_t** | Der nullbasierte Index der Zeile, um das Element zu erhalten |
| column | **int32_t** | Der nullbasierte Index der Spalte, um das Element zu erhalten |
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
* Klasse [IMathMatrix](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)