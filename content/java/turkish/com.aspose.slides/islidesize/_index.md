---
title: ISlideSize
second_title: Aspose.Slides for Java API Reference
description: Represents the size and orientation of a slide.
type: docs
url: /tr/com.aspose.slides/islidesize/
---```
public interface ISlideSize
```

Bir slaytın boyutunu ve yönünü temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSize()](#getSize--) | Slayt boyutlarını nokta cinsinden alır. |
| [getType()](#getType--) | Slayt boyut tipini alır. |
| [getOrientation()](#getOrientation--) | Slayt yönünü alır veya ayarlar. |
| [setOrientation(int value)](#setOrientation-int-) | Slayt yönünü alır veya ayarlar. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | Slayt boyutunu tipe göre ayarlar ve mevcut içeriği ölçeklendirir. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | Slayt boyutlarını açıkça ayarlar ve mevcut içeriği ölçeklendirir. |
### getSize() {#getSize--}
```
public abstract Dimension2D getSize()
```

Slayt boyutlarını nokta cinsinden alır.

--------------------

Yeni bir değer atandığında \#getType.getType özelliği [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) olarak sıfırlanır ve \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) ayarlanır.

**Dönen değer:**
java.awt.geom.Dimension2D
### getType() {#getType--}
```
public abstract int getType()
```

Slayt boyut tipini alır.

--------------------

[SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) dışındaki herhangi bir değer atandığında \#getSize.getSize, önceden tanımlı boyutlara göre ayarlanır, mevcut \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) ise korunur.

**Dönen değer:**
int
### getOrientation() {#getOrientation--}
```
public abstract int getOrientation()
```

Slayt yönünü alır veya ayarlar.

--------------------

Bu değeri değiştirmek, slaytın genişliğini ve yüksekliğini değiştirir.

**Dönen değer:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public abstract void setOrientation(int value)
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
public abstract void setSize(int type, int scaleType)
```

Slayt boyutunu tipe göre ayarlar ve mevcut içeriği ölçeklendirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | int | Uygulanacak önceden tanımlı slayt boyutu. |
| scaleType | int | Kullanılacak içerik ölçekleme modu. |

--------------------

[SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) dışındaki herhangi bir değer atandığında \#getSize.getSize, seçilen türe göre ayarlanır, \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) korunur. |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public abstract void setSize(float width, float height, int scaleType)
```

Slayt boyutlarını açıkça ayarlar ve mevcut içeriği ölçeklendirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| width | float | Yeni slayt genişliği, nokta cinsinden. |
| height | float | Yeni slayt yüksekliği, nokta cinsinden. |
| scaleType | int | Kullanılacak içerik ölçekleme modu. |

--------------------

Bu, \#getType.getType özelliğini [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) olarak sıfırlar ve \{\#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) ayarlar. |