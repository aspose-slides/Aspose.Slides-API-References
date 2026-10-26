---
title: insert_picture_frame method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/shapecollection/insert_picture_frame/
weight: 290
---
## insert_picture_frame(self, index, shape_type, x, y, width, height, image) {#int-shapetype-float-float-float-float-ippimage}
Cria uma nova moldura de imagem contendo a imagem especificada e a insere na forma
            coleção no índice especificado.

### Retorno

O [`IPictureFrame`](/slides/python-net/pt/aspose.slides/ipictureframe) recém-criado.



```python
def insert_picture_frame(self, index, shape_type, x, y, width, height, image):
    ...
```



| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| index | **int** | O índice baseado em zero no qual inserir a moldura de imagem. |
| shape_type | [`ShapeType`](/slides/python-net/pt/aspose.slides/shapetype) | Especifica o tipo de forma contido em [`ShapeType`](/slides/python-net/pt/aspose.slides/shapetype),<br/><br/>            exceto para todos os tipos de linhas:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | A coordenada x da moldura de imagem, em pontos. |
| y | **float** | A coordenada y da moldura de imagem, em pontos. |
| width | **float** | A largura da moldura de imagem, em pontos. |
| height | **float** | A altura da moldura de imagem, em pontos. |
| image | [`IPPImage`](/slides/python-net/pt/aspose.slides/ippimage) | O [`IPPImage`](/slides/python-net/pt/aspose.slides/ippimage) a ser exibido na moldura de imagem. |



### Veja Também
* classe [`IPictureFrame`](/slides/python-net/pt/aspose.slides/ipictureframe)
* classe [`IPPImage`](/slides/python-net/pt/aspose.slides/ippimage)
* classe [`ShapeCollection`](/slides/python-net/pt/aspose.slides/shapecollection)
* enumeração [`ShapeType`](/slides/python-net/pt/aspose.slides/shapetype)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)