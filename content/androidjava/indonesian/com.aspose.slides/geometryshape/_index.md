---
title: GeometryShape
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili kelas induk untuk semua bentuk geometris.
type: docs
url: /id/com.aspose.slides/geometryshape/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public abstract class GeometryShape extends Shape implements IGeometryShape
```

Mewakili kelas induk untuk semua bentuk geometris.
## Metode

| Method | Description |
| --- | --- |
| [getGeometryPaths()](#getGeometryPaths--) | Mengembalikan salinan jalur bentuk geometris. |
| [setGeometryPath(IGeometryPath geometryPath)](#setGeometryPath-com.aspose.slides.IGeometryPath-) | Memperbarui geometri bentuk dari objek [IGeometryPath](../../com.aspose.slides/igeometrypath). |
| [setGeometryPaths(IGeometryPath[] geometryPaths)](#setGeometryPaths-com.aspose.slides.IGeometryPath---) | Memperbarui geometri bentuk dari array [IGeometryPath](../../com.aspose.slides/igeometrypath). |
| [getShapeStyle()](#getShapeStyle--) | Mengembalikan objek gaya bentuk. |
| [getShapeType()](#getShapeType--) | Mengembalikan atau mengatur jenis preset geometri. |
| [setShapeType(int value)](#setShapeType-int-) | Mengembalikan atau mengatur jenis preset geometri. |
| [getAdjustments()](#getAdjustments--) | Mengembalikan koleksi nilai penyesuaian bentuk. |
| [createShapeElements()](#createShapeElements--) | Membuat dan mengembalikan array elemen bentuk. |
### getGeometryPaths() {#getGeometryPaths--}
```
public final IGeometryPath[] getGeometryPaths()
```

Mengembalikan salinan jalur bentuk geometris. Koordinat relatif terhadap sudut kiri atas bentuk.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      GeometryShape shape = (GeometryShape) pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 200, 100);
>      IGeometryPath geometryPath = shape.getGeometryPaths()[0];
>      geometryPath.lineTo(100, 50, 1);
>      geometryPath.lineTo(100, 50, 4);
>      shape.setGeometryPath(geometryPath);
>      pres.save("output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Mengembalikan:**
com.aspose.slides.IGeometryPath[] - Array dari [IGeometryPath](../../com.aspose.slides/igeometrypath)
### setGeometryPath(IGeometryPath geometryPath) {#setGeometryPath-com.aspose.slides.IGeometryPath-}
```
public final void setGeometryPath(IGeometryPath geometryPath)
```

Memperbarui geometri bentuk dari objek [IGeometryPath](../../com.aspose.slides/igeometrypath). Koordinat harus relatif terhadap sudut kiri atas bentuk. Mengubah tipe bentuk (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) menjadi [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      GeometryShape shape = (GeometryShape) pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 200, 100);
>      GeometryPath geometryPath0 = new GeometryPath();
>      geometryPath0.moveTo(0, 0);
>      geometryPath0.lineTo(shape.getWidth(), 0);
>      geometryPath0.lineTo(shape.getWidth(), shape.getHeight()/3);
>      geometryPath0.lineTo(0, shape.getHeight() / 3);
>      geometryPath0.closeFigure();
>      GeometryPath geometryPath1 = new GeometryPath();
>      geometryPath1.moveTo(0, shape.getHeight()/3 * 2);
>      geometryPath1.lineTo(shape.getWidth(), shape.getHeight() / 3 * 2);
>      geometryPath1.lineTo(shape.getWidth(), shape.getHeight());
>      geometryPath1.lineTo(0, shape.getHeight());
>      geometryPath1.closeFigure();
>      shape.setGeometryPaths(new GeometryPath[] { geometryPath0, geometryPath1});
>      pres.save("output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| geometryPath | [IGeometryPath](../../com.aspose.slides/igeometrypath) | Jalur geometri |

### setGeometryPaths(IGeometryPath[] geometryPaths) {#setGeometryPaths-com.aspose.slides.IGeometryPath---}
```
public final void setGeometryPaths(IGeometryPath[] geometryPaths)
```

Memperbarui geometri bentuk dari array [IGeometryPath](../../com.aspose.slides/igeometrypath). Koordinat harus relatif terhadap sudut kiri atas bentuk. Mengubah tipe bentuk (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) menjadi [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      GeometryShape shape = (GeometryShape)pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 200, 100);
>      IGeometryPath geometryPath = shape.getGeometryPaths()[0];
>      geometryPath.lineTo(100, 50, 1);
>      geometryPath.lineTo(100, 50, 4);
>      shape.setGeometryPath(geometryPath);
>      pres.save("output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| geometryPaths | [IGeometryPath\[\]](../../com.aspose.slides/igeometrypath) | Array jalur geometri |

### getShapeStyle() {#getShapeStyle--}
```
public final IShapeStyle getShapeStyle()
```

Mengembalikan objek gaya bentuk. Hanya-baca [IShapeStyle](../../com.aspose.slides/ishapestyle).

**Mengembalikan:**
[IShapeStyle](../../com.aspose.slides/ishapestyle)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

Mengembalikan atau mengatur jenis preset geometri. Catatan: saat nilai berubah semua nilai penyesuaian akan direset ke nilai default mereka. Baca/tulis [ShapeType](../../com.aspose.slides/shapetype).

**Mengembalikan:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

Mengembalikan atau mengatur jenis preset geometri. Catatan: saat nilai berubah semua nilai penyesuaian akan direset ke nilai default mereka. Baca/tulis [ShapeType](../../com.aspose.slides/shapetype).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAdjustments() {#getAdjustments--}
```
public final IAdjustValueCollection getAdjustments()
```

Mengembalikan koleksi nilai penyesuaian bentuk. Hanya-baca [IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection).

**Mengembalikan:**
[IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
### createShapeElements() {#createShapeElements--}
```
public final IShapeElement[] createShapeElements()
```

Membuat dan mengembalikan array elemen bentuk.

**Mengembalikan:**
com.aspose.slides.IShapeElement[] - Array dari [ShapeElement](../../com.aspose.slides/shapeelement)