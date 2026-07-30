---
title: AddContentPlaceholder()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere contenuti, come un'immagine, una tabella, media o testo.
type: docs
weight: 1
url: /it/aspose.slides/ilayoutplaceholdermanager/addcontentplaceholder/
---
## ILayoutPlaceholderManager::AddContentPlaceholder(float, float, float, float) metodo

Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere contenuti, come un'immagine, una tabella, media o testo.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddContentPlaceholder(float x, float y, float width, float height)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | **float** | La coordinata X della nuova forma segnaposto. |
| y | **float** | La coordinata Y della nuova forma segnaposto. |
| width | **float** | La larghezza della nuova forma segnaposto. |
| height | **float** | L'altezza della nuova forma segnaposto. |

### Valore di ritorno

Creato [IAutoShape](../../iautoshape/) con un segnaposto Content.

## Osservazioni

Il seguente esempio mostra come aggiungere la forma segnaposto Content alla diapositiva di layout. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddContentPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAutoShape](../../iautoshape/)
* Classe [ILayoutPlaceholderManager](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)