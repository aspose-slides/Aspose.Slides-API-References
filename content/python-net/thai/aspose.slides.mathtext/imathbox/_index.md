---
title: IMathBox class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides.mathtext/imathbox/
---
## IMathBox คลาส

กำหนดการบรรจุ (boxing) เชิงตรรกะขององค์ประกอบคณิตศาสตร์
            ตัวอย่างเช่น วัตถุที่บรรจุสามารถทำหน้าที่เป็นอีมูเลเตอร์ตัวดำเนินการได้ทั้งมีหรือไม่มีจุดจัดแนว,
            ทำหน้าที่เป็นจุดตัดบรรทัด, หรือถูกจัดกลุ่มเพื่อไม่ให้มีการตัดบรรทัดภายใน
            ตัวอย่างเช่น ตัวดำเนินการ "==" ควรจะถูกบรรจุเพื่อป้องกันการตัดบรรทัด

The IMathBox type exposes the following members:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`base`](/slides/python-net/th/aspose.slides.mathtext/imathbox/base/) | อาร์กิวเมนต์พื้นฐาน |
| [`operator_emulator`](/slides/python-net/th/aspose.slides.mathtext/imathbox/operator_emulator/) | อีมูเลเตอร์ตัวดำเนินการ.<br/>            เมื่อค่าเป็น true, กล่องและเนื้อหาภายในทำหน้าที่เป็นตัวดำเนินการเดียวและรับคุณสมบัติของตัวดำเนินการ.<br/>            ซึ่งหมายความว่า ตัวอักษรสามารถทำหน้าที่เป็นจุดตัดบรรทัดและจัดแนวกับตัวดำเนินการอื่นได้.<br/>            อีมูเลเตอร์ตัวดำเนินการมักใช้เมื่อหนึ่งหรือหลาย glyph ผสานเป็นตัวดำเนินการ เช่น '==' .<br/>            ค่าเริ่มต้น: false |
| [`no_break`](/slides/python-net/th/aspose.slides.mathtext/imathbox/no_break/) | ไม่มีการตัดบรรทัด.<br/>            คุณสมบัตินี้ระบุคุณสมบัติ "unbreakable" บนกล่องวัตถุ เมื่อเป็น true, จะไม่เกิดการตัดบรรทัดภายในกล่อง.<br/>            สิ่งนี้อาจสำคัญสำหรับอีมูเลเตอร์ตัวดำเนินการที่ประกอบด้วยตัวดำเนินการแบบไบนารีมากกว่าหนึ่งตัว.<br/>            หากไม่ได้ระบุส่วนนี้, การตัดบรรทัดอาจเกิดขึ้นภายในกล่อง.<br/>            ค่าเริ่มต้น: true |
| [`differential`](/slides/python-net/th/aspose.slides.mathtext/imathbox/differential/) | อนุพันธ์.<br/>            เมื่อเป็น true, กล่องทำหน้าที่เป็นอนุพันธ์ (เช่น 𝑑𝑥 ในส่วนประกอบการอินทิกรัล), และรับระยะห่างแนวนอนที่เหมาะสมสำหรับอนุพันธ์ทางคณิตศาสตร์.<br/>            ค่าเริ่มต้น: false |
| [`alignment_point`](/slides/python-net/th/aspose.slides.mathtext/imathbox/alignment_point/) | เมื่อเป็น true, อีมูเลเตอร์ตัวดำเนินการนี้ทำหน้าที่เป็นจุดจัดแนว; นั่นคือ, จุดจัดแนวที่กำหนดในสมการอื่น ๆ สามารถจัดแนวกับมันได้.<br/>            ค่าเริ่มต้น: false |
| [`explicit_break`](/slides/python-net/th/aspose.slides.mathtext/imathbox/explicit_break/) | Explicit break ระบุว่ามีการตัดบรรทัดที่จุดเริ่มต้นของวัตถุ Box หรือไม่, <br/>            เพื่อให้บรรทัดตัดเมื่อเริ่มวัตถุ box.<br/>            ระบุจำนวนของตัวดำเนินการในบรรทัดก่อนหน้าของข้อความคณิตศาสตร์ ซึ่งจะ<br/>            ใช้เป็นจุดจัดแนวสำหรับบรรทัดปัจจุบันของข้อความคณิตศาสตร์<br/>            ค่าที่เป็นไปได้: 1..255<br/>            ค่าเริ่มต้น: 0 (ไม่มีการตัดบรรทัดโดยเจตนา) |

## เมธอด

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_children(self)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/th/aspose.slides.mathtext/imathbox/to_box/#) |  |


### ดูเพิ่มเติม
* โมดูล [`aspose.slides.mathtext`](/slides/python-net/th/aspose.slides.mathtext)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)