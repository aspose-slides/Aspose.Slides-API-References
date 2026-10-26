---
title: MathLimit class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET การอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.mathtext/mathlimit/
---
## MathLimit คลาส

ระบุอ็อบเจ็กต์ Limit ที่ประกอบด้วยข้อความบนเส้นฐานและข้อความขนาดเล็กที่อยู่เหนือหรือใต้เส้นฐานโดยตรง.

การสืบทอด:[`MathLimit`](/slides/python-net/th/aspose.slides.mathtext/mathlimit) → [`MathElementBase`](/slides/python-net/th/aspose.slides.mathtext/mathelementbase)

MathLimit type เปิดเผยสมาชิกต่อไปนี้:

## ผู้สร้าง

| คอนสตรัคเตอร์ | คำอธิบาย |
| :- | :- |
| [`__init__(self, base_arg, limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/__init__/#imathelement-imathelement-bool) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส MathLimit. |
| [`__init__(self, base_arg, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/__init__/#imathelement-imathelement) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส MathLimit กับลิมิตล่าง |

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`base`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/base/) | อากิวเมนต์ฐาน |
| [`limit`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/limit/) | อากิวเมนต์ลิมิต |
| [`upper_limit`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/upper_limit/) | ระบุลิมิตบนหรือลิมิตล่าง |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/join/#imathelement) | เชื่อมต่อองค์ประกอบคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| [`join(self, math_text)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/join/#str) | เชื่อมต่อข้อความคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| [`divide(self, denominator)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/divide/#imathelement) | สร้างเศษส่วนโดยใช้ตัวเศษนี้และตัวส่วนที่ระบุ |
| [`divide(self, denominator)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/divide/#str) | สร้างเศษส่วนโดยใช้ตัวเศษนี้และตัวส่วนที่ระบุ |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/divide/#imathelement-mathfractiontypes) | สร้างเศษส่วนประเภทที่ระบุโดยใช้ตัวเศษนี้และตัวส่วนที่ระบุ |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/divide/#str-mathfractiontypes) | สร้างเศษส่วนประเภทที่ระบุโดยใช้ตัวเศษนี้และตัวส่วนที่ระบุ |
| [`enclose(self)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/enclose/#) | ล้อมรอบองค์ประกอบคณิตศาสตร์ด้วยวงเล็บ |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/enclose/#char-char) | ล้อมรอบองค์ประกอบคณิตศาสตร์ด้วยอักขระที่ระบุ เช่น วงเล็บหรืออักขระอื่นเป็นกรอบ |
| [`function(self, function_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/function/#imathelement) | รับฟังก์ชันของอากิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [`function(self, function_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/function/#str) | รับฟังก์ชันของอากิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/as_argument_of_function/#imathelement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอากิวเมนต์ |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/as_argument_of_function/#str) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอากิวเมนต์ |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/as_argument_of_function/#mathfunctionsofoneargument) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอากิวเมนต์ |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอากิวเมนต์และอากิวเมนต์เพิ่มเติมที่ระบุ |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/as_argument_of_function/#mathfunctionsoftwoarguments-str) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอากิวเมนต์และอากิวเมนต์เพิ่มเติมที่ระบุ |
| [`set_subscript(self, subscript)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/set_subscript/#imathelement) | สร้างตัวห้อย |
| [`set_subscript(self, subscript)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/set_subscript/#str) | สร้างตัวห้อย |
| [`set_superscript(self, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/set_superscript/#imathelement) | สร้างตัวยก |
| [`set_superscript(self, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/set_superscript/#str) | สร้างตัวยก |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_right/#imathelement-imathelement) | สร้างตัวห้อยและตัวยกทางด้านขวา |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_right/#str-str) | สร้างตัวห้อยและตัวยกทางด้านขวา |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_left/#imathelement-imathelement) | สร้างตัวห้อยและตัวยกทางด้านซ้าย |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_left/#str-str) | สร้างตัวห้อยและตัวยกทางด้านซ้าย |
| [`radical(self, degree)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/radical/#imathelement) | ระบุรากคณิตศาสตร์ของดีกรีที่กำหนดจากอากิวเมนต์ที่ระบุ |
| [`radical(self, degree)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/radical/#str) | ระบุรากคณิตศาสตร์ของดีกรีที่กำหนดจากอากิวเมนต์ที่ระบุ |
| [`set_upper_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/set_upper_limit/#imathelement) | รับลิมิตบน |
| [`set_upper_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/set_upper_limit/#str) | รับลิมิตบน |
| [`set_lower_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/set_lower_limit/#imathelement) | รับลิมิตล่าง |
| [`set_lower_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/set_lower_limit/#str) | รับลิมิตล่าง |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/nary/#mathnaryoperatortypes-imathelement-imathelement) | สร้างตัวดำเนินการ N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/nary/#mathnaryoperatortypes-str-str) | สร้างตัวดำเนินการ N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | รับอินทิกรัล |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-imathelement-imathelement) | รับอินทิกรัล |
| [`integral(self, integral_type)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes) | รับอินทิกรัลโดยไม่มีลิมิต |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-str-str-mathlimitlocations) | รับอินทิกรัล |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-str-str) | รับอินทิกรัล |
| [`group(self)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/group/#) | ใส่องค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บปีกกาด้านล่าง |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/group/#char-mathtopbotpositions-mathtopbotpositions) | ใส่องค์ประกอบนี้ในกลุ่มโดยใช้อักขระจัดกลุ่ม เช่น วงเล็บปีกกาด้านล่างหรืออักขระอื่น |
| [`to_border_box(self)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/to_border_box/#) | ใส่องค์ประกอบนี้ในกล่องกรอบ |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | ใส่องค์ประกอบนี้ในกล่องกรอบ |
| [`to_math_array(self)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/to_math_array/#) | ใส่ในอาเรย์แนวตั้ง |
| [`accent(self, accent_character)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/accent/#char) | ตั้งเครื่องหมายสำเนียง (อักขระบนส่วนบนขององค์ประกอบนี้) |
| [`overbar(self)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/overbar/#) | ตั้งแถบบนส่วนบนขององค์ประกอบนี้ |
| [`underbar(self)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/underbar/#) | ตั้งแถบบนส่วนล่างขององค์ประกอบนี้ |
| [`to_box(self)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/to_box/#) | ใส่องค์ประกอบนี้ในกล่องที่ไม่แสดงผล (การจัดกลุ่มเชิงตรรกะ) <br/>            ซึ่งใช้เพื่อจัดกลุ่มส่วนประกอบของสมการหรือข้อความคณิตศาสตร์อื่น.<br/>            วัตถุในกล่องสามารถ (เช่น) ทำหน้าที่เป็นตัวอิมูเลเตอร์ของตัวดำเนินการโดยมีหรือไม่มีจุดจัดแนว, <br/>            ทำหน้าที่เป็นจุดแบ่งบรรทัด, หรือจัดกลุ่มเพื่อไม่ให้มีการแบ่งบรรทัดภายใน. |
| [`get_children(self)`](/slides/python-net/th/aspose.slides.mathtext/mathlimit/get_children/#) | รับองค์ประกอบลูก |


### ดูเพิ่มเติม
* คลาส [`MathElementBase`](/slides/python-net/th/aspose.slides.mathtext/mathelementbase)
* คลาส [`MathLimit`](/slides/python-net/th/aspose.slides.mathtext/mathlimit)
* โมดูล [`aspose.slides.mathtext`](/slides/python-net/th/aspose.slides.mathtext)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)