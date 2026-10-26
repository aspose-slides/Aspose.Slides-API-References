---
title: LegacyDiagram
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นอ็อบเจ็กต์ไดอะแกรมรุ่นเก่า.
type: docs
url: /th/com.aspose.slides/legacydiagram/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.ILegacyDiagram](../../com.aspose.slides/ilegacydiagram)
```
public class LegacyDiagram extends GraphicalObject implements ILegacyDiagram
```

เป็นอ็อบเจ็กต์ไดอะแกรมรุ่นเก่า.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | แปลง digram รุ่นเก่าให้เป็นอ็อบเจ็กต์ SmartArt ที่แก้ไขได้. |
| [convertToGroupShape()](#convertToGroupShape--) | แปลง digram รุ่นเก่าให้เป็นกลุ่มรูปร่างที่แก้ไขได้. |
### convertToSmartArt() {#convertToSmartArt--}
```
public final ISmartArt convertToSmartArt()
```


แปลง digram รุ่นเก่าให้เป็นอ็อบเจ็กต์ SmartArt ที่แก้ไขได้. สร้างอ็อบเจ็กต์ SmartArt จะเพิ่มเข้าไปในกลุ่มรูปร่างแม่ที่ตำแหน่งเดียวกัน.

**คืนค่า:**
[ISmartArt](../../com.aspose.slides/ismartart) - สร้างอ็อบเจ็กต์ SmartArt.
### convertToGroupShape() {#convertToGroupShape--}
```
public final IGroupShape convertToGroupShape()
```


แปลง digram รุ่นเก่าให้เป็นกลุ่มรูปร่างที่แก้ไขได้. สร้างอ็อบเจ็กต์ GroupShape จะเพิ่มเข้าไปในกลุ่มรูปร่างแม่ที่ตำแหน่งเดียวกัน.

**คืนค่า:**
[IGroupShape](../../com.aspose.slides/igroupshape) - สร้างอ็อบเจ็กต์ GroupShape.