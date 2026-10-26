---
title: InsertColumnAfter()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt eine neue Spalte nach der angegebenen ein. Anfangs sind alle Elemente in der neuen Spalte Null.
type: docs
weight: 326
url: /de/aspose.slides.mathtext/imathmatrix/insertcolumnafter/
---
## IMathMatrix::InsertColumnAfter(int32_t) Methode


Fügt eine neue Spalte nach der angegebenen ein. Anfangs sind alle Elemente in der neuen Spalte Null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertColumnAfter(int32_t columnIndex)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| columnIndex | **int32_t** | Index der Spalte, nach der eine neue eingefügt werden soll |
## Bemerkungen



Beispiel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnAfter(0);
```

## Siehe auch

* Klasse [IMathMatrix](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)