---
title: AddPictureFrame()
second_title: Referência da API Aspose.Slides para C++
description: Cria um novo quadro de imagem contendo a imagem especificada e o adiciona ao final da coleção de formas.
type: docs
weight: 443
url: /pt/aspose.slides/shapecollection/addpictureframe/
---
## ShapeCollection::AddPictureFrame(ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) método

Cria um novo quadro de imagem contendo a imagem especificada e o adiciona ao final da coleção de formas.

```cpp
System::SharedPtr<IPictureFrame> Aspose::Slides::ShapeCollection::AddPictureFrame(ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Especifica o tipo de forma contido em [ShapeType](../../shapetype/), exceto para todos os tipos de linhas:

[ShapeType::Line](../../shapetype/),

[ShapeType::StraightConnector1](../../shapetype/),

[ShapeType::BentConnector2](../../shapetype/),

[ShapeType::BentConnector3](../../shapetype/),

[ShapeType::BentConnector4](../../shapetype/),

[ShapeType::BentConnector5](../../shapetype/),

[ShapeType::CurvedConnector2](../../shapetype/),

[ShapeType::CurvedConnector3](../../shapetype/),

[ShapeType::CurvedConnector4](../../shapetype/),

[ShapeType::CurvedConnector5](../../shapetype/). |
| x | **float** | A coordenada x do quadro de imagem, em pontos. |
| y | **float** | A coordenada y do quadro de imagem, em pontos. |
| width | **float** | A largura do quadro de imagem, em pontos. |
| height | **float** | A altura do quadro de imagem, em pontos. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | O [IPPImage](../../ippimage/) a ser exibido no quadro de imagem. |

### Valor de Retorno

O [IPictureFrame](../../ipictureframe/) recém-criado.

## Veja Também

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [IPictureFrame](../../ipictureframe/)
* classe [IPPImage](../../ippimage/)
* classe [ShapeCollection](../)
* espaço de nomes [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)