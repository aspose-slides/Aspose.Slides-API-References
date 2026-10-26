---
title: add_picture_frame method
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/shapecollection/add_picture_frame/
weight: 110
---
## add_picture_frame(self, shape_type, x, y, width, height, image) {#shapetype-float-float-float-float-ippimage}
Cria um novo quadro de imagem contendo a imagem especificada e o adiciona ao final da coleção de formas.

### Retorna

O [`IPictureFrame`](/slides/python-net/pt/aspose.slides/ipictureframe) recém-criado.

```python
def add_picture_frame(self, shape_type, x, y, width, height, image):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/pt/aspose.slides/shapetype) | Especifica o tipo de forma contido em [`ShapeType`](/slides/python-net/pt/aspose.slides/shapetype),<br/><br/>            exceto todos os tipos de linhas:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | A coordenada x do quadro de imagem, em pontos. |
| y | **float** | A coordenada y do quadro de imagem, em pontos. |
| width | **float** | A largura do quadro de imagem, em pontos. |
| height | **float** | A altura do quadro de imagem, em pontos. |
| image | [`IPPImage`](/slides/python-net/pt/aspose.slides/ippimage) | O [`IPPImage`](/slides/python-net/pt/aspose.slides/ippimage) a ser exibido no quadro de imagem. |

### Veja Também
* class [`IPictureFrame`](/slides/python-net/pt/aspose.slides/ipictureframe)
* class [`IPPImage`](/slides/python-net/pt/aspose.slides/ippimage)
* class [`ShapeCollection`](/slides/python-net/pt/aspose.slides/shapecollection)
* enumeration [`ShapeType`](/slides/python-net/pt/aspose.slides/shapetype)
* module [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)