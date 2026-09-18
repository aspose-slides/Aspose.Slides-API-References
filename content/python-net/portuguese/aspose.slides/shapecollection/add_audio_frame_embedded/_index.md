---
title: add_audio_frame_embedded method
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides/shapecollection/add_audio_frame_embedded/
weight: 20
---
## add_audio_frame_embedded(self, x, y, width, height, audio_stream) {#float-float-float-float-iorawiobase}
Cria um novo quadro de áudio com um arquivo WAV incorporado e o adiciona ao final da coleção de formas. O áudio incorporado é adicionado à coleção Presentation.Audios.

### Returns

O [`IAudioFrame`](/slides/python-net/pt/aspose.slides/iaudioframe) recém-criado.

```python
def add_audio_frame_embedded(self, x, y, width, height, audio_stream):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| x | **float** | A coordenada x do novo quadro de áudio, em pontos. |
| y | **float** | A coordenada y do novo quadro de áudio, em pontos. |
| width | **float** | A largura do novo quadro de áudio, em pontos. |
| height | **float** | A altura do novo quadro de áudio, em pontos. |
| audio_stream | **io.RawIOBase** | Um fluxo de entrada contendo dados de áudio WAV para incorporar. |

## add_audio_frame_embedded(self, x, y, width, height, audio) {#float-float-float-float-iaudio}
Cria um novo quadro de áudio e o adiciona ao final da coleção de formas usando um objeto de áudio existente da lista Presentation.Audios.

### Returns

O [`IAudioFrame`](/slides/python-net/pt/aspose.slides/iaudioframe) recém-criado.

```python
def add_audio_frame_embedded(self, x, y, width, height, audio):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| x | **float** | A coordenada x do novo quadro de áudio, em pontos. |
| y | **float** | A coordenada y do novo quadro de áudio, em pontos. |
| width | **float** | A largura do novo quadro de áudio, em pontos. |
| height | **float** | A altura do novo quadro de áudio, em pontos. |
| audio | [`IAudio`](/slides/python-net/pt/aspose.slides/iaudio) | Uma instância [`IAudio`](/slides/python-net/pt/aspose.slides/iaudio) da coleção Presentation.Audios. |

### Veja também
* classe [`IAudio`](/slides/python-net/pt/aspose.slides/iaudio)
* classe [`IAudioFrame`](/slides/python-net/pt/aspose.slides/iaudioframe)
* classe [`ShapeCollection`](/slides/python-net/pt/aspose.slides/shapecollection)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)