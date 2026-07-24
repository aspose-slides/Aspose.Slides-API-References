---
title: InsertRowAfter()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt eine neue Zeile nach der angegebenen ein. Anfangs sind alle Elemente in der neuen Zeile null.
type: docs
weight: 287
url: /de/aspose.slides.mathtext/imathmatrix/insertrowafter/
---
## IMathMatrix::InsertRowAfter(int32_t) Methode


Fügt eine neue Zeile nach der angegebenen ein. Anfangs sind alle Elemente in der neuen Zeile null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertRowAfter(int32_t rowIndex)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rowIndex | **int32_t** | Index der Zeile, nach der eine neue eingefügt werden soll |
## Bemerkungen



Beispiel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowAfter(1);
```

## Siehe auch

* Klasse [IMathMatrix](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)