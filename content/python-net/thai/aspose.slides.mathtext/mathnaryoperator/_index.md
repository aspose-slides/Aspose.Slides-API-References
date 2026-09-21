---
title: MathNaryOperator class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.mathtext/mathnaryoperator/
---
## MathNaryOperator คลาส

ระบุวัตถุคณิตศาสตร์แบบ N-ary เช่น Summation และ Integral.
            It consists of an operator, a base (or operand), and optional upper and lower limits. 
            ตัวอย่างของตัวดำเนินการ N-ary ได้แก่: Summation, Union, Intersection, Integral

**การสืบทอด:**[`MathNaryOperator`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator) → [`MathElementBase`](/slides/python-net/th/aspose.slides.mathtext/mathelementbase)

ประเภท MathNaryOperator เปิดเผยสมาชิกต่อไปนี้:

## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| :- | :- |
| [`__init__(self, operator_symbol, base_argument, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement-imathelement-imathelement) | สร้างอินสแตนซ์ใหม่ของคลาส MathNaryOperator. |
| [`__init__(self, operator_symbol, base_argument, lower_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement-imathelement) | สร้างอินสแตนซ์ใหม่ของคลาส MathNaryOperator. |
| [`__init__(self, operator_symbol, base_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement) | สร้างอินสแตนซ์ใหม่ของคลาส MathNaryOperator. |

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`base`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/base/) | อาร์กิวเมนต์ฐาน |
| [`subscript`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/subscript/) | ระบุอาร์กิวเมนต์ซับสคริปต์ที่, ตัวอย่างเช่นในกรณีของ integral, กำหนดขอบล่าง |
| [`superscript`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/superscript/) | ระบุอาร์กิวเมนต์ซูเปอร์สคริปต์ที่, ตัวอย่างเช่นในกรณีของ integral, กำหนดขอบบน |
| [`operator`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/operator/) | อักขระตัวดำเนินการ Nary<br/>            ตัวอย่าง: '∑', '∫' |
| [`limit_location`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/limit_location/) | ตำแหน่งของขอบ (ซับสคริปต์และซูเปอร์สคริปต์) |
| [`grow_to_match_operand_height`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/grow_to_match_operand_height/) | อักขระตัวดำเนินการขยายแนวตั้งเพื่อให้ตรงกับความสูงของ operand |
| [`hide_subscript`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/hide_subscript/) | ซ่อนซับสคริปต์ |
| [`hide_superscript`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/hide_superscript/) | ซ่อนซูเปอร์สคริปต์ |

## วิธี

| วิธี | คำอธิบาย |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/join/#imathelement) | เชื่อมต่อองค์ประกอบคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| [`join(self, math_text)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/join/#str) | เชื่อมต่อข้อความคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| [`divide(self, denominator)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/divide/#imathelement) | สร้างเศษส่วนด้วยเศษนี้และตัวส่วนที่ระบุ |
| [`divide(self, denominator)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/divide/#str) | สร้างเศษส่วนด้วยเศษนี้และตัวส่วนที่ระบุ |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/divide/#imathelement-mathfractiontypes) | สร้างเศษส่วนประเภทที่ระบุด้วยเศษนี้และตัวส่วนที่ระบุ |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/divide/#str-mathfractiontypes) | สร้างเศษส่วนประเภทที่ระบุด้วยเศษนี้และตัวส่วนที่ระบุ |
| [`enclose(self)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/enclose/#) | ล้อมรอบองค์ประกอบคณิตศาสตร์ด้วยวงเล็บ |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/enclose/#char-char) | ล้อมรอบองค์ประกอบคณิตศาสตร์ด้วยอักขระที่ระบุ เช่น วงเล็บหรืออักขระอื่นเป็นกรอบ |
| [`function(self, function_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/function/#imathelement) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [`function(self, function_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/function/#str) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#imathelement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#str) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsofoneargument) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsoftwoarguments-str) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [`set_subscript(self, subscript)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/set_subscript/#imathelement) | สร้างซับสคริปต์ |
| [`set_subscript(self, subscript)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/set_subscript/#str) | สร้างซับสคริปต์ |
| [`set_superscript(self, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/set_superscript/#imathelement) | สร้างซูเปอร์สคริปต์ |
| [`set_superscript(self, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/set_superscript/#str) | สร้างซูเปอร์สคริปต์ |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_right/#imathelement-imathelement) | สร้างซับสคริปต์และซูเปอร์สคริปต์ด้านขวา |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_right/#str-str) | สร้างซับสคริปต์และซูเปอร์สคริปต์ด้านขวา |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_left/#imathelement-imathelement) | สร้างซับสคริปต์และซูเปอร์สคริปต์ด้านซ้าย |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_left/#str-str) | สร้างซับสคริปต์และซูเปอร์สคริปต์ด้านซ้าย |
| [`radical(self, degree)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/radical/#imathelement) | ระบุรากคณิตศาสตร์ของระดับที่กำหนดจากอาร์กิวเมนต์ที่ระบุ. |
| [`radical(self, degree)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/radical/#str) | ระบุรากคณิตศาสตร์ของระดับที่กำหนดจากอาร์กิวเมนต์ที่ระบุ. |
| [`set_upper_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/set_upper_limit/#imathelement) | รับค่าขอบบน |
| [`set_upper_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/set_upper_limit/#str) | รับค่าขอบบน |
| [`set_lower_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/set_lower_limit/#imathelement) | รับค่าขอบล่าง |
| [`set_lower_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/set_lower_limit/#str) | รับค่าขอบล่าง |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/nary/#mathnaryoperatortypes-imathelement-imathelement) | สร้างตัวดำเนินการ N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/nary/#mathnaryoperatortypes-str-str) | สร้างตัวดำเนินการ N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | รับ integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-imathelement-imathelement) | รับ integral |
| [`integral(self, integral_type)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes) | รับ integral โดยไม่มีขอบ |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-str-str-mathlimitlocations) | รับ integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-str-str) | รับ integral |
| [`group(self)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/group/#) | วางองค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บปีกกาล่าง |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/group/#char-mathtopbotpositions-mathtopbotpositions) | วางองค์ประกอบนี้ในกลุ่มโดยใช้ตัวอักษรกำหนดกลุ่ม เช่น วงเล็บปีกกาล่างหรืออักขระอื่น |
| [`to_border_box(self)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/to_border_box/#) | วางองค์ประกอบนี้ในกล่องขอบ |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | วางองค์ประกอบนี้ในกล่องขอบ |
| [`to_math_array(self)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/to_math_array/#) | ใส่ในอาร์เรย์แนวตั้ง |
| [`accent(self, accent_character)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/accent/#char) | ตั้งเครื่องหมายสำเนียง (อักขระบนสุดขององค์ประกอบนี้) |
| [`overbar(self)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/overbar/#) | ตั้งบาร์บนสุดขององค์ประกอบนี้ |
| [`underbar(self)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/underbar/#) | ตั้งบาร์ด้านล่างขององค์ประกอบนี้ |
| [`to_box(self)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/to_box/#) | วางองค์ประกอบนี้ในกล่องที่ไม่แสดงผล (การจัดกลุ่มเชิงตรรกะ) <br/>            ที่ใช้เพื่อจัดกลุ่มส่วนประกอบของสมการหรือข้อความคณิตศาสตร์อื่น ๆ<br/>            วัตถุที่อยู่ในกล่องสามารถ (ตัวอย่างเช่น) ทำหน้าที่เป็นอิมูเลเตอร์ตัวดำเนินการที่มีหรือไม่มีจุดจัดแนว, <br/>            ทำหน้าที่เป็นจุดขึ้นบรรทัดใหม่, หรือจัดกลุ่มเพื่อไม่ให้มีการขึ้นบรรทัดใหม่ภายใน. |
| [`get_children(self)`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator/get_children/#) | รับองค์ประกอบลูก |

### ดูเพิ่มเติม
* คลาส [`MathElementBase`](/slides/python-net/th/aspose.slides.mathtext/mathelementbase)
* คลาส [`MathNaryOperator`](/slides/python-net/th/aspose.slides.mathtext/mathnaryoperator)
* โมดูล [`aspose.slides.mathtext`](/slides/python-net/th/aspose.slides.mathtext)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)