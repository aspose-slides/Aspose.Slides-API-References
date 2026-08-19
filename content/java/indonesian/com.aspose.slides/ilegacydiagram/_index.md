---
title: ILegacyDiagram
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili objek diagram lama
type: docs
url: /id/com.aspose.slides/ilegacydiagram/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ILegacyDiagram extends IGraphicalObject
```

Mewakili objek diagram lama
## Metode

| Metode | Deskripsi |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | Mengonversi diagram lama menjadi objek SmartArt yang dapat diedit. |
| [convertToGroupShape()](#convertToGroupShape--) | Mengonversi diagram lama menjadi bentuk grup yang dapat diedit. |
### convertToSmartArt() {#convertToSmartArt--}
```
public abstract ISmartArt convertToSmartArt()
```

Mengonversi diagram lama menjadi objek SmartArt yang dapat diedit. Objek SmartArt yang dibuat ditambahkan ke bentuk grup induk pada posisi yang sama.

**Mengembalikan:**
[ISmartArt](../../com.aspose.slides/ismartart) - Objek SmartArt yang dibuat.
### convertToGroupShape() {#convertToGroupShape--}
```
public abstract IGroupShape convertToGroupShape()
```

Mengonversi diagram lama menjadi bentuk grup yang dapat diedit. Objek GroupShape yang dibuat ditambahkan ke bentuk grup induk pada posisi yang sama.

**Mengembalikan:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Objek GroupShape yang dibuat.