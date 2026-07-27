---
title: AddPictureFrame()
second_title: Aspose.Slides para C++ - Referência da API
description: Cria uma nova moldura de imagem contendo a imagem especificada e a adiciona ao final da coleção de formas.
type: docs
weight: 404
url: /pt/aspose.slides/ishapecollection/addpictureframe/
---
## IShapeCollection::AddPictureFrame(ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) method

Cria uma nova moldura de imagem contendo a imagem especificada e a adiciona ao final da coleção de formas.

```cpp
virtual System::SharedPtr<IPictureFrame> Aspose::Slides::IShapeCollection::AddPictureFrame(ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image)=0
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
| x | **float** | A coordenada x da moldura da imagem, em pontos. |
| y | **float** | A coordenada y da moldura da imagem, em pontos. |
| width | **float** | A largura da moldura da imagem, em pontos. |
| height | **float** | A altura da moldura da imagem, em pontos. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | O [IPPImage](../../ippimage/) a ser exibido na moldura da imagem. |

### Valor de Retorno

O [IPictureFrame](../../ipictureframe/) recém-criado.

## Veja Também

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPictureFrame](../../ipictureframe/)
* Classe [IPPImage](../../ippimage/)
* Classe [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)