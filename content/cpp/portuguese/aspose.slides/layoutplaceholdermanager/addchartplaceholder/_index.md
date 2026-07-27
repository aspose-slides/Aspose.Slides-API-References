---
title: AddChartPlaceholder()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona uma nova forma de placeholder ao slide de layout para conter um gráfico.
type: docs
weight: 66
url: /pt/aspose.slides/layoutplaceholdermanager/addchartplaceholder/
---
## LayoutPlaceholderManager::AddChartPlaceholder(float, float, float, float) method


Adiciona uma nova forma de placeholder ao slide de layout para conter um gráfico.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddChartPlaceholder(float x, float y, float width, float height) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | **float** | A coordenada X da nova forma de placeholder. |
| y | **float** | A coordenada Y da nova forma de placeholder. |
| width | **float** | A largura da nova forma de placeholder. |
| height | **float** | A altura da nova forma de placeholder. |

### Valor de Retorno

Criado [IAutoShape](../../iautoshape/) com um placeholder de Chart.

## Observações



O exemplo a seguir mostra como adicionar a forma de placeholder Chart ao slide de layout. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddChartPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [LayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)