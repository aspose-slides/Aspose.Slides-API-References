---
title: AddOnlineImagePlaceholder()
second_title: Aspose.Slides para C++ Referência da API
description: Adiciona uma nova forma placeholder ao slide de layout para conter uma imagem online.
type: docs
weight: 118
url: /pt/aspose.slides/layoutplaceholdermanager/addonlineimageplaceholder/
---
## LayoutPlaceholderManager::AddOnlineImagePlaceholder(float, float, float, float) método

Adiciona uma nova forma placeholder ao slide de layout para conter uma imagem online.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddOnlineImagePlaceholder(float x, float y, float width, float height) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | **float** | A coordenada X da nova forma placeholder. |
| y | **float** | A coordenada Y da nova forma placeholder. |
| width | **float** | A largura da nova forma placeholder. |
| height | **float** | A altura da nova forma placeholder. |

### Valor de Retorno

Criado [IAutoShape](../../iautoshape/) com um placeholder de imagem online.

## Observações

O exemplo a seguir mostra como adicionar a forma placeholder de imagem online ao slide de layout. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddOnlineImagePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [LayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)