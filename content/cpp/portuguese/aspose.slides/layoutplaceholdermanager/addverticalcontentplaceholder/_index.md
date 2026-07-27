---
title: AddVerticalContentPlaceholder()
second_title: Aspose.Slides para C++ Referência da API
description: Adiciona uma nova forma de espaço reservado ao slide de layout para conter conteúdo, como uma imagem, tabela, mídia ou texto em direção vertical.
type: docs
weight: 14
url: /pt/aspose.slides/layoutplaceholdermanager/addverticalcontentplaceholder/
---
## LayoutPlaceholderManager::AddVerticalContentPlaceholder(float, float, float, float) método

Adiciona uma nova forma de espaço reservado ao slide de layout para conter conteúdo, como uma imagem, tabela, mídia ou texto em direção vertical.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddVerticalContentPlaceholder(float x, float y, float width, float height) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | **float** | A coordenada X da nova forma de espaço reservado. |
| y | **float** | A coordenada Y da nova forma de espaço reservado. |
| width | **float** | A largura da nova forma de espaço reservado. |
| height | **float** | A altura da nova forma de espaço reservado. |

### Valor de Retorno

Criado [IAutoShape](../../iautoshape/) com um espaço reservado de Conteúdo (Vertical).

## Observações

O exemplo a seguir mostra como adicionar a forma de espaço reservado de Conteúdo (Vertical) ao slide de layout. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalContentPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAutoShape](../../iautoshape/)
* Classe [LayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)