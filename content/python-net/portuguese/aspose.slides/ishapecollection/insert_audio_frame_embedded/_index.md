---
title: insert_audio_frame_embedded method
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides/ishapecollection/insert_audio_frame_embedded/
weight: 210
---
## insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream) {#int-float-float-float-float-iorawiobase}
Cria um novo quadro de áudio com um arquivo WAV incorporado e o insere na coleção de formas no índice especificado. O áudio incorporado é adicionado à coleção Presentation.Audios.

### Retorno

O [`IAudioFrame`](/slides/python-net/pt/aspose.slides/iaudioframe) recém criado.



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| index | **int** | O índice baseado em zero no qual inserir o quadro de áudio. |
| x | **float** | A coordenada x do novo quadro de áudio, em pontos. |
| y | **float** | A coordenada y do novo quadro de áudio, em pontos. |
| width | **float** | A largura do novo quadro de áudio, em pontos. |
| height | **float** | A altura do novo quadro de áudio, em pontos. |
| audio_stream | **io.RawIOBase** | Um fluxo de entrada contendo dados de áudio WAV para incorporar. |


## insert_audio_frame_embedded(self, index, x, y, width, height, audio) {#int-float-float-float-float-iaudio}
Cria um novo quadro de áudio e o insere na coleção de formas no índice especificado usando um objeto de áudio existente da lista Presentation.Audios.

### Retorno

O [`IAudioFrame`](/slides/python-net/pt/aspose.slides/iaudioframe) recém criado.



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| index | **int** | O índice baseado em zero no qual inserir o quadro de áudio. |
| x | **float** | A coordenada x do novo quadro de áudio, em pontos. |
| y | **float** | A coordenada y do novo quadro de áudio, em pontos. |
| width | **float** | A largura do novo quadro de áudio, em pontos. |
| height | **float** | A altura do novo quadro de áudio, em pontos. |
| audio | [`IAudio`](/slides/python-net/pt/aspose.slides/iaudio) | Uma instância de [`IAudio`](/slides/python-net/pt/aspose.slides/iaudio) da coleção Presentation.Audios para incorporar. |



### Veja Também
* classe [`IAudio`](/slides/python-net/pt/aspose.slides/iaudio)
* classe [`IAudioFrame`](/slides/python-net/pt/aspose.slides/iaudioframe)
* classe [`IShapeCollection`](/slides/python-net/pt/aspose.slides/ishapecollection)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)