---
title: MathDelimiter class
second_title: อ้างอิง API Aspose.Slides สำหรับ Python ผ่าน .NET
description: 
type: docs
url: /th/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter คลาส

ระบุวัตถุ delimiter ซึ่งประกอบด้วยอักขระเปิดและปิด (เช่น วงเล็บ, เครื่องหมายโค้ง, วงเหลี่ยมเหลี่ยม, และแท่งแนวตั้ง) และหนึ่งหรือหลายองค์ประกอบคณิตศาสตร์ภายใน ที่คั่นด้วยอักขระที่ระบุ ตัวอย่าง: (𝑥2); [𝑥2|𝑦2]

**การสืบทอด:**[`MathDelimiter`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter) → [`MathElementBase`](/slides/python-net/th/aspose.slides.mathtext/mathelementbase)

ประเภท MathDelimiter แสดงสมาชิกต่อไปนี้:

## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/__init__/#imathelement) | เริ่มต้น MathDelimiter ด้วยองค์ประกอบที่ระบุเป็นอาร์กิวเมนต์ฐานเดียว |

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`arguments`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/arguments/) | หนึ่งหรือหลายองค์ประกอบคณิตศาสตร์ที่คั่นด้วยอักขระ delimiter |
| [`beginning_character`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/beginning_character/) | Delimiter Beginning Character ระบุอักขระ delimiter ที่เป็นจุดเริ่มต้น หรืออักขระเปิด <br/>            delimiter ทางคณิตศาสตร์คืออักขระที่ล้อมรอบ เช่น วงเล็บ, วงเหลี่ยม, และเครื่องหมายโค้ง.<br/>            ค่าเริ่มต้น: '(' |
| [`separator_character`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/separator_character/) | Delimiter Separator Character ระบุอักขระที่คั่นอาร์กิวเมนต์ในวัตถุ delimiter <br/>            ค่าเริ่มต้น: '\|' |
| [`ending_character`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/ending_character/) | Delimiter Ending Character ระบุอักขระ delimiter ที่เป็นจุดสิ้นสุด หรืออักขระปิด <br/>            delimiter ทางคณิตศาสตร์คืออักขระที่ล้อมรอบ เช่น วงเล็บ, วงเหลี่ยม, และเครื่องหมายโค้ง.<br/>            ค่าเริ่มต้น: ')' |
| [`grow_to_match_operand_height`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/grow_to_match_operand_height/) | ระบุการขยายของ BeginningCharacter, SeparatorCharacter, EndingCharacter<br/>            เมื่อเป็น true, delimiter จะขยายแนวตั้งเพื่อให้ตรงกับความสูงของ operand<br/>            ค่าเริ่มต้นคือ true |
| [`delimiter_shape`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/delimiter_shape/) | ระบุรูปแบบของ delimiter ในวัตถุ delimiter <br/>            เมื่อเป็น MathDelimiterShape.Centered, delimiter จะอยู่กึ่งกลางแกนคณิตศาสตร์ของข้อความคณิตศาสตร์ <br/>            และยังปรับให้พอดีกับความสูงทั้งหมดของเนื้อหา<br/>            เมื่อเป็น MathDelimiterShape.Match, ความสูงและรูปแบบของมันจะถูกปรับให้ตรงกับเนื้อหาอย่าง exact |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/join/#imathelement) | เชื่อมต่อองค์ประกอบคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| [`join(self, math_text)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/join/#str) | เชื่อมต่อข้อความคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| [`divide(self, denominator)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/divide/#imathelement) | สร้างเศษส่วนโดยใช้ตัวเศษนี้และส่วนที่ระบุ |
| [`divide(self, denominator)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/divide/#str) | สร้างเศษส่วนโดยใช้ตัวเศษนี้และส่วนที่ระบุ |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/divide/#imathelement-mathfractiontypes) | สร้างเศษส่วนประเภทที่ระบุโดยใช้ตัวเศษนี้และส่วนที่ระบุ |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/divide/#str-mathfractiontypes) | สร้างเศษส่วนประเภทที่ระบุโดยใช้ตัวเศษนี้และส่วนที่ระบุ |
| [`enclose(self)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/enclose/#) | ล้อมรอบองค์ประกอบคณิตศาสตร์ด้วยวงเล็บ |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/enclose/#char-char) | ล้อมรอบองค์ประกอบคณิตศาสตร์ด้วยอักขระที่ระบุ เช่น วงเล็บหรืออักขระอื่น ๆ เป็นกรอบ |
| [`function(self, function_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/function/#imathelement) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้ตัวอย่างนี้เป็นชื่อฟังก์ชัน |
| [`function(self, function_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/function/#str) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้ตัวอย่างนี้เป็นชื่อฟังก์ชัน |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#imathelement) | รับฟังก์ชันที่ระบุโดยใช้ตัวอย่างนี้เป็นอาร์กิวเมนต์ |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#str) | รับฟังก์ชันที่ระบุโดยใช้ตัวอย่างนี้เป็นอาร์กิวเมนต์ |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsofoneargument) | รับฟังก์ชันที่ระบุโดยใช้ตัวอย่างนี้เป็นอาร์กิวเมนต์ |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | รับฟังก์ชันที่ระบุโดยใช้ตัวอย่างนี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | รับฟังก์ชันที่ระบุโดยใช้ตัวอย่างนี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [`set_subscript(self, subscript)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/set_subscript/#imathelement) | สร้างซับสคริปต์ |
| [`set_subscript(self, subscript)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/set_subscript/#str) | สร้างซับสคริปต์ |
| [`set_superscript(self, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/set_superscript/#imathelement) | สร้างซูพอร์สคริปต์ |
| [`set_superscript(self, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/set_superscript/#str) | สร้างซูพอร์สคริปต์ |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#imathelement-imathelement) | สร้างซับสคริปต์และซูพอร์สคริปต์ทางด้านขวา |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#str-str) | สร้างซับสคริปต์และซูพอร์สคริปต์ทางด้านขวา |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#imathelement-imathelement) | สร้างซับสคริปต์และซูพอร์สคริปต์ทางด้านซ้าย |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#str-str) | สร้างซับสคริปต์และซูพอร์สคริปต์ทางด้านซ้าย |
| [`radical(self, degree)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/radical/#imathelement) | ระบุรากคณิตศาสตร์ของระดับที่กำหนดจากอาร์กิวเมนต์ที่ระบุ |
| [`radical(self, degree)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/radical/#str) | ระบุรากคณิตศาสตร์ของระดับที่กำหนดจากอาร์กิวเมนต์ที่ระบุ |
| [`set_upper_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#imathelement) | รับขีดบน |
| [`set_upper_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#str) | รับขีดบน |
| [`set_lower_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#imathelement) | รับขีดล่าง |
| [`set_lower_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#str) | รับขีดล่าง |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-imathelement-imathelement) | สร้างตัวดำเนินการ N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-str-str) | สร้างตัวดำเนินการ N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | รับอินทิกรัล |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement) | รับอินทิกรัล |
| [`integral(self, integral_type)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes) | รับอินทิกรัลโดยไม่มีขีดจำกัด |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str-mathlimitlocations) | รับอินทิกรัล |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str) | รับอินทิกรัล |
| [`group(self)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/group/#) | ใส่องค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บปีกกาล่าง |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/group/#char-mathtopbotpositions-mathtopbotpositions) | ใส่องค์ประกอบนี้ในกลุ่มโดยใช้อักขระการจัดกลุ่ม เช่น วงเล็บปีกกาล่างหรืออื่น ๆ |
| [`to_border_box(self)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/to_border_box/#) | ใส่องค์ประกอบนี้ในกล่องขอบ |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | ใส่องค์ประกอบนี้ในกล่องขอบ |
| [`to_math_array(self)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/to_math_array/#) | ใส่ในอาเรย์แนวตั้ง |
| [`accent(self, accent_character)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/accent/#char) | ตั้งเครื่องหมายสำเนียง (อักขระบนสุดขององค์ประกอบนี้) |
| [`overbar(self)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/overbar/#) | ตั้งบาร์บนสุดขององค์ประกอบนี้ |
| [`underbar(self)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/underbar/#) | ตั้งบาร์ด้านล่างขององค์ประกอบนี้ |
| [`to_box(self)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/to_box/#) | ใส่องค์ประกอบนี้ในกล่องที่ไม่แสดงผล (การจัดกลุ่มเชิงตรรกะ) <br/>            ซึ่งใช้เพื่อจัดกลุ่มส่วนประกอบของสมการหรือข้อความคณิตศาสตร์อื่น ๆ<br/>            วัตถุในกล่องสามารถ (เช่น) ทำหน้าที่เป็นอิมูเลเตอร์ของตัวดำเนินการพร้อมหรือไม่มีจุดจัดแนว,<br/>            ทำหน้าที่เป็นจุดตัดบรรทัด, หรือจัดกลุ่มเพื่อไม่ให้มีการตัดบรรทัดภายใน |
| [`delimit(self, separator_character)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/delimit/#char) | จำกัดอาร์กิวเมนต์โดยใช้อักขระ delimiter ที่ระบุ |
| [`get_children(self)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/get_children/#) | รับองค์ประกอบลูก |

### ดูเพิ่มเติม
* คลาส [`MathDelimiter`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter)
* คลาส [`MathElementBase`](/slides/python-net/th/aspose.slides.mathtext/mathelementbase)
* โมดูล [`aspose.slides.mathtext`](/slides/python-net/th/aspose.slides.mathtext)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)