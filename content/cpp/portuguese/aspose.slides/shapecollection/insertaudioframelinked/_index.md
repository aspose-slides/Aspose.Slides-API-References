---
title: InsertAudioFrameLinked()
second_title: Referência da API Aspose.Slides para C++
description: Cria um novo quadro de áudio vinculado a um arquivo de áudio externo e o insere na coleção de formas no índice especificado.
type: docs
weight: 274
url: /pt/aspose.slides/shapecollection/insertaudioframelinked/
---
## ShapeCollection::InsertAudioFrameLinked(int32_t, float, float, float, float, System::String) método

Cria um novo quadro de áudio vinculado a um arquivo de áudio externo e o insere na coleção de formas no índice especificado.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameLinked(int32_t index, float x, float y, float width, float height, System::String fname) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | O índice baseados em zero no qual inserir o quadro de áudio. |
| x | **float** | A coordenada x do novo quadro de áudio, em pontos. |
| y | **float** | A coordenada y do novo quadro de áudio, em pontos. |
| width | **float** | A largura do novo quadro de áudio, em pontos. |
| height | **float** | A altura do novo quadro de áudio, em pontos. |
| fname | [System::String](../../../system/string/) | O caminho ou nome do arquivo de áudio externo a ser vinculado. |

### Valor de Retorno

O [IAudioFrame](../../iaudioframe/) recém-criado.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudioFrame](../../iaudioframe/)
* Class [String](../../../system/string/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)