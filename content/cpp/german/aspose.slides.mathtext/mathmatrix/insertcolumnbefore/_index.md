---
title: InsertColumnBefore()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt vor der angegebenen Spalte eine neue Spalte ein. Anfangs sind alle Elemente in der neuen Spalte null.
type: docs
weight: 326
url: /de/aspose.slides.mathtext/mathmatrix/insertcolumnbefore/
---
## MathMatrix::InsertColumnBefore(int32_t) Methode

Fügt vor der angegebenen Spalte eine neue Spalte ein. Anfangs sind alle Elemente in der neuen Spalte null.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertColumnBefore(int32_t columnIndex) override
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| columnIndex | **int32_t** | Index der Spalte, vor der eine neue eingefügt werden soll |
## Hinweise

Beispiel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnBefore(0);
```

## Siehe auch

* Klasse [MathMatrix](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)