---
title: ILegacyDiagram
second_title: Aspose.Slides สำหรับ Java เอกสารอ้างอิง API
description: เป็นตัวแทนของวัตถุแผนภาพเก่า
type: docs
url: /th/com.aspose.slides/ilegacydiagram/
---
**อินเทอร์เฟซที่ทำงานทั้งหมด:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ILegacyDiagram extends IGraphicalObject
```

เป็นตัวแทนของวัตถุแผนภาพเก่า
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | แปลง digram เก่าเป็นวัตถุ SmartArt ที่แก้ไขได้ |
| [convertToGroupShape()](#convertToGroupShape--) | แปลง digram เก่าเป็นรูปกลุ่มที่แก้ไขได้ |
### convertToSmartArt() {#convertToSmartArt--}
```
public abstract ISmartArt convertToSmartArt()
```

แปลง digram เก่าเป็นวัตถุ SmartArt ที่แก้ไขได้ วัตถุ SmartArt ที่สร้างขึ้นจะถูกเพิ่มลงในรูปกลุ่มแม่ในตำแหน่งเดียวกัน

**คืนค่า:**
[ISmartArt](../../com.aspose.slides/ismartart) - วัตถุ SmartArt ที่สร้างขึ้น
### convertToGroupShape() {#convertToGroupShape--}
```
public abstract IGroupShape convertToGroupShape()
```

แปลง digram เก่าเป็นรูปกลุ่มที่แก้ไขได้ วัตถุ GroupShape ที่สร้างขึ้นจะถูกเพิ่มลงในรูปกลุ่มแม่ในตำแหน่งเดียวกัน

**คืนค่า:**
[IGroupShape](../../com.aspose.slides/igroupshape) - วัตถุ GroupShape ที่สร้างขึ้น