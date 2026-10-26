---
title: ISlideSize
second_title: Aspose.Slides for Android via Java API Reference
description: Bir slaytın boyutunu ve yönelimini temsil eder.
type: docs
url: /tr/com.aspose.slides/islidesize/
---```
public interface ISlideSize
```

Bir slaytın boyutunu ve yönelimini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSize()](#getSize--) | Slayt boyutlarını puan cinsinden alır. |
| [getType()](#getType--) | Slayt boyut türünü alır. |
| [getOrientation()](#getOrientation--) | Slayt yönelimini alır veya ayarlar. |
| [setOrientation(int value)](#setOrientation-int-) | Slayt yönelimini alır veya ayarlar. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | Slayt boyutunu türe göre ayarlar ve mevcut içeriği ölçeklendirir. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | Slayt boyutlarını açıkça ayarlar ve mevcut içeriği ölçeklendirir. |
### getSize() {#getSize--}
```
public abstract SizeF getSize()
```

Slayt boyutlarını puan cinsinden alır.

--------------------

Yeni bir değer atandığında \#getType.getType özelliği [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) değerine sıfırlanır ve \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) ayarlanır.

**Döndürür:**
[SizeF](../../com.aspose.slides.android/sizef)
### getType() {#getType--}
```
public abstract int getType()
```

Slayt boyut türünü alır.

--------------------

[SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) dışındaki herhangi bir değer atandığında \#getSize.getSize önceden tanımlanmış boyutlara göre ayarlanır, mevcut \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) korunur.

**Döndürür:**
int
### getOrientation() {#getOrientation--}
```
public abstract int getOrientation()
```

Slayt yönelimini alır veya ayarlar.

--------------------

Bu değer değiştirildiğinde slaytın genişliği ve yüksekliği yer değiştirir.

**Döndürür:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public abstract void setOrientation(int value)
```

Slayt yönelimini alır veya ayarlar.

--------------------

Bu değer değiştirildiğinde slaytın genişliği ve yüksekliği yer değiştirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### setSize(int type, int scaleType) {#setSize-int-int-}
```
public abstract void setSize(int type, int scaleType)
```

Slayt boyutunu türe göre ayarlar ve mevcut içeriği ölçeklendirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | int | Uygulanacak önceden tanımlanmış slayt boyutu. |
| scaleType | int | Kullanılacak içerik ölçekleme modu. |

--------------------

[SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) dışındaki herhangi bir değer atandığında \#getSize.getSize seçilen tipe göre ayarlanır, \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) korunur. |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public abstract void setSize(float width, float height, int scaleType)
```

Slayt boyutlarını açıkça ayarlar ve mevcut içeriği ölçeklendirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| width | float | Yeni slayt genişliği, puan cinsinden. |
| height | float | Yeni slayt yüksekliği, puan cinsinden. |
| scaleType | int | Kullanılacak içerik ölçekleme modu. |

--------------------

Bu, \#getType.getType özelliğini [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) değerine sıfırlar ve {\#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) ayarlar. |