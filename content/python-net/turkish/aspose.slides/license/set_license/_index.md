---
title: set_license method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/license/set_license/
weight: 40
---
## set_license(self, license_name) {#str}
Bileşeni lisanslar.


```python
def set_license(self, license_name):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| license_name | **str** | Tam veya kısa dosya adı ya da gömülü kaynağın adı olabilir.<br/><br/>            Değerlendirme moduna geçmek için boş bir dize kullanın. |

### Açıklamalar

Lisansi aşağıdaki konumlarda bulmaya çalışır:


1. Açık yol.

2. Bileşen derlemesinin klasörü.

3. İstemcinin çağıran derlemesinin klasörü.

4. Giriş derlemesinin klasörü.

5. İstemcinin çağıran derlemesinde gömülü kaynak.

**Not:** .NET Compact Framework üzerinde, lisansı yalnızca bu konumlarda bulmaya çalışır:


1. Açık yol.

2. İstemcinin çağıran derlemesinde gömülü kaynak.



## set_license(self, stream) {#iorawiobase}
Bileşeni lisanslar.


```python
def set_license(self, stream):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream | **io.RawIOBase** | Lisansı içeren bir akış. |

### Açıklamalar

Bu yöntemi bir akıştan lisans yüklemek için kullanın.



### Bakınız
* sınıf [`License`](/slides/python-net/tr/aspose.slides/license)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)