---
title: InsertRowBefore()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügen Sie eine neue Zeile vor der angegebenen ein. Anfangs sind alle Elemente in der neuen Zeile null.
type: docs
weight: 287
url: /de/aspose.slides.mathtext/mathmatrix/insertrowbefore/
---
## MathMatrix::InsertRowBefore(int32_t) Methode

Fügen Sie eine neue Zeile vor der angegebenen ein. Anfangs sind alle Elemente in der neuen Zeile null.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertRowBefore(int32_t rowIndex) override
```

### Parameter

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

* Klasse [MathMatrix](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)