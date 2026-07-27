---
title: AddSmartArtPlaceholder()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona uma nova forma de placeholder ao slide de layout para conter um diagrama SmartArt.
type: docs
weight: 92
url: /pt/aspose.slides/layoutplaceholdermanager/addsmartartplaceholder/
---
## LayoutPlaceholderManager::AddSmartArtPlaceholder(float, float, float, float) método


Adiciona uma nova forma de placeholder ao slide de layout para conter um diagrama [SmartArt](../../../aspose.slides.smartart/).

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddSmartArtPlaceholder(float x, float y, float width, float height) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | **float** | A coordenada X da nova forma de placeholder. |
| y | **float** | A coordenada Y da nova forma de placeholder. |
| width | **float** | A largura da nova forma de placeholder. |
| height | **float** | A altura da nova forma de placeholder. |

### Valor de retorno

Criado [IAutoShape](../../iautoshape/) com um placeholder [SmartArt](../../../aspose.slides.smartart/).

## Observações



O exemplo a seguir mostra como adicionar a forma de placeholder [SmartArt](../../../aspose.slides.smartart/) ao slide de layout. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddSmartArtPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAutoShape](../../iautoshape/)
* Classe [LayoutPlaceholderManager](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)