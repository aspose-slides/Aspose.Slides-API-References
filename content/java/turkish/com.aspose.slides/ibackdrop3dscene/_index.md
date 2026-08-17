---
title: IBackdrop3DScene
second_title: Aspose.Slides for Java API Reference
description: Parlama ve gölge gibi efektlerin, uygulandıkları şekle göre uygulandığı bir düzlemi tanımlar.
type: docs
url: /tr/com.aspose.slides/ibackdrop3dscene/
---```
public interface IBackdrop3DScene
```

Parlama ve gölge gibi efektlerin, uygulandıkları şekle göre uygulandığı bir düzlemi tanımlar.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getNormalVector()](#getNormalVector--) | Normal bir vektörü döndürür veya ayarlar. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Normal bir vektörü döndürür veya ayarlar. |
| [getAnchorPoint()](#getAnchorPoint--) | 3D uzaydaki bir noktayı döndürür veya ayarlar. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | 3D uzaydaki bir noktayı döndürür veya ayarlar. |
| [getUpVector()](#getUpVector--) | Yukarıyı temsil eden bir vektörü döndürür veya ayarlar. |
| [setUpVector(float[] value)](#setUpVector-float---) | Yukarıyı temsil eden bir vektörü döndürür veya ayarlar. |
### getNormalVector() {#getNormalVector--}
```
public abstract float[] getNormalVector()
```


Normal bir vektörü döndürür veya ayarlar. Daha kesin olmak gerekirse, bu öznitelik arka plan düzleminin yüzeyine dik bir vektörü tanımlar. Vektör, X, Y ve Z koordinatlarını tanımlayan 3 adet float değerinden oluşan bir diziyle temsil edilir. Okunur/yazılır float[].

**Döndürür:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public abstract void setNormalVector(float[] value)
```


Normal bir vektörü döndürür veya ayarlar. Daha kesin olmak gerekirse, bu öznitelik arka plan düzleminin yüzeyine dik bir vektörü tanımlar. Vektör, X, Y ve Z koordinatlarını tanımlayan 3 adet float değerinden oluşan bir diziyle temsil edilir. Okunur/yazılır float[].

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public abstract float[] getAnchorPoint()
```


3D uzaydaki bir noktayı döndürür veya ayarlar. Bu nokta, arka plan düzlemini konumlandıran uzaydaki noktadır. 3D nokta, X, Y ve Z koordinatlarını tanımlayan 3 adet float değerinden oluşan bir diziyle temsil edilir. Okunur/yazılır float[].

**Döndürür:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public abstract void setAnchorPoint(float[] value)
```


3D uzaydaki bir noktayı döndürür veya ayarlar. Bu nokta, arka plan düzlemini konumlandıran uzaydaki noktadır. 3D nokta, X, Y ve Z koordinatlarını tanımlayan 3 adet float değerinden oluşan bir diziyle temsil edilir. Okunur/yazılır float[].

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public abstract float[] getUpVector()
```


Yukarıyı temsil eden bir vektörü döndürür veya ayarlar. Daha kesin olmak gerekirse, bu öznitelik arka plan düzleminin yüzeyine göre yukarıyı temsil eden bir vektörü tanımlar. Vektör, X, Y ve Z koordinatlarını tanımlayan 3 adet float değerinden oluşan bir diziyle temsil edilir. Okunur/yazılır float[].

**Döndürür:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public abstract void setUpVector(float[] value)
```


Yukarıyı temsil eden bir vektörü döndürür veya ayarlar. Daha kesin olmak gerekirse, bu öznitelik arka plan düzleminin yüzeyine göre yukarıyı temsil eden bir vektörü tanımlar. Vektör, X, Y ve Z koordinatlarını tanımlayan 3 adet float değerinden oluşan bir diziyle temsil edilir. Okunur/yazılır float[].

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | float[] |  |