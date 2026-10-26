---
title: ShapeCollection class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/shapecollection/
---
## ShapeCollection คลาส

แสดงชุดของรูปร่าง

ประเภท ShapeCollection เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`parent_group`](/slides/python-net/th/aspose.slides/shapecollection/parent_group/) | ดึงอ็อบเจกต์กลุ่มรูปร่างแม่สำหรับคอลเลกชันรูปทรง.<br/>            อ่านอย่างเดียว [`IGroupShape`](/slides/python-net/th/aspose.slides/igroupshape). |

ดึงองค์ประกอบที่ตำแหน่งที่ระบุ.  
            อ่านอย่างเดียว [`IShape`](/slides/python-net/th/aspose.slides/ishape).

## ดัชนี

| ชื่อ | คำอธิบาย |
| :- | :- |
| [`[index]`](/slides/python-net/th/aspose.slides/shapecollection/__getitem__/) |  |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`add_chart(self, type, x, y, width, height)`](/slides/python-net/th/aspose.slides/shapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float) | สร้างแผนภูมิใหม่, ตั้งค่าโดยใช้ข้อมูลซีรีส์ตัวอย่างและการตั้งค่า, แล้วเพิ่ม<br/>            ลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง. |
| [`add_chart(self, type, x, y, width, height, init_with_sample)`](/slides/python-net/th/aspose.slides/shapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float-bool) | สร้างแผนภูมิใหม่, ตั้งค่าโดยใช้ข้อมูลซีรีส์ตัวอย่างและการตั้งค่า, แล้วเพิ่ม<br/>            ลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง. |
| [`insert_chart(self, type, x, y, width, height, index)`](/slides/python-net/th/aspose.slides/shapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int) | สร้างแผนภูมิใหม่, ตั้งค่าโดยใช้ข้อมูลซีรีส์ตัวอย่างและการตั้งค่า,<br/>            แล้วแทรกลงในคอลเลกชันรูปทรง ณ ดัชนีที่ระบุ. |
| [`insert_chart(self, type, x, y, width, height, index, init_with_sample)`](/slides/python-net/th/aspose.slides/shapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int-bool) | สร้างแผนภูมิใหม่, ตั้งค่าโดยใช้ข้อมูลซีรีส์ตัวอย่างและการตั้งค่า,<br/>            แล้วแทรกลงในคอลเลกชันรูปทรง ณ ดัชนีที่ระบุ. |
| [`add_zoom_frame(self, x, y, width, height, slide)`](/slides/python-net/th/aspose.slides/shapecollection/add_zoom_frame/#float-float-float-float-islide) | สร้างเฟรม Zoom ใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง. |
| [`add_zoom_frame(self, x, y, width, height, slide, image)`](/slides/python-net/th/aspose.slides/shapecollection/add_zoom_frame/#float-float-float-float-islide-ippimage) | สร้างเฟรม Zoom ใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide)`](/slides/python-net/th/aspose.slides/shapecollection/insert_zoom_frame/#int-float-float-float-float-islide) | สร้างเฟรม Zoom ใหม่และแทรกลงในคอลเลกชันรูปทรง ณ ดัชนีที่ระบุ. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide, image)`](/slides/python-net/th/aspose.slides/shapecollection/insert_zoom_frame/#int-float-float-float-float-islide-ippimage) | สร้างเฟรม Zoom ใหม่พร้อมภาพที่กำหนดล่วงหน้าและแทรกลงในคอลเลกชันรูปทรง<br/>            ณ ดัชนีที่ระบุ. |
| [`add_section_zoom_frame(self, x, y, width, height, section)`](/slides/python-net/th/aspose.slides/shapecollection/add_section_zoom_frame/#float-float-float-float-isection) | สร้างเฟรม Section Zoom ใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง. |
| [`add_section_zoom_frame(self, x, y, width, height, section, image)`](/slides/python-net/th/aspose.slides/shapecollection/add_section_zoom_frame/#float-float-float-float-isection-ippimage) | สร้างเฟรม Section Zoom ใหม่พร้อมภาพที่กำหนดล่วงหน้าและเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section)`](/slides/python-net/th/aspose.slides/shapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection) | สร้างเฟรม Section Zoom ใหม่และแทรกลงในคอลเลกชันรูปทรง ณ ดัชนีที่ระบุ. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section, image)`](/slides/python-net/th/aspose.slides/shapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection-ippimage) | สร้างเฟรม Section Zoom ใหม่พร้อมภาพที่กำหนดล่วงหน้าและแทรกลงในคอลเลกชันรูปทรง<br/>            ณ ดัชนีที่ระบุ. |
| [`add_ole_object_frame(self, x, y, width, height, data_info)`](/slides/python-net/th/aspose.slides/shapecollection/add_ole_object_frame/#float-float-float-float-ioleembeddeddatainfo) | สร้างเฟรมอ็อบเจกต์ OLE ใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง. |
| [`add_ole_object_frame(self, x, y, width, height, class_name, path)`](/slides/python-net/th/aspose.slides/shapecollection/add_ole_object_frame/#float-float-float-float-str-str) | สร้างเฟรมอ็อบเจกต์ OLE ใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง. |
| [`insert_ole_object_frame(self, index, x, y, width, height, data_info)`](/slides/python-net/th/aspose.slides/shapecollection/insert_ole_object_frame/#int-float-float-float-float-ioleembeddeddatainfo) | สร้างเฟรมอ็อบเจกต์ OLE ใหม่และแทรกลงในคอลเลกชันรูปทรง ณ ดัชนีที่ระบุ. |
| [`insert_ole_object_frame(self, index, x, y, width, height, class_name, path)`](/slides/python-net/th/aspose.slides/shapecollection/insert_ole_object_frame/#int-float-float-float-float-str-str) | สร้างเฟรมอ็อบเจกต์ OLE ใหม่และแทรกลงในคอลเลกชันรูปทรง ณ ดัชนีที่ระบุ. |
| [`add_video_frame(self, x, y, width, height, fname)`](/slides/python-net/th/aspose.slides/shapecollection/add_video_frame/#float-float-float-float-str) | สร้างเฟรมวิดีโอใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง. |
| [`add_video_frame(self, x, y, width, height, video)`](/slides/python-net/th/aspose.slides/shapecollection/add_video_frame/#float-float-float-float-ivideo) | สร้างเฟรมวิดีโอใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio_stream)`](/slides/python-net/th/aspose.slides/shapecollection/add_audio_frame_embedded/#float-float-float-float-iorawiobase) | สร้างเฟรมเสียงใหม่พร้อมไฟล์ WAV ฝังและเพิ่มลงในตำแหน่งสุดท้ายของ<br/>            คอลเลกชันรูปทรง. ไฟล์เสียงฝังจะถูกเพิ่มไปยังคอลเลกชัน Presentation.Audios. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio)`](/slides/python-net/th/aspose.slides/shapecollection/add_audio_frame_embedded/#float-float-float-float-iaudio) | สร้างเฟรมเสียงใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรงโดยใช้<br/>            วัตถุเสียงที่มีอยู่จากรายการ Presentation.Audios. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream)`](/slides/python-net/th/aspose.slides/shapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iorawiobase) | สร้างเฟรมเสียงใหม่พร้อมไฟล์ WAV ฝังและแทรกลงในคอลเลกชันรูปทรง ณ ดัชนีที่ระบุ. ไฟล์เสียงฝังจะถูกเพิ่มไปยังคอลเลกชัน Presentation.Audios<br/>            . |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio)`](/slides/python-net/th/aspose.slides/shapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iaudio) | สร้างเฟรมเสียงใหม่และแทรกลงในคอลเลกชันรูปทรง ณ ดัชนีที่ระบุ<br/>            โดยใช้วัตถุเสียงที่มีอยู่จากรายการ Presentation.Audios. |
| [`to_array(self)`](/slides/python-net/th/aspose.slides/shapecollection/to_array/#) | สร้างและส่งกลับอาร์เรย์ที่มีรูปทั้งหมด. |
| [`to_array(self, start_index, count)`](/slides/python-net/th/aspose.slides/shapecollection/to_array/#int-int) | สร้างและส่งกลับอาร์เรย์ที่มีรูปในช่วงที่ระบุ. |
| [`reorder(self, index, shape)`](/slides/python-net/th/aspose.slides/shapecollection/reorder/#int-ishape) | ย้ายรูปที่ระบุไปยังตำแหน่งใหม่ภายในคอลเลกชันรูปทรง. |
| [`reorder(self, index, shapes)`](/slides/python-net/th/aspose.slides/shapecollection/reorder/#int-listishape) | ย้ายรูปที่ระบุหลายรูปภายในคอลเลกชันรูปทรง, เริ่มวางจากดัชนีที่กำหนด. |
| [`add_auto_shape(self, shape_type, x, y, width, height)`](/slides/python-net/th/aspose.slides/shapecollection/add_auto_shape/#shapetype-float-float-float-float) | สร้างรูปร่างอัตโนมัติใหม่พร้อมการจัดรูปแบบเริ่มต้นและเพิ่มลงในตำแหน่งสุดท้ายของ<br/>            คอลเลกชันรูปทรง. |
| [`add_auto_shape(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/th/aspose.slides/shapecollection/add_auto_shape/#shapetype-float-float-float-float-bool) | สร้างรูปร่างอัตโนมัติใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง, โดยอาจ<br/>            เริ่มต้นด้วยรูปแบบเทมเพลตเริ่มต้น. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height)`](/slides/python-net/th/aspose.slides/shapecollection/insert_auto_shape/#int-shapetype-float-float-float-float) | สร้างรูปร่างอัตโนมัติใหม่และแทรกลงในคอลเลกชันรูปทรง ณ ดัชนีที่ระบุ,<br/>            พร้อมใช้รูปแบบเทมเพลตเริ่มต้น. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/th/aspose.slides/shapecollection/insert_auto_shape/#int-shapetype-float-float-float-float-bool) | สร้างรูปร่างอัตโนมัติใหม่และแทรกลงในคอลเลกชันรูปทรง ณ ดัชนีที่ระบุ,<br/>            โดยอาจเริ่มต้นด้วยสไตล์เทมเพลตเริ่มต้น. |
| [`add_group_shape(self)`](/slides/python-net/th/aspose.slides/shapecollection/add_group_shape/#) | สร้างกลุ่มรูปร่างเปล่ใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง.<br/>            กรอบของกลุ่มจะปรับอัตโนมัติเพื่อพิมพ์รูปใด ๆ ที่เพิ่มเข้าไป. |
| [`add_group_shape(self, svg_image, x, y, width, height)`](/slides/python-net/th/aspose.slides/shapecollection/add_group_shape/#isvgimage-float-float-float-float) | สร้างกลุ่มรูปร่างใหม่, แปลงภาพ SVG ที่ระบุเป็นรูปแยกส่วน, และเพิ่มกลุ่มที่ได้ลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง. |
| [`add_connector(self, shape_type, x, y, width, height)`](/slides/python-net/th/aspose.slides/shapecollection/add_connector/#shapetype-float-float-float-float) | สร้างรูปเชื่อมต่อใหม่พร้อมสไตล์เทมเพลตเริ่มต้นและเพิ่มลงในตำแหน่งสุดท้ายของ<br/>            คอลเลกชันรูปทรง. |
| [`add_connector(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/th/aspose.slides/shapecollection/add_connector/#shapetype-float-float-float-float-bool) | สร้างรูปเชื่อมต่อใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง,<br/>            โดยอาจใช้สไตล์เทมเพลตเริ่มต้น. |
| [`insert_connector(self, index, shape_type, x, y, width, height)`](/slides/python-net/th/aspose.slides/shapecollection/insert_connector/#int-shapetype-float-float-float-float) | สร้างรูปเชื่อมต่อใหม่และแทรกลงในคอลเลกชันรูปทรง ณ ดัชนีที่ระบุ,<br/>            ใช้สไตล์เทมเพลตเริ่มต้น. |
| [`insert_connector(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/th/aspose.slides/shapecollection/insert_connector/#int-shapetype-float-float-float-float-bool) | สร้างรูปเชื่อมต่อใหม่และแทรกลงในคอลเลกชันรูปทรง ณ ดัชนีที่ระบุ,<br/>            โดยอาจใช้สไตล์เทมเพลตเริ่มต้น. |
| [`add_clone(self, source_shape, x, y, width, height)`](/slides/python-net/th/aspose.slides/shapecollection/add_clone/#ishape-float-float-float-float) | สร้างสำเนาของรูปที่ระบุและเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง. |
| [`add_clone(self, source_shape, x, y)`](/slides/python-net/th/aspose.slides/shapecollection/add_clone/#ishape-float-float) | สร้างสำเนาของรูปที่ระบุและเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง.<br/>            รูปใหม่จะคงความกว้างและความสูงของ `source_shape`. |
| [`add_clone(self, source_shape)`](/slides/python-net/th/aspose.slides/shapecollection/add_clone/#ishape) | สร้างสำเนาของรูปที่ระบุและเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง.<br/>            รูปที่โคลนจะคงตำแหน่งและขนาดเดิม. |
| [`insert_clone(self, index, source_shape, x, y, width, height)`](/slides/python-net/th/aspose.slides/shapecollection/insert_clone/#int-ishape-float-float-float-float) | สร้างสำเนาของรูปที่ระบุและแทรกลงในคอลเลกชันรูปทรง ณ ดัชนีที่ระบุ. |
| [`insert_clone(self, index, source_shape, x, y)`](/slides/python-net/th/aspose.slides/shapecollection/insert_clone/#int-ishape-float-float) | สร้างสำเนาของรูปที่ระบุและแทรกลงในคอลเลกชันรูปทรง ณ ดัชนีที่ระบุ.<br/>            รูปใหม่จะคงความกว้างและความสูงของ `source_shape`. |
| [`insert_clone(self, index, source_shape)`](/slides/python-net/th/aspose.slides/shapecollection/insert_clone/#int-ishape) | สร้างสำเนาของรูปที่ระบุและแทรกลงในคอลเลกชันรูปทรง ณ ดัชนีที่ระบุ.<br/>            รูปที่โคลนจะคงตำแหน่งและขนาดเดิม. |
| [`add_smart_art(self, x, y, width, height, layout_type)`](/slides/python-net/th/aspose.slides/shapecollection/add_smart_art/#float-float-float-float-asposeslidessmartartsmartartlayouttype) | สร้างไดอะแกรม SmartArt และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง. |
| [`add_summary_zoom_frame(self, x, y, width, height)`](/slides/python-net/th/aspose.slides/shapecollection/add_summary_zoom_frame/#float-float-float-float) | สร้างเฟรม Summary Zoom ใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง. |
| [`insert_summary_zoom_frame(self, index, x, y, width, height)`](/slides/python-net/th/aspose.slides/shapecollection/insert_summary_zoom_frame/#int-float-float-float-float) | สร้างเฟรม Summary Zoom ใหม่และแทรกลงในคอลเลกชันรูปทรง ณ ดัชนีที่ระบุ. |
| [`insert_video_frame(self, index, x, y, width, height, fname)`](/slides/python-net/th/aspose.slides/shapecollection/insert_video_frame/#int-float-float-float-float-str) | สร้างเฟรมวิดีโอใหม่และแทรกลงในคอลเลกชันรูปทรง ณ ดัชนีที่ระบุ. |
| [`add_audio_frame_cd(self, x, y, width, height)`](/slides/python-net/th/aspose.slides/shapecollection/add_audio_frame_cd/#float-float-float-float) | สร้างเฟรมเสียงใหม่ที่เชื่อมต่อกับแทร็ก CD และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง. |
| [`insert_audio_frame_cd(self, index, x, y, width, height)`](/slides/python-net/th/aspose.slides/shapecollection/insert_audio_frame_cd/#int-float-float-float-float) | สร้างเฟรมเสียงใหม่ที่เชื่อมต่อกับแทร็ก CD และแทรกลงในคอลเลกชันรูปทรง<br/>            ณ ดัชนีที่ระบุ. |
| [`add_audio_frame_linked(self, x, y, width, height, fname)`](/slides/python-net/th/aspose.slides/shapecollection/add_audio_frame_linked/#float-float-float-float-str) | สร้างเฟรมเสียงใหม่ที่เชื่อมต่อกับไฟล์เสียงภายนอกและเพิ่มลงในตำแหน่งสุดท้ายของ<br/>            คอลเลกชันรูปทรง. |
| [`insert_audio_frame_linked(self, index, x, y, width, height, fname)`](/slides/python-net/th/aspose.slides/shapecollection/insert_audio_frame_linked/#int-float-float-float-float-str) | สร้างเฟรมเสียงใหม่ที่เชื่อมต่อกับไฟล์เสียงภายนอกและแทรกลงในคอลเลกชันรูปทรง<br/>            ณ ดัชนีที่ระบุ. |
| [`index_of(self, shape)`](/slides/python-net/th/aspose.slides/shapecollection/index_of/#ishape) | ส่งกลับดัชนีเริ่มต้นที่ศูนย์ของการพบครั้งแรกของรูปที่ระบุในคอลเลกชัน. |
| [`add_math_shape(self, x, y, width, height)`](/slides/python-net/th/aspose.slides/shapecollection/add_math_shape/#float-float-float-float) | สร้างรูปร่างอัตโนมัติสี่เหลี่ยมใหม่เพื่อโฮสต์เนื้อหาทางคณิตศาสตร์และเพิ่มลงใน<br/>            ตำแหน่งสุดท้ายของคอลเลกชันรูปทรง. |
| [`insert_group_shape(self, index)`](/slides/python-net/th/aspose.slides/shapecollection/insert_group_shape/#int) | สร้างกลุ่มรูปร่างเปล่ใหม่และแทรกลงในคอลเลกชันรูปทรง ณ ดัชนีที่ระบุ.<br/>            กรอบของกลุ่มจะปรับอัตโนมัติเพื่อพิมพ์รูปใด ๆ ที่เพิ่มเข้าไป. |
| [`add_picture_frame(self, shape_type, x, y, width, height, image)`](/slides/python-net/th/aspose.slides/shapecollection/add_picture_frame/#shapetype-float-float-float-float-ippimage) | สร้างเฟรมภาพใหม่ที่บรรจุภาพที่ระบุและเพิ่มลงในตำแหน่งสุดท้ายของ<br/>            คอลเลกชันรูปทรง. |
| [`insert_picture_frame(self, index, shape_type, x, y, width, height, image)`](/slides/python-net/th/aspose.slides/shapecollection/insert_picture_frame/#int-shapetype-float-float-float-float-ippimage) | สร้างเฟรมภาพใหม่ที่บรรจุภาพที่ระบุและแทรกลงในคอลเลกชันรูปทรง ณ ดัชนีที่ระบุ. |
| [`add_table(self, x, y, column_widths, row_heights)`](/slides/python-net/th/aspose.slides/shapecollection/add_table/#float-float-listfloat-listfloat) | สร้างตารางใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง. |
| [`insert_table(self, index, x, y, column_widths, row_heights)`](/slides/python-net/th/aspose.slides/shapecollection/insert_table/#int-float-float-listfloat-listfloat) | สร้างตารางใหม่และแทรกลงในคอลเลกชันรูปทรง ณ ดัชนีที่ระบุ. |
| [`remove_at(self, index)`](/slides/python-net/th/aspose.slides/shapecollection/remove_at/#int) | ลบรูปร่างที่ตำแหน่งที่ระบุออกจากคอลเลกชันรูปทรง. |
| [`remove(self, shape)`](/slides/python-net/th/aspose.slides/shapecollection/remove/#ishape) | ลบการพบครั้งแรกของรูปที่ระบุออกจากคอลเลกชันรูปทรง. |
| [`clear(self)`](/slides/python-net/th/aspose.slides/shapecollection/clear/#) | ลบรูปทั้งหมดออกจากคอลเลกชันรูปทรง. |

### ดูเพิ่มเติม
* class [`IShape`](/slides/python-net/th/aspose.slides/ishape)
* module [`aspose.slides`](/slides/python-net/th/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)