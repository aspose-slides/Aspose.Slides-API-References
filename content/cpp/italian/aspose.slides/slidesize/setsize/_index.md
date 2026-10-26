---
title: SetSize()
second_title: Riferimento API di Aspose.Slides per C++
description: Imposta la dimensione della diapositiva in base al tipo e scala il contenuto esistente.
type: docs
weight: 53
url: /it/aspose.slides/slidesize/setsize/
---
## SlideSize::SetSize(SlideSizeType, SlideSizeScaleType) metodo

Imposta la dimensione della diapositiva per tipo e ridimensiona il contenuto esistente.

```cpp
void Aspose::Slides::SlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | La dimensione della diapositiva predefinita da applicare. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | La modalità di ridimensionamento del contenuto da utilizzare. |
## Note

Assegnare qualsiasi valore diverso da [SlideSizeType::Custom](../../slidesizetype/) regola il [SlideSize::get_Size](../get_size/) in base al tipo selezionato, preservando [SlideSize::get_Orientation](../get_orientation/). 

## SlideSize::SetSize(float, float, SlideSizeScaleType) metodo

Imposta le dimensioni della diapositiva esplicitamente e ridimensiona il contenuto esistente.

```cpp
void Aspose::Slides::SlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | **float** | La nuova larghezza della diapositiva, in punti. |
| height | **float** | La nuova altezza della diapositiva, in punti. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | La modalità di ridimensionamento del contenuto da utilizzare. |
## Note

Questo reimposta la proprietà [SlideSize::get_Type](../get_type/) a [SlideSizeType::Custom](../../slidesizetype/) e imposta il [Orientation](../../orientation/). 

## Vedi anche

* Enum [SlideSizeType](../../slidesizetype/)
* Enum [SlideSizeScaleType](../../slidesizescaletype/)
* Classe [SlideSize](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)