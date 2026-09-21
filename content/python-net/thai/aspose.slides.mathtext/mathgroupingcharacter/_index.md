---
title: MathGroupingCharacter class
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Python ผ่าน .NET
description: 
type: docs
url: /th/aspose.slides.mathtext/mathgroupingcharacter/
---
## MathGroupingCharacter คลาส

ระบุสัญลักษณ์การจัดกลุ่มเหนือหรือต่ำกว่าการแสดงผลโดยทั่วไปเพื่อเน้นความสัมพันธ์ระหว่างองค์ประกอบ

**การสืบทอด:**[`MathGroupingCharacter`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter) → [`MathElementBase`](/slides/python-net/th/aspose.slides.mathtext/mathelementbase)

ประเภท MathGroupingCharacter เปิดเผยสมาชิกต่อไปนี้:

## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/__init__/#imathelement) | กำหนดค่าอินสแตนซ์ใหม่ของคลาส MathGroupingCharacter <br/>            พร้อมกับอักขระการจัดกลุ่มค่าเริ่มต้น U+23DF (BOTTOM CURLY BRACKET) |
| [`__init__(self, element, character, position, vertical_justification)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/__init__/#imathelement-char-mathtopbotpositions-mathtopbotpositions) | กำหนดค่าอินสแตนซ์ใหม่ของคลาส MathGroupingCharacter. |

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`base`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/base/) | อาร์กิวเมนต์ฐาน |
| [`character`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/character/) | อักขระการจัดกลุ่ม<br/>            ค่าเริ่มต้น: U+23DF (BOTTOM CURLY BRACKET) |
| [`position`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/position/) | ตำแหน่งของอักขระการจัดกลุ่ม.<br/>            Default: Bottom |
| [`vertical_justification`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/vertical_justification/) | การจัดแนวตั้งของอักขระกลุ่ม.<br/>            ระบุการจัดตำแหน่งของออบเจ็กต์สัมพันธ์กับเส้นฐาน.<br/>            ตัวอย่างเช่น เมื่ออักขระกลุ่มอยู่เหนือออบเจ็กต์, <br/>            VerticalJustification of Top หมายความว่าด้านบนของออบเจ็กต์ตรงกับเส้นฐาน;<br/>            เมื่อ VerticalJustification ถูกตั้งเป็น Bottom, ด้านล่างของออบเจ็กต์อยู่บนเส้นฐาน<br/>            Default: Bottom สำหรับ Position=Top, และ Top สำหรับ Position=Bottom |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/join/#imathelement) | เชื่อมต่อส่วนคณิตศาสตร์และสร้างบล็อคคณิตศาสตร์ |
| [`join(self, math_text)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/join/#str) | เชื่อมต่อข้อความคณิตศาสตร์และสร้างบล็อคคณิตศาสตร์ |
| [`divide(self, denominator)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/divide/#imathelement) | สร้างเศษส่วนด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| [`divide(self, denominator)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/divide/#str) | สร้างเศษส่วนด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/divide/#imathelement-mathfractiontypes) | สร้างเศษส่วนประเภทที่ระบุด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/divide/#str-mathfractiontypes) | สร้างเศษส่วนประเภทที่ระบุด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| [`enclose(self)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/enclose/#) | ล้อมรอบส่วนคณิตศาสตร์ด้วยวงเล็บ |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/enclose/#char-char) | ล้อมรอบส่วนคณิตศาสตร์ด้วยอักขระที่ระบุ เช่น วงเล็บหรืออักขระอื่นเป็นกรอบ |
| [`function(self, function_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/function/#imathelement) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [`function(self, function_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/function/#str) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#imathelement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#str) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsofoneargument) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [`set_subscript(self, subscript)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/set_subscript/#imathelement) | สร้างตัวห้อย |
| [`set_subscript(self, subscript)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/set_subscript/#str) | สร้างตัวห้อย |
| [`set_superscript(self, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/set_superscript/#imathelement) | สร้างตัวเหนือ |
| [`set_superscript(self, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/set_superscript/#str) | สร้างตัวเหนือ |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_right/#imathelement-imathelement) | สร้างตัวห้อยและตัวเหนือทางด้านขวา |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_right/#str-str) | สร้างตัวห้อยและตัวเหนือทางด้านขวา |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_left/#imathelement-imathelement) | สร้างตัวห้อยและตัวเหนือทางด้านซ้าย |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_left/#str-str) | สร้างตัวห้อยและตัวเหนือทางด้านซ้าย |
| [`radical(self, degree)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/radical/#imathelement) | ระบุรูทคณิตศาสตร์ของระดับที่กำหนดจากอาร์กิวเมนต์ที่ระบุ |
| [`radical(self, degree)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/radical/#str) | ระบุรูทคณิตศาสตร์ของระดับที่กำหนดจากอาร์กิวเมนต์ที่ระบุ |
| [`set_upper_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/set_upper_limit/#imathelement) | รับค่าขอบบน |
| [`set_upper_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/set_upper_limit/#str) | รับค่าขอบบน |
| [`set_lower_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/set_lower_limit/#imathelement) | รับค่าขอบล่าง |
| [`set_lower_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/set_lower_limit/#str) | รับค่าขอบล่าง |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/nary/#mathnaryoperatortypes-imathelement-imathelement) | สร้างโอเปอเรเตอร์ N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/nary/#mathnaryoperatortypes-str-str) | สร้างโอเปอเรเตอร์ N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | รับอินทิกรัล |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement) | รับอินทิกรัล |
| [`integral(self, integral_type)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes) | รับอินทิกรัลโดยไม่มีขอบเขต |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-str-str-mathlimitlocations) | รับอินทิกรัล |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-str-str) | รับอินทิกรัล |
| [`group(self)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/group/#) | วางส่วนนี้ในกลุ่มโดยใช้วงเล็บโค้งล่าง |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/group/#char-mathtopbotpositions-mathtopbotpositions) | วางส่วนนี้ในกลุ่มโดยใช้อักขระการจัดกลุ่มเช่นวงเล็บโค้งล่างหรืออักขระอื่น |
| [`to_border_box(self)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/to_border_box/#) | วางส่วนนี้ในกล่องขอบ |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | วางส่วนนี้ในกล่องขอบ |
| [`to_math_array(self)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/to_math_array/#) | ใส่ในอาเรย์แนวตั้ง |
| [`accent(self, accent_character)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/accent/#char) | ตั้งเครื่องหมายสำเนียง (อักขระบนส่วนนี้) |
| [`overbar(self)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/overbar/#) | ตั้งบาร์บนส่วนนี้ |
| [`underbar(self)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/underbar/#) | ตั้งบาร์ที่ด้านล่างของส่วนนี้ |
| [`to_box(self)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/to_box/#) | วางส่วนนี้ในกล่องที่ไม่แสดงผล (การจัดกลุ่มเชิงโลจิก) <br/>            ซึ่งใช้เพื่อจัดกลุ่มส่วนประกอบของสมการหรือข้อความคณิตศาสตร์อื่น ๆ.<br/>            วัตถุที่อยู่ในกล่องสามารถ (เช่น) ทำหน้าที่เป็นตัวจำลองโอเปอเรเตอร์พร้อมหรือไม่มีจุดจัดตำแหน่ง, <br/>            ทำหน้าที่เป็นจุดตัดบรรทัด, หรือจัดกลุ่มเพื่อไม่ให้มีการตัดบรรทัดภายใน. |
| [`get_children(self)`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter/get_children/#) | รับองค์ประกอบลูก |

### ดูเพิ่มเติม
* คลาส [`MathElementBase`](/slides/python-net/th/aspose.slides.mathtext/mathelementbase)
* คลาส [`MathGroupingCharacter`](/slides/python-net/th/aspose.slides.mathtext/mathgroupingcharacter)
* โมดูล [`aspose.slides.mathtext`](/slides/python-net/th/aspose.slides.mathtext)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)