---
title: ShapeFrame
second_title: Aspose.Slides for Android via Java API Referansı
description: Şekil çerçevelerinin özelliklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/shapeframe/
---
**Kalıtım:**  
java.lang.Object

**Tüm Uygulanan Arayüzler:**  
[com.aspose.slides.IShapeFrame](../../com.aspose.slides/ishapeframe)  
```
public class ShapeFrame implements IShapeFrame
```

Şekil çerçevesinin özelliklerini temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)](#ShapeFrame-float-float-float-float-byte-byte-float-) | Yeni bir şekil çerçevesinin özelliklerini oluşturur. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getX()](#getX--) | Bir çerçevenin sol üst köşesinin X koordinatını döndürür. |
| [getY()](#getY--) | Bir çerçevenin sol üst köşesinin Y koordinatını döndürür. |
| [getWidth()](#getWidth--) | Bir çerçevenin genişliğini döndürür. |
| [getHeight()](#getHeight--) | Bir çerçevenin yüksekliğini döndürür. |
| [getRotation()](#getRotation--) | Bir çerçevenin z ekseni etrafında döndüğü derece sayısını döndürür. |
| [getCenterX()](#getCenterX--) | Bir çerçevenin merkezinin X koordinatını döndürür. |
| [getCenterY()](#getCenterY--) | Bir çerçevenin merkezinin Y koordinatını döndürür. |
| [getFlipH()](#getFlipH--) | Bir çerçevenin yatay olarak çevrilip çevrilmediğini belirler. |
| [getFlipV()](#getFlipV--) | Bir çerçevenin dikey olarak çevrilip çevrilmediğini belirler. |
| [getRectangle()](#getRectangle--) | Bir çerçevenin koordinatlarını döndürür. |
| [deepClone()](#deepClone--) | Klonlar |
| [cloneT()](#cloneT--) | Klonlar. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Bu örneğin belirtilen nesneye eşit olup olmadığını belirten bir değer döndürür. |
| [equals(ShapeFrame value)](#equals-com.aspose.slides.ShapeFrame-) | Bu örneğin belirtilen nesneye eşit olup olmadığını belirten bir değer döndürür. |

### ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle) {#ShapeFrame-float-float-float-float-byte-byte-float-}
```
public ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)
```

Yeni bir şekil çerçevesinin özelliklerini oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Bir çerçevenin X koordinatı. |
| y | float | Bir çerçevenin Y koordinatı. |
| width | float | Bir çerçevenin genişliği. |
| height | float | Bir çerçevenin yüksekliği. |
| flipH | byte | Çerçeve yatay olarak çevrilmişse doğru. |
| flipV | byte | Çerçeve dikey olarak çevrilmişse doğru. |
| rotationAngle | float | Bir çerçevenin döndüğü derece sayısı. |

### getX() {#getX--}
```
public final float getX()
```

Bir çerçevenin sol üst köşesinin X koordinatını döndürür. Yalnızca okunabilir float.

**Döndürür:**  
float

### getY() {#getY--}
```
public final float getY()
```

Bir çerçevenin sol üst köşesinin Y koordinatını döndürür. Yalnızca okunabilir float.

**Döndürür:**  
float

### getWidth() {#getWidth--}
```
public final float getWidth()
```

Bir çerçevenin genişliğini döndürür. Yalnızca okunabilir float.

**Döndürür:**  
float

### getHeight() {#getHeight--}
```
public final float getHeight()
```

Bir çerçevenin yüksekliğini döndürür. Yalnızca okunabilir float.

**Döndürür:**  
float

### getRotation() {#getRotation--}
```
public final float getRotation()
```

Bir çerçevenin z ekseni etrafında döndüğü derece sayısını döndürür. Pozitif bir değer saat yönünde döndürmeyi, negatif bir değer saat yönünün tersine döndürmeyi gösterir. Yalnızca okunabilir float.

**Döndürür:**  
float

### getCenterX() {#getCenterX--}
```
public final float getCenterX()
```

Bir çerçevenin merkezinin X koordinatını döndürür. Yalnızca okunabilir float.

**Döndürür:**  
float

### getCenterY() {#getCenterY--}
```
public final float getCenterY()
```

Bir çerçevenin merkezinin Y koordinatını döndürür. Yalnızca okunabilir float.

**Döndürür:**  
float

### getFlipH() {#getFlipH--}
```
public final byte getFlipH()
```

Bir çerçevenin yatay olarak çevrilip çevrilmediğini belirler. Yalnızca okunabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**  
byte

### getFlipV() {#getFlipV--}
```
public final byte getFlipV()
```

Bir çerçevenin dikey olarak çevrilip çevrilmediğini belirler. Yalnızca okunabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**  
byte

### getRectangle() {#getRectangle--}
```
public final RectF getRectangle()
```

Bir çerçevenin koordinatlarını döndürür. Yalnızca okunabilir android.graphics.RectF.

**Döndürür:**  
android.graphics.RectF

### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Klonlar

**Döndürür:**  
java.lang.Object - Klonlanmış şekil çerçevesi.

### cloneT() {#cloneT--}
```
public final IShapeFrame cloneT()
```

Klonlar.

**Döndürür:**  
[IShapeFrame](../../com.aspose.slides/ishapeframe) - Klonlanmış şekil çerçevesi.

### hashCode() {#hashCode--}
```
public int hashCode()
```

**Döndürür:**  
int

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Bu örneğin belirtilen nesneyle eşit olup olmadığını belirten bir değer döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Bu örnekle karşılaştırılacak nesne. |

**Döndürür:**  
boolean - **true** ise obj bu örnekle aynı değere sahip bir ShapeFrame; aksi takdirde **false**.

### equals(ShapeFrame value) {#equals-com.aspose.slides.ShapeFrame-}
```
public final boolean equals(ShapeFrame value)
```

Bu örneğin belirtilen nesneyle eşit olup olmadığını belirten bir değer döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ShapeFrame](../../com.aspose.slides/shapeframe) | Bu örnekle karşılaştırılacak ShapeFRameEx. |

**Döndürür:**  
boolean - **true** ise value bu örnekle aynı değere sahip bir ShapeFrame; aksi takdirde **false**.