---
title: AddTextPlaceholder()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona uma nova forma de placeholder ao slide de layout para conter conteúdo de texto.
type: docs
weight: 27
url: /pt/aspose.slides/layoutplaceholdermanager/addtextplaceholder/
---
## LayoutPlaceholderManager::AddTextPlaceholder(float, float, float, float) método

Adiciona uma nova forma de placeholder ao slide de layout para conter conteúdo de texto.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddTextPlaceholder(float x, float y, float width, float height) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | **float** | A coordenada X da nova forma de placeholder. |
| y | **float** | A coordenada Y da nova forma de placeholder. |
| width | **float** | A largura da nova forma de placeholder. |
| height | **float** | A altura da nova forma de placeholder. |

### Valor de Retorno

Criado [IAutoShape](../../iautoshape/) com um placeholder de Texto.

## Observações

O exemplo a seguir mostra como adicionar a forma de placeholder de Texto ao slide de layout. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTextPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAutoShape](../../iautoshape/)
* Classe [LayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)