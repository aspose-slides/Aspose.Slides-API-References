---
title: GetTile()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un'immagine tile per il riempimento del pattern con colori specificati.
type: docs
weight: 53
url: /it/aspose.slides/ipatternformat/gettile/
---
## IPatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) metodo

Crea un'immagine tile per il riempimento del pattern con colori specificati.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | Lo sfondo [System::Drawing::Color](../../../system.drawing/color/) per il pattern. |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | Il primo piano [System::Drawing::Color](../../../system.drawing/color/) per il pattern. |

### Valore di ritorno

Tile [System::Drawing::Bitmap](../../../system.drawing/bitmap/).

## IPatternFormat::GetTile(System::Drawing::Color) metodo

Crea un'immagine tile per il riempimento del pattern.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color styleColor)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | Il valore predefinito [System::Drawing::Color](../../../system.drawing/color/), definito nell'oggetto StyleEx di ShapeEx. I colori del riempimento possono dipendere da questo. |

### Valore di ritorno

Tile [System::Drawing::Bitmap](../../../system.drawing/bitmap/).

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IImage](../../iimage/)
* Classe [Color](../../../system.drawing/color/)
* Classe [IPatternFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)