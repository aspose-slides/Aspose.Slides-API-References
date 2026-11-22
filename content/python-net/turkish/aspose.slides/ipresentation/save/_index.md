---
title: save method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/ipresentation/save/
weight: 90
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
Bir sunumun tüm slaytlarını XAML işaretlemesini temsil eden bir dizi dosyaya kaydeder.


```python
def save(self, options):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/tr/aspose.slides.export.xaml/ixamloptions) | XAML formatı seçenekleri. |


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
| stream | **io.RawIOBase** | Çıkış akışı. |
| format | [`SaveFormat`](/slides/python-net/tr/aspose.slides.export/saveformat) | Dışa aktarılan verinin formatı. |


## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Bir sunumun tüm slaytlarını belirtilen formatta ve ek seçeneklerle bir dosyaya kaydeder.


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
Bir sunumun tüm slaytlarını belirtilen formatta ve ek seçeneklerle bir akışa kaydeder.


```python
def save(self, stream, format, options):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream | **io.RawIOBase** | Çıkış akışı. |
| format | [`SaveFormat`](/slides/python-net/tr/aspose.slides.export/saveformat) | Dışa aktarılan verinin formatı. |
| options | [`ISaveOptions`](/slides/python-net/tr/aspose.slides.export/isaveoptions) | Ek format seçenekleri. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | Şifreli bir dosyayı <br/>            Office 2007-2010 dışı bir formatta kaydetmeye çalışırsanız |


## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
Bir sunumun belirtilen slaytlarını belirtilen formatta bir dosyaya kaydeder.


```python
def save(self, fname, slides, format):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| fname | **str** | Oluşturulan dosyanın yolu. |
| slides | **List[int]** | 1'den başlayan slayt konumlarını içeren dizi. |
| format | [`SaveFormat`](/slides/python-net/tr/aspose.slides.export/saveformat) | Dışa aktarılan verinin formatı. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Akış ya da slaytlar parametresi None olduğunda. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Slaytlar parametresi hatalı sayfa numaraları içerdiğinde. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Desteklenmeyen bir SaveFormat kullanıldığında, örn. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
Bir sunumun belirtilen slaytlarını belirtilen formatta bir akışa kaydeder.


```python
def save(self, stream, slides, format):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream | **io.RawIOBase** | Çıkış akışı. |
| slides | **List[int]** | 1'den başlayan slayt konumlarını içeren dizi. |
| format | [`SaveFormat`](/slides/python-net/tr/aspose.slides.export/saveformat) | Dışa aktarılan verinin formatı. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Akış ya da slaytlar parametresi None olduğunda. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Slaytlar parametresi hatalı sayfa numaraları içerdiğinde. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Desteklenmeyen bir SaveFormat kullanıldığında, örn. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Bir sunumun belirtilen slaytlarını belirtilen formatta ve ek seçeneklerle bir dosyaya kaydeder.


```python
def save(self, fname, slides, format, options):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| fname | **str** | Oluşturulan dosyanın yolu. |
| slides | **List[int]** | 1'den başlayan slayt konumlarını içeren dizi. |
| format | [`SaveFormat`](/slides/python-net/tr/aspose.slides.export/saveformat) | Dışa aktarılan verinin formatı. |
| options | [`ISaveOptions`](/slides/python-net/tr/aspose.slides.export/isaveoptions) | Ek format seçenekleri. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Akış ya da slaytlar parametresi None olduğunda. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Slaytlar parametresi hatalı sayfa numaraları içerdiğinde. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Desteklenmeyen bir SaveFormat kullanıldığında, örn. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Bir sunumun belirtilen slaytlarını belirtilen formatta bir akışa kaydeder.


```python
def save(self, stream, slides, format, options):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream | **io.RawIOBase** | Çıkış akışı. |
| slides | **List[int]** | 1'den başlayan slayt konumlarını içeren dizi. |
| format | [`SaveFormat`](/slides/python-net/tr/aspose.slides.export/saveformat) | Dışa aktarılan verinin formatı. |
| options | [`ISaveOptions`](/slides/python-net/tr/aspose.slides.export/isaveoptions) | Ek format seçenekleri. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Akış ya da slaytlar parametresi None olduğunda. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Slaytlar parametresi hatalı sayfa numaraları içerdiğinde. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Desteklenmeyen bir SaveFormat kullanıldığında, örn. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |



### İlgili
* sınıf [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation)
* sınıf [`ISaveOptions`](/slides/python-net/tr/aspose.slides.export/isaveoptions)
* sınıf [`IXamlOptions`](/slides/python-net/tr/aspose.slides.export.xaml/ixamloptions)
* enum [`SaveFormat`](/slides/python-net/tr/aspose.slides.export/saveformat)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)