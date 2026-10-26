---
title: DeleteRow()
second_title: Aspose.Slides für C++ API-Referenz
description: Löscht die angegebene Zeile
type: docs
weight: 313
url: /de/aspose.slides.mathtext/mathmatrix/deleterow/
---
## MathMatrix::DeleteRow(int32_t) Methode


Löscht die angegebene Zeile

```cpp
void Aspose::Slides::MathText::MathMatrix::DeleteRow(int32_t rowIndex) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rowIndex | **int32_t** | Der nullbasierte Index der zu löschenden Zeile. |
## Bemerkungen



Beispiel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->DeleteRow(0);
```

## Siehe auch

* Klasse [MathMatrix](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)