---
title: IConnector
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili sebuah connector.
type: docs
url: /id/com.aspose.slides/iconnector/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IConnector extends IGeometryShape
```

Mewakili sebuah connector.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Mengembalikan kunci shape. |
| [getConnectorLock()](#getConnectorLock--) | Mengembalikan kunci Connector. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Mengembalikan atau mengatur shape untuk menempelkan awal connector. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Mengembalikan atau mengatur shape untuk menempelkan awal connector. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Mengembalikan atau mengatur shape untuk menempelkan akhir connector. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Mengembalikan atau mengatur shape untuk menempelkan akhir connector. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Mengembalikan atau mengatur indeks situs koneksi untuk shape awal. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Mengembalikan atau mengatur indeks situs koneksi untuk shape awal. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Mengembalikan atau mengatur indeks situs koneksi untuk shape akhir. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Mengembalikan atau mengatur indeks situs koneksi untuk shape akhir. |
| [reroute()](#reroute--) | Mengarahkan ulang connector sehingga mengambil jalur terpendek yang mungkin antara shape yang terhubung. |
### getShapeLock() {#getShapeLock--}
```
public abstract IConnectorLock getShapeLock()
```

Mengembalikan kunci shape. Hanya baca [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Mengembalikan:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public abstract IConnectorLock getConnectorLock()
```

Mengembalikan kunci Connector. Hanya baca [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Mengembalikan:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public abstract IShape getStartShapeConnectedTo()
```

Mengembalikan atau mengatur shape untuk menempelkan awal connector. Baca/tulis [IShape](../../com.aspose.slides/ishape).

**Mengembalikan:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setStartShapeConnectedTo(IShape value)
```

Mengembalikan atau mengatur shape untuk menempelkan awal connector. Baca/tulis [IShape](../../com.aspose.slides/ishape).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public abstract IShape getEndShapeConnectedTo()
```

Mengembalikan atau mengatur shape untuk menempelkan akhir connector. Baca/tulis [IShape](../../com.aspose.slides/ishape).

**Mengembalikan:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setEndShapeConnectedTo(IShape value)
```

Mengembalikan atau mengatur shape untuk menempelkan akhir connector. Baca/tulis [IShape](../../com.aspose.slides/ishape).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public abstract long getStartShapeConnectionSiteIndex()
```

Mengembalikan atau mengatur indeks situs koneksi untuk shape awal. Baca/tulis long.

**Mengembalikan:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public abstract void setStartShapeConnectionSiteIndex(long value)
```

Mengembalikan atau mengatur indeks situs koneksi untuk shape awal. Baca/tulis long.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | long |  |
### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public abstract long getEndShapeConnectionSiteIndex()
```

Mengembalikan atau mengatur indeks situs koneksi untuk shape akhir. Baca/tulis long.

**Mengembalikan:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public abstract void setEndShapeConnectionSiteIndex(long value)
```

Mengembalikan atau mengatur indeks situs koneksi untuk shape akhir. Baca/tulis long.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | long |  |
### reroute() {#reroute--}
```
public abstract void reroute()
```

Mengarahkan ulang connector sehingga mengambil jalur terpendek yang mungkin antara shape yang terhubung.