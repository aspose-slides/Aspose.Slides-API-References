---
title: GetTile()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un'immagine a tassello per il riempimento a motivo con colori specificati.
type: docs
weight: 53
url: /it/aspose.slides/patternformat/gettile/
---
## PatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) method


Crea un'immagine a tassello per il riempimento a motivo con i colori specificati.

```cpp
System::SharedPtr<IImage> Aspose::Slides::PatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | Lo sfondo [System::Drawing::Color](../../../system.drawing/color/) per il motivo. |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | Il primo piano [System::Drawing::Color](../../../system.drawing/color/) per il motivo. |

### Valore restituito

Tassello [IImage](../../iimage/).

## PatternFormat::GetTile(System::Drawing::Color) method


Crea un'immagine a tassello per il riempimento a motivo.

```cpp
System::SharedPtr<IImage> Aspose::Slides::PatternFormat::GetTile(System::Drawing::Color styleColor) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | Il valore predefinito [System::Drawing::Color](../../../system.drawing/color/) |

### Valore restituito

Tassello [IImage](../../iimage/).

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IImage](../../iimage/)
* Classe [Color](../../../system.drawing/color/)
* Classe [PatternFormat](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)