---
title: add_video method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/ivideocollection/add_video/
weight: 10
---
## add_video(self, video) {#ivideo}
Adiciona uma cópia de um arquivo de vídeo de outra apresentação.

### Retorna

Vídeo adicionado.



```python
def add_video(self, video):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| video | [`IVideo`](/slides/python-net/pt/aspose.slides/ivideo) | Vídeo de origem. |


## add_video(self, video_data) {#bytes}
Cria e adiciona um vídeo a uma apresentação a partir de um array de bytes.

### Retorna

Vídeo adicionado.



```python
def add_video(self, video_data):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| video_data | **bytes** | Bytes de vídeo. |


## add_video(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Cria e adiciona um vídeo a uma apresentação a partir de um stream.

### Retorna

Adicionado [`IVideo`](/slides/python-net/pt/aspose.slides/ivideo).



```python
def add_video(self, stream, loading_stream_behavior):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream para adicionar o arquivo de vídeo. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/pt/aspose.slides/loadingstreambehavior) | O comportamento que será aplicado ao stream. |



### Veja Também
* classe [`IVideo`](/slides/python-net/pt/aspose.slides/ivideo)
* classe [`IVideoCollection`](/slides/python-net/pt/aspose.slides/ivideocollection)
* enumeration [`LoadingStreamBehavior`](/slides/python-net/pt/aspose.slides/loadingstreambehavior)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)