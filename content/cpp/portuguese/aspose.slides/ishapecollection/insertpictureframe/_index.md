---
title: InsertPictureFrame()
second_title: Referência da API Aspose.Slides para C++
description: Cria um novo quadro de imagem contendo a imagem especificada e o insere na coleção de formas no índice especificado.
type: docs
weight: 417
url: /pt/aspose.slides/ishapecollection/insertpictureframe/
---
## IShapeCollection::InsertPictureFrame(int32_t, ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) method


Cria um novo quadro de imagem contendo a imagem especificada e o insere na coleção de formas no índice especificado.

```cpp
virtual System::SharedPtr<IPictureFrame> Aspose::Slides::IShapeCollection::InsertPictureFrame(int32_t index, ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image)=0
```


### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | O índice base zero no qual inserir o quadro de imagem. |
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

### Return Value

O [IPictureFrame](../../ipictureframe/) recém-criado.

## Ver também

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPictureFrame](../../ipictureframe/)
* Class [IPPImage](../../ippimage/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)