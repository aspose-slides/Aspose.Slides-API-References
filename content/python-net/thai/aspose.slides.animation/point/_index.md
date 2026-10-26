---
title: Point class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.animation/point/
---
## Point คลาส

แสดงจุดแอนิเมชัน

ประเภท Point เปิดเผยสมาชิกต่อไปนี้:

## ตัวสร้าง

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/th/aspose.slides.animation/point/__init__/#) | คอนสตรัคเตอร์เริ่มต้น |
| [`__init__(self, time, value, formula)`](/slides/python-net/th/aspose.slides.animation/point/__init__/#float-any-str) | สร้างจุดแอนิเมชันด้วยเวลา, ค่า และสูตร |

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`time`](/slides/python-net/th/aspose.slides.animation/point/time/) | แทนค่าระยะเวลา.<br/>            อ่าน/เขียน **float**. |
| [`value`](/slides/python-net/th/aspose.slides.animation/point/value/) | แทนค่าจุด.<br/>            เฉพาะ: bool, ColorFormat, float, int, string.<br/>            อ่าน/เขียน **any**. |
| [`formula`](/slides/python-net/th/aspose.slides.animation/point/formula/) | สูตรภายในค่า, แอตทริบิวต์ from, to, by สามารถประกอบด้วยสิ่งต่อไปนี้:<br/>            ตัวดำเนินการคณิตศาสตร์มาตรฐาน: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)<br/>            ค่าคงที่: ‘pi’ ‘e’<br/>            ตัวดำเนินการเชิงเงื่อนไข: ‘abs’, ‘min’, ‘max’, ‘?’ (if)<br/>            ตัวดำเนินการเปรียบเทียบ: '==', '>=', '', '!=', '!'<br/>            ตัวดำเนินการตรีโกณมิติ: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’<br/>            ลอการิทึมธรรมชาติ ‘ln()’<br/>            การอ้างอิงคุณสมบัติ (คุณสมบัติที่โฮสต์สนับสนุน)<br/>            <br/>            for example: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"<br/>            อ่าน/เขียน **str**. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides.animation`](/slides/python-net/th/aspose.slides.animation)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)