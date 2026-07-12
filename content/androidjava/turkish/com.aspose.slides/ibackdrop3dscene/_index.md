---
title: IBackdrop3DScene
second_title: Aspose.Slides for Android via Java API Reference
description: Defines a plane in which effects such as glow and shadow are applied in relation to the shape they are being applied to.
type: docs
url: /tr/com.aspose.slides/ibackdrop3dscene/
---```
public interface IBackdrop3DScene
```

Parlaklık ve gölge gibi efektlerin, uygulanacak şekle göre uygulandığı bir düzlemi tanımlar.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getNormalVector()](#getNormalVector--) | Normal bir vektörü döndürür veya ayarlar. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Normal bir vektörü döndürür veya ayarlar. |
| [getAnchorPoint()](#getAnchorPoint--) | 3B uzaydaki bir noktayı döndürür veya ayarlar. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | 3B uzaydaki bir noktayı döndürür veya ayarlar. |
| [getUpVector()](#getUpVector--) | Yukarıyı temsil eden bir vektörü döndürür veya ayarlar. |
| [setUpVector(float[] value)](#setUpVector-float---) | Yukarıyı temsil eden bir vektörü döndürür veya ayarlar. |
### getNormalVector() {#getNormalVector--}
```
public abstract float[] getNormalVector()
```

Normal bir vektörü döndürür veya ayarlar. Daha kesin olmak gerekirse, bu öznitelik arka plan düzleminin yüzeyine dik bir vektörü tanımlar. Vektör, X, Y ve Z koordinatlarını tanımlayan 3 float değerinden oluşan bir dizi olarak temsil edilir. Okunur/yazılır float[].

**Döndürür:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public abstract void setNormalVector(float[] value)
```

Normal bir vektörü döndürür veya ayarlar. Daha kesin olmak gerekirse, bu öznitelik arka plan düzleminin yüzeyine dik bir vektörü tanımlar. Vektör, X, Y ve Z koordinatlarını tanımlayan 3 float değerinden oluşan bir dizi olarak temsil edilir. Okunur/yazılır float[].

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public abstract float[] getAnchorPoint()
```

3B uzaydaki bir noktayı döndürür veya ayarlar. Bu nokta, arka plan düzlemini sabitleyen uzaydaki noktadır. 3B nokta, X, Y ve Z koordinatlarını tanımlayan 3 float değerinden oluşan bir dizi olarak temsil edilir. Okunur/yazılır float[].

**Döndürür:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public abstract void setAnchorPoint(float[] value)
```

3B uzaydaki bir noktayı döndürür veya ayarlar. Bu nokta, arka plan düzlemini sabitleyen uzaydaki noktadır. 3B nokta, X, Y ve Z koordinatlarını tanımlayan 3 float değerinden oluşan bir dizi olarak temsil edilir. Okunur/yazılır float[].

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public abstract float[] getUpVector()
```

Yukarıyı temsil eden bir vektörü döndürür veya ayarlar. Daha kesin olmak gerekirse, bu öznitelik arka plan düzleminin yüzeyine göre yukarıyı temsil eden bir vektörü tanımlar. Vektör, X, Y ve Z koordinatlarını tanımlayan 3 float değerinden oluşan bir dizi olarak temsil edilir. Okunur/yazılır float[].

**Döndürür:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public abstract void setUpVector(float[] value)
```

Yukarıyı temsil eden bir vektörü döndürür veya ayarlar. Daha kesin olmak gerekirse, bu öznitelik arka plan düzleminin yüzeyine göre yukarıyı temsil eden bir vektörü tanımlar. Vektör, X, Y ve Z koordinatlarını tanımlayan 3 float değerinden oluşan bir dizi olarak temsil edilir. Okunur/yazılır float[].

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float[] |  |