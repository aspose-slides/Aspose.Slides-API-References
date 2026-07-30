---
title: AddChartPlaceholder()
second_title: Riferimento API Aspose.Slides per C++
description: Aggiunge una nuova forma placeholder alla diapositiva del layout per contenere un grafico.
type: docs
weight: 66
url: /it/aspose.slides/layoutplaceholdermanager/addchartplaceholder/
---
## LayoutPlaceholderManager::AddChartPlaceholder(float, float, float, float) metodo

Aggiunge una nuova forma placeholder alla diapositiva del layout per contenere un grafico.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddChartPlaceholder(float x, float y, float width, float height) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | **float** | La coordinata X della nuova forma placeholder. |
| y | **float** | La coordinata Y della nuova forma placeholder. |
| width | **float** | La larghezza della nuova forma placeholder. |
| height | **float** | L'altezza della nuova forma placeholder. |

### Valore restituito

Creato [IAutoShape](../../iautoshape/) con un placeholder Chart.

## Osservazioni

Il seguente esempio mostra come aggiungere la forma placeholder Chart alla diapositiva del layout. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddChartPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAutoShape](../../iautoshape/)
* Classe [LayoutPlaceholderManager](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)