---
title: add method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/icustomxmlpartcollection/add/
weight: 10
---
## add(self, xml_data) {#bytes}
Yeni özel xml bölümünü ekler.

### Döndürür

Özel xml bölümü oluşturuldu.



```python
def add(self, xml_data):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| xml_data | **bytes** | Eklenecek yeni bölümün xml verisi. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlData `None`dır. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlData boştur veya geçersizdir. |


## add(self, xml_string) {#str}
Yeni özel xml bölümünü ekler.

### Döndürür

Özel xml bölümü oluşturuldu.



```python
def add(self, xml_string):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| xml_string | **str** | Eklenecek yeni bölümün xml dizesi. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlString `None`dır. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlString boştur veya xml verisi geçersizdir. |


## add(self, input_stream) {#iorawiobase}
Yeni özel xml bölümünü ekler.

### Döndürür

Özel xml bölümü oluşturuldu.



```python
def add(self, input_stream):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| input_stream | **io.RawIOBase** | Eklenecek yeni bölümün xml verisini içeren inputStream. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | inputStream `None`dır. |
| **RuntimeError(Proxy error(ArgumentException))** | inputStream içindeki veri boştur veya geçersizdir. |



### Ayrıca Bakınız
* sınıf [`ICustomXmlPart`](/slides/python-net/tr/aspose.slides/icustomxmlpart)
* sınıf [`ICustomXmlPartCollection`](/slides/python-net/tr/aspose.slides/icustomxmlpartcollection)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)