---
title: DeleteRow()
second_title: Aspose.Slides für C++ API-Referenz
description: Löscht die angegebene Zeile
type: docs
weight: 300
url: /de/aspose.slides.mathtext/imathmatrix/deleterow/
---
## IMathMatrix::DeleteRow(int32_t) Methode


Löscht die angegebene Zeile

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::DeleteRow(int32_t rowIndex)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rowIndex | **int32_t** | Der nullbasierte Index der zu löschenden Zeile. |
| ## Anmerkungen


Beispiel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->DeleteRow(0);
```

## Siehe auch

* Klasse [IMathMatrix](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)