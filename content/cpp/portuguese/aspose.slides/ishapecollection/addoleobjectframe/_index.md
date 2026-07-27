---
title: AddOleObjectFrame()
second_title: Referência da API Aspose.Slides para C++
description: Cria um novo quadro de objeto OLE e o adiciona ao final da coleção de formas.
type: docs
weight: 66
url: /pt/aspose.slides/ishapecollection/addoleobjectframe/
---
## IShapeCollection::AddOleObjectFrame(float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) método

Cria um novo quadro de objeto OLE e o adiciona ao final da coleção de formas.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | **float** | A coordenada x do novo quadro OLE, em pontos. |
| y | **float** | A coordenada y do novo quadro OLE, em pontos. |
| width | **float** | A largura do novo quadro OLE, em pontos. |
| height | **float** | A altura do novo quadro OLE, em pontos. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | As informações de dados OLE incorporados ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Valor de Retorno

O [IOleObjectFrame](../../ioleobjectframe/) recém-criado.

## IShapeCollection::AddOleObjectFrame(float, float, float, float, System::String, System::String) método

Cria um novo quadro de objeto OLE e o adiciona ao final da coleção de formas.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::String className, System::String path)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | **float** | A coordenada x do novo quadro OLE, em pontos. |
| y | **float** | A coordenada y do novo quadro OLE, em pontos. |
| width | **float** | A largura do novo quadro OLE, em pontos. |
| height | **float** | A altura do novo quadro OLE, em pontos. |
| className | [System::String](../../../system/string/) | O nome da classe do objeto OLE. |
| path | [System::String](../../../system/string/) | O caminho para o arquivo vinculado. |

### Valor de Retorno

O [IOleObjectFrame](../../ioleobjectframe/) recém-criado.
## Observações

Este caminho é armazenado exatamente como está na apresentação. Se um caminho relativo for especificado, o arquivo ficará inacessível ao abrir a apresentação a partir de um diretório diferente.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOleObjectFrame](../../ioleobjectframe/)
* Class [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Class [IShapeCollection](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)