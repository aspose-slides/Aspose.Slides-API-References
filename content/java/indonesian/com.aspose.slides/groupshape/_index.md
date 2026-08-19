---
title: GroupShape
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili sekelompok bentuk pada slide.
type: docs
url: /id/com.aspose.slides/groupshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**All Implemented Interfaces:**
[com.aspose.slides.IGroupShape](../../com.aspose.slides/igroupshape)
```
public class GroupShape extends Shape implements IGroupShape
```

Mewakili sekelompok bentuk pada slide.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Mengembalikan objek LineFormat yang berisi properti pemformatan garis untuk sebuah bentuk. |
| [getGroupShapeLock()](#getGroupShapeLock--) | Mengembalikan kunci bentuk. |
| [getShapes()](#getShapes--) | Mengembalikan koleksi bentuk di dalam grup. |
### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

Mengembalikan objek LineFormat yang berisi properti pemformatan garis untuk sebuah bentuk. Catatan: Mengembalikan null untuk objek GroupShape karena mereka tidak memiliki properti garis. Hanya baca [ILineFormat](../../com.aspose.slides/ilineformat).

**Mengembalikan:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getGroupShapeLock() {#getGroupShapeLock--}
```
public final IGroupShapeLock getGroupShapeLock()
```

Mengembalikan kunci bentuk. Hanya baca [IGroupShapeLock](../../com.aspose.slides/igroupshapelock).

**Mengembalikan:**
[IGroupShapeLock](../../com.aspose.slides/igroupshapelock)
### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```

Mengembalikan koleksi bentuk di dalam grup. Hanya baca [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Mengembalikan:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)