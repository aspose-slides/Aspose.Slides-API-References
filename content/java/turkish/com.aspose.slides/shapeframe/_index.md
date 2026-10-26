---
title: ShapeFrame
second_title: Aspose.Slides for Java API Referansı
description: Şekil çerçevelerinin özelliklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/shapeframe/
---
**Kalıtım:**  
java.lang.Object

**Tüm Uygulanan Arabirimler:**  
[com.aspose.slides.IShapeFrame](../../com.aspose.slides/ishapeframe)  
```
public class ShapeFrame implements IShapeFrame
```

Şekil çerçevesinin özelliklerini temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)](#ShapeFrame-float-float-float-float-byte-byte-float-) | Yeni şekil çerçevesinin özelliklerini oluşturur. |
## Metodlar

| Metod | Açıklama |
| --- | --- |
| [getX()](#getX--) | Bir çerçevenin sol üst köşesinin X koordinatını döndürür. |
| [getY()](#getY--) | Bir çerçevenin sol üst köşesinin Y koordinatını döndürür. |
| [getWidth()](#getWidth--) | Bir çerçevenin genişliğini döndürür. |
| [getHeight()](#getHeight--) | Bir çerçevenin yüksekliğini döndürür. |
| [getRotation()](#getRotation--) | Bir çerçevenin z ekseni etrafında döndürüldüğü derece sayısını döndürür. |
| [getCenterX()](#getCenterX--) | Bir çerçevenin merkezinin X koordinatını döndürür. |
| [getCenterY()](#getCenterY--) | Bir çerçevenin merkezinin Y koordinatını döndürür. |
| [getFlipH()](#getFlipH--) | Bir çerçevenin yatay olarak çevrilip çevrilmediğini belirler. |
| [getFlipV()](#getFlipV--) | Bir çerçevenin dikey olarak çevrilip çevrilmediğini belirler. |
| [getRectangle()](#getRectangle--) | Bir çerçevenin koordinatlarını döndürür. |
| [deepClone()](#deepClone--) | Kopyalar |
| [cloneT()](#cloneT--) | Kopyalar. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Bu örnekle belirtilen nesneye eşit olup olmadığını gösteren bir değer döndürür. |
| [equals(ShapeFrame value)](#equals-com.aspose.slides.ShapeFrame-) | Bu örnekle belirtilen nesneye eşit olup olmadığını gösteren bir değer döndürür. |
### ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle) {#ShapeFrame-float-float-float-float-byte-byte-float-}
```
public ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)
```

Yeni şekil çerçevesinin özelliklerini oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Bir çerçevenin X koordinatı. |
| y | float | Bir çerçevenin Y koordinatı. |
| width | float | Bir çerçevenin genişliği. |
| height | float | Bir çerçevenin yüksekliği. |
| flipH | byte | Çerçeve yatay olarak çevrildiyse true. |
| flipV | byte | Çerçeve dikey olarak çevrildiyse true. |
| rotationAngle | float | Bir çerçevenin döndürülme derecesi. |

### getX() {#getX--}
```
public final float getX()
```

Bir çerçevenin sol üst köşesinin X koordinatını döndürür. Yalnızca okunur float.

**Dönüş:**
float
### getY() {#getY--}
```
public final float getY()
```

Bir çerçevenin sol üst köşesinin Y koordinatını döndürür. Yalnızca okunur float.

**Dönüş:**
float
### getWidth() {#getWidth--}
```
public final float getWidth()
```

Bir çerçevenin genişliğini döndürür. Yalnızca okunur float.

**Dönüş:**
float
### getHeight() {#getHeight--}
```
public final float getHeight()
```

Bir çerçevenin yüksekliğini döndürür. Yalnızca okunur float.

**Dönüş:**
float
### getRotation() {#getRotation--}
```
public final float getRotation()
```

Bir çerçevenin z ekseni etrafında döndürüldüğü derece sayısını döndürür. Pozitif bir değer saat yönünde döndürmeyi, negatif bir değer saat yönünün tersine döndürmeyi gösterir. Yalnızca okunur float.

**Dönüş:**
float
### getCenterX() {#getCenterX--}
```
public final float getCenterX()
```

Bir çerçevenin merkezinin X koordinatını döndürür. Yalnızca okunur float.

**Dönüş:**
float
### getCenterY() {#getCenterY--}
```
public final float getCenterY()
```

Bir çerçevenin merkezinin Y koordinatını döndürür. Yalnızca okunur float.

**Dönüş:**
float
### getFlipH() {#getFlipH--}
```
public final byte getFlipH()
```

Bir çerçevenin yatay olarak çevrilip çevrilmediğini belirler. Yalnızca okunur [NullableBool](../../com.aspose.slides/nullablebool).

**Dönüş:**
byte
### getFlipV() {#getFlipV--}
```
public final byte getFlipV()
```

Bir çerçevenin dikey olarak çevrilip çevrilmediğini belirler. Yalnızca okunur [NullableBool](../../com.aspose.slides/nullablebool).

**Dönüş:**
byte
### getRectangle() {#getRectangle--}
```
public final Rectangle2D.Float getRectangle()
```

Bir çerçevenin koordinatlarını döndürür. Yalnızca okunur java.awt.geom.Rectangle2D.Float.

**Dönüş:**
java.awt.geom.Rectangle2D.Float
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Kopyalar

**Dönüş:**
java.lang.Object - Kopyalanmış şekil çerçevesi.
### cloneT() {#cloneT--}
```
public final IShapeFrame cloneT()
```

Kopyalar.

**Dönüş:**
[IShapeFrame](../../com.aspose.slides/ishapeframe) - Kopyalanmış şekil çerçevesi.
### hashCode() {#hashCode--}
```
public int hashCode()
```

**Dönüş:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Bu örnekle belirtilen nesneye eşit olup olmadığını gösteren bir değer döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Bu örnekle karşılaştırılacak nesne. |

**Dönüş:**
boolean - **true** eğer obj bu örnekle aynı değere sahip bir ShapeFrame ise; aksi takdirde **false**.
### equals(ShapeFrame value) {#equals-com.aspose.slides.ShapeFrame-}
```
public final boolean equals(ShapeFrame value)
```

Bu örnekle belirtilen nesneye eşit olup olmadığını gösteren bir değer döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ShapeFrame](../../com.aspose.slides/shapeframe) | Bu örnekle karşılaştırılacak ShapeFRameEx. |

**Dönüş:**
boolean - **true** eğer value bu örnekle aynı değere sahip bir ShapeFrame ise; aksi takdirde **false**.