---
title: AddVideoFrame()
second_title: Referência da API Aspose.Slides para C++
description: Cria um novo quadro de vídeo e o adiciona ao final da coleção de formas.
type: docs
weight: 170
url: /pt/aspose.slides/ishapecollection/addvideoframe/
---
## IShapeCollection::AddVideoFrame(float, float, float, float, System::String) método

Cria um novo quadro de vídeo e o adiciona ao final da coleção de formas.

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::String fname)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | **float** | A coordenada x do novo quadro de vídeo, em pontos. |
| y | **float** | A coordenada y do novo quadro de vídeo, em pontos. |
| width | **float** | A largura do novo quadro de vídeo, em pontos. |
| height | **float** | A altura do novo quadro de vídeo, em pontos. |
| fname | [System::String](../../../system/string/) | O caminho ou nome do arquivo de vídeo a incorporar. |

### Valor de Retorno

O [IVideoFrame](../../ivideoframe/) recém-criado.

## IShapeCollection::AddVideoFrame(float, float, float, float, System::SharedPtr\<IVideo\>) método

Cria um novo quadro de vídeo e o adiciona ao final da coleção de formas.

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::SharedPtr<IVideo> video)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | **float** | A coordenada x do novo quadro de vídeo, em pontos. |
| y | **float** | A coordenada y do novo quadro de vídeo, em pontos. |
| width | **float** | A largura do novo quadro de vídeo, em pontos. |
| height | **float** | A altura do novo quadro de vídeo, em pontos. |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | O [IVideo](../../ivideo/) a incorporar no quadro de vídeo. |

### Valor de Retorno

O [IVideoFrame](../../ivideoframe/) recém-criado.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IVideoFrame](../../ivideoframe/)
* Classe [String](../../../system/string/)
* Classe [IShapeCollection](../)
* Classe [IVideo](../../ivideo/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)