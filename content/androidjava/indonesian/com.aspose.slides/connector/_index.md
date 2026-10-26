---
title: Connector
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili sebuah konektor.
type: docs
url: /id/com.aspose.slides/connector/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IConnector](../../com.aspose.slides/iconnector)
```
public class Connector extends GeometryShape implements IConnector
```

Mewakili sebuah konektor.
## Metode

| Method | Description |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Mengembalikan kunci shape. |
| [getConnectorLock()](#getConnectorLock--) | Mengembalikan kunci connector. |
| [getShapeType()](#getShapeType--) | Mengembalikan atau mengatur tipe AutoShape. |
| [setShapeType(int value)](#setShapeType-int-) | Mengembalikan atau mengatur tipe AutoShape. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Mengembalikan atau mengatur shape untuk melampirkan awal connector. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Mengembalikan atau mengatur shape untuk melampirkan awal connector. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Mengembalikan atau mengatur shape untuk melampirkan akhir connector. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Mengembalikan atau mengatur shape untuk melampirkan akhir connector. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Mengembalikan atau mengatur indeks situs koneksi untuk shape awal. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Mengembalikan atau mengatur indeks situs koneksi untuk shape awal. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Mengembalikan atau mengatur indeks situs koneksi untuk shape akhir. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Mengembalikan atau mengatur indeks situs koneksi untuk shape akhir. |
| [reroute()](#reroute--) | Menata ulang connector sehingga mengambil jalur terpendek antara shape yang terhubung. |
### getShapeLock() {#getShapeLock--}
```
public final IConnectorLock getShapeLock()
```


Mengembalikan kunci shape. Baca-saja [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Mengembalikan:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public final IConnectorLock getConnectorLock()
```


Mengembalikan kunci connector. Baca-saja [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Mengembalikan:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```


Mengembalikan atau mengatur tipe AutoShape. Baca/tulis [ShapeType](../../com.aspose.slides/shapetype).

**Mengembalikan:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```


Mengembalikan atau mengatur tipe AutoShape. Baca/tulis [ShapeType](../../com.aspose.slides/shapetype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public final IShape getStartShapeConnectedTo()
```


Mengembalikan atau mengatur shape untuk melampirkan awal connector. Baca/tulis [IShape](../../com.aspose.slides/ishape).

**Mengembalikan:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setStartShapeConnectedTo(IShape value)
```


Mengembalikan atau mengatur shape untuk melampirkan awal connector. Baca/tulis [IShape](../../com.aspose.slides/ishape).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public final IShape getEndShapeConnectedTo()
```


Mengembalikan atau mengatur shape untuk melampirkan akhir connector. Baca/tulis [IShape](../../com.aspose.slides/ishape).

**Mengembalikan:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setEndShapeConnectedTo(IShape value)
```


Mengembalikan atau mengatur shape untuk melampirkan akhir connector. Baca/tulis [IShape](../../com.aspose.slides/ishape).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public final long getStartShapeConnectionSiteIndex()
```


Mengembalikan atau mengatur indeks situs koneksi untuk shape awal. Baca/tulis long.

**Mengembalikan:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public final void setStartShapeConnectionSiteIndex(long value)
```


Mengembalikan atau mengatur indeks situs koneksi untuk shape awal. Baca/tulis long.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | long |  |
### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public final long getEndShapeConnectionSiteIndex()
```


Mengembalikan atau mengatur indeks situs koneksi untuk shape akhir. Baca/tulis long.

**Mengembalikan:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public final void setEndShapeConnectionSiteIndex(long value)
```


Mengembalikan atau mengatur indeks situs koneksi untuk shape akhir. Baca/tulis long.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | long |  |
### reroute() {#reroute--}
```
public final void reroute()
```


Menata ulang connector sehingga mengambil jalur terpendek antara shape yang terhubung.