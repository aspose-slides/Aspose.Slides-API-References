---
title: MathBox class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET การอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.mathtext/mathbox/
---
## MathBox คลาส

ระบุการบรรจุตรรกะ (การแพ็คเกจ) ขององค์ประกอบทางคณิตศาสตร์
            ตัวอย่างเช่น วัตถุบ็อกซ์สามารถทำหน้าที่เป็นตัวจำลองโอเปอเรเตอร์พร้อมหรือไม่มีจุดการจัดตำแหน่ง,
            ทำหน้าที่เป็นจุดตัดบรรทัด, หรือจัดกลุ่มเพื่อไม่ให้มีการตัดบรรทัดภายใน
            ตัวอย่างเช่น ตัวดำเนินการ "==" ควรถูกบ็อกซ์เพื่อป้องกันการตัดบรรทัด

**Inheritance:**[`MathBox`](/slides/python-net/th/aspose.slides.mathtext/mathbox) → [`MathElementBase`](/slides/python-net/th/aspose.slides.mathtext/mathelementbase)

The MathBox type exposes the following members:

## คอนสตรัคเตอร์

| Constructor | Description |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/__init__/#imathelement) | เริ่มต้น MathBox ด้วยองค์ประกอบที่ระบุเป็นอาร์กิวเมนต์ |

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`base`](/slides/python-net/th/aspose.slides.mathtext/mathbox/base/) | อาร์กิวเมนต์ฐาน |
| [`operator_emulator`](/slides/python-net/th/aspose.slides.mathtext/mathbox/operator_emulator/) | จำลองโอเปอเรเตอร์.<br/>            เมื่อเป็น true, กล่องและเนื้อหาในกล่องทำงานเหมือนโอเปอเรเตอร์เดียวและสืบทอดคุณสมบัติของโอเปอเรเตอร์. <br/>            ซึ่งหมายความว่า, ตัวอักษรสามารถทำหน้าที่เป็นจุดตัดบรรทัดและสามารถจัดตำแหน่งกับโอเปอเรเตอร์อื่นได้.<br/>            จำลองโอเปอเรเตอร์มักใช้เมื่อหนึ่งหรือหลาย glyph รวมกันเป็นโอเปอเรเตอร์, เช่น '=='.<br/>            ค่าเริ่มต้น: false |
| [`no_break`](/slides/python-net/th/aspose.slides.mathtext/mathbox/no_break/) | ไม่มีการตัดบรรทัด<br/>            คุณสมบัตินี้ระบุคุณสมบัติ "unbreakable" บนกล่องวัตถุ. เมื่อเป็น true, จะไม่มีการตัดบรรทัดภายในกล่อง.<br/>            สิ่งนี้อาจสำคัญสำหรับจำลองโอเปอเรเตอร์ที่ประกอบด้วยโอเปอเรเตอร์ไบนารีมากกว่าหนึ่งตัว. <br/>            หากไม่ระบุองค์ประกอบนี้, การตัดบรรทัดอาจเกิดขึ้นภายในกล่อง.<br/>            ค่าเริ่มต้น: true |
| [`differential`](/slides/python-net/th/aspose.slides.mathtext/mathbox/differential/) | ดิฟเฟอเรนเชียล<br/>            เมื่อเป็น true, กล่องทำหน้าที่เป็นดิฟเฟอเรนเชียล (เช่น 𝑑𝑥 ในอินเทกรัล), และรับระยะห่างแนวนอนที่เหมาะสมสำหรับดิฟเฟอเรนเชียลทางคณิตศาสตร์.<br/>            ค่าเริ่มต้น: false |
| [`alignment_point`](/slides/python-net/th/aspose.slides.mathtext/mathbox/alignment_point/) | เมื่อเป็น true, จำลองโอเปอเรเตอร์นี้ทำหน้าที่เป็นจุดการจัดตำแหน่ง; คือ, <br/>            จุดการจัดตำแหน่งที่กำหนดในสมการอื่นสามารถจัดตำแหน่งกับมันได้.<br/>            ค่าเริ่มต้น: false |
| [`explicit_break`](/slides/python-net/th/aspose.slides.mathtext/mathbox/explicit_break/) | การตัดบรรทัดโดยเจาะจงระบุว่าจะมีการตัดบรรทัดที่จุดเริ่มต้นของอ็อบเจกต์ Box หรือไม่, <br/>            เพื่อให้บรรทัดพับที่จุดเริ่มต้นของอ็อบเจกต์บ็อกซ์.<br/>            ระบุจำนวนของโอเปอเรเตอร์ในบรรทัดก่อนหน้าของข้อความคณิตศาสตร์ที่ต้อง<br/>            ใช้เป็นจุดจัดตำแหน่งสำหรับบรรทัดปัจจุบันของข้อความคณิตศาสตร์<br/>            ค่าที่เป็นไปได้: 1..255<br/>            ค่าเริ่มต้น: 0 (ไม่มีการตัดบรรทัดโดยเจาะจง) |

