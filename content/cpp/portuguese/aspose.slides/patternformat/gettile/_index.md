---
title: GetTile()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma imagem de ladrilho para o preenchimento de padrão com cores especificadas.
type: docs
weight: 53
url: /pt/aspose.slides/patternformat/gettile/
---
## PatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) método


Cria uma imagem de ladrilho para o preenchimento de padrão com cores especificadas.

```cpp
System::SharedPtr<IImage> Aspose::Slides::PatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | O fundo [System::Drawing::Color](../../../system.drawing/color/) para o padrão. |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | O primeiro plano [System::Drawing::Color](../../../system.drawing/color/) para o padrão. |

### Valor de Retorno

Ladrilho [IImage](../../iimage/).

## PatternFormat::GetTile(System::Drawing::Color) método


Cria uma imagem de ladrilho para o preenchimento de padrão.

```cpp
System::SharedPtr<IImage> Aspose::Slides::PatternFormat::GetTile(System::Drawing::Color styleColor) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | O padrão [System::Drawing::Color](../../../system.drawing/color/) |

### Valor de Retorno

Ladrilho [IImage](../../iimage/).

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IImage](../../iimage/)
* Classe [Color](../../../system.drawing/color/)
* Classe [PatternFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)