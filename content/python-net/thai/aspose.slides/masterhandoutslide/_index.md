---
title: MasterHandoutSlide class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/masterhandoutslide/
---
## MasterHandoutSlide คลาส

เป็นตัวแทนของสไลด์หลักสำหรับเอกสารจัดพิมพ์

**การสืบทอด:**[`MasterHandoutSlide`](/slides/python-net/th/aspose.slides/masterhandoutslide) → [`BaseSlide`](/slides/python-net/th/aspose.slides/baseslide)

ประเภท MasterHandoutSlide เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/th/aspose.slides/masterhandoutslide/shapes/) | คืนค่ารูปร่างของสไลด์.<br/>            อ่านอย่างเดียว [`IShapeCollection`](/slides/python-net/th/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/th/aspose.slides/masterhandoutslide/controls/) | คืนค่าคอลเลกชันของคอนโทรล ActiveX บนสไลด์.<br/>            อ่านอย่างเดียว [`IControlCollection`](/slides/python-net/th/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/th/aspose.slides/masterhandoutslide/name/) | คืนค่าหรือกำหนดชื่อของสไลด์.<br/>            อ่าน/เขียน **str**. |
| [`slide_id`](/slides/python-net/th/aspose.slides/masterhandoutslide/slide_id/) | คืนค่า ID ของสไลด์.<br/>            อ่านอย่างเดียว **int**. |
| [`custom_data`](/slides/python-net/th/aspose.slides/masterhandoutslide/custom_data/) | คืนค่าข้อมูลที่กำหนดเองของสไลด์.<br/>            อ่านอย่างเดียว [`ICustomData`](/slides/python-net/th/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/th/aspose.slides/masterhandoutslide/timeline/) | คืนค่าออบเจกต์ animation timeline.<br/>            อ่านอย่างเดียว [`IAnimationTimeLine`](/slides/python-net/th/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/th/aspose.slides/masterhandoutslide/slide_show_transition/) | คืนค่าออบเจกต์ Transition ที่บรรจุข้อมูลเกี่ยวกับ<br/>            วิธีที่สไลด์ที่กำหนดจะก้าวหน้าในการแสดงสไลด์.<br/>            อ่านอย่างเดียว [`ISlideShowTransition`](/slides/python-net/th/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/th/aspose.slides/masterhandoutslide/background/) | คืนค่าพื้นหลังของสไลด์.<br/>            อ่านอย่างเดียว [`IBackground`](/slides/python-net/th/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/th/aspose.slides/masterhandoutslide/hyperlink_queries/) | ให้การเข้าถึงลิงก์ภายในอย่างง่ายดาย.<br/>            อ่านอย่างเดียว [`IHyperlinkQueries`](/slides/python-net/th/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/th/aspose.slides/masterhandoutslide/show_master_shapes/) | ระบุว่ารูปร่างบน master slide ควรแสดงบนสไลด์หรือไม่.<br/>            สำหรับ master slide เอง property นี้จะคืนค่า `false` เสมอ.<br/>            อ่าน/เขียน **bool**. |
| [`presentation`](/slides/python-net/th/aspose.slides/masterhandoutslide/presentation/) | คืนค่าอินเทอร์เฟซ IPresentation.<br/>            อ่านอย่างเดียว [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/th/aspose.slides/masterhandoutslide/header_footer_manager/) | คืนค่า HeaderFooter manager ของ master handout slide.<br/>            อ่านอย่างเดียว [`IMasterHandoutSlideHeaderFooterManager`](/slides/python-net/th/aspose.slides/imasterhandoutslideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/th/aspose.slides/masterhandoutslide/theme_manager/) | คืนค่า theme manager.<br/>            อ่านอย่างเดียว [`IMasterThemeManager`](/slides/python-net/th/aspose.slides.theme/imasterthememanager). |
| [`drawing_guides`](/slides/python-net/th/aspose.slides/masterhandoutslide/drawing_guides/) | คืนค่าคอลเลกชันของ drawing guides สำหรับ master handout slide.<br/>            อ่านอย่างเดียว [`IDrawingGuidesCollection`](/slides/python-net/th/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/th/aspose.slides/masterhandoutslide/slide/) |  |

## เมธอด

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/th/aspose.slides/masterhandoutslide/join_portions_with_same_formatting/#) | รวม runs ที่มีการจัดรูปแบบเดียวกันในทุกพารากราฟและรูปทรงที่ยอมรับทั้งหมด. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/th/aspose.slides/masterhandoutslide/join_portions_with_same_formatting/#ishapecollection) | รวม runs ที่มีการจัดรูปแบบเดียวกันในทุกพารากราฟและรูปทรงที่ยอมรับทั้งหมด. |
| [`equals(self, slide)`](/slides/python-net/th/aspose.slides/masterhandoutslide/equals/#ibaseslide) | กำหนดว่าตัวอย่าง IBaseSlide สองตัวเท่ากันหรือไม่.<br/>            ค่าที่คืนคำนวณจากโครงสร้างสไลด์และเนื้อหาคงที่.<br/>            สไลด์สองสไลด์เท่ากันหากรูปทรง, สไตล์, ข้อความ, การเคลื่อนไหวและการตั้งค่าอื่น ๆ เป็นต้น มีค่าเท่ากัน. การเปรียบเทียบจะไม่พิจารณาค่าตัวระบุที่เป็นเอกลักษณ์ เช่น SlideId และเนื้อหาแบบไดนามิก เช่น ค่าวันที่ปัจจุบันใน Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/th/aspose.slides/masterhandoutslide/create_theme_effective/#) | คืนค่า theme ที่มีผลสำหรับสไลด์นี้. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/th/aspose.slides/masterhandoutslide/find_shape_by_alt_text/#str) | ค้นหาการปรากฏครั้งแรกของรูปร่างที่มีข้อความแทนที่ระบุ. |


### ดูเพิ่มเติม
* คลาส [`BaseSlide`](/slides/python-net/th/aspose.slides/baseslide)
* คลาส [`MasterHandoutSlide`](/slides/python-net/th/aspose.slides/masterhandoutslide)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)