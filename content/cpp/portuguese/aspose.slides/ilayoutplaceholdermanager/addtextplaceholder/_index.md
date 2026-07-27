---
title: AddTextPlaceholder()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona uma nova forma de espaço reservado ao slide de layout para conter conteúdo de texto.
type: docs
weight: 27
url: /pt/aspose.slides/ilayoutplaceholdermanager/addtextplaceholder/
---
## ILayoutPlaceholderManager::AddTextPlaceholder(float, float, float, float) method


Adiciona uma nova forma de espaço reservado ao slide de layout para conter conteúdo de texto.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddTextPlaceholder(float x, float y, float width, float height)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | **float** | A coordenada X da nova forma de espaço reservado. |
| y | **float** | A coordenada Y da nova forma de espaço reservado. |
| width | **float** | A largura da nova forma de espaço reservado. |
| height | **float** | A altura da nova forma de espaço reservado. |

### Valor de Retorno

Criado [IAutoShape](../../iautoshape/) com um espaço reservado de Texto.
## Observações



O exemplo a seguir mostra como adicionar a forma de espaço reservado de Texto ao slide de layout. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTextPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAutoShape](../../iautoshape/)
* Classe [ILayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)