---
title: AddTextPlaceholder()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge una nuova forma segnaposto alla diapositiva layout per contenere contenuto testuale.
type: docs
weight: 27
url: /it/aspose.slides/layoutplaceholdermanager/addtextplaceholder/
---
## LayoutPlaceholderManager::AddTextPlaceholder(float, float, float, float) metodo

Aggiunge una nuova forma segnaposto alla diapositiva layout per contenere contenuto testuale.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddTextPlaceholder(float x, float y, float width, float height) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | **float** | La coordinata X della nuova forma segnaposto. |
| y | **float** | La coordinata Y della nuova forma segnaposto. |
| width | **float** | La larghezza della nuova forma segnaposto. |
| height | **float** | L'altezza della nuova forma segnaposto. |

### Valore restituito

Creato [IAutoShape](../../iautoshape/) con un segnaposto di testo.

## Osservazioni

Il seguente esempio mostra come aggiungere la forma segnaposto di testo alla diapositiva layout. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTextPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAutoShape](../../iautoshape/)
* Classe [LayoutPlaceholderManager](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)