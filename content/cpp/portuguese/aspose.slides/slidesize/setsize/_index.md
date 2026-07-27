---
title: SetSize()
second_title: Referência da API Aspose.Slides para C++
description: Define o tamanho do slide por tipo e escala o conteúdo existente.
type: docs
weight: 53
url: /pt/aspose.slides/slidesize/setsize/
---
## SlideSize::SetSize(SlideSizeType, SlideSizeScaleType) método

Define o tamanho do slide por tipo e escala o conteúdo existente.

```cpp
void Aspose::Slides::SlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | O tamanho de slide predefinido a ser aplicado. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | O modo de dimensionamento de conteúdo a ser usado. |

## Observações

Atribuir qualquer valor diferente de [SlideSizeType::Custom](../../slidesizetype/) ajusta o [SlideSize::get_Size](../get_size/) com base no tipo selecionado, preservando o [SlideSize::get_Orientation](../get_orientation/). 

## SlideSize::SetSize(float, float, SlideSizeScaleType) método

Define as dimensões do slide explicitamente e escala o conteúdo existente.

```cpp
void Aspose::Slides::SlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| width | **float** | A nova largura do slide, em pontos. |
| height | **float** | A nova altura do slide, em pontos. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | O modo de dimensionamento de conteúdo a ser usado. |

## Observações

Isso redefine a propriedade [SlideSize::get_Type](../get_type/) para [SlideSizeType::Custom](../../slidesizetype/) e define o [Orientation](../../orientation/). 

## Veja Também

* Enum [SlideSizeType](../../slidesizetype/)
* Enum [SlideSizeScaleType](../../slidesizescaletype/)
* Classe [SlideSize](../)
* Espaço de nomes [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)