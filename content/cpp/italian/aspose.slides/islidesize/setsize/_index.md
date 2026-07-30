---
title: SetSize()
second_title: Aspose.Slides per C++ Riferimento API
description: "Imposta la dimensione della diapositiva per tipo e scala il contenuto esistente. Assegnare qualsiasi valore diverso da SlideSizeType::Custom regola ISlideSize::get_Size in base al tipo selezionato, preservando ISlideSize::get_Orientation."
type: docs
weight: 53
url: /it/aspose.slides/islidesize/setsize/
---
## ISlideSize::SetSize(SlideSizeType, SlideSizeScaleType) metodo

Imposta la dimensione della diapositiva per tipo e scala il contenuto esistente. Assegnare qualsiasi valore diverso da [SlideSizeType::Custom](../../slidesizetype/) regola il [ISlideSize::get_Size](../get_size/) in base al tipo selezionato, preservando [ISlideSize::get_Orientation](../get_orientation/).

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | The predefined slide size to apply. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | The content scaling mode to use. |

## Osservazioni

Assegnare qualsiasi valore diverso da [SlideSizeType::Custom](../../slidesizetype/) regola il [System::Drawing::Size](../../../system.drawing/size/) in base al tipo selezionato, preservando [Orientation](../../orientation/). 

## ISlideSize::SetSize(float, float, SlideSizeScaleType) metodo

Imposta esplicitamente le dimensioni della diapositiva e scala il contenuto esistente. Questa operazione ripristina il valore [ISlideSize::get_Type](../get_type/) a [SlideSizeType::Custom](../../slidesizetype/) e imposta il [ISlideSize::get_Orientation](../get_orientation/).

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | **float** | The new slide width, in points. |
| height | **float** | The new slide height, in points. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | The content scaling mode to use. |

## Osservazioni

Questa operazione ripristina la proprietà [ISlideSize::get_Type](../get_type/) a [SlideSizeType::Custom](../../slidesizetype/) e imposta il [Orientation](../../orientation/). 

## Vedi anche

* Enum [SlideSizeType](../../slidesizetype/)
* Enum [SlideSizeScaleType](../../slidesizescaletype/)
* Classe [ISlideSize](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)