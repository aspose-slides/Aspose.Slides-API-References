---
title: AddMediaPlaceholder()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere un oggetto multimediale.
type: docs
weight: 105
url: /it/aspose.slides/layoutplaceholdermanager/addmediaplaceholder/
---
## LayoutPlaceholderManager::AddMediaPlaceholder(float, float, float, float) metodo


Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere un oggetto multimediale.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddMediaPlaceholder(float x, float y, float width, float height) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | **float** | La coordinata X della nuova forma segnaposto. |
| y | **float** | La coordinata Y della nuova forma segnaposto. |
| width | **float** | La larghezza della nuova forma segnaposto. |
| height | **float** | L'altezza della nuova forma segnaposto. |

### Valore di ritorno

Creato [IAutoShape](../../iautoshape/) con un segnaposto Media.
## Note



Il seguente esempio mostra come aggiungere la forma segnaposto Media alla diapositiva di layout. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddMediaPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAutoShape](../../iautoshape/)
* Classe [LayoutPlaceholderManager](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)