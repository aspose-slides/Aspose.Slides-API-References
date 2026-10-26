---
title: IRotation3D class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides.charts/irotation3d/
---
## IRotation3D คลาส

แสดงการหมุน 3 มิติของแผนภูมิ

ชนิด IRotation3D แสดงสมาชิกต่อไปนี้:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`rotation_x`](/slides/python-net/th/aspose.slides.charts/irotation3d/rotation_x/) | คืนค่า หรือกำหนดองศาการหมุนรอบแกน X, หรือในทิศทาง Y สำหรับแผนภูมิ 3 มิติ (ระหว่าง -90 ถึง 90 องศา).<br/>            คุณสมบัตินี้สอดคล้องกับรายการ 21.2.2.157 rotX (X Rotation) ใน ECMA-376 และกับตัวเลือก "Y Rotation" ใน PowerPoint 2007+.<br/>            อ่าน/เขียน **int**. |
| [`rotation_y`](/slides/python-net/th/aspose.slides.charts/irotation3d/rotation_y/) | คืนค่า หรือกำหนดองศาการหมุนรอบแกน Y, หรือในทิศทาง X สำหรับแผนภูมิ 3 มิติ (ระหว่าง 0 ถึง 360 องศา).<br/>            คุณสมบัตินี้สอดคล้องกับรายการ 21.2.2.158 rotY (Y Rotation) ใน ECMA-376 และกับตัวเลือก "X Rotation" ใน PowerPoint 2007+.<br/>            อ่าน/เขียน **int**. |
| [`perspective`](/slides/python-net/th/aspose.slides.charts/irotation3d/perspective/) | คืนค่า หรือกำหนดค่ามุมมอง (field of view angle) สำหรับแผนภูมิ 3 มิติ (ระหว่าง 0 ถึง 100).<br/>            จะถูกละเว้นหากค่าคุณสมบัติ RightAngleAxes เป็น true.<br/>            อ่าน/เขียน **int**. |
| [`right_angle_axes`](/slides/python-net/th/aspose.slides.charts/irotation3d/right_angle_axes/) | กำหนดว่าแกนของแผนภูมิเป็นมุมฉากหรือไม่, แทนที่จะวาดในมุมมองเชิงลึก.<br/>            อีกอย่างหนึ่ง มันกำหนดว่ามุมแกนของแผนภูมิเป็นอิสระจากการ <br/>            หมุนหรือการยกของแผนภูมิ.<br/>            อ่าน/เขียน **bool**. |
| [`depth_percents`](/slides/python-net/th/aspose.slides.charts/irotation3d/depth_percents/) | คืนค่า หรือกำหนดความลึกของแผนภูมิ 3 มิติเป็นเปอร์เซ็นต์ของความกว้างของแผนภูมิ (ระหว่าง 20 ถึง 2000 เปอร์เซ็นต์).<br/>            อ่าน/เขียน **int**. |
| [`height_percents`](/slides/python-net/th/aspose.slides.charts/irotation3d/height_percents/) | ระบุความสูงของแผนภูมิ 3-D เป็นเปอร์เซ็นต์ของความกว้างของแผนภูมิ (ระหว่าง 5 ถึง 500 เปอร์เซ็นต์).<br/>            อ่าน/เขียน **int**. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)