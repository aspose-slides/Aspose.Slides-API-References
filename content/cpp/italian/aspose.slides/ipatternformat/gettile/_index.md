---
title: GetTile()
second_title: Riferimento API Aspose.Slides per C++
description: Crea un'immagine tile per il riempimento a trama con i colori specificati.
type: docs
weight: 53
url: /it/aspose.slides/ipatternformat/gettile/
---
## IPatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) metodo

Crea un'immagine tile per il riempimento a trama con i colori specificati.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | Il [System::Drawing::Color](../../../system.drawing/color/) di sfondo per la trama. |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | Il [System::Drawing::Color](../../../system.drawing/color/) di primo piano per la trama. |

### Valore di ritorno

Tile [IImage](../../iimage/).

## IPatternFormat::GetTile(System::Drawing::Color) metodo

Crea un'immagine tile per il riempimento a trama.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color styleColor)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | Il [System::Drawing::Color](../../../system.drawing/color/) predefinito, definito nell'oggetto StyleEx di ShapeEx. I colori di riempimento possono dipendere da questo. |

### Valore di ritorno

Tile [IImage](../../iimage/).

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IImage](../../iimage/)
* Classe [Color](../../../system.drawing/color/)
* Classe [IPatternFormat](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)