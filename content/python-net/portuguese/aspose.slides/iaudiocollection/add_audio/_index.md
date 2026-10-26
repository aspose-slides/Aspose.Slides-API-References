---
title: add_audio method
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides/iaudiocollection/add_audio/
weight: 10
---
## add_audio(self, audio) {#iaudio}
Adiciona uma cópia de um arquivo de áudio de outra apresentação.

### Retorno

Áudio adicionado.



```python
def add_audio(self, audio):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| audio | [`IAudio`](/slides/python-net/pt/aspose.slides/iaudio) | Áudio de origem. |


## add_audio(self, stream) {#iorawiobase}
Cria e adiciona um áudio a uma apresentação a partir de um fluxo.

### Retorno

Áudio adicionado.



```python
def add_audio(self, stream):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| stream | **io.RawIOBase** | Fluxo de onde adicionar o áudio. |


## add_audio(self, audio_data) {#bytes}
Cria e adiciona um áudio a uma apresentação a partir de um array de bytes.

### Retorno

Áudio adicionado.



```python
def add_audio(self, audio_data):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| audio_data | **bytes** | Bytes de áudio. |


## add_audio(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Cria e adiciona um áudio a uma apresentação a partir de um fluxo.

### Retorno

Áudio adicionado.



```python
def add_audio(self, stream, loading_stream_behavior):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| stream | **io.RawIOBase** | Fluxo de onde adicionar o áudio do vídeo. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/pt/aspose.slides/loadingstreambehavior) | O comportamento que será aplicado ao fluxo. |



### Veja também
* classe [`IAudio`](/slides/python-net/pt/aspose.slides/iaudio)
* classe [`IAudioCollection`](/slides/python-net/pt/aspose.slides/iaudiocollection)
* enumeração [`LoadingStreamBehavior`](/slides/python-net/pt/aspose.slides/loadingstreambehavior)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)