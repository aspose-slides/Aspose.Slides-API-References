--- 
title: AddTablePlaceholder()
second_title: Aspose.Slides para C++ Referência da API
description: Adiciona uma nova forma de placeholder ao slide de layout para conter uma tabela.
type: docs
weight: 79
url: /pt/aspose.slides/layoutplaceholdermanager/addtableplaceholder/
---
## LayoutPlaceholderManager::AddTablePlaceholder(float, float, float, float) método

Adiciona uma nova forma de placeholder ao slide de layout para conter uma tabela.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddTablePlaceholder(float x, float y, float width, float height) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | **float** | A coordenada X da nova forma de placeholder. |
| y | **float** | A coordenada Y da nova forma de placeholder. |
| width | **float** | A largura da nova forma de placeholder. |
| height | **float** | A altura da nova forma de placeholder. |

### Valor de Retorno

Criado [IAutoShape](../../iautoshape/) com um placeholder [Table](../../table/).

## Observações

O exemplo a seguir mostra como adicionar a forma placeholder [Table](../../table/) ao slide de layout. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTablePlaceholder(20.0f, 20.0f, 500.0f, 200.0f);
```

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [LayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)