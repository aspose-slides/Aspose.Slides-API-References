---
title: set_license method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/ilicense/set_license/
weight: 30
---
## set_license(self, license_name) {#str}
Bileşeni lisanslar.


```python
def set_license(self, license_name):
    ...
```


| Parametre | Tip | Açıklama |
| :- | :- | :- |
| license_name | **str** | Tam veya kısa dosya adı ya da gömülü bir kaynağın adı olabilir.<br/><br/>            Değerlendirme moduna geçmek için boş bir dize kullanın. |

### Açıklamalar

Lisansı aşağıdaki konumlarda bulmaya çalışır:


1. Belirtilen yol.

2. Bileşen derlemesinin klasörü.

3. İstemcinin çağıran derlemesinin klasörü.

4. Giriş derlemesinin klasörü.

5. İstemcinin çağıran derlemesindeki gömülü kaynak.

**Not:** .NET Compact Framework üzerinde, lisansı yalnızca şu konumlarda bulmaya çalışır:


1. Belirtilen yol.

2. İstemcinin çağıran derlemesindeki gömülü kaynak.

## set_license(self, stream) {#iorawiobase}
Bileşeni lisanslar.


```python
def set_license(self, stream):
    ...
```


| Parametre | Tip | Açıklama |
| :- | :- | :- |
| stream | **io.RawIOBase** | Lisansı içeren bir akış. |

### Açıklamalar

Bu yöntemi bir akıştan lisans yüklemek için kullanın.



### Diğer Bağlantılar
* sınıf [`ILicense`](/slides/python-net/tr/aspose.slides/ilicense)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)