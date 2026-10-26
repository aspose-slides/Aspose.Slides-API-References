---
title: LegacyDiagram
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงอ็อบเจกต์แผนภาพรุ่นเก่า.
type: docs
url: /th/com.aspose.slides/legacydiagram/
---
**การสืบทอด:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**  
[com.aspose.slides.ILegacyDiagram](../../com.aspose.slides/ilegacydiagram)  
```
public class LegacyDiagram extends GraphicalObject implements ILegacyDiagram
```

แสดงอ็อบเจกต์แผนภาพรุ่นเก่า.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | แปลง digram รุ่นเก่าเป็นอ็อบเจกต์ SmartArt ที่แก้ไขได้. |
| [convertToGroupShape()](#convertToGroupShape--) | แปลง digram รุ่นเก่าเป็นรูปร่างกลุ่มที่สามารถแก้ไขได้. |

### convertToSmartArt() {#convertToSmartArt--}
```
public final ISmartArt convertToSmartArt()
```

แปลง digram รุ่นเก่าเป็นอ็อบเจกต์ SmartArt ที่แก้ไขได้. อ็อบเจกต์ SmartArt ที่สร้างขึ้นจะเพิ่มเข้าไปในรูปร่างกลุ่มแม่ในตำแหน่งเดียวกัน.

**ผลลัพธ์:**  
[ISmartArt](../../com.aspose.slides/ismartart) - อ็อบเจกต์ SmartArt ที่สร้างขึ้น.

### convertToGroupShape() {#convertToGroupShape--}
```
public final IGroupShape convertToGroupShape()
```

แปลง digram รุ่นเก่าเป็นรูปร่างกลุ่มที่แก้ไขได้. อ็อบเจกต์ GroupShape ที่สร้างขึ้นจะเพิ่มเข้าไปในรูปร่างกลุ่มแม่ในตำแหน่งเดียวกัน.

**ผลลัพธ์:**  
[IGroupShape](../../com.aspose.slides/igroupshape) - อ็อบเจกต์ GroupShape ที่สร้างขึ้น.