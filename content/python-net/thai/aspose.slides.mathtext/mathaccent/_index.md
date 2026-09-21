---
title: MathAccent class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.mathtext/mathaccent/
---
## MathAccent คลาส

ระบุฟังก์ชันสำเนียงประกอบด้วยฐานและเครื่องหมายการรวมที่เป็นอักขระพิเศษ ตัวอย่าง: 𝑎́

**การสืบทอด:**[`MathAccent`](/slides/python-net/th/aspose.slides.mathtext/mathaccent) → [`MathElementBase`](/slides/python-net/th/aspose.slides.mathtext/mathelementbase)

ประเภท MathAccent มีสมาชิกดังต่อไปนี้:

## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/__init__/#imathelement) | สร้างสำเนียงคณิตศาสตร์ที่ใช้กับองค์ประกอบคณิตศาสตร์ที่ระบุพร้อมค่าตัวอักษรสำเนียงเริ่มต้น |
| [`__init__(self, element, accent_character)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/__init__/#imathelement-char) | สร้างสำเนียงคณิตศาสตร์ที่ใช้กับองค์ประกอบคณิตศาสตร์ที่ระบุ |

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`base`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/base/) | อาร์กิวเมนต์ที่ถูกใส่สำเนียง |
| [`character`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/character/) | ตัวอักษรสำเนียง<br/>            ค่านั้นควรอยู่ในช่วง (U+0300–U+036F) หรือ (U+20D0–U+20EF)<br/>            ค่าเริ่มต้น: Combining Circumflex Accent (U+0302) |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/join/#imathelement) | เชื่อมต่อองค์ประกอบคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| [`join(self, math_text)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/join/#str) | เชื่อมต่อข้อความคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| [`divide(self, denominator)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/divide/#imathelement) | สร้างเศษส่วนโดยใช้ตัวเศษนี้และตัวส่วนที่ระบุ |
| [`divide(self, denominator)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/divide/#str) | สร้างเศษส่วนโดยใช้ตัวเศษนี้และตัวส่วนที่ระบุ |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/divide/#imathelement-mathfractiontypes) | สร้างเศษส่วนประเภทที่ระบุโดยใช้ตัวเศษนี้และตัวส่วนที่ระบุ |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/divide/#str-mathfractiontypes) | สร้างเศษส่วนประเภทที่ระบุโดยใช้ตัวเศษนี้และตัวส่วนที่ระบุ |
| [`enclose(self)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/enclose/#) | ใส่กรอบองค์ประกอบคณิตศาสตร์ด้วยวงเล็บ |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/enclose/#char-char) | ใส่กรอบองค์ประกอบคณิตศาสตร์ด้วยอักขระที่ระบุ เช่น วงเล็บหรืออักขระอื่นเป็นกรอบ |
| [`function(self, function_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/function/#imathelement) | รับฟังก์ชันของอากูเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [`function(self, function_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/function/#str) | รับฟังก์ชันของอากูเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/as_argument_of_function/#imathelement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอากูเมนต์ |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/as_argument_of_function/#str) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอากูเมนต์ |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/as_argument_of_function/#mathfunctionsofoneargument) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอากูเมนต์ |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอากูเมนต์และอากูเมนต์เพิ่มเติมที่ระบุ |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/as_argument_of_function/#mathfunctionsoftwoarguments-str) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอากูเมนต์และอากูเมนต์เพิ่มเติมที่ระบุ |
| [`set_subscript(self, subscript)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/set_subscript/#imathelement) | สร้างตัวห้อย |
| [`set_subscript(self, subscript)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/set_subscript/#str) | สร้างตัวห้อย |
| [`set_superscript(self, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/set_superscript/#imathelement) | สร้างตัวยก |
| [`set_superscript(self, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/set_superscript/#str) | สร้างตัวยก |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_right/#imathelement-imathelement) | สร้างตัวห้อยและตัวยกที่ด้านขวา |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_right/#str-str) | สร้างตัวห้อยและตัวยกที่ด้านขวา |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_left/#imathelement-imathelement) | สร้างตัวห้อยและตัวยกที่ด้านซ้าย |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_left/#str-str) | สร้างตัวห้อยและตัวยกที่ด้านซ้าย |
| [`radical(self, degree)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/radical/#imathelement) | กำหนดรากคณิตศาสตร์ของระดับที่กำหนดจากอากูเมนต์ที่ระบุ |
| [`radical(self, degree)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/radical/#str) | กำหนดรากคณิตศาสตร์ของระดับที่กำหนดจากอากูเมนต์ที่ระบุ |
| [`set_upper_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/set_upper_limit/#imathelement) | รับขอบบน |
| [`set_upper_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/set_upper_limit/#str) | รับขอบบน |
| [`set_lower_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/set_lower_limit/#imathelement) | รับขอบล่าง |
| [`set_lower_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/set_lower_limit/#str) | รับขอบล่าง |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/nary/#mathnaryoperatortypes-imathelement-imathelement) | สร้างตัวดำเนินการ N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/nary/#mathnaryoperatortypes-str-str) | สร้างตัวดำเนินการ N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | รับอินทิกรัล |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-imathelement-imathelement) | รับอินทิกรัล |
| [`integral(self, integral_type)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes) | รับอินทิกรัลโดยไม่มีขอบเขต |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-str-str-mathlimitlocations) | รับอินทิกรัล |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-str-str) | รับอินทิกรัล |
| [`group(self)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/group/#) | ใส่องค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บปีกกาเปิดด้านล่าง |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/group/#char-mathtopbotpositions-mathtopbotpositions) | ใส่องค์ประกอบนี้ในกลุ่มโดยใช้อักขระจัดกลุ่มเช่นวงเล็บปีกกาท้ายหรืออักขระอื่น |
| [`to_border_box(self)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/to_border_box/#) | ใส่องค์ประกอบนี้ในกล่องขอบ |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | ใส่องค์ประกอบนี้ในกล่องขอบ |
| [`to_math_array(self)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/to_math_array/#) | วางในอาเรย์แนวตั้ง |
| [`accent(self, accent_character)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/accent/#char) | ตั้งเครื่องหมายสำเนียง (อักขระที่อยู่บนสุดขององค์ประกอบนี้) |
| [`overbar(self)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/overbar/#) | ตั้งบาร์บนสุดขององค์ประกอบนี้ |
| [`underbar(self)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/underbar/#) | ตั้งบาร์ด้านล่างขององค์ประกอบนี้ |
| [`to_box(self)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/to_box/#) | ใส่องค์ประกอบนี้ในกล่องที่ไม่ปรากฏ (การจัดกลุ่มเชิงตรรกะ) <br/>            ซึ่งใช้เพื่อจัดกลุ่มส่วนประกอบของสมการหรือข้อความคณิตศาสตร์อื่น ๆ<br/>            วัตถุกล่องนี้สามารถ (เช่น) ทำหน้าที่เป็นอีมูเลเตอร์ของตัวดำเนินการพร้อมหรือไม่มีจุดจัดแนว,<br/>            ทำหน้าที่เป็นจุดตัดบรรทัด, หรือจัดกลุ่มเพื่อไม่ให้มีการตัดบรรทัดภายใน. |
| [`get_children(self)`](/slides/python-net/th/aspose.slides.mathtext/mathaccent/get_children/#) | ดึงเอาอีเลเมนต์ลูก |

### ดูเพิ่มเติม
* คลาส [`MathAccent`](/slides/python-net/th/aspose.slides.mathtext/mathaccent)
* คลาส [`MathElementBase`](/slides/python-net/th/aspose.slides.mathtext/mathelementbase)
* โมดูล [`aspose.slides.mathtext`](/slides/python-net/th/aspose.slides.mathtext)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)