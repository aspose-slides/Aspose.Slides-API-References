---
title: AddVerticalTextPlaceholder()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona uma nova forma de placeholder ao slide de layout para conter conteúdo de texto em direção vertical.
type: docs
weight: 40
url: /pt/aspose.slides/layoutplaceholdermanager/addverticaltextplaceholder/
---
## LayoutPlaceholderManager::AddVerticalTextPlaceholder(float, float, float, float) método


Adiciona uma nova forma de placeholder ao slide de layout para conter conteúdo de texto em direção vertical.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddVerticalTextPlaceholder(float x, float y, float width, float height) override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | The X coordinate of the new placeholder shape. |
| y | **float** | The Y coordinate of the new placeholder shape. |
| width | **float** | The width of the new placeholder shape. |
| height | **float** | The height of the new placeholder shape. |

### Valor de Retorno

Criado [IAutoShape](../../iautoshape/) com um placeholder de Texto (Vertical).
## Observações



O exemplo a seguir mostra como adicionar a forma de placeholder Texto (Vertical) ao slide de layout. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalTextPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAutoShape](../../iautoshape/)
* Classe [LayoutPlaceholderManager](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)