## เมธอด

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/join/#imathelement) | รวมองค์ประกอบทางคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| [`join(self, math_text)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/join/#str) | รวมข้อความทางคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| [`divide(self, denominator)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/divide/#imathelement) | สร้างเศษส่วนด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| [`divide(self, denominator)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/divide/#str) | สร้างเศษส่วนด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/divide/#imathelement-mathfractiontypes) | สร้างเศษส่วนประเภทที่ระบุด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/divide/#str-mathfractiontypes) | สร้างเศษส่วนประเภทที่ระบุด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| [`enclose(self)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/enclose/#) | ล้อมรอบองค์ประกอบคณิตศาสตร์ด้วยวงเล็บ |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/enclose/#char-char) | ล้อมรอบองค์ประกอบคณิตศาสตร์ด้วยอักขระที่ระบุ เช่น วงเล็บหรืออักขระอื่นเป็นกรอบ |
| [`function(self, function_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/function/#imathelement) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [`function(self, function_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/function/#str) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/as_argument_of_function/#imathelement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/as_argument_of_function/#str) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsofoneargument) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [`set_subscript(self, subscript)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/set_subscript/#imathelement) | สร้างตัวห้อย |
| [`set_subscript(self, subscript)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/set_subscript/#str) | สร้างตัวห้อย |
| [`set_superscript(self, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/set_superscript/#imathelement) | สร้างตัวยกกำลัง |
| [`set_superscript(self, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/set_superscript/#str) | สร้างตัวยกกำลัง |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_right/#imathelement-imathelement) | สร้างตัวห้อยและตัวยกกำลังทางขวา |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_right/#str-str) | สร้างตัวห้อยและตัวยกกำลังทางขวา |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_left/#imathelement-imathelement) | สร้างตัวห้อยและตัวยกกำลังทางซ้าย |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_left/#str-str) | สร้างตัวห้อยและตัวยกกำลังทางซ้าย |
| [`radical(self, degree)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/radical/#imathelement) | ระบุรากคณิตศาสตร์ของดีกรีที่กำหนดจากอาร์กิวเมนต์ที่ระบุ. |
| [`radical(self, degree)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/radical/#str) | ระบุรากคณิตศาสตร์ของดีกรีที่กำหนดจากอาร์กิวเมนต์ที่ระบุ. |
| [`set_upper_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/set_upper_limit/#imathelement) | รับค่าขอบบน |
| [`set_upper_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/set_upper_limit/#str) | รับค่าขอบบน |
| [`set_lower_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/set_lower_limit/#imathelement) | รับค่าขอบล่าง |
| [`set_lower_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/set_lower_limit/#str) | รับค่าขอบล่าง |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/nary/#mathnaryoperatortypes-imathelement-imathelement) | สร้างโอเปอเรเตอร์ N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/nary/#mathnaryoperatortypes-str-str) | สร้างโอเปอเรเตอร์ N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | รับค่าอินทิกรัล |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-imathelement-imathelement) | รับค่าอินทิกรัล |
| [`integral(self, integral_type)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes) | รับค่าอินทิกรัลโดยไม่มีขอบเขต |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-str-str-mathlimitlocations) | รับค่าอินทิกรัล |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-str-str) | รับค่าอินทิกรัล |
| [`group(self)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/group/#) | วางองค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บโค้งล่าง |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/group/#char-mathtopbotpositions-mathtopbotpositions) | วางองค์ประกอบนี้ในกลุ่มโดยใช้อักขระการจัดกลุ่มเช่นวงเล็บโค้งล่างหรืออักขระอื่น |
| [`to_border_box(self)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/to_border_box/#) | วางองค์ประกอบนี้ในกล่องกรอบ |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | วางองค์ประกอบนี้ในกล่องกรอบ |
| [`to_math_array(self)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/to_math_array/#) | ใส่ในอาเรย์แนวตั้ง |
| [`accent(self, accent_character)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/accent/#char) | ตั้งเครื่องหมายสำเนียง (อักขระบนสุดขององค์ประกอบนี้) |
| [`overbar(self)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/overbar/#) | ตั้งบาร์บนสุดขององค์ประกอบนี้ |
| [`underbar(self)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/underbar/#) | ตั้งบาร์ที่ด้านล่างขององค์ประกอบนี้ |
| [`to_box(self)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/to_box/#) | วางองค์ประกอบนี้ในกล่องไม่แสดงผล (การจัดกลุ่มเชิงตรรกะ) <br/>            ซึ่งใช้เพื่อจัดกลุ่มส่วนประกอบของสมการหรืออินสแตนซ์อื่นของข้อความคณิตศาสตร์.<br/>            วัตถุบ็อกซ์สามารถ (เช่น) ทำหน้าที่เป็นจำลองโอเปอเรเตอร์พร้อมหรือไม่มีจุดจัดตำแหน่ง, <br/>            ทำหน้าที่เป็นจุดตัดบรรทัด, หรือจัดกลุ่มเพื่อไม่ให้เกิดการตัดบรรทัดภายใน. |
| [`get_children(self)`](/slides/python-net/th/aspose.slides.mathtext/mathbox/get_children/#) | รับองค์ประกอบลูก |


### ดูเพิ่มเติม
* คลาส [`MathBox`](/slides/python-net/th/aspose.slides.mathtext/mathbox)
* คลาส [`MathElementBase`](/slides/python-net/th/aspose.slides.mathtext/mathelementbase)
* โมดูล [`aspose.slides.mathtext`](/slides/python-net/th/aspose.slides.mathtext)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)