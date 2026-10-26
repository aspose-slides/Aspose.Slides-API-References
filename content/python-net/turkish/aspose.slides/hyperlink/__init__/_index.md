---
title: Hyperlink constructor
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/hyperlink/__init__/
weight: 10
---
## __init__(self, url) {#str}
Bir hiperalink örneği oluşturur.


```python
def __init__(self, url):
    ...
```


| Parametre | Tip | Açıklama |
| :- | :- | :- |
| url | **str** | Hiperalink URL'si. |


## __init__(self, slide) {#islide}
Belirli bir slayta işaret eden bir hiperalink örneği oluşturur.
            Not: oluşturulan hiperalink aynı sunumdaki bir nesneye atanmalıdır, aksi takdirde bağlantı NoAction olarak kaydedilir.


```python
def __init__(self, slide):
    ...
```


| Parametre | Tip | Açıklama |
| :- | :- | :- |
| slide | [`ISlide`](/slides/python-net/tr/aspose.slides/islide) | Hedef slayt. |


## __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click) {#hyperlink-str-str-bool-bool-bool}
Başka bir hiperalinki kaynak olarak kullanarak, ikincil özellikleri geçersiz kılan bir hiperalink örneği oluşturur.


```python
def __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click):
    ...
```


| Parametre | Tip | Açıklama |
| :- | :- | :- |
| source | [`Hyperlink`](/slides/python-net/tr/aspose.slides/hyperlink) | Kaynak hiperalink |
| target_frame | **str** | Hedef çerçeve |
| tooltip | **str** | İpucu metni |
| history | **bool** |  |
| stop_sounds_on_click | **bool** |  |
| highlight_click | **bool** |  |



### Ayrıca Bakınız
* sınıf [`Hyperlink`](/slides/python-net/tr/aspose.slides/hyperlink)
* sınıf [`ISlide`](/slides/python-net/tr/aspose.slides/islide)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)