---
title: GroupShape
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili sekelompok bentuk pada slide.
type: docs
url: /id/com.aspose.slides/groupshape/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IGroupShape](../../com.aspose.slides/igroupshape)
```
public class GroupShape extends Shape implements IGroupShape
```

Mewakili sekelompok bentuk pada slide.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Mengembalikan objek LineFormat yang berisi properti format garis untuk sebuah bentuk. |
| [getGroupShapeLock()](#getGroupShapeLock--) | Mengembalikan kunci bentuk. |
| [getShapes()](#getShapes--) | Mengembalikan koleksi bentuk di dalam grup. |
### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```


Mengembalikan objek LineFormat yang berisi properti format garis untuk sebuah bentuk. Catatan: Mengembalikan null untuk objek GroupShape karena mereka tidak memiliki properti garis. Baca-saja [ILineFormat](../../com.aspose.slides/ilineformat).

**Mengembalikan:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getGroupShapeLock() {#getGroupShapeLock--}
```
public final IGroupShapeLock getGroupShapeLock()
```


Mengembalikan kunci bentuk. Baca-saja [IGroupShapeLock](../../com.aspose.slides/igroupshapelock).

**Mengembalikan:**
[IGroupShapeLock](../../com.aspose.slides/igroupshapelock)
### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```


Mengembalikan koleksi bentuk di dalam grup. Baca-saja [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Mengembalikan:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)