---
title: ILegacyDiagram
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: เป็นอ็อบเจ็กต์ diagram แบบ legacy
type: docs
url: /th/com.aspose.slides/ilegacydiagram/
---
**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ILegacyDiagram extends IGraphicalObject
```

เป็นอ็อบเจ็กต์ diagram แบบ legacy
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | แปลง legacy digram ไปเป็นอ็อบเจ็กต์ SmartArt ที่แก้ไขได้ |
| [convertToGroupShape()](#convertToGroupShape--) | แปลง legacy digram ไปเป็น group shape ที่แก้ไขได้ |
### convertToSmartArt() {#convertToSmartArt--}
```
public abstract ISmartArt convertToSmartArt()
```

แปลง legacy digram ไปเป็นอ็อบเจ็กต์ SmartArt ที่แก้ไขได้. อ็อบเจ็กต์ SmartArt ที่สร้างขึ้นจะถูกเพิ่มไปยัง group shape พาเรนต์ในตำแหน่งเดียวกัน

**คืนค่า:**
[ISmartArt](../../com.aspose.slides/ismartart) - อ็อบเจ็กต์ SmartArt ที่สร้างขึ้น
### convertToGroupShape() {#convertToGroupShape--}
```
public abstract IGroupShape convertToGroupShape()
```

แปลง legacy digram ไปเป็น group shape ที่แก้ไขได้. อ็อบเจ็กต์ GroupShape ที่สร้างขึ้นจะถูกเพิ่มไปยัง group shape พาเรนต์ในตำแหน่งเดียวกัน

**คืนค่า:**
[IGroupShape](../../com.aspose.slides/igroupshape) - อ็อบเจ็กต์ GroupShape ที่สร้างขึ้น