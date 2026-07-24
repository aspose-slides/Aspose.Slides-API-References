---
title: InsertColumnBefore()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügen Sie eine neue Spalte vor der angegebenen ein. Anfangs sind alle Elemente in der neuen Spalte null.
type: docs
weight: 313
url: /de/aspose.slides.mathtext/imathmatrix/insertcolumnbefore/
---
## IMathMatrix::InsertColumnBefore(int32_t) Methode


Fügen Sie eine neue Spalte vor der angegebenen ein. Anfangs sind alle Elemente in der neuen Spalte null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertColumnBefore(int32_t columnIndex)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| columnIndex | **int32_t** | Index der Spalte, vor der eine neue eingefügt werden soll |
## Bemerkungen



Beispiel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnBefore(0);
```

## Siehe auch

* Klasse [IMathMatrix](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)