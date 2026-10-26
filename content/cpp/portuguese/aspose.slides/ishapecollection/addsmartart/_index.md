---
title: AddSmartArt()
second_title: Referência da API Aspose.Slides para C++
description: Cria um diagrama SmartArt e o adiciona ao final da coleção de formas.
type: docs
weight: 40
url: /pt/aspose.slides/ishapecollection/addsmartart/
---
## IShapeCollection::AddSmartArt(float, float, float, float, SmartArt::SmartArtLayoutType) método

Cria um diagrama [SmartArt](../../../aspose.slides.smartart/) e o adiciona ao final da coleção de formas.

```cpp
virtual System::SharedPtr<SmartArt::ISmartArt> Aspose::Slides::IShapeCollection::AddSmartArt(float x, float y, float width, float height, SmartArt::SmartArtLayoutType layoutType)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | **float** | A coordenada x da moldura do diagrama, em pontos. |
| y | **float** | A coordenada y da moldura do diagrama, em pontos. |
| width | **float** | A largura da moldura do diagrama, em pontos. |
| height | **float** | A altura da moldura do diagrama, em pontos. |
| layoutType | [SmartArt::SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/) | O tipo de layout [SmartArt](../../../aspose.slides.smartart/). |

### Valor de Retorno

O [SmartArt::ISmartArt](../../../aspose.slides.smartart/ismartart/) recém-criado.

## Observações

```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slide(0);
auto smart = slide->get_Shapes()->AddSmartArt(0.0f, 0.0f, 400.0f, 400.0f, SmartArtLayoutType::BasicBlockList);
```

## Veja Também

* Enum [SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISmartArt](../../../aspose.slides.smartart/ismartart/)
* Classe [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)