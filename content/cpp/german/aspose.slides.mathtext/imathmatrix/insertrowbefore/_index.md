---
title: InsertRowBefore()
second_title: Aspose.Slides für C++ API Referenz
description: Fügt eine neue Zeile vor der angegebenen ein. Anfangs sind alle Elemente in der neuen Zeile null.
type: docs
weight: 274
url: /de/aspose.slides.mathtext/imathmatrix/insertrowbefore/
---
## IMathMatrix::InsertRowBefore(int32_t) Methode

Fügt eine neue Zeile vor der angegebenen ein. Anfangs sind alle Elemente in der neuen Zeile null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertRowBefore(int32_t rowIndex)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rowIndex | **int32_t** | Index der Zeile, vor der eine neue eingefügt werden soll |

## Hinweise

Beispiel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowBefore(1);
```

## Siehe auch

* Klasse [IMathMatrix](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)