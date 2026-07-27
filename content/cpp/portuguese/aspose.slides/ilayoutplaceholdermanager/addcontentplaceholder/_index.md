---
title: AddContentPlaceholder()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona uma nova forma placeholder ao slide de layout para conter conteúdo, como uma imagem, tabela, mídia ou texto.
type: docs
weight: 1
url: /pt/aspose.slides/ilayoutplaceholdermanager/addcontentplaceholder/
---
## ILayoutPlaceholderManager::AddContentPlaceholder(float, float, float, float) método

Adiciona uma nova forma placeholder ao slide de layout para conter conteúdo, como uma imagem, tabela, mídia ou texto.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddContentPlaceholder(float x, float y, float width, float height)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | **float** | A coordenada X da nova forma placeholder. |
| y | **float** | A coordenada Y da nova forma placeholder. |
| width | **float** | A largura da nova forma placeholder. |
| height | **float** | A altura da nova forma placeholder. |

### Valor de Retorno

Criado [IAutoShape](../../iautoshape/) com um placeholder de Conteúdo.

## Observações

O exemplo a seguir mostra como adicionar a forma placeholder de Conteúdo ao slide de layout. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddContentPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAutoShape](../../iautoshape/)
* Classe [ILayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)