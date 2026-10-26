---
title: InsertColumnAfter()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügen Sie eine neue Spalte nach der angegebenen ein. Zu Beginn sind alle Elemente in der neuen Spalte null.
type: docs
weight: 339
url: /de/aspose.slides.mathtext/mathmatrix/insertcolumnafter/
---
## MathMatrix::InsertColumnAfter(int32_t) Methode

Fügen Sie eine neue Spalte nach der angegebenen ein. Zu Beginn sind alle Elemente in der neuen Spalte null.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertColumnAfter(int32_t columnIndex) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| columnIndex | **int32_t** | Index der Spalte, nach der eine neue eingefügt werden soll |
## Anmerkungen



Beispiel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnAfter(0);
```

## Siehe auch

* Klasse [MathMatrix](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)