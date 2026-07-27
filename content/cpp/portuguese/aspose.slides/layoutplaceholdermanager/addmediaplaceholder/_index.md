---
title: AddMediaPlaceholder()
second_title: Referência da API Aspose.Slides for C++ 
description: Adiciona uma nova forma de espaço reservado ao slide de layout para conter um objeto de mídia.
type: docs
weight: 105
url: /pt/aspose.slides/layoutplaceholdermanager/addmediaplaceholder/
---
## LayoutPlaceholderManager::AddMediaPlaceholder(float, float, float, float) método

Adiciona uma nova forma de espaço reservado ao slide de layout para conter um objeto de mídia.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddMediaPlaceholder(float x, float y, float width, float height) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | **float** | A coordenada X da nova forma de espaço reservado. |
| y | **float** | A coordenada Y da nova forma de espaço reservado. |
| width | **float** | A largura da nova forma de espaço reservado. |
| height | **float** | A altura da nova forma de espaço reservado. |

### Valor de Retorno

Criado [IAutoShape](../../iautoshape/) com um placeholder Media.

## Observações

O exemplo a seguir mostra como adicionar a forma placeholder Media ao slide de layout. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddMediaPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAutoShape](../../iautoshape/)
* Classe [LayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)