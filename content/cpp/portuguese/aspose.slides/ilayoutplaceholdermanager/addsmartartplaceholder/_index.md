---
title: AddSmartArtPlaceholder()
second_title: Referência da API do Aspose.Slides para C++
description: Adiciona uma nova forma de marcador de posição ao slide de layout para conter um diagrama SmartArt.
type: docs
weight: 92
url: /pt/aspose.slides/ilayoutplaceholdermanager/addsmartartplaceholder/
---
## ILayoutPlaceholderManager::AddSmartArtPlaceholder(float, float, float, float) método


Adiciona uma nova forma de marcador de posição ao slide de layout para conter um diagrama [SmartArt](../../../aspose.slides.smartart/).

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddSmartArtPlaceholder(float x, float y, float width, float height)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | **float** | A coordenada X da nova forma de marcador de posição. |
| y | **float** | A coordenada Y da nova forma de marcador de posição. |
| width | **float** | A largura da nova forma de marcador de posição. |
| height | **float** | A altura da nova forma de marcador de posição. |

### Valor de retorno

Criado [IAutoShape](../../iautoshape/) com um marcador de posição [SmartArt](../../../aspose.slides.smartart/).

## Observações



O exemplo a seguir mostra como adicionar a forma de marcador de posição [SmartArt](../../../aspose.slides.smartart/) ao slide de layout. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddSmartArtPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAutoShape](../../iautoshape/)
* Classe [ILayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)