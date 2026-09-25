---
title: from_argb method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/color/from_argb/
weight: 20
---
## from_argb(argb) {#int}
32 bitlik ARGB değerinden bir renk oluşturur.

### Dönüş Değeri

Belirtilen değerden oluşturulan renk.



```python
@staticmethod
def from_argb(argb):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| argb | **int** | 32 bitlik ARGB değerini (işaretli veya işaretsiz) belirten bir değer. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **ValueError** | Bir bileşen değeri 0'dan küçük veya 255'ten büyük. |
| **TypeError** | Yanlış sayıdaki veya türdeki argüman. |


## from_argb(alpha, base_color) {#int-color}
Belirtilen alfa değeri ve temel renkten bir renk oluşturur.

### Dönüş Değeri

Belirtilen değerlerden oluşturulan renk.



```python
@staticmethod
def from_argb(alpha, base_color):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| alpha | **int** | Alfa bileşen değeri. Geçerli değerler 0 ile 255 arasındadır. |
| base_color | [`Color`](/slides/python-net/tr/aspose.slides/color) | Yeni rengin oluşturulacağı temel renk. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **ValueError** | Bir bileşen değeri 0'dan küçük veya 255'ten büyük. |
| **TypeError** | Yanlış sayıdaki veya türdeki argüman. |


## from_argb(red, green, blue) {#int-int-int}
Belirtilen kırmızı, yeşil ve mavi değerlerinden opak bir renk (alfa 255) oluşturur.

### Dönüş Değeri

Belirtilen değerlerden oluşturulan renk.



```python
@staticmethod
def from_argb(red, green, blue):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| red | **int** | Kırmızı bileşen değeri. Geçerli değerler 0 ile 255 arasındadır. |
| green | **int** | Yeşil bileşen değeri. Geçerli değerler 0 ile 255 arasındadır. |
| blue | **int** | Mavi bileşen değeri. Geçerli değerler 0 ile 255 arasındadır. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **ValueError** | Bir bileşen değeri 0'dan küçük veya 255'ten büyük. |
| **TypeError** | Yanlış sayıdaki veya türdeki argüman. |


## from_argb(alpha, red, green, blue) {#int-int-int-int}
Dört ARGB bileşeni (alfa, kırmızı, yeşil ve mavi) değerlerinden bir renk oluşturur.

### Dönüş Değeri

Belirtilen değerlerden oluşturulan renk.



```python
@staticmethod
def from_argb(alpha, red, green, blue):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| alpha | **int** | Alfa bileşen değeri. Geçerli değerler 0 ile 255 arasındadır. |
| red | **int** | Kırmızı bileşen değeri. Geçerli değerler 0 ile 255 arasındadır. |
| green | **int** | Yeşil bileşen değeri. Geçerli değerler 0 ile 255 arasındadır. |
| blue | **int** | Mavi bileşen değeri. Geçerli değerler 0 ile 255 arasındadır. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **ValueError** | Bir bileşen değeri 0'dan küçük veya 255'ten büyük. |
| **TypeError** | Yanlış sayıdaki veya türdeki argüman. |



### Diğer Bilgiler
* sınıf [`Color`](/slides/python-net/tr/aspose.slides/color)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)