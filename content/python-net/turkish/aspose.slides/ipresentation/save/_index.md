---
title: save method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/ipresentation/save/
weight: 80
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
Bir sunumun tüm slaytlarını XAML işaretlemesini temsil eden bir dizi dosyaya kaydeder.


```python
def save(self, options):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/tr/aspose.slides.export.xaml/ixamloptions) | XAML format seçenekleri. |


## save(self, fname, format) {#str-asposeslidesexportsaveformat}
Bir sunumun tüm slaytlarını belirtilen formatta bir dosyaya kaydeder.


```python
def save(self, fname, format):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| fname | **str** | Oluşturulan dosyanın yolu. |
| format | [`SaveFormat`](/slides/python-net/tr/aspose.slides.export/saveformat) | Dışa aktarılan verinin formatı. |


## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
Bir sunumun tüm slaytlarını belirtilen formatta bir akışa kaydeder.


```python
def save(self, stream, format):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream | **io.RawIOBase** | Çıktı akışı. |
| format | [`SaveFormat`](/slides/python-net/tr/aspose.slides.export/saveformat) | Dışa aktarılan verinin formatı. |


## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Bir sunumun tüm slaytlarını belirtilen formatta bir dosyaya ve ek seçeneklerle kaydeder.


```python
def save(self, fname, format, options):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| fname | **str** | Oluşturulan dosyanın yolu. |
| format | [`SaveFormat`](/slides/python-net/tr/aspose.slides.export/saveformat) | Dışa aktarılan verinin formatı. |
| options | [`ISaveOptions`](/slides/python-net/tr/aspose.slides.export/isaveoptions) | Ek format seçenekleri. |


## save(self, stream, format, options) {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Bir sunumun tüm slaytlarını belirtilen formatta bir akışa ve ek seçeneklerle kaydeder.


```python
def save(self, stream, format, options):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream | **io.RawIOBase** | Çıktı akışı. |
| format | [`SaveFormat`](/slides/python-net/tr/aspose.slides.export/saveformat) | Dışa aktarılan verinin formatı. |
| options | [`ISaveOptions`](/slides/python-net/tr/aspose.slides.export/isaveoptions) | Ek format seçenekleri. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | Şifreli dosyayı Office 2007-2010 dışı bir formatta kaydetmeye çalışırsanız |
  

## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
Belirtilen slaytları bir sunumdan belirtilen formatta bir dosyaya kaydeder.


```python
def save(self, fname, slides, format):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| fname | **str** | Oluşturulan dosyanın yolu. |
| slides | **List[int]** | 1'den başlayan slayt konumları içeren dizi. |
| format | [`SaveFormat`](/slides/python-net/tr/aspose.slides.export/saveformat) | Dışa aktarılan verinin formatı. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Akış veya slayt parametresi None olduğunda. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Slayt parametresi hatalı sayfa numaraları içerdiğinde. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Desteklenmeyen bir SaveFormat kullanıldığında, ör. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
Belirtilen slaytları bir sunumdan belirtilen formatta bir akışa kaydeder.


```python
def save(self, stream, slides, format):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream | **io.RawIOBase** | Çıktı akışı. |
| slides | **List[int]** | 1'den başlayan slayt konumları içeren dizi. |
| format | [`SaveFormat`](/slides/python-net/tr/aspose.slides.export/saveformat) | Dışa aktarılan verinin formatı. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Akış veya slayt parametresi None olduğunda. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Slayt parametresi hatalı sayfa numaraları içerdiğinde. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Desteklenmeyen bir SaveFormat kullanıldığında, ör. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Belirtilen slaytları bir sunumdan belirtilen formatta bir dosyaya ve ek seçeneklerle kaydeder.


```python
def save(self, fname, slides, format, options):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| fname | **str** | Oluşturulan dosyanın yolu. |
| slides | **List[int]** | 1'den başlayan slayt konumları içeren dizi. |
| format | [`SaveFormat`](/slides/python-net/tr/aspose.slides.export/saveformat) | Dışa aktarılan verinin formatı. |
| options | [`ISaveOptions`](/slides/python-net/tr/aspose.slides.export/isaveoptions) | Ek format seçenekleri. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Akış veya slayt parametresi None olduğunda. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Slayt parametresi hatalı sayfa numaraları içerdiğinde. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Desteklenmeyen bir SaveFormat kullanıldığında, ör. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Belirtilen slaytları bir sunumdan belirtilen formatta bir akışa ve ek seçeneklerle kaydeder.


```python
def save(self, stream, slides, format, options):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream | **io.RawIOBase** | Çıktı akışı. |
| slides | **List[int]** | 1'den başlayan slayt konumları içeren dizi. |
| format | [`SaveFormat`](/slides/python-net/tr/aspose.slides.export/saveformat) | Dışa aktarılan verinin formatı. |
| options | [`ISaveOptions`](/slides/python-net/tr/aspose.slides.export/isaveoptions) | Ek format seçenekleri. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Akış veya slayt parametresi None olduğunda. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Slayt parametresi hatalı sayfa numaraları içerdiğinde. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Desteklenmeyen bir SaveFormat kullanıldığında, ör. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |



### Ayrıca Bakınız
* sınıf [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation)
* sınıf [`ISaveOptions`](/slides/python-net/tr/aspose.slides.export/isaveoptions)
* sınıf [`IXamlOptions`](/slides/python-net/tr/aspose.slides.export.xaml/ixamloptions)
* enum [`SaveFormat`](/slides/python-net/tr/aspose.slides.export/saveformat)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)