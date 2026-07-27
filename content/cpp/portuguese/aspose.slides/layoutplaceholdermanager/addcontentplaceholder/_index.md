---
title: AddContentPlaceholder()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona uma nova forma de marcador de posição ao slide de layout para conter conteúdo, como uma imagem, tabela, mídia ou texto.
type: docs
weight: 1
url: /pt/aspose.slides/layoutplaceholdermanager/addcontentplaceholder/
---
## LayoutPlaceholderManager::AddContentPlaceholder(float, float, float, float) método

Adiciona uma nova forma de marcador de posição ao slide de layout para conter conteúdo, como uma imagem, tabela, mídia ou texto.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddContentPlaceholder(float x, float y, float width, float height) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | **float** | A coordenada X da nova forma de marcador de posição. |
| y | **float** | A coordenada Y da nova forma de marcador de posição. |
| width | **float** | A largura da nova forma de marcador de posição. |
| height | **float** | A altura da nova forma de marcador de posição. |

### Valor de Retorno

Criado [IAutoShape](../../iautoshape/) com um marcador de posição de conteúdo.

## Observações

O exemplo a seguir mostra como adicionar a forma de marcador de posição de conteúdo ao slide de layout. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddContentPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAutoShape](../../iautoshape/)
* Classe [LayoutPlaceholderManager](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)