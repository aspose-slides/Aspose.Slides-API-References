---
title: AddOnlineImagePlaceholder()
second_title: Riferimento API Aspose.Slides per C++
description: Aggiunge una nuova forma placeholder alla diapositiva di layout per contenere un'immagine online.
type: docs
weight: 118
url: /it/aspose.slides/ilayoutplaceholdermanager/addonlineimageplaceholder/
---
## ILayoutPlaceholderManager::AddOnlineImagePlaceholder(float, float, float, float) method


Aggiunge una nuova forma placeholder alla diapositiva di layout per contenere un'immagine online.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddOnlineImagePlaceholder(float x, float y, float width, float height)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | **float** | La coordinata X della nuova forma placeholder. |
| y | **float** | La coordinata Y della nuova forma placeholder. |
| width | **float** | La larghezza della nuova forma placeholder. |
| height | **float** | L'altezza della nuova forma placeholder. |

### Valore di ritorno

Creato [IAutoShape](../../iautoshape/) con un placeholder Online Image.
## Osservazioni



Il seguente esempio mostra come aggiungere la forma placeholder Online Image alla diapositiva di layout. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddOnlineImagePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAutoShape](../../iautoshape/)
* Classe [ILayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)