---
title: add_ole_object_frame method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/shapecollection/add_ole_object_frame/
weight: 100
---
## add_ole_object_frame(self, x, y, width, height, data_info) {#float-float-float-float-ioleembeddeddatainfo}
Cria um novo quadro de objeto OLE e o adiciona ao final da coleção de formas.

### Retorno

O [`IOleObjectFrame`](/slides/python-net/pt/aspose.slides/ioleobjectframe) recém-criado.



```python
def add_ole_object_frame(self, x, y, width, height, data_info):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| x | **float** | A coordenada x do novo quadro OLE, em pontos. |
| y | **float** | A coordenada y do novo quadro OLE, em pontos. |
| width | **float** | A largura do novo quadro OLE, em pontos. |
| height | **float** | A altura do novo quadro OLE, em pontos. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/pt/aspose.slides/ioleembeddeddatainfo) | As informações sobre os dados OLE incorporados ([`IOleEmbeddedDataInfo`](/slides/python-net/pt/aspose.slides/ioleembeddeddatainfo)). |


## add_ole_object_frame(self, x, y, width, height, class_name, path) {#float-float-float-float-str-str}
Cria um novo quadro de objeto OLE e o adiciona ao final da coleção de formas.

### Retorno

O [`IOleObjectFrame`](/slides/python-net/pt/aspose.slides/ioleobjectframe) recém-criado.



```python
def add_ole_object_frame(self, x, y, width, height, class_name, path):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| x | **float** | A coordenada x do novo quadro OLE, em pontos. |
| y | **float** | A coordenada y do novo quadro OLE, em pontos. |
| width | **float** | A largura do novo quadro OLE, em pontos. |
| height | **float** | A altura do novo quadro OLE, em pontos. |
| class_name | **str** | O nome da classe do objeto OLE. |
| path | **str** | O caminho para o arquivo vinculado. <br/><br/>Este caminho é armazenado literalmente na apresentação.<br/><br/>            Se um caminho relativo for especificado, o arquivo ficará inacessível ao abrir<br/><br/>            a apresentação a partir de um diretório diferente. |



### Veja Também
* class [`IOleEmbeddedDataInfo`](/slides/python-net/pt/aspose.slides/ioleembeddeddatainfo)
* class [`IOleObjectFrame`](/slides/python-net/pt/aspose.slides/ioleobjectframe)
* class [`ShapeCollection`](/slides/python-net/pt/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)