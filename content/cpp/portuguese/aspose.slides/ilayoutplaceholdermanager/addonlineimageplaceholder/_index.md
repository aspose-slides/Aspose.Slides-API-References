---
title: AddOnlineImagePlaceholder()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona uma nova forma placeholder ao slide de layout para conter uma imagem online.
type: docs
weight: 118
url: /pt/aspose.slides/ilayoutplaceholdermanager/addonlineimageplaceholder/
---
## ILayoutPlaceholderManager::AddOnlineImagePlaceholder(float, float, float, float) method


Adiciona uma nova forma placeholder ao slide de layout para conter uma imagem online.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddOnlineImagePlaceholder(float x, float y, float width, float height)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | **float** | A coordenada X da nova forma placeholder. |
| y | **float** | A coordenada Y da nova forma placeholder. |
| width | **float** | A largura da nova forma placeholder. |
| height | **float** | A altura da nova forma placeholder. |

### Valor de retorno

Criado [IAutoShape](../../iautoshape/) com um placeholder de imagem online.
## Observações



O exemplo a seguir mostra como adicionar a forma placeholder de imagem online ao slide de layout. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddOnlineImagePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAutoShape](../../iautoshape/)
* Classe [ILayoutPlaceholderManager](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)