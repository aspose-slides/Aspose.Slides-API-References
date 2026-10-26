---
title: insert_ole_object_frame method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/shapecollection/insert_ole_object_frame/
weight: 280
---
## insert_ole_object_frame(self, index, x, y, width, height, data_info) {#int-float-float-float-float-ioleembeddeddatainfo}
Cria um novo quadro de objeto OLE e o insere na coleção de formas no índice especificado.

### Retorna

O [`IOleObjectFrame`](/slides/python-net/pt/aspose.slides/ioleobjectframe) recém-criado.



```python
def insert_ole_object_frame(self, index, x, y, width, height, data_info):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| index | **int** | O índice baseado em zero no qual inserir o quadro de objeto OLE. |
| x | **float** | A coordenada x do novo quadro OLE, em pontos. |
| y | **float** | A coordenada y do novo quadro OLE, em pontos. |
| width | **float** | A largura do novo quadro OLE, em pontos. |
| height | **float** | A altura do novo quadro OLE, em pontos. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/pt/aspose.slides/ioleembeddeddatainfo) | As informações de dados OLE incorporados ([`IOleEmbeddedDataInfo`](/slides/python-net/pt/aspose.slides/ioleembeddeddatainfo)). |


## insert_ole_object_frame(self, index, x, y, width, height, class_name, path) {#int-float-float-float-float-str-str}
Cria um novo quadro de objeto OLE e o insere na coleção de formas no índice especificado.

### Retorna

O quadro de objeto OLE recém-criado.



```python
def insert_ole_object_frame(self, index, x, y, width, height, class_name, path):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| index | **int** | O índice baseado em zero no qual inserir o quadro de objeto OLE. |
| x | **float** | A coordenada x do novo quadro OLE, em pontos. |
| y | **float** | A coordenada y do novo quadro OLE, em pontos. |
| width | **float** | A largura do novo quadro OLE, em pontos. |
| height | **float** | A altura do novo quadro OLE, em pontos. |
| class_name | **str** | O nome da classe do objeto OLE. |
| path | **str** | O caminho para o arquivo vinculado. <br/><br/>Este caminho é armazenado literalmente na apresentação.<br/><br/>            Se um caminho relativo for especificado, o arquivo ficará inacessível ao abrir<br/><br/>            a apresentação a partir de um diretório diferente. |



### Veja Também
* classe [`IOleEmbeddedDataInfo`](/slides/python-net/pt/aspose.slides/ioleembeddeddatainfo)
* classe [`IOleObjectFrame`](/slides/python-net/pt/aspose.slides/ioleobjectframe)
* classe [`ShapeCollection`](/slides/python-net/pt/aspose.slides/shapecollection)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)