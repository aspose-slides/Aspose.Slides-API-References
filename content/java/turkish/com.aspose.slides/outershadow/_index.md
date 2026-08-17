---
title: OuterShadow
second_title: Aspose.Slides for Java API Referansı
description: Bir Outer Shadow etkisini temsil eder.
type: docs
url: /tr/com.aspose.slides/outershadow/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IOuterShadow](../../com.aspose.slides/ioutershadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class OuterShadow implements IOuterShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Bir Outer Shadow etkisini temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Bulanıklık yarıçapı, puan cinsinden. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Bulanıklık yarıçapı, puan cinsinden. |
| [getDirection()](#getDirection--) | Gölgenin yönü, derece cinsinden. |
| [setDirection(float value)](#setDirection-float-) | Gölgenin yönü, derece cinsinden. |
| [getDistance()](#getDistance--) | Gölge ile nesne arasındaki mesafe, puan cinsinden. |
| [setDistance(double value)](#setDistance-double-) | Gölge ile nesne arasındaki mesafe, puan cinsinden. |
| [getShadowColor()](#getShadowColor--) | Gölgenin rengi. |
| [getRectangleAlign()](#getRectangleAlign--) | Dikdörtgen hizalaması. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | Dikdörtgen hizalaması. |
| [getSkewHorizontal()](#getSkewHorizontal--) | Yatay eğim açısı, derece cinsinden. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | Yatay eğim açısı, derece cinsinden. |
| [getSkewVertical()](#getSkewVertical--) | Dikey eğim açısı, derece cinsinden. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | Dikey eğim açısı, derece cinsinden. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | Gölgenin şekil ile birlikte dönüp dönmediğini gösterir. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | Gölgenin şekil ile birlikte dönüp dönmediğini gösterir. |
| [getScaleHorizontal()](#getScaleHorizontal--) | Yatay ölçekleme faktörü, orijinal boyutun yüzde cinsinden. |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | Yatay ölçekleme faktörü, orijinal boyutun yüzde cinsinden. |
| [getScaleVertical()](#getScaleVertical--) | Dikey ölçekleme faktörü, orijinal boyutun yüzde cinsinden. |
| [setScaleVertical(double value)](#setScaleVertical-double-) | Dikey ölçekleme faktörü, orijinal boyutun yüzde cinsinden. |
| [getEffective()](#getEffective--) | Kalıtım uygulanarak etkili Outer Shadow efekt verilerini alır. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen [OuterShadow](../../com.aspose.slides/outershadow) öğesinin geçerli [OuterShadow](../../com.aspose.slides/outershadow) öğesiyle eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Belirli bir tür için hash işlevi olarak hizmet eder. |

### getBlurRadius() {#getBlurRadius--}
```
public final double getBlurRadius()
```

Bulanıklık yarıçapı, puan cinsinden. Varsayılan değer - 0 pt. Okunabilir/Yazılabilir double.

**Döndürür:**
double

### setBlurRadius(double value) {#setBlurRadius-double-}
```
public final void setBlurRadius(double value)
```

Bulanıklık yarıçapı, puan cinsinden. Varsayılan değer - 0 pt. Okunabilir/Yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public final float getDirection()
```

Gölgenin yönü, derece cinsinden. Varsayılan değer - 0 � (soldan sağa). Okunabilir/Yazılabilir float.

**Döndürür:**
float

### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

Gölgenin yönü, derece cinsinden. Varsayılan değer - 0 � (soldan sağa). Okunabilir/Yazılabilir float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public final double getDistance()
```

Gölge ile nesne arasındaki mesafe, puan cinsinden. Varsayılan değer - 0 pt. Okunabilir/Yazılabilir double.

**Döndürür:**
double

### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

Gölge ile nesne arasındaki mesafe, puan cinsinden. Varsayılan değer - 0 pt. Okunabilir/Yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```

Gölgenin rengi. Varsayılan değer - otomatik siyah (tema bağımlı). Yalnızca okuma [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getRectangleAlign() {#getRectangleAlign--}
```
public final byte getRectangleAlign()
```

Dikdörtgen hizalaması. Varsayılan değer - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Okunabilir/Yazılabilir [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Döndürür:**
byte

### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public final void setRectangleAlign(byte value)
```

Dikdörtgen hizalaması. Varsayılan değer - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Okunabilir/Yazılabilir [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public final double getSkewHorizontal()
```

Yatay eğim açısı, derece cinsinden. Varsayılan değer - 0 �. Okunabilir/Yazılabilir double.

**Döndürür:**
double

### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public final void setSkewHorizontal(double value)
```

Yatay eğim açısı, derece cinsinden. Varsayılan değer - 0 �. Okunabilir/Yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public final double getSkewVertical()
```

Dikey eğim açısı, derece cinsinden. Varsayılan değer - 0 �. Okunabilir/Yazılabilir double.

**Döndürür:**
double

### setSkewVertical(double value) {#setSkewVertical-double-}
```
public final void setSkewVertical(double value)
```

Dikey eğim açısı, derece cinsinden. Varsayılan değer - 0 �. Okunabilir/Yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public final boolean getRotateShadowWithShape()
```

Gölgenin şekil ile birlikte dönüp dönmediğini gösterir. Varsayılan değer - true. Okunabilir/Yazılabilir boolean.

**Döndürür:**
boolean

### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public final void setRotateShadowWithShape(boolean value)
```

Gölgenin şekil ile birlikte dönüp dönmediğini gösterir. Varsayılan değer - true. Okunabilir/Yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public final double getScaleHorizontal()
```

Yatay ölçekleme faktörü, orijinal boyutun yüzde cinsinden. Negatif ölçekleme tersine çevirme yapar. Varsayılan değer - 100 %. Okunabilir/Yazılabilir double.

**Döndürür:**
double

### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public final void setScaleHorizontal(double value)
```

Yatay ölçekleme faktörü, orijinal boyutun yüzde cinsinden. Negatif ölçekleme tersine çevirme yapar. Varsayılan değer - 100 %. Okunabilir/Yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public final double getScaleVertical()
```

Dikey ölçekleme faktörü, orijinal boyutun yüzde cinsinden. Negatif ölçekleme tersine çevirme yapar. Varsayılan değer - 100 %. Okunabilir/Yazılabilir double.

**Döndürür:**
double

### setScaleVertical(double value) {#setScaleVertical-double-}
```
public final void setScaleVertical(double value)
```

Dikey ölçekleme faktörü, orijinal boyutun yüzde cinsinden. Negatif ölçekleme tersine çevirme yapar. Varsayılan değer - 100 %. Okunabilir/Yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getEffective() {#getEffective--}
```
public final IOuterShadowEffectiveData getEffective()
```

Kalıtım uygulanarak etkili Outer Shadow efekt verilerini alır.

**Döndürür:**
[IOuterShadowEffectiveData](../../com.aspose.slides/ioutershadoweffectivedata) - A [IOuterShadowEffectiveData](../../com.aspose.slides/ioutershadoweffectivedata).

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Yalnızca okuma IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject

### getVersion() {#getVersion--}
```
public final long getVersion()
```

Versiyon. Yalnızca okuma long.

**Döndürür:**
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Üst IPresentationComponent nesnesini döndürür. Yalnızca okuma [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Döndürür:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Belirtilen [OuterShadow](../../com.aspose.slides/outershadow) öğesinin geçerli [OuterShadow](../../com.aspose.slides/outershadow) öğesiyle eşit olup olmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Karşılaştırılacak [OuterShadow](../../com.aspose.slides/outershadow). |

**Döndürür:**
boolean - nesneler eşitse true; aksi takdirde false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Belirli bir tür için hash işlevi olarak hizmet eder.

**Döndürür:**
int - Geçerli nesne için bir hash kodu.