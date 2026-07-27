---
title: InsertVideoFrame()
second_title: Referência da API Aspose.Slides para C++
description: Cria um novo quadro de vídeo e o insere na coleção de formas no índice especificado.
type: docs
weight: 183
url: /pt/aspose.slides/ishapecollection/insertvideoframe/
---
## IShapeCollection::InsertVideoFrame(int32_t, float, float, float, float, System::String) método

Cria um novo quadro de vídeo e o insere na coleção de formas no índice especificado.

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::InsertVideoFrame(int32_t index, float x, float y, float width, float height, System::String fname)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | O índice baseado em zero no qual inserir o quadro de vídeo. |
| x | **float** | A coordenada x do novo quadro de vídeo, em pontos. |
| y | **float** | A coordenada y do novo quadro de vídeo, em pontos. |
| width | **float** | A largura do novo quadro de vídeo, em pontos. |
| height | **float** | A altura do novo quadro de vídeo, em pontos. |
| fname | [System::String](../../../system/string/) | O caminho ou nome do arquivo de vídeo a ser incorporado. |

### Valor de Retorno

O [IVideoFrame](../../ivideoframe/) recém-criado.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IVideoFrame](../../ivideoframe/)
* Classe [String](../../../system/string/)
* Classe [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)