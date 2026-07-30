---
title: AddVerticalTextPlaceholder()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge una nuova forma segnaposto alla diapositiva modello per contenere il testo in direzione verticale.
type: docs
weight: 40
url: /it/aspose.slides/layoutplaceholdermanager/addverticaltextplaceholder/
---
## LayoutPlaceholderManager::AddVerticalTextPlaceholder(float, float, float, float) method

Aggiunge una nuova forma segnaposto alla diapositiva modello per contenere il testo in direzione verticale.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddVerticalTextPlaceholder(float x, float y, float width, float height) override
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | La coordinata X della nuova forma segnaposto. |
| y | **float** | La coordinata Y della nuova forma segnaposto. |
| width | **float** | La larghezza della nuova forma segnaposto. |
| height | **float** | L'altezza della nuova forma segnaposto. |

### Valore di ritorno

Creato [IAutoShape](../../iautoshape/) con un segnaposto Testo (Verticale).

## Note



L'esempio seguente mostra come aggiungere la forma segnaposto Testo (Verticale) alla diapositiva modello. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalTextPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [LayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)