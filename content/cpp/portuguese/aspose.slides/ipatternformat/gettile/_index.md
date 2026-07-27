---
title: GetTile()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma imagem de ladrilho para o preenchimento de padrão com cores especificadas.
type: docs
weight: 53
url: /pt/aspose.slides/ipatternformat/gettile/
---
## IPatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) method

Cria uma imagem de ladrilho para o preenchimento de padrão com cores específicas.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground)=0
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | O fundo [System::Drawing::Color](../../../system.drawing/color/) para o padrão. |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | O primeiro plano [System::Drawing::Color](../../../system.drawing/color/) para o padrão. |

### Valor de Retorno

Tile [System::Drawing::Bitmap](../../../system.drawing/bitmap/).

## IPatternFormat::GetTile(System::Drawing::Color) method

Cria uma imagem de ladrilho para o preenchimento de padrão.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color styleColor)=0
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | O [System::Drawing::Color](../../../system.drawing/color/) padrão, definido no objeto StyleEx de ShapeEx. As cores do preenchimento podem depender disso. |

### Valor de Retorno

Tile [System::Drawing::Bitmap](../../../system.drawing/bitmap/).

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [Color](../../../system.drawing/color/)
* Class [IPatternFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)