---
title: process method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.lowcode/merger/process/
weight: 10
---
## process(input_file_names, output_file_name) {#liststr-str}
Aynı formatta birden çok PowerPoint sunumunu tek bir sunum dosyasında birleştirir.


```python
@staticmethod
def process(input_file_names, output_file_name):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| input_file_names | **List[str]** | Giriş sunum dosyası adlarının bir dizisi. |
| output_file_name | **str** | Oluşturulan birleştirilmiş sunum dosyasının çıktı dosya adı. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Giriş dosya adları geçersiz olduğunda veya biçimler eşleşmediğinde atılır. |


## process(input_file_names, output_stream) {#liststr-iorawiobase}
Aynı formatta birden çok PowerPoint sunumunu tek bir sunum dosyasında birleştirir.


```python
@staticmethod
def process(input_file_names, output_stream):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| input_file_names | **List[str]** | Giriş sunum dosyası adlarının bir dizisi. |
| output_stream | **io.RawIOBase** | Çıktı akışı. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Giriş dosya adları geçersiz olduğunda veya biçimler eşleşmediğinde atılır. |


## process(input_file_names, output_file_name, options) {#liststr-str-asposeslidesexportisaveoptions}
Aynı formatta birden çok PowerPoint sunumunu tek bir sunum dosyasında birleştirir.


```python
@staticmethod
def process(input_file_names, output_file_name, options):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| input_file_names | **List[str]** | Giriş sunum dosyası adlarının bir dizisi. |
| output_file_name | **str** | Oluşturulan birleştirilmiş sunum dosyasının çıktı dosya adı. |
| options | [`ISaveOptions`](/slides/python-net/tr/aspose.slides.export/isaveoptions) | Birleştirilmiş sunumun nasıl kaydedileceğini tanımlayan ek seçenekler. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Giriş dosya adları geçersiz olduğunda veya biçimler eşleşmediğinde atılır. |


## process(input_file_names, output_stream, options) {#liststr-iorawiobase-asposeslidesexportisaveoptions}
Aynı formatta birden çok PowerPoint sunumunu tek bir sunum dosyasında birleştirir.


```python
@staticmethod
def process(input_file_names, output_stream, options):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| input_file_names | **List[str]** | Giriş sunum dosyası adlarının bir dizisi. |
| output_stream | **io.RawIOBase** | Çıktı akışı. |
| options | [`ISaveOptions`](/slides/python-net/tr/aspose.slides.export/isaveoptions) | Birleştirilmiş sunumun nasıl kaydedileceğini tanımlayan ek seçenekler. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Giriş dosya adları geçersiz olduğunda veya biçimler eşleşmediğinde atılır. |



### Bakınız
* sınıf [`ISaveOptions`](/slides/python-net/tr/aspose.slides.export/isaveoptions)
* sınıf [`Merger`](/slides/python-net/tr/aspose.slides.lowcode/merger)
* modül [`aspose.slides.lowcode`](/slides/python-net/tr/aspose.slides.lowcode)
* kütüphane [`Aspose.Slides`](/slides/python-net)