---
title: Backdrop3DScene
second_title: Aspose.Slides for Android için Java API Referansı
description: Parıltı ve gölge gibi efektlerin, uygulanacak şekle göre uygulandığı bir düzlemi tanımlar.
type: docs
url: /tr/com.aspose.slides/backdrop3dscene/
---
**Miras:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IBackdrop3DScene](../../com.aspose.slides/ibackdrop3dscene)
```
public final class Backdrop3DScene extends PVIObject implements IBackdrop3DScene
```

Bir şekle uygulanırken, parıltı ve gölge gibi efektlerin şekle göre uygulanmasını sağlayan bir düzlem tanımlar.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNormalVector()](#getNormalVector--) | Normal bir vektör döndürür veya ayarlar. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Normal bir vektör döndürür veya ayarlar. |
| [getAnchorPoint()](#getAnchorPoint--) | 3B uzaydaki bir noktayı döndürür veya ayarlar. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | 3B uzaydaki bir noktayı döndürür veya ayarlar. |
| [getUpVector()](#getUpVector--) | Yukarıyı temsil eden bir vektörü döndürür veya ayarlar. |
| [setUpVector(float[] value)](#setUpVector-float---) | Yukarıyı temsil eden bir vektörü döndürür veya ayarlar. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Sürüm. Salt okunur uzun.

**Döndürür:**
long
### getNormalVector() {#getNormalVector--}
```
public final float[] getNormalVector()
```


Normal bir vektör döndürür veya ayarlar. Daha kesin olmak gerekirse, bu öznitelik arka plan düzleminin yüzeyine dik bir vektörü tanımlar. Vektör, X, Y ve Z koordinatlarını tanımlayan 3 adet float değerinden oluşan bir dizi ile temsil edilir. Okunabilir/yazılabilir float[].

**Döndürür:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public final void setNormalVector(float[] value)
```


Normal bir vektör döndürür veya ayarlar. Daha kesin olmak gerekirse, bu öznitelik arka plan düzleminin yüzeyine dik bir vektörü tanımlar. Vektör, X, Y ve Z koordinatlarını tanımlayan 3 adet float değerinden oluşan bir dizi ile temsil edilir. Okunabilir/yazılabilir float[].

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public final float[] getAnchorPoint()
```


3B uzaydaki bir noktayı döndürür veya ayarlar. Bu nokta, arka plan düzlemini konumlandıran noktadır. 3B nokta, X, Y ve Z koordinatlarını tanımlayan 3 adet float değerinden oluşan bir dizi ile temsil edilir. Okunabilir/yazılabilir float[].

**Döndürür:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public final void setAnchorPoint(float[] value)
```


3B uzaydaki bir noktayı döndürür veya ayarlar. Bu nokta, arka plan düzlemini konumlandıran noktadır. 3B nokta, X, Y ve Z koordinatlarını tanımlayan 3 adet float değerinden oluşan bir dizi ile temsil edilir. Okunabilir/yazılabilir float[].

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public final float[] getUpVector()
```


Yukarıyı temsil eden bir vektör döndürür veya ayarlar. Daha kesin olmak gerekirse, bu öznitelik arka plan düzleminin yüzeyine göre yukarıyı temsil eden bir vektörü tanımlar. Vektör, X, Y ve Z koordinatlarını tanımlayan 3 adet float değerinden oluşan bir dizi ile temsil edilir. Okunabilir/yazılabilir float[].

**Döndürür:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public final void setUpVector(float[] value)
```


Yukarıyı temsil eden bir vektör döndürür veya ayarlar. Daha kesin olmak gerekirse, bu öznitelik arka plan düzleminin yüzeyine göre yukarıyı temsil eden bir vektörü tanımlar. Vektör, X, Y ve Z koordinatlarını tanımlayan 3 adet float değerinden oluşan bir dizi ile temsil edilir. Okunabilir/yazılabilir float[].

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float[] |  |