---
title: InsertVideoFrame()
second_title: Referência da API Aspose.Slides para C++
description: Cria um novo quadro de vídeo e o insere na coleção de formas no índice especificado.
type: docs
weight: 222
url: /pt/aspose.slides/shapecollection/insertvideoframe/
---
## ShapeCollection::InsertVideoFrame(int32_t, float, float, float, float, System::String) método

Cria um novo quadro de vídeo e o insere na coleção de formas no índice especificado.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::InsertVideoFrame(int32_t index, float x, float y, float width, float height, System::String fname) override
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
* Classe [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)