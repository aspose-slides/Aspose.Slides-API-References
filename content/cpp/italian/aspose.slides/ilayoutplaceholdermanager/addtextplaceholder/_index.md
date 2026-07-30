---
title: AddTextPlaceholder()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere testo.
type: docs
weight: 27
url: /it/aspose.slides/ilayoutplaceholdermanager/addtextplaceholder/
---
## ILayoutPlaceholderManager::AddTextPlaceholder(float, float, float, float) metodo


Adds a new placeholder shape to the layout slide to hold text content.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddTextPlaceholder(float x, float y, float width, float height)=0
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | La coordinata X della nuova forma segnaposto. |
| y | **float** | La coordinata Y della nuova forma segnaposto. |
| width | **float** | La larghezza della nuova forma segnaposto. |
| height | **float** | L'altezza della nuova forma segnaposto. |

## Valore di ritorno

Creato [IAutoShape](../../iautoshape/) con un segnaposto di Testo.
## Osservazioni



Il seguente esempio mostra come aggiungere la forma segnaposto di Testo alla diapositiva di layout. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTextPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAutoShape](../../iautoshape/)
* Classe [ILayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)