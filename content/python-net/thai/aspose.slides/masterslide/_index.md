---
title: MasterSlide class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET – เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/masterslide/
---
## MasterSlide คลาส

Represents a master slide in a presentation.

**การสืบทอด:**[`MasterSlide`](/slides/python-net/th/aspose.slides/masterslide) → [`BaseSlide`](/slides/python-net/th/aspose.slides/baseslide)

The MasterSlide type exposes the following members:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`shapes`](/slides/python-net/th/aspose.slides/masterslide/shapes/) | ส่งคืนรูปร่างของสไลด์.<br/>            อ่านอย่างเดียว [`IShapeCollection`](/slides/python-net/th/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/th/aspose.slides/masterslide/controls/) | ส่งคืนคอลเลกชันของคอนโทรล ActiveX บนสไลด์.<br/>            อ่านอย่างเดียว [`IControlCollection`](/slides/python-net/th/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/th/aspose.slides/masterslide/name/) | ส่งคืนหรือกำหนดชื่อของสไลด์แม่.<br/>            อ่าน/เขียน **str**. |
| [`slide_id`](/slides/python-net/th/aspose.slides/masterslide/slide_id/) | ส่งคืน ID ของสไลด์.<br/>            อ่านอย่างเดียว **int**. |
| [`custom_data`](/slides/python-net/th/aspose.slides/masterslide/custom_data/) | ส่งคืนข้อมูลที่กำหนดเองของสไลด์.<br/>            อ่านอย่างเดียว [`ICustomData`](/slides/python-net/th/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/th/aspose.slides/masterslide/timeline/) | ส่งคืนออบเจ็กต์ไทม์ไลน์การเคลื่อนไหว.<br/>            อ่านอย่างเดียว [`IAnimationTimeLine`](/slides/python-net/th/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/th/aspose.slides/masterslide/slide_show_transition/) | ส่งคืนออบเจ็กต์ Transition ซึ่งมีข้อมูลเกี่ยวกับ<br/>            วิธีที่สไลด์ที่ระบุก้าวหน้าในระหว่างการแสดงสไลด์.<br/>            อ่านอย่างเดียว [`ISlideShowTransition`](/slides/python-net/th/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/th/aspose.slides/masterslide/background/) | ส่งคืนพื้นหลังของสไลด์.<br/>            อ่านอย่างเดียว [`IBackground`](/slides/python-net/th/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/th/aspose.slides/masterslide/hyperlink_queries/) | ให้การเข้าถึงไฮเปอร์ลิงก์ที่บรรจุอยู่ได้อย่างง่ายดาย.<br/>            อ่านอย่างเดียว [`IHyperlinkQueries`](/slides/python-net/th/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/th/aspose.slides/masterslide/show_master_shapes/) | ระบุว่ารูปร่างบนสไลด์แม่ควรแสดงบนสไลด์หรือไม่.<br/>            สำหรับสไลด์แม่เอง คุณสมบัตินี้จะคืนค่า `false` เสมอ.<br/>            อ่าน/เขียน **bool**. |
| [`presentation`](/slides/python-net/th/aspose.slides/masterslide/presentation/) | ส่งคืนอินเทอร์เฟซ IPresentation.<br/>            อ่านอย่างเดียว [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/th/aspose.slides/masterslide/header_footer_manager/) | ส่งคืนผู้จัดการ HeaderFooter ของสไลด์แม่.<br/>            อ่านอย่างเดียว [`IMasterSlideHeaderFooterManager`](/slides/python-net/th/aspose.slides/imasterslideheaderfootermanager). |
| [`title_style`](/slides/python-net/th/aspose.slides/masterslide/title_style/) | ส่งคืนสไตล์ของข้อความหัวเรื่อง.<br/>            อ่านอย่างเดียว [`ITextStyle`](/slides/python-net/th/aspose.slides/itextstyle). |
| [`body_style`](/slides/python-net/th/aspose.slides/masterslide/body_style/) | ส่งคืนสไตล์ของข้อความเนื้อหา.<br/>            อ่านอย่างเดียว [`ITextStyle`](/slides/python-net/th/aspose.slides/itextstyle). |
| [`other_style`](/slides/python-net/th/aspose.slides/masterslide/other_style/) | ส่งคืนสไตล์ของข้อความอื่น.<br/>            อ่านอย่างเดียว [`ITextStyle`](/slides/python-net/th/aspose.slides/itextstyle). |
| [`layout_slides`](/slides/python-net/th/aspose.slides/masterslide/layout_slides/) | ส่งคืนคอลเลกชันของสไลด์เลย์เอาต์ลูกสำหรับสไลด์แม่นี้.<br/>            อ่านอย่างเดียว [`IMasterLayoutSlideCollection`](/slides/python-net/th/aspose.slides/imasterlayoutslidecollection). |
| [`preserve`](/slides/python-net/th/aspose.slides/masterslide/preserve/) | กำหนดว่ามาสเตอร์ที่สอดคล้องจะถูกลบหรือไม่เมื่อสไลด์ทั้งหมดที่ตามมาหลังจากมาสเตอร์นั้นถูกลบ.<br/>            หมายเหตุ: Aspose.Slides จะไม่ลบมาสเตอร์ที่ไม่ได้ใช้ใดๆ ด้วยตนเอง เพื่อที่จะลบมาสเตอร์ที่ไม่ได้ใช้จริงๆ ให้เรียก **Aspose.Slides.MasterSlideCollection.RemoveUnused(Syste**<br/>            อ่าน/เขียน **bool**. |
| [`has_depending_slides`](/slides/python-net/th/aspose.slides/masterslide/has_depending_slides/) | ส่งคืนค่า true หากมีสไลด์อย่างน้อยหนึ่งสไลด์ที่ขึ้นอยู่กับสไลด์แม่นี้.<br/>            อ่านอย่างเดียว **bool**. |
| [`theme_manager`](/slides/python-net/th/aspose.slides/masterslide/theme_manager/) | ส่งคืนผู้จัดการธีม.<br/>            อ่านอย่างเดียว [`IMasterThemeManager`](/slides/python-net/th/aspose.slides.theme/imasterthememanager). |
| [`drawing_guides`](/slides/python-net/th/aspose.slides/masterslide/drawing_guides/) | ส่งคืนคอลเลกชันของไกด์การวาดสำหรับสไลด์แม่.<br/>            อ่านอย่างเดียว [`IDrawingGuidesCollection`](/slides/python-net/th/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/th/aspose.slides/masterslide/slide/) |  |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/th/aspose.slides/masterslide/join_portions_with_same_formatting/#) | รวม run ที่มีการจัดรูปแบบเดียวกันในทุกย่อหน้าในรูปทรงที่ยอมรับทั้งหมด. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/th/aspose.slides/masterslide/join_portions_with_same_formatting/#ishapecollection) | รวม run ที่มีการจัดรูปแบบเดียวกันในทุกย่อหน้าในรูปทรงที่ยอมรับทั้งหมด. |
| [`equals(self, slide)`](/slides/python-net/th/aspose.slides/masterslide/equals/#ibaseslide) | กำหนดว่าตัวอย่าง IBaseSlide สองตัวเท่ากันหรือไม่.<br/>            ค่าที่คืนจะคำนวณจากโครงสร้างของสไลด์และเนื้อหาคงที่.<br/>            สองสไลด์เท่ากันหากรูปร่าง, สไตล์, ข้อความ, การเคลื่อนไหวและการตั้งค่าอื่นๆ เป็นต้น เท่ากันทั้งหมด.<br/>            การเปรียบเทียบจะไม่พิจารณาค่าตัวระบุที่เป็นเอกลักษณ์ เช่น SlideId และเนื้อหาไดนามิก เช่น ค่าจากวันที่ปัจจุบันใน Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/th/aspose.slides/masterslide/create_theme_effective/#) | ส่งคืนธีมที่มีผลสำหรับสไลด์นี้. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/th/aspose.slides/masterslide/find_shape_by_alt_text/#str) | ค้นหาการพบครั้งแรกของรูปทรงที่มีข้อความแทนที่ระบุ. |
| [`apply_external_theme_to_depending_slides(self, fname)`](/slides/python-net/th/aspose.slides/masterslide/apply_external_theme_to_depending_slides/#str) | สร้างสไลด์แม่ใหม่จากสไลด์ปัจจุบันโดยนำธีมภายนอกมาใช้กับมัน<br/>            และนำสไลด์แม่ที่สร้างไปใช้กับสไลด์ที่ขึ้นอยู่ทั้งหมด. |
| [`get_depending_slides(self)`](/slides/python-net/th/aspose.slides/masterslide/get_depending_slides/#) | ส่งคืนอาเรย์ที่มีสไลด์ทั้งหมดที่ขึ้นอยู่กับสไลด์แม่นี้. |

### ดูเพิ่มเติม
* คลาส [`BaseSlide`](/slides/python-net/th/aspose.slides/baseslide)
* คลาส [`MasterSlide`](/slides/python-net/th/aspose.slides/masterslide)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)