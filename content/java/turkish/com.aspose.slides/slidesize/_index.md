---
title: SlideSize
second_title: Aspose.Slides for Java API Referansı
description: Bir slaytın boyutunu ve yönünü temsil eder.
type: docs
url: /tr/com.aspose.slides/slidesize/
---
**Kalıtım:**
java.lang.Object, com.aspose.slides.DomObject

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.ISlideSize](../../com.aspose.slides/islidesize)
```
public class SlideSize extends DomObject<Presentation> implements ISlideSize
```

Bir slaytın boyutunu ve yönünü temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSize()](#getSize--) | Slayt boyutlarını puan cinsinden alır. |
| [getType()](#getType--) | Slayt boyut türünü alır. |
| [getOrientation()](#getOrientation--) | Slayt yönünü alır veya ayarlar. |
| [setOrientation(int value)](#setOrientation-int-) | Slayt yönünü alır veya ayarlar. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | Slayt boyutunu türe göre ayarlar ve mevcut içeriği ölçeklendirir. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | Slayt boyutlarını açıkça ayarlar ve mevcut içeriği ölçeklendirir. |
### getSize() {#getSize--}
```
public final Dimension2D getSize()
```

Slayt boyutlarını puan cinsinden alır.

--------------------

Yeni bir değer atamak, \#getType.getType özelliğini [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) değerine sıfırlar ve \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) özelliğini ayarlar.

**Döndürür:**
java.awt.geom.Dimension2D
### getType() {#getType--}
```
public final int getType()
```

Slayt boyut türünü alır.

--------------------

[SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) dışındaki herhangi bir değer atamak, \#getSize.getSize özelliğini önceden tanımlanmış boyutlara göre ayarlar, mevcut \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) değerini korur.

**Döndürür:**
int
### getOrientation() {#getOrientation--}
```
public final int getOrientation()
```

Slayt yönünü alır veya ayarlar.

--------------------

Bu değeri değiştirmek, slaytın genişliğini ve yüksekliğini değiştirir.

**Döndürür:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public final void setOrientation(int value)
```

Slayt yönünü alır veya ayarlar.

--------------------

Bu değeri değiştirmek, slaytın genişliğini ve yüksekliğini değiştirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### setSize(int type, int scaleType) {#setSize-int-int-}
```
public final void setSize(int type, int scaleType)
```

Slayt boyutunu türe göre ayarlar ve mevcut içeriği ölçeklendirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | int | Uygulanacak önceden tanımlı slayt boyutu. |
| scaleType | int | Kullanılacak içerik ölçekleme modu. |

--------------------

[SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) dışındaki herhangi bir değer atamak, seçilen tipe göre \#getSize.getSize özelliğini ayarlar, \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) değerini korur. |
### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public final void setSize(float width, float height, int scaleType)
```

Slayt boyutlarını açıkça ayarlar ve mevcut içeriği ölçeklendirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| width | float | Yeni slayt genişliği, puan cinsinden. |
| height | float | Yeni slayt yüksekliği, puan cinsinden. |
| scaleType | int | Kullanılacak içerik ölçekleme modu. |

--------------------

Bu, \#getType.getType özelliğini [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) değerine sıfırlar ve \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) değerini ayarlar. |