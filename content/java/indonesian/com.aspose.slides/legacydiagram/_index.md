---
title: LegacyDiagram
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili objek diagram warisan.
type: docs
url: /id/com.aspose.slides/legacydiagram/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ILegacyDiagram](../../com.aspose.slides/ilegacydiagram)
```
public class LegacyDiagram extends GraphicalObject implements ILegacyDiagram
```

Mewakili objek diagram warisan.
## Metode

| Method | Description |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | Mengonversi diagram warisan menjadi objek SmartArt yang dapat diedit. |
| [convertToGroupShape()](#convertToGroupShape--) | Mengonversi diagram warisan menjadi group shape yang dapat diedit. |
### convertToSmartArt() {#convertToSmartArt--}
```
public final ISmartArt convertToSmartArt()
```


Mengonversi diagram warisan menjadi objek SmartArt yang dapat diedit. Objek SmartArt yang dibuat ditambahkan ke parent group shape pada posisi yang sama.

**Mengembalikan:**
[ISmartArt](../../com.aspose.slides/ismartart) - Created SmartArt object.
### convertToGroupShape() {#convertToGroupShape--}
```
public final IGroupShape convertToGroupShape()
```


Mengonversi diagram warisan menjadi group shape yang dapat diedit. Objek GroupShape yang dibuat ditambahkan ke parent group shape pada posisi yang sama.

**Mengembalikan:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Created GroupShape object.