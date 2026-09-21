---
title: MathPhantom class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides.mathtext/mathphantom/
---
## MathPhantom คลาส

แสดงถึงอ็อบเจกต์คณิตศาสตร์แบบฟานท์ (<m:phant>) ที่ส่งผลต่อการจัดตำแหน่งขององค์ประกอบลูกโดยไม่จำเป็นต้องแสดงผลออกมา ฟานท์สามารถซ่อนนิพจน์ฐานในขณะที่ยังคงรักษาความกว้าง, ความสูง หรือความลึกเพื่อจัดแนวสูตรหรือสำรองพื้นที่ พฤติกรรมการมองเห็นและเรขาคณิตถูกควบคุมโดยคุณสมบัติเช่น Show, ZeroWid, ZeroAsc, ZeroDesc, และ Transp

**การสืบทอด:**[`MathPhantom`](/slides/python-net/th/aspose.slides.mathtext/mathphantom) → [`MathElementBase`](/slides/python-net/th/aspose.slides.mathtext/mathelementbase)

ประเภท MathPhantom เปิดเผยสมาชิกต่อไปนี้:

## ตัวกำเนิด

| ตัวกำเนิด | คำอธิบาย |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/__init__/#imathelement) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [`MathPhantom`](/slides/python-net/th/aspose.slides.mathtext/mathphantom) <br/> โดยใช้องค์ประกอบคณิตศาสตร์ฐานที่ระบุไว้. |

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`base`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/base/) | อาร์กิวเมนต์ฐาน |
| [`show`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/show/) | รับหรือตั้งค่าค่าที่แสดงว่าองค์ประกอบฐานจะแสดงหรือไม่ |
| [`zero_width`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/zero_width/) | รับหรือตั้งค่าค่าที่บ่งบอกว่าความกว้างขององค์ประกอบฐาน <br/> ควรถูกถือเป็นศูนย์ |
| [`zero_asc`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/zero_asc/) | รับหรือตั้งค่าค่าที่บ่งบอกว่าการยก (ความสูงเหนือบรรทัดฐาน) <br/> ขององค์ประกอบฐานควรถูกถือเป็นศูนย์ |
| [`zero_desc`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/zero_desc/) | รับหรือตั้งค่าค่าที่บ่งบอกว่าการลง (ความลึกต่ำกว่าบรรทัดฐาน) <br/> ขององค์ประกอบฐานควรถูกถือเป็นศูนย์ |
| [`transp`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/transp/) | รับหรือตั้งค่าค่าที่บ่งบอกว่าฟานท์เป็นแบบโปร่งใส <br/> สำหรับกฎการเว้นระยะตามคลาส |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/join/#imathelement) | เชื่อมโยงองค์ประกอบคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| [`join(self, math_text)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/join/#str) | เชื่อมโยงข้อความคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| [`divide(self, denominator)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/divide/#imathelement) | สร้างเศษส่วนด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| [`divide(self, denominator)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/divide/#str) | สร้างเศษส่วนด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/divide/#imathelement-mathfractiontypes) | สร้างเศษส่วนประเภทที่ระบุด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/divide/#str-mathfractiontypes) | สร้างเศษส่วนประเภทที่ระบุด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| [`enclose(self)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/enclose/#) | ล้อมรอบองค์ประกอบคณิตศาสตร์ด้วยวงเล็บ |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/enclose/#char-char) | ล้อมรอบองค์ประกอบคณิตศาสตร์ด้วยอักขระที่ระบุ เช่น วงเล็บหรืออักขระอื่นเป็นกรอบ |
| [`function(self, function_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/function/#imathelement) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [`function(self, function_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/function/#str) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/as_argument_of_function/#imathelement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/as_argument_of_function/#str) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsofoneargument) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-str) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [`set_subscript(self, subscript)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/set_subscript/#imathelement) | สร้างตัวห้อย |
| [`set_subscript(self, subscript)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/set_subscript/#str) | สร้างตัวห้อย |
| [`set_superscript(self, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/set_superscript/#imathelement) | สร้างตัวห้อยบน |
| [`set_superscript(self, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/set_superscript/#str) | สร้างตัวห้อยบน |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_right/#imathelement-imathelement) | สร้างตัวห้อยและตัวห้อยบนทางขวา |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_right/#str-str) | สร้างตัวห้อยและตัวห้อยบนทางขวา |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_left/#imathelement-imathelement) | สร้างตัวห้อยและตัวห้อยบนทางซ้าย |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_left/#str-str) | สร้างตัวห้อยและตัวห้อยบนทางซ้าย |
| [`radical(self, degree)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/radical/#imathelement) | ระบุรากคณิตศาสตร์ของระดับที่กำหนดจากอาร์กิวเมนต์ที่ระบุ |
| [`radical(self, degree)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/radical/#str) | ระบุรากคณิตศาสตร์ของระดับที่กำหนดจากอาร์กิวเมนต์ที่ระบุ |
| [`set_upper_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/set_upper_limit/#imathelement) | รับค่าขอบบน |
| [`set_upper_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/set_upper_limit/#str) | รับค่าขอบบน |
| [`set_lower_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/set_lower_limit/#imathelement) | รับค่าขอบล่าง |
| [`set_lower_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/set_lower_limit/#str) | รับค่าขอบล่าง |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/nary/#mathnaryoperatortypes-imathelement-imathelement) | สร้างตัวดำเนินการ N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/nary/#mathnaryoperatortypes-str-str) | สร้างตัวดำเนินการ N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | รับอินทิגרัล |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-imathelement-imathelement) | รับอินทิกรัล |
| [`integral(self, integral_type)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes) | รับอินทิกรัลโดยไม่มีขอบ |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-str-str-mathlimitlocations) | รับอินทิกรัล |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-str-str) | รับอินทิกรัล |
| [`group(self)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/group/#) | วางองค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บโค้งล่าง |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/group/#char-mathtopbotpositions-mathtopbotpositions) | วางองค์ประกอบนี้ในกลุ่มโดยใช้อักขระการจัดกลุ่ม เช่น วงเล็บโค้งล่างหรืออักขระอื่น |
| [`to_border_box(self)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/to_border_box/#) | วางองค์ประกอบนี้ในกล่องขอบ |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | วางองค์ประกอบนี้ในกล่องขอบ |
| [`to_math_array(self)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/to_math_array/#) | วางในอาร์เรย์แนวตั้ง |
| [`accent(self, accent_character)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/accent/#char) | ตั้งเครื่องหมายสำเนียง (อักขระบนสุดขององค์ประกอบนี้) |
| [`overbar(self)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/overbar/#) | ตั้งแถบบนสุดขององค์ประกอบนี้ |
| [`underbar(self)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/underbar/#) | ตั้งแถบล่างขององค์ประกอบนี้ |
| [`to_box(self)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/to_box/#) | วางองค์ประกอบนี้ในกล่องที่ไม่เป็นภาพ (การจัดกลุ่มเชิงตรรกะ) <br/> ที่ใช้เพื่อจัดกลุ่มส่วนประกอบของสมการหรือข้อความคณิตศาสตร์อื่น ๆ <br/> วัตถุที่บรรจุในกล่องอาจ (เช่น) ทำหน้าที่เป็นอิมูเลเตอร์ของโอเปอเรเตอร์ที่มีหรือไม่มีจุดจัดแนว, <br/> ทำหน้าที่เป็นจุดตัดบรรทัด, หรือจัดกลุ่มเพื่อไม่ให้มีการตัดบรรทัดภายใน |
| [`get_children(self)`](/slides/python-net/th/aspose.slides.mathtext/mathphantom/get_children/#) | รับองค์ประกอบลูก |

### ดูเพิ่มเติม
* คลาส [`MathElementBase`](/slides/python-net/th/aspose.slides.mathtext/mathelementbase)
* คลาส [`MathPhantom`](/slides/python-net/th/aspose.slides.mathtext/mathphantom)
* โมดูล [`aspose.slides.mathtext`](/slides/python-net/th/aspose.slides.mathtext)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)