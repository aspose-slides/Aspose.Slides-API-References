---
title: OuterShadow
second_title: Aspose.Slides Android için Java API Referansı
description: Bir Dış Gölge etkisini temsil eder.
type: docs
url: /tr/com.aspose.slides/outershadow/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IOuterShadow](../../com.aspose.slides/ioutershadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class OuterShadow implements IOuterShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Dış Gölge etkisini temsil eder.
## Yöntemler

| Method | Description |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Bulanıklık yarıçapı, nokta cinsinden. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Bulanıklık yarıçapı, nokta cinsinden. |
| [getDirection()](#getDirection--) | Gölgenin yönü, derece cinsinden. |
| [setDirection(float value)](#setDirection-float-) | Gölgenin yönü, derece cinsinden. |
| [getDistance()](#getDistance--) | Gölgenin nesneden uzaklığı, nokta cinsinden. |
| [setDistance(double value)](#setDistance-double-) | Gölgenin nesneden uzaklığı, nokta cinsinden. |
| [getShadowColor()](#getShadowColor--) | Gölgenin rengi. |
| [getRectangleAlign()](#getRectangleAlign--) | Dikdörtgen hizalaması. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | Dikdörtgen hizalaması. |
| [getSkewHorizontal()](#getSkewHorizontal--) | Yatay eğim açısı, derece cinsinden. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | Yatay eğim açısı, derece cinsinden. |
| [getSkewVertical()](#getSkewVertical--) | Dikey eğim açısı, derece cinsinden. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | Dikey eğim açısı, derece cinsinden. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | Gölgenin şekil ile birlikte döndürülüp döndürülmediğini gösterir. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | Gölgenin şekil ile birlikte döndürülüp döndürülmediğini gösterir. |
| [getScaleHorizontal()](#getScaleHorizontal--) | Orijinal boyutun yüzde olarak yatay ölçek faktörü. |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | Orijinal boyutun yüzde olarak yatay ölçek faktörü. |
| [getScaleVertical()](#getScaleVertical--) | Orijinal boyutun yüzde olarak dikey ölçek faktörü. |
| [setScaleVertical(double value)](#setScaleVertical-double-) | Orijinal boyutun yüzde olarak dikey ölçek faktörü. |
| [getEffective()](#getEffective--) | Kalıtım uygulanmış etkili Dış Gölge verilerini alır. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen [OuterShadow](../../com.aspose.slides/outershadow)'nin geçerli [OuterShadow](../../com.aspose.slides/outershadow) ile eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Belirli bir tür için karma işlevi olarak hizmet eder. |

### getBlurRadius() {#getBlurRadius--}
```
public final double getBlurRadius()
```

Bulanıklık yarıçapı, nokta cinsinden. Varsayılan değer - 0 pt. Okunur/Yazılabilir double.

**Döndürür:**
double

### setBlurRadius(double value) {#setBlurRadius-double-}
```
public final void setBlurRadius(double value)
```

Bulanıklık yarıçapı, nokta cinsinden. Varsayılan değer - 0 pt. Okunur/Yazılabilir double.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public final float getDirection()
```

Gölgenin yönü, derece cinsinden. Varsayılan değer - 0 � (soldan sağa). Okunur/Yazılabilir float.

**Döndürür:**
float

### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

Gölgenin yönü, derece cinsinden. Varsayılan değer - 0 � (soldan sağa). Okunur/Yazılabilir float.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public final double getDistance()
```

Gölgenin nesneden uzaklığı, nokta cinsinden. Varsayılan değer - 0 pt. Okunur/Yazılabilir double.

**Döndürür:**
double

### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

Gölgenin nesneden uzaklığı, nokta cinsinden. Varsayılan değer - 0 pt. Okunur/Yazılabilir double.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```

Gölgenin rengi. Varsayılan değer - otomatik siyah (tema bağımlı). Yalnızca okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getRectangleAlign() {#getRectangleAlign--}
```
public final byte getRectangleAlign()
```

Dikdörtgen hizalaması. Varsayılan değer - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Okunur/Yazılabilir [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Döndürür:**
byte

### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public final void setRectangleAlign(byte value)
```

Dikdörtgen hizalaması. Varsayılan değer - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Okunur/Yazılabilir [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public final double getSkewHorizontal()
```

Yatay eğim açısı, derece cinsinden. Varsayılan değer - 0 �. Okunur/Yazılabilir double.

**Döndürür:**
double

### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public final void setSkewHorizontal(double value)
```

Yatay eğim açısı, derece cinsinden. Varsayılan değer - 0 �. Okunur/Yazılabilir double.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public final double getSkewVertical()
```

Dikey eğim açısı, derece cinsinden. Varsayılan değer - 0 �. Okunur/Yazılabilir double.

**Döndürür:**
double

### setSkewVertical(double value) {#setSkewVertical-double-}
```
public final void setSkewVertical(double value)
```

Dikey eğim açısı, derece cinsinden. Varsayılan değer - 0 �. Okunur/Yazılabilir double.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public final boolean getRotateShadowWithShape()
```

Gölgenin şekil ile birlikte döndürülüp döndürülmediğini gösterir. Varsayılan değer - true. Okunur/Yazılabilir boolean.

**Döndürür:**
boolean

### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public final void setRotateShadowWithShape(boolean value)
```

Gölgenin şekil ile birlikte döndürülüp döndürülmediğini gösterir. Varsayılan değer - true. Okunur/Yazılabilir boolean.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public final double getScaleHorizontal()
```

Orijinal boyutun yüzde olarak yatay ölçek faktörü. Negatif ölçekleme ters çevirme oluşturur. Varsayılan değer - 100 %. Okunur/Yazılabilir double.

**Döndürür:**
double

### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public final void setScaleHorizontal(double value)
```

Orijinal boyutun yüzde olarak yatay ölçek faktörü. Negatif ölçekleme ters çevirme oluşturur. Varsayılan değer - 100 %. Okunur/Yazılabilir double.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public final double getScaleVertical()
```

Orijinal boyutun yüzde olarak dikey ölçek faktörü. Negatif ölçekleme ters çevirme oluşturur. Varsayılan değer - 100 %. Okunur/Yazılabilir double.

**Döndürür:**
double

### setScaleVertical(double value) {#setScaleVertical-double-}
```
public final void setScaleVertical(double value)
```

Orijinal boyutun yüzde olarak dikey ölçek faktörü. Negatif ölçekleme ters çevirme oluşturur. Varsayılan değer - 100 %. Okunur/Yazılabilir double.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getEffective() {#getEffective--}
```
public final IOuterShadowEffectiveData getEffective()
```

Kalıtım uygulanmış etkili Dış Gölge verilerini alır.

**Döndürür:**
[IOuterShadowEffectiveData](../../com.aspose.slides/ioutershadoweffectivedata) - Bir [IOuterShadowEffectiveData](../../com.aspose.slides/ioutershadoweffectivedata).

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Yalnızca okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject

### getVersion() {#getVersion--}
```
public final long getVersion()
```

Versiyon. Yalnızca okunur long.

**Döndürür:**
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Üst IPresentationComponent nesnesini döndürür. Yalnızca okunur [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Döndürür:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Belirtilen [OuterShadow](../../com.aspose.slides/outershadow)'nin geçerli [OuterShadow](../../com.aspose.slides/outershadow) ile eşit olup olmadığını belirler.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Karşılaştırılacak [OuterShadow](../../com.aspose.slides/outershadow). |

**Döndürür:**
boolean - nesneler eşitse true; aksi takdirde false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Belirli bir tür için karma işlevi olarak hizmet eder.

**Döndürür:**
int - geçerli nesnenin bir karma kodu.