---
title: InsertOleObjectFrame()
second_title: Referência da API Aspose.Slides para C++
description: Cria um novo quadro de objeto OLE e o insere na coleção de shapes no índice especificado.
type: docs
weight: 196
url: /pt/aspose.slides/shapecollection/insertoleobjectframe/
---
## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) método

Cria um novo quadro de objeto OLE e o insere na coleção de shapes no índice especificado.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | O índice baseado em zero no qual inserir o quadro de objeto OLE. |
| x | **float** | A coordenada x do novo quadro OLE, em pontos. |
| y | **float** | A coordenada y do novo quadro OLE, em pontos. |
| width | **float** | A largura do novo quadro OLE, em pontos. |
| height | **float** | A altura do novo quadro OLE, em pontos. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | As informações de dados OLE incorporados ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Valor de Retorno

O [IOleObjectFrame](../../ioleobjectframe/) recém-criado.

## Observações



Este exemplo demonstra a inserção de um objeto OLE no segundo índice:
```cpp
ArrayPtr<uint8_t> fileData = IO::File::ReadAllBytes(u"test.zip");
auto dataInfo = MakeObject<OleEmbeddedDataInfo>(fileData, u"zip");
auto oleObjectFrame = slide->get_Shapes()->InsertOleObjectFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, dataInfo);
```

## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) método


Cria um novo quadro de objeto OLE e o insere na coleção de shapes no índice especificado.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | O índice baseado em zero no qual inserir o quadro de objeto OLE. |
| x | **float** | A coordenada x do novo quadro OLE, em pontos. |
| y | **float** | A coordenada y do novo quadro OLE, em pontos. |
| width | **float** | A largura do novo quadro OLE, em pontos. |
| height | **float** | A altura do novo quadro OLE, em pontos. |
| className | [System::String](../../../system/string/) | O nome da classe do objeto OLE. |
| path | [System::String](../../../system/string/) | O caminho para o arquivo vinculado. |

### Valor de Retorno

O quadro de objeto OLE recém-criado.

## Observações



Este caminho é armazenado literalmente na apresentação. Se um caminho relativo for especificado, o arquivo ficará inacessível ao abrir a apresentação a partir de um diretório diferente.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IOleObjectFrame](../../ioleobjectframe/)
* Classe [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Classe [ShapeCollection](../)
* Classe [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)