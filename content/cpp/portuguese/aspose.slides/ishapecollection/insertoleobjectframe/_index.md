---
title: InsertOleObjectFrame()
second_title: Referência da API Aspose.Slides para C++
description: Cria um novo quadro de objeto OLE e o insere na coleção de formas no índice especificado.
type: docs
weight: 79
url: /pt/aspose.slides/ishapecollection/insertoleobjectframe/
---
## IShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) método

Cria um novo quadro de objeto OLE e o insere na coleção de formas no índice especificado.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo)=0
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | O índice baseado em zero no qual inserir o quadro de objeto OLE. |
| x | **float** | A coordenada x do novo quadro OLE, em pontos. |
| y | **float** | A coordenada y do novo quadro OLE, em pontos. |
| width | **float** | A largura do novo quadro OLE, em pontos. |
| height | **float** | A altura do novo quadro OLE, em pontos. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | As informações de dados OLE incorporados ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Valor de retorno

O recém-criado [IOleObjectFrame](../../ioleobjectframe/).

## IShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) método

Cria um novo quadro de objeto OLE e o insere na coleção de formas no índice especificado.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path)=0
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | O índice baseado em zero no qual inserir o quadro de objeto OLE. |
| x | **float** | A coordenada x do novo quadro OLE, em pontos. |
| y | **float** | A coordenada y do novo quadro OLE, em pontos. |
| width | **float** | A largura do novo quadro OLE, em pontos. |
| height | **float** | A altura do novo quadro OLE, em pontos. |
| className | [System::String](../../../system/string/) | O nome da classe do objeto OLE. |
| path | [System::String](../../../system/string/) | O caminho para o arquivo vinculado. |

### Valor de retorno

O recém-criado [IOleObjectFrame](../../ioleobjectframe/).

## Observações

Este caminho é armazenado literalmente na apresentação. Se um caminho relativo for especificado, o arquivo ficará inacessível ao abrir a apresentação a partir de um diretório diferente.

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IOleObjectFrame](../../ioleobjectframe/)
* Classe [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Classe [IShapeCollection](../)
* Classe [String](../../../system/string/)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)