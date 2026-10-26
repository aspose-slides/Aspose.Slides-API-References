---
title: SetSize()
second_title: Aspose.Slides para C++ Referência da API
description: "Define o tamanho do slide por tipo e dimensiona o conteúdo existente. Atribuir qualquer valor diferente de SlideSizeType::Custom ajusta o ISlideSize::get_Size com base no tipo selecionado, enquanto preserva o ISlideSize::get_Orientation."
type: docs
weight: 53
url: /pt/aspose.slides/islidesize/setsize/
---
## ISlideSize::SetSize(SlideSizeType, SlideSizeScaleType) método

Define o tamanho do slide por tipo e dimensiona o conteúdo existente. Atribuir qualquer valor diferente de [SlideSizeType::Custom](../../slidesizetype/) ajusta o [ISlideSize::get_Size](../get_size/) com base no tipo selecionado, preservando [ISlideSize::get_Orientation](../get_orientation/).

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | O tamanho de slide predefinido a ser aplicado. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | O modo de dimensionamento de conteúdo a ser usado. |

## Observações

Atribuir qualquer valor diferente de [SlideSizeType::Custom](../../slidesizetype/) ajusta o [System::Drawing::Size](../../../system.drawing/size/) com base no tipo selecionado, preservando [Orientation](../../orientation/). 

## ISlideSize::SetSize(float, float, SlideSizeScaleType) método

Define as dimensões do slide explicitamente e dimensiona o conteúdo existente. Isso redefinirá o valor [ISlideSize::get_Type](../get_type/) para [SlideSizeType::Custom](../../slidesizetype/) e definirá o [ISlideSize::get_Orientation](../get_orientation/).

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| width | **float** | A nova largura do slide, em pontos. |
| height | **float** | A nova altura do slide, em pontos. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | O modo de dimensionamento de conteúdo a ser usado. |

## Observações

Isso redefinirá a propriedade [ISlideSize::get_Type](../get_type/) para [SlideSizeType::Custom](../../slidesizetype/) e definirá o [Orientation](../../orientation/). 

## Veja Também

* Enum [SlideSizeType](../../slidesizetype/)
* Enum [SlideSizeScaleType](../../slidesizescaletype/)
* Classe [ISlideSize](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)