---
title: Backdrop3DScene
second_title: Aspose.Slides for Java API Referansı
description: Parlaklık ve gölge gibi etkilerin, uygulandıkları şekle göre uygulandığı bir düzlemi tanımlar.
type: docs
url: /tr/com.aspose.slides/backdrop3dscene/
---
**Kalıtım:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Uygulanan Tüm Arabirimler:**  
[com.aspose.slides.IBackdrop3DScene](../../com.aspose.slides/ibackdrop3dscene)  
```
public final class Backdrop3DScene extends PVIObject implements IBackdrop3DScene
```

Parlaklık ve gölge gibi efektlerin, uygulandıkları şekle göre uygulandığı bir düzlemi tanımlar.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNormalVector()](#getNormalVector--) | Normal bir vektörü döndürür veya ayarlar. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Normal bir vektörü döndürür veya ayarlar. |
| [getAnchorPoint()](#getAnchorPoint--) | 3B uzayda bir noktayı döndürür veya ayarlar. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | 3B uzayda bir noktayı döndürür veya ayarlar. |
| [getUpVector()](#getUpVector--) | Yukarıyı temsil eden bir vektörü döndürür veya ayarlar. |
| [setUpVector(float[] value)](#setUpVector-float---) | Yukarıyı temsil eden bir vektörü döndürür veya ayarlar. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Sürüm. Yalnızca okunabilir long.

**Döndürür:**  
long

### getNormalVector() {#getNormalVector--}
```
public final float[] getNormalVector()
```

Normal bir vektörü döndürür veya ayarlar. Daha kesin olmak gerekirse, bu öznitelik, arka plan düzleminin yüzeyine dik bir vektörü tanımlar. Vektör, X, Y ve Z koordinatlarını tanımlayan 3 float değerinden oluşan bir dizi ile temsil edilir. Okunabilir/yazılabilir float[].

**Döndürür:**  
float[]

### setNormalVector(float[] value) {#setNormalVector-float---}
```
public final void setNormalVector(float[] value)
```

Normal bir vektörü döndürür veya ayarlar. Daha kesin olmak gerekirse, bu öznitelik, arka plan düzleminin yüzeyine dik bir vektörü tanımlar. Vektör, X, Y ve Z koordinatlarını tanımlayan 3 float değerinden oluşan bir dizi ile temsil edilir. Okunabilir/yazılabilir float[].

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public final float[] getAnchorPoint()
```

3B uzayda bir noktayı döndürür veya ayarlar. Bu nokta, arka plan düzlemini konumlandıran uzaydaki noktadır. 3B nokta, X, Y ve Z koordinatlarını tanımlayan 3 float değerinden oluşan bir dizi ile temsil edilir. Okunabilir/yazılabilir float[].

**Döndürür:**  
float[]

### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public final void setAnchorPoint(float[] value)
```

3B uzayda bir noktayı döndürür veya ayarlar. Bu nokta, arka plan düzlemini konumlandıran uzaydaki noktadır. 3B nokta, X, Y ve Z koordinatlarını tanımlayan 3 float değerinden oluşan bir dizi ile temsil edilir. Okunabilir/yazılabilir float[].

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public final float[] getUpVector()
```

Yukarıyı temsil eden bir vektörü döndürür veya ayarlar. Daha kesin olmak gerekirse, bu öznitelik, arka plan düzleminin yüzeyine göre yukarıyı temsil eden bir vektörü tanımlar. Vektör, X, Y ve Z koordinatlarını tanımlayan 3 float değerinden oluşan bir dizi ile temsil edilir. Okunabilir/yazılabilir float[].

**Döndürür:**  
float[]

### setUpVector(float[] value) {#setUpVector-float---}
```
public final void setUpVector(float[] value)
```

Yukarıyı temsil eden bir vektörü döndürür veya ayarlar. Daha kesin olmak gerekirse, bu öznitelik, arka plan düzleminin yüzeyine göre yukarıyı temsil eden bir vektörü tanımlar. Vektör, X, Y ve Z koordinatlarını tanımlayan 3 float değerinden oluşan bir dizi ile temsil edilir. Okunabilir/yazılabilir float[].

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float[] |  |