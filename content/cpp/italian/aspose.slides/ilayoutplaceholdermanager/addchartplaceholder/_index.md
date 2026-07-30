---
title: AddChartPlaceholder()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere un grafico.
type: docs
weight: 66
url: /it/aspose.slides/ilayoutplaceholdermanager/addchartplaceholder/
---
## ILayoutPlaceholderManager::AddChartPlaceholder(float, float, float, float) method


Aggiunge una nuova forma segnaposto alla diapositiva di layout per contenere un grafico.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddChartPlaceholder(float x, float y, float width, float height)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | **float** | La coordinata X della nuova forma segnaposto. |
| y | **float** | La coordinata Y della nuova forma segnaposto. |
| width | **float** | La larghezza della nuova forma segnaposto. |
| height | **float** | L'altezza della nuova forma segnaposto. |

### Valore restituito

Creato [IAutoShape](../../iautoshape/) con un segnaposto Chart.
## Osservazioni



Il seguente esempio mostra come aggiungere la forma segnaposto Chart alla diapositiva di layout. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddChartPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [ILayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)