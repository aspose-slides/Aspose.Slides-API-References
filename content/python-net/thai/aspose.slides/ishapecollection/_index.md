---
title: IShapeCollection class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/ishapecollection/
---
## IShapeCollection คลาส

เป็นตัวแทนของคอลเลกชันของรูปร่าง

ประเภท IShapeCollection เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`parent_group`](/slides/python-net/th/aspose.slides/ishapecollection/parent_group/) | รับอ็อบเจ็กต์กลุ่มรูปร่างแม่สำหรับคอลเลกชันของรูปทรง.<br/>            อ่านอย่างเดียว [`IGroupShape`](/slides/python-net/th/aspose.slides/igroupshape). |
|  | รับอีลีเมนต์ที่ดัชนีที่ระบุ.<br/>            อ่านอย่างเดียว [`IShape`](/slides/python-net/th/aspose.slides/ishape). |

## ตัวชี้ดัชนี

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/th/aspose.slides/ishapecollection/__getitem__/) |  |

## วิธีการ

| Method | Description |
| :- | :- |
| [`add_chart(self, type, x, y, width, height)`](/slides/python-net/th/aspose.slides/ishapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float) | สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลซีรีส์ตัวอย่างและการตั้งค่า, และเพิ่ม<br/>            ไปยังตำแหน่งสุดท้ายของคอลเลกชันของรูปร่าง. |
| [`add_chart(self, type, x, y, width, height, init_with_sample)`](/slides/python-net/th/aspose.slides/ishapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float-bool) | สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลซีรีส์ตัวอย่างและการตั้งค่า, และเพิ่ม<br/>            ไปยังตำแหน่งสุดท้ายของคอลเลกชันของรูปร่าง. |
| [`insert_chart(self, type, x, y, width, height, index)`](/slides/python-net/th/aspose.slides/ishapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int) | สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลซีรีส์ตัวอย่างและการตั้งค่า,<br/>            และแทรกเข้ากลุ่มรูปร่างที่ดัชนีที่ระบุ. |
| [`insert_chart(self, type, x, y, width, height, index, init_with_sample)`](/slides/python-net/th/aspose.slides/ishapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int-bool) | สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลซีรีส์ตัวอย่างและการตั้งค่า,<br/>            และแทรกเข้ากลุ่มรูปร่างที่ดัชนีที่ระบุ. |
| [`add_ole_object_frame(self, x, y, width, height, data_info)`](/slides/python-net/th/aspose.slides/ishapecollection/add_ole_object_frame/#float-float-float-float-ioleembeddeddatainfo) | สร้างเฟรมวัตถุ OLE ใหม่และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันของรูปร่าง. |
| [`add_ole_object_frame(self, x, y, width, height, class_name, path)`](/slides/python-net/th/aspose.slides/ishapecollection/add_ole_object_frame/#float-float-float-float-str-str) | สร้างเฟรมวัตถุ OLE ใหม่และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันของรูปร่าง. |
| [`insert_ole_object_frame(self, index, x, y, width, height, data_info)`](/slides/python-net/th/aspose.slides/ishapecollection/insert_ole_object_frame/#int-float-float-float-float-ioleembeddeddatainfo) | สร้างเฟรมวัตถุ OLE ใหม่และแทรกเข้ากลุ่มรูปร่างที่ดัชนีที่ระบุ. |
| [`insert_ole_object_frame(self, index, x, y, width, height, class_name, path)`](/slides/python-net/th/aspose.slides/ishapecollection/insert_ole_object_frame/#int-float-float-float-float-str-str) | สร้างเฟรมวัตถุ OLE ใหม่และแทรกเข้ากลุ่มรูปร่างที่ดัชนีที่ระบุ. |
| [`add_zoom_frame(self, x, y, width, height, slide)`](/slides/python-net/th/aspose.slides/ishapecollection/add_zoom_frame/#float-float-float-float-islide) | สร้างเฟรม Zoom ใหม่และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันของรูปร่าง. |
| [`add_zoom_frame(self, x, y, width, height, slide, image)`](/slides/python-net/th/aspose.slides/ishapecollection/add_zoom_frame/#float-float-float-float-islide-ippimage) | สร้างเฟรม Zoom ใหม่และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันของรูปร่าง. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide)`](/slides/python-net/th/aspose.slides/ishapecollection/insert_zoom_frame/#int-float-float-float-float-islide) | สร้างเฟรม Zoom ใหม่และแทรกเข้ากลุ่มรูปร่างที่ดัชนีที่ระบุ. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide, image)`](/slides/python-net/th/aspose.slides/ishapecollection/insert_zoom_frame/#int-float-float-float-float-islide-ippimage) | สร้างเฟรม Zoom ใหม่พร้อมภาพที่กำหนดล่วงหน้าและแทรกเข้ากลุ่มรูปร่าง<br/>            ที่ดัชนีที่ระบุ. |
| [`add_section_zoom_frame(self, x, y, width, height, section)`](/slides/python-net/th/aspose.slides/ishapecollection/add_section_zoom_frame/#float-float-float-float-isection) | สร้างเฟรม Section Zoom ใหม่และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันของรูปร่าง. |
| [`add_section_zoom_frame(self, x, y, width, height, section, image)`](/slides/python-net/th/aspose.slides/ishapecollection/add_section_zoom_frame/#float-float-float-float-isection-ippimage) | สร้างเฟรม Section Zoom ใหม่พร้อมภาพที่กำหนดล่วงหน้าและเพิ่มไปยังตำแหน่งสุดท้ายของ<br/>            คอลเลกชันของรูปร่าง. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section)`](/slides/python-net/th/aspose.slides/ishapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection) | สร้างเฟรม Section Zoom ใหม่และแทรกเข้ากลุ่มรูปร่างที่ดัชนีที่<br/>            ระบุ. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section, image)`](/slides/python-net/th/aspose.slides/ishapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection-ippimage) | สร้างเฟรม Section Zoom ใหม่พร้อมภาพที่กำหนดล่วงหน้าและแทรกเข้ากลุ่มรูปร่าง<br/>            ที่ดัชนีที่ระบุ. |
| [`add_video_frame(self, x, y, width, height, fname)`](/slides/python-net/th/aspose.slides/ishapecollection/add_video_frame/#float-float-float-float-str) | สร้างเฟรมวิดีโอใหม่และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันของรูปร่าง. |
| [`add_video_frame(self, x, y, width, height, video)`](/slides/python-net/th/aspose.slides/ishapecollection/add_video_frame/#float-float-float-float-ivideo) | สร้างเฟรมวิดีโอใหม่และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันของรูปร่าง. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio_stream)`](/slides/python-net/th/aspose.slides/ishapecollection/add_audio_frame_embedded/#float-float-float-float-iorawiobase) | สร้างเฟรมเสียงใหม่พร้อมไฟล์ WAV ที่ฝังอยู่และเพิ่มไปยังตำแหน่งสุดท้ายของ<br/>            คอลเลกชันของรูปร่าง. เสียงที่ฝังอยู่จะถูกเพิ่มไปยัง Presentation.Audios collection. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio)`](/slides/python-net/th/aspose.slides/ishapecollection/add_audio_frame_embedded/#float-float-float-float-iaudio) | สร้างเฟรมเสียงใหม่และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันของรูปร่างโดยใช้<br/>            อ็อบเจ็กต์เสียงที่มีอยู่จากรายการ Presentation.Audios. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream)`](/slides/python-net/th/aspose.slides/ishapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iorawiobase) | สร้างเฟรมเสียงใหม่พร้อมไฟล์ WAV ที่ฝังอยู่และแทรกเข้ากลุ่มรูปร่างที่ดัชนีที่ระบุ. เสียงที่ฝังอยู่จะถูกเพิ่มไปยัง Presentation.Audios<br/>            collection. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio)`](/slides/python-net/th/aspose.slides/ishapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iaudio) | สร้างเฟรมเสียงใหม่และแทรกเข้ากลุ่มรูปร่างที่ดัชนีที่ระบุ<br/>            โดยใช้อ็อบเจ็กต์เสียงที่มีอยู่จากรายการ Presentation.Audios. |
| [`to_array(self)`](/slides/python-net/th/aspose.slides/ishapecollection/to_array/#) | สร้างและคืนค่าอาร์เรย์ที่ประกอบด้วยรูปร่างทั้งหมด. |
| [`to_array(self, start_index, count)`](/slides/python-net/th/aspose.slides/ishapecollection/to_array/#int-int) | สร้างและคืนค่าอาร์เรย์ที่ประกอบด้วยรูปร่างทั้งหมดในช่วงที่ระบุ. |
| [`reorder(self, index, shape)`](/slides/python-net/th/aspose.slides/ishapecollection/reorder/#int-ishape) | ย้ายรูปร่างที่ระบุไปยังตำแหน่งใหม่ภายในคอลเลกชันของรูปร่าง. |
| [`reorder(self, index, shapes)`](/slides/python-net/th/aspose.slides/ishapecollection/reorder/#int-listishape) | ย้ายรูปร่างที่ระบุภายในคอลเลกชันของรูปร่างโดยเริ่มวางที่ดัชนีที่ระบุ. |
| [`add_auto_shape(self, shape_type, x, y, width, height)`](/slides/python-net/th/aspose.slides/ishapecollection/add_auto_shape/#shapetype-float-float-float-float) | สร้างรูปอัตโนมัติใหม่ด้วยการจัดรูปแบบเริ่มต้นและเพิ่มไปยังตำแหน่งสุดท้ายของ<br/>            คอลเลกชันของรูปร่าง. |
| [`add_auto_shape(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/th/aspose.slides/ishapecollection/add_auto_shape/#shapetype-float-float-float-float-bool) | สร้างรูปอัตโนมัติใหม่และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันของรูปร่าง, โดยอาจ<br/>            เริ่มต้นด้วยการจัดรูปแบบเทมเพลตเริ่มต้น. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height)`](/slides/python-net/th/aspose.slides/ishapecollection/insert_auto_shape/#int-shapetype-float-float-float-float) | สร้างรูปอัตโนมัติใหม่และแทรกเข้ากลุ่มรูปร่างที่ดัชนีที่ระบุ,<br/>            โดยใช้การจัดรูปแบบเทมเพลตเริ่มต้น. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/th/aspose.slides/ishapecollection/insert_auto_shape/#int-shapetype-float-float-float-float-bool) | สร้างรูปอัตโนมัติใหม่และแทรกเข้ากลุ่มรูปร่างที่ดัชนีที่ระบุ,<br/>            โดยอาจเริ่มต้นด้วยสไตล์เทมเพลตเริ่มต้น. |
| [`add_group_shape(self)`](/slides/python-net/th/aspose.slides/ishapecollection/add_group_shape/#) | สร้างกลุ่มรูปร่างเปล่าใหม่และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันของรูปร่าง.<br/>            กรอบของกลุ่มจะปรับอัตโนมัติเพื่อให้พอดีกับรูปทรงใด ๆ ที่เพิ่มเข้าไป. |
| [`add_group_shape(self, svg_image, x, y, width, height)`](/slides/python-net/th/aspose.slides/ishapecollection/add_group_shape/#isvgimage-float-float-float-float) | สร้างกลุ่มรูปร่างใหม่, แปลงภาพ SVG ที่ระบุเป็นรูปร่างเดี่ยว ๆ,<br/>            และเพิ่มกลุ่มที่ได้ไปยังตำแหน่งสุดท้ายของคอลเลกชันของรูปร่าง. |
| [`add_connector(self, shape_type, x, y, width, height)`](/slides/python-net/th/aspose.slides/ishapecollection/add_connector/#shapetype-float-float-float-float) | สร้างรูปเชื่อมต่อใหม่ด้วยสไตล์เทมเพลตเริ่มต้นและเพิ่มไปยังตำแหน่งสุดท้ายของ<br/>            คอลเลกชันของรูปร่าง. |
| [`add_connector(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/th/aspose.slides/ishapecollection/add_connector/#shapetype-float-float-float-float-bool) | สร้างรูปเชื่อมต่อใหม่และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันของรูปร่าง,<br/>            โดยอาจใช้สไตล์เทมเพลตเริ่มต้น. |
| [`insert_connector(self, index, shape_type, x, y, width, height)`](/slides/python-net/th/aspose.slides/ishapecollection/insert_connector/#int-shapetype-float-float-float-float) | สร้างรูปเชื่อมต่อใหม่และแทรกเข้ากลุ่มรูปร่างที่ดัชนีที่ระบุ,<br/>            โดยใช้สไตล์เทมเพลตเริ่มต้น. |
| [`insert_connector(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/th/aspose.slides/ishapecollection/insert_connector/#int-shapetype-float-float-float-float-bool) | สร้างรูปเชื่อมต่อใหม่และแทรกเข้ากลุ่มรูปร่างที่ดัชนีที่ระบุ,<br/>            โดยอาจใช้สไตล์เทมเพลตเริ่มต้น. |
| [`add_clone(self, source_shape, x, y, width, height)`](/slides/python-net/th/aspose.slides/ishapecollection/add_clone/#ishape-float-float-float-float) | สร้างสำเนาของรูปทร่างที่ระบุและเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันของรูปร่าง. |
| [`add_clone(self, source_shape, x, y)`](/slides/python-net/th/aspose.slides/ishapecollection/add_clone/#ishape-float-float) | สร้างสำเนาของรูปทร่างที่ระบุและเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันของรูปร่าง.<br/>            รูปร่างใหม่คงความกว้างและความสูงของ `source_shape`. |
| [`add_clone(self, source_shape)`](/slides/python-net/th/aspose.slides/ishapecollection/add_clone/#ishape) | สร้างสำเนาของรูปทร่างที่ระบุและเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันของรูปร่าง.<br/>            รูปร่างที่คัดลอกคงตำแหน่งและขนาดของต้นฉบับ. |
| [`insert_clone(self, index, source_shape, x, y, width, height)`](/slides/python-net/th/aspose.slides/ishapecollection/insert_clone/#int-ishape-float-float-float-float) | สร้างสำเนาของรูปทร่างที่ระบุและแทรกเข้ากลุ่มรูปร่างที่ดัชนีที่ระบุ. |
| [`insert_clone(self, index, source_shape, x, y)`](/slides/python-net/th/aspose.slides/ishapecollection/insert_clone/#int-ishape-float-float) | สร้างสำเนาของรูปทร่างที่ระบุและแทรกเข้ากลุ่มรูปร่างที่ดัชนีที่ระบุ.<br/>            รูปร่างใหม่คงความกว้างและความสูงของ `source_shape`. |
| [`insert_clone(self, index, source_shape)`](/slides/python-net/th/aspose.slides/ishapecollection/insert_clone/#int-ishape) | สร้างสำเนาของรูปทร่างที่ระบุและแทรกเข้ากลุ่มรูปร่างที่ดัชนีที่ระบุ.<br/>            รูปร่างที่คัดลอกคงตำแหน่งและขนาดของต้นฉบับ. |
| [`add_smart_art(self, x, y, width, height, layout_type)`](/slides/python-net/th/aspose.slides/ishapecollection/add_smart_art/#float-float-float-float-asposeslidessmartartsmartartlayouttype) | สร้างไดอะแกรม SmartArt และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันของรูปร่าง. |
| [`add_summary_zoom_frame(self, x, y, width, height)`](/slides/python-net/th/aspose.slides/ishapecollection/add_summary_zoom_frame/#float-float-float-float) | สร้างเฟรม Summary Zoom ใหม่และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันของรูปร่าง. |
| [`insert_summary_zoom_frame(self, index, x, y, width, height)`](/slides/python-net/th/aspose.slides/ishapecollection/insert_summary_zoom_frame/#int-float-float-float-float) | สร้างเฟรม Summary Zoom ใหม่และแทรกเข้ากลุ่มรูปร่างที่ดัชนีที่ระบุ. |
| [`insert_video_frame(self, index, x, y, width, height, fname)`](/slides/python-net/th/aspose.slides/ishapecollection/insert_video_frame/#int-float-float-float-float-str) | สร้างเฟรมวิดีโอใหม่และแทรกเข้ากลุ่มรูปร่างที่ดัชนีที่ระบุ. |
| [`add_audio_frame_cd(self, x, y, width, height)`](/slides/python-net/th/aspose.slides/ishapecollection/add_audio_frame_cd/#float-float-float-float) | สร้างเฟรมเสียงใหม่ที่เชื่อมโยงกับแทร็ก CD และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันของรูปร่าง. |
| [`insert_audio_frame_cd(self, index, x, y, width, height)`](/slides/python-net/th/aspose.slides/ishapecollection/insert_audio_frame_cd/#int-float-float-float-float) | สร้างเฟรมเสียงใหม่ที่เชื่อมโยงกับแทร็ก CD และแทรกเข้ากลุ่มรูปร่าง<br/>            ที่ดัชนีที่ระบุ. |
| [`add_audio_frame_linked(self, x, y, width, height, fname)`](/slides/python-net/th/aspose.slides/ishapecollection/add_audio_frame_linked/#float-float-float-float-str) | สร้างเฟรมเสียงใหม่ที่เชื่อมโยงกับไฟล์เสียงภายนอกและเพิ่มไปยังตำแหน่งสุดท้ายของ<br/>            คอลเลกชันของรูปร่าง. |
| [`insert_audio_frame_linked(self, index, x, y, width, height, fname)`](/slides/python-net/th/aspose.slides/ishapecollection/insert_audio_frame_linked/#int-float-float-float-float-str) | สร้างเฟรมเสียงใหม่ที่เชื่อมโยงกับไฟล์เสียงภายนอกและแทรกเข้ากลุ่มรูปร่าง<br/>            ที่ดัชนีที่ระบุ. |
| [`index_of(self, shape)`](/slides/python-net/th/aspose.slides/ishapecollection/index_of/#ishape) | คืนค่าดัชนีเริ่มจากศูนย์ของการพบครั้งแรกของรูปทร่างที่ระบุในคอลเลกชัน. |
| [`add_math_shape(self, x, y, width, height)`](/slides/python-net/th/aspose.slides/ishapecollection/add_math_shape/#float-float-float-float) | สร้างรูปสี่เหลี่ยมอัตโนมัติใหม่เพื่อเป็นที่ใส่เนื้อหาคณิตศาสตร์และเพิ่มไปยังตำแหน่งสุดท้ายของ<br/>            คอลเลกชันของรูปร่าง. |
| [`insert_group_shape(self, index)`](/slides/python-net/th/aspose.slides/ishapecollection/insert_group_shape/#int) | สร้างกลุ่มรูปร่างเปล่าใหม่และแทรกเข้ากลุ่มรูปร่างที่ดัชนีที่ระบุ.<br/>            กรอบของกลุ่มจะปรับอัตโนมัติเพื่อให้พอดีกับรูปทรงใด ๆ ที่เพิ่มเข้าไป. |
| [`add_picture_frame(self, shape_type, x, y, width, height, image)`](/slides/python-net/th/aspose.slides/ishapecollection/add_picture_frame/#shapetype-float-float-float-float-ippimage) | สร้างกรอบภาพใหม่ที่มีภาพที่ระบุและเพิ่มไปยังตำแหน่งสุดท้ายของ<br/>            คอลเลกชันของรูปร่าง. |
| [`insert_picture_frame(self, index, shape_type, x, y, width, height, image)`](/slides/python-net/th/aspose.slides/ishapecollection/insert_picture_frame/#int-shapetype-float-float-float-float-ippimage) | สร้างกรอบภาพใหม่ที่มีภาพที่ระบุและแทรกเข้ากลุ่มรูปร่าง<br/>            ที่ดัชนีที่ระบุ. |
| [`add_table(self, x, y, column_widths, row_heights)`](/slides/python-net/th/aspose.slides/ishapecollection/add_table/#float-float-listfloat-listfloat) | สร้างตารางใหม่และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันของรูปร่าง. |
| [`insert_table(self, index, x, y, column_widths, row_heights)`](/slides/python-net/th/aspose.slides/ishapecollection/insert_table/#int-float-float-listfloat-listfloat) | สร้างตารางใหม่และแทรกเข้ากลุ่มรูปร่างที่ดัชนีที่ระบุ. |
| [`remove_at(self, index)`](/slides/python-net/th/aspose.slides/ishapecollection/remove_at/#int) | ลบรูปร่างที่ดัชนีที่ระบุออกจากคอลเลกชันของรูปร่าง. |
| [`remove(self, shape)`](/slides/python-net/th/aspose.slides/ishapecollection/remove/#ishape) | ลบการพบครั้งแรกของรูปร่างที่ระบุออกจากคอลเลกชันของรูปร่าง. |
| [`clear(self)`](/slides/python-net/th/aspose.slides/ishapecollection/clear/#) | ลบรูปร่างทั้งหมดออกจากคอลเลกชันของรูปร่าง. |

### ดูเพิ่มเติม
* คลาส [`IShape`](/slides/python-net/th/aspose.slides/ishape)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)