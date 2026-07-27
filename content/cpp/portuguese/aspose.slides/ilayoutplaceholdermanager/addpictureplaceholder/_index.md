---
title: AddPicturePlaceholder()
second_title: Aspose.Slides para C++ Referência da API
description: Adiciona uma nova forma placeholder ao slide de layout para conter uma imagem.
type: docs
weight: 53
url: /pt/aspose.slides/ilayoutplaceholdermanager/addpictureplaceholder/
---
## ILayoutPlaceholderManager::AddPicturePlaceholder(float, float, float, float) método

Adiciona uma nova forma de placeholder ao slide de layout para conter uma imagem.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddPicturePlaceholder(float x, float y, float width, float height)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | **float** | The X coordinate of the new placeholder shape. |
| y | **float** | The Y coordinate of the new placeholder shape. |
| width | **float** | The width of the new placeholder shape. |
| height | **float** | The height of the new placeholder shape. |

### Valor de Retorno

Criado [IAutoShape](../../iautoshape/) com um placeholder [Picture](../../picture/).

## Observações

O exemplo a seguir mostra como adicionar a forma placeholder [Picture](../../picture/) ao slide de layout. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddPicturePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [IAutoShape](../../iautoshape/)
* classe [ILayoutPlaceholderManager](../)
* espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)