---
title: SlideSize
second_title: Aspose.Slides Android için Java API Referansı
description: Bir slaydın boyutunu ve yönünü temsil eder.
type: docs
url: /tr/com.aspose.slides/slidesize/
---
**Kalıtım:**
java.lang.Object, com.aspose.slides.DomObject

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.ISlideSize](../../com.aspose.slides/islidesize)
```
public class SlideSize extends DomObject<Presentation> implements ISlideSize
```

Bir slaydın boyutunu ve yönünü temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSize()](#getSize--) | Slayd boyutlarını nokta cinsinden alır. |
| [getType()](#getType--) | Slayd boyut tipini alır. |
| [getOrientation()](#getOrientation--) | Slayd yönünü alır veya ayarlar. |
| [setOrientation(int value)](#setOrientation-int-) | Slayd yönünü alır veya ayarlar. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | Slayd boyutunu tipine göre ayarlar ve mevcut içeriği ölçeklendirir. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | Slayd boyutlarını açıkça ayarlar ve mevcut içeriği ölçeklendirir. |
### getSize() {#getSize--}
```
public final SizeF getSize()
```

Slayd boyutlarını nokta cinsinden alır.

--------------------

Yeni bir değer atandığında \#getType.getType özelliği [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) olarak sıfırlanır ve \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) ayarlanır.

**Döndürür:**
[SizeF](../../com.aspose.slides.android/sizef)
### getType() {#getType--}
```
public final int getType()
```

Slayd boyut tipini alır.

--------------------

[SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) dışındaki herhangi bir değer atandığında, önceden tanımlı boyutlara göre \#getSize.getSize ayarlanır, mevcut \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) korunur.

**Döndürür:**
int
### getOrientation() {#getOrientation--}
```
public final int getOrientation()
```

Slayd yönünü alır veya ayarlar.

--------------------

Bu değer değiştirildiğinde slaydın genişliği ve yüksekliği yer değiştirir.

**Döndürür:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public final void setOrientation(int value)
```

Slayd yönünü alır veya ayarlar.

--------------------

Bu değer değiştirildiğinde slaydın genişliği ve yüksekliği yer değiştirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### setSize(int type, int scaleType) {#setSize-int-int-}
```
public final void setSize(int type, int scaleType)
```

Slayd boyutunu tipe göre ayarlar ve mevcut içeriği ölçeklendirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | int | Uygulanacak önceden tanımlı slayd boyutu. |
| scaleType | int | Kullanılacak içerik ölçekleme modu. |

--------------------

[SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) dışındaki herhangi bir değer atandığında, seçilen tipe göre \#getSize.getSize ayarlanır, \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) korunur. |
### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public final void setSize(float width, float height, int scaleType)
```

Slayd boyutlarını açıkça ayarlar ve mevcut içeriği ölçeklendirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| width | float | Yeni slayd genişliği, nokta cinsinden. |
| height | float | Yeni slayd yüksekliği, nokta cinsinden. |
| scaleType | int | Kullanılacak içerik ölçekleme modu. |

--------------------

Bu, \#getType.getType özelliğini [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) olarak sıfırlar ve \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) ayarlar. |