---
title: InsertRowAfter()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt nach der angegebenen Zeile eine neue Zeile ein. Anfangs sind alle Elemente in der neuen Zeile null.
type: docs
weight: 300
url: /de/aspose.slides.mathtext/mathmatrix/insertrowafter/
---
## MathMatrix::InsertRowAfter(int32_t) Methode

Fügt nach der angegebenen Zeile eine neue Zeile ein. Anfangs sind alle Elemente in der neuen Zeile Null.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertRowAfter(int32_t rowIndex) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rowIndex | **int32_t** | Index der Zeile, nach der eine neue Zeile eingefügt werden soll |
## Bemerkungen

Beispiel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowAfter(1);
```

## Siehe auch

* Klasse [MathMatrix](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)