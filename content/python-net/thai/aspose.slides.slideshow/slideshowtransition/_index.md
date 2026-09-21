---
title: SlideShowTransition class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.slideshow/slideshowtransition/
---
## SlideShowTransition คลาส

เป็นตัวแทนของการเปลี่ยนสไลด์โชว์

ประเภท SlideShowTransition เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`sound`](/slides/python-net/th/aspose.slides.slideshow/slideshowtransition/sound/) | คืนค่า หรือกำหนดข้อมูลเสียงฝังอยู่.<br/>            อ่าน/เขียน [`IAudio`](/slides/python-net/th/aspose.slides/iaudio). |
| [`sound_mode`](/slides/python-net/th/aspose.slides.slideshow/slideshowtransition/sound_mode/) | กำหนดหรือคืนค่าโหมดเสียงสำหรับการเปลี่ยนสไลด์.<br/>            อ่าน/เขียน [`TransitionSoundMode`](/slides/python-net/th/aspose.slides.slideshow/transitionsoundmode). |
| [`sound_loop`](/slides/python-net/th/aspose.slides.slideshow/slideshowtransition/sound_loop/) | แอตทริบิวต์นี้ระบุว่ามีการวนซ้ำเสียงจนกว่าจะเกิดเหตุการณ์เสียงถัดไปใน<br/>            สไลด์โชว์.<br/>            อ่าน/เขียน **bool**. |
| [`advance_on_click`](/slides/python-net/th/aspose.slides.slideshow/slideshowtransition/advance_on_click/) | ระบุว่าการคลิกเมาส์จะทำให้สไลด์เลื่อนต่อหรือไม่ หากแอตทริบิวต์นี้ไม่ได้<br/>            ระบุจะถือว่ามีค่าจริงโดยค่าเริ่มต้น.<br/>            อ่าน/เขียน **bool**. |
| [`advance_after`](/slides/python-net/th/aspose.slides.slideshow/slideshowtransition/advance_after/) | แอตทริบิวต์นี้ระบุว่าการแสดงสไลด์จะย้ายไปสไลด์ถัดไปหลังจากเวลาที่กำหนดหรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`advance_after_time`](/slides/python-net/th/aspose.slides.slideshow/slideshowtransition/advance_after_time/) | ระบุเวลาเป็นมิลลิวินาทีที่การเปลี่ยนควรเริ่มต้น การตั้งค่านี้<br/>            สามารถใช้ร่วมกับแอตทริบิวต์ advClick หากแอตทริบิวต์นี้ไม่ได้ระบุ<br/>            จะถือว่าไม่มีการเลื่อนไปอัตโนมัติ.<br/>            อ่าน/เขียน **int**. |
| [`speed`](/slides/python-net/th/aspose.slides.slideshow/slideshowtransition/speed/) | ระบุความเร็วของการเปลี่ยนที่จะใช้เมื่อต้องเปลี่ยนจากสไลด์ปัจจุบัน<br/>            ไปสไลด์ถัดไป.<br/>            อ่าน/เขียน [`TransitionSpeed`](/slides/python-net/th/aspose.slides.slideshow/transitionspeed). |
| [`value`](/slides/python-net/th/aspose.slides.slideshow/slideshowtransition/value/) | ค่าการเปลี่ยนสไลด์โชว์.<br/>            อ่านอย่างเดียว [`ITransitionValueBase`](/slides/python-net/th/aspose.slides.slideshow/itransitionvaluebase). |
| [`type`](/slides/python-net/th/aspose.slides.slideshow/slideshowtransition/type/) | ประเภทของการเปลี่ยน.<br/>            อ่าน/เขียน [`TransitionType`](/slides/python-net/th/aspose.slides.slideshow/transitiontype). |
| [`sound_is_built_in`](/slides/python-net/th/aspose.slides.slideshow/slideshowtransition/sound_is_built_in/) | ระบุว่าเสียงนี้เป็นเสียงที่มีมาในระบบหรือไม่ หากแอตทริบิวต์นี้ตั้งค่าเป็นจริง<br/>            แอปพลิเคชันที่สร้างจะได้รับการแจ้งให้ตรวจสอบแอตทริบิวต์ชื่อที่ระบุสำหรับเสียงนี้<br/>            ในรายการเสียงที่มีมาในระบบและสามารถแสดงชื่อหรือ UI ที่กำหนดเองตามต้องการ.<br/>            อ่าน/เขียน **bool**. |
| [`sound_name`](/slides/python-net/th/aspose.slides.slideshow/slideshowtransition/sound_name/) | ระบุชื่อที่อ่านเข้าใจได้สำหรับเสียงของการเปลี่ยน แอตทริบิวต์ [`SlideShowTransition.sound`](/slides/python-net/th/aspose.slides.slideshow/slideshowtransition/sound) จะต้องถูกกำหนดเพื่อรับหรือกำหนดชื่อเสียง.<br/>            อ่าน/เขียน **str**. |
| [`duration`](/slides/python-net/th/aspose.slides.slideshow/slideshowtransition/duration/) | รับหรือกำหนดระยะเวลาของเอฟเฟ็กต์การเปลี่ยนสไลด์ในหน่วยมิลลิวินาที.<br/>            อ่าน/เขียน **int**. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides.slideshow`](/slides/python-net/th/aspose.slides.slideshow)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)