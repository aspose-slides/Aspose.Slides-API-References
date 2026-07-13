---
title: ShapeThumbnailBounds
second_title: Referensi API Java Aspose.Slides untuk Android
description: Enumerasi tipe batas thumbnail shape.
type: docs
url: /id/com.aspose.slides/shapethumbnailbounds/
---
**Pewarisan:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ShapeThumbnailBounds extends System.Enum
```

Enumerasi tipe batas thumbnail shape.
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [Slide](#Slide) | Shape thumbnail will have the size equal to slide size. |
| [Shape](#Shape) | Shape thumbnail will have size equal to the shape bounds rectangle with taking into account shape outline settings. |
| [Appearance](#Appearance) | Shape thumbnail will have size equal to the shape appearance (in bounds of a slide). |
### Slide {#Slide}
```
public static final int Slide
```

Shape thumbnail akan memiliki ukuran yang sama dengan ukuran slide. Posisi Shape akan disimpan.

### Shape {#Shape}
```
public static final int Shape
```

Shape thumbnail akan memiliki ukuran yang sama dengan persegi panjang batas Shape dengan memperhitungkan pengaturan outline Shape.

### Appearance {#Appearance}
```
public static final int Appearance
```

Shape thumbnail akan memiliki ukuran yang sama dengan tampilan Shape (dalam batas slide). Bisa jadi ada kasus ketika tampilan Shape tidak cocok dengan batas Shape. Misalnya rotasi, sambungan miter pada sudut tajam, efek 3D, dll.