---
title: ISlideShowTransition class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/islideshowtransition/
---
## คลาส ISlideShowTransition

Represents slide show transition.

The ISlideShowTransition type exposes the following members:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`sound`](/slides/python-net/th/aspose.slides/islideshowtransition/sound/) | คืนค่า หรือ ตั้งค่าข้อมูลเสียงแบบฝังในตัว.<br/>            อ่าน-เขียน [`IAudio`](/slides/python-net/th/aspose.slides/iaudio). |
| [`sound_mode`](/slides/python-net/th/aspose.slides/islideshowtransition/sound_mode/) | ตั้งค่าหรือคืนค่าโหมดเสียงสำหรับการเปลี่ยนสไลด์.<br/>            อ่าน-เขียน [`TransitionSoundMode`](/slides/python-net/th/aspose.slides.slideshow/transitionsoundmode). |
| [`sound_loop`](/slides/python-net/th/aspose.slides/islideshowtransition/sound_loop/) | คุณลักษณะนี้ระบุว่าเสียงจะวนซ้ำจนกว่าจะเกิดเหตุการณ์เสียงถัดไปใน<br/>            การแสดงสไลด์.<br/>            อ่าน-เขียน **bool**. |
| [`advance_on_click`](/slides/python-net/th/aspose.slides/islideshowtransition/advance_on_click/) | ระบุว่าการคลิกเมาส์จะทำให้สไลด์เลื่อนไปข้างหน้าหรือไม่. หากคุณลักษณะนี้ไม่ได้<br/>            ระบุ จะถือว่ามีค่าเป็น true.<br/>            อ่าน-เขียน **bool**. |
| [`advance_after`](/slides/python-net/th/aspose.slides/islideshowtransition/advance_after/) | คุณลักษณะนี้ระบุว่าการแสดงสไลด์จะเคลื่อนไปสไลด์ถัดไปหลังจากเวลาที่กำหนดหรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`advance_after_time`](/slides/python-net/th/aspose.slides/islideshowtransition/advance_after_time/) | ระบุเวลาเป็นมิลลิวินาทีหลังจากนั้นการเปลี่ยนสไลด์ควรเริ่มต้น. การตั้งค่านี้<br/>            สามารถใช้ร่วมกับคุณลักษณะ advClick. หากคุณลักษณะนี้ไม่ได้ระบุ<br/>            จะถือว่าการเลื่อนอัตโนมัติจะไม่เกิดขึ้น.<br/>            อ่าน-เขียน **int**. |
| [`speed`](/slides/python-net/th/aspose.slides/islideshowtransition/speed/) | ระบุความเร็วของการเปลี่ยนสไลด์ที่จะใช้เมื่อเปลี่ยนจากสไลด์ปัจจุบัน<br/>            ไปยังสไลด์ถัดไป.<br/>            อ่าน-เขียน [`TransitionSpeed`](/slides/python-net/th/aspose.slides.slideshow/transitionspeed). |
| [`value`](/slides/python-net/th/aspose.slides/islideshowtransition/value/) | ค่าการเปลี่ยนสไลด์โชว์.<br/>            อ่านอย่างเดียว [`ITransitionValueBase`](/slides/python-net/th/aspose.slides.slideshow/itransitionvaluebase). |
| [`type`](/slides/python-net/th/aspose.slides/islideshowtransition/type/) | ประเภทของการเปลี่ยนสไลด์.<br/>            อ่าน-เขียน [`TransitionType`](/slides/python-net/th/aspose.slides.slideshow/transitiontype). |
| [`sound_is_built_in`](/slides/python-net/th/aspose.slides/islideshowtransition/sound_is_built_in/) | ระบุว่าเสียงนี้เป็นเสียงที่มีอยู่ในระบบหรือไม่. หากคุณลักษณะนี้ตั้งค่าเป็น true แล้ว<br/>            แอปพลิเคชันที่สร้างจะได้รับการแจ้งให้ตรวจสอบคุณลักษณะ name ที่ระบุสำหรับเสียงนี้<br/>            ในรายการเสียงที่มีอยู่ในระบบและสามารถแสดงชื่อหรือ UI ที่กำหนดเองได้ตามต้องการ.<br/>            อ่าน-เขียน **bool**. |
| [`sound_name`](/slides/python-net/th/aspose.slides/islideshowtransition/sound_name/) | ระบุชื่อที่อ่านได้โดยมนุษย์สำหรับเสียงของการเปลี่ยนสไลด์. คุณลักษณะ [`ISlideShowTransition.sound`](/slides/python-net/th/aspose.slides/islideshowtransition/sound) ต้องถูกกำหนดเพื่อรับหรือกำหนดชื่อเสียง.<br/>            อ่าน-เขียน **str**. |
| [`duration`](/slides/python-net/th/aspose.slides/islideshowtransition/duration/) | รับหรือกำหนดระยะเวลาของเอฟเฟกต์การเปลี่ยนสไลด์เป็นมิลลิวินาที.<br/>            อ่าน/เขียน **int**. |


### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)