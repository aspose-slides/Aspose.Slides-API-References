---
title: MathArray class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API อ้างอิง
description: 
type: docs
url: /th/aspose.slides.mathtext/matharray/
---
## MathArray คลาส

ระบุอาเรย์แนวตั้งของสมการหรือวัตถุทางคณิตศาสตร์ใด ๆ

**การสืบทอด:**[`MathArray`](/slides/python-net/th/aspose.slides.mathtext/matharray) → [`MathElementBase`](/slides/python-net/th/aspose.slides.mathtext/mathelementbase)

ประเภท MathArray เปิดเผยสมาชิกต่อไปนี้:

## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/th/aspose.slides.mathtext/matharray/__init__/#imathelement) | สร้างอาเรย์ทางคณิตศาสตร์และวางองค์ประกอบที่ระบุไว้ในนั้น |
| [`__init__(self, elements)`](/slides/python-net/th/aspose.slides.mathtext/matharray/__init__/#iterableimathelement) |  |

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`arguments`](/slides/python-net/th/aspose.slides.mathtext/matharray/arguments/) | ชุดของรายการในอาเรย์ |
| [`base_justification`](/slides/python-net/th/aspose.slides.mathtext/matharray/base_justification/) | ระบุการจัดตำแหน่งของอาเรย์สัมพันธ์กับข้อความรอบข้าง<br/>            ข้อความที่อยู่นอกอาเรย์สามารถจัดตำแหน่งกับด้านล่าง, ด้านบน, หรือศูนย์กลางของออบเจกต์อาเรย์ได้.<br/>            ค่าเริ่มต้น: Center |
| [`maximum_distribution`](/slides/python-net/th/aspose.slides.mathtext/matharray/maximum_distribution/) | การกระจายสูงสุด<br/>            เมื่อเป็น true, อาเรย์จะถูกจัดระยะห่างให้เต็มความกว้างสูงสุดขององค์ประกอบที่บรรจุ (หน้า, คอลัมน์, เซลล์, ฯลฯ). |
| [`object_distribution`](/slides/python-net/th/aspose.slides.mathtext/matharray/object_distribution/) | การกระจายออบเจกต์<br/>            เมื่อเป็น true, เนื้อหาในอาเรย์จะถูกจัดระยะห่างให้เต็มความกว้างสูงสุดของออบเจกต์อาเรย์. |
| [`row_spacing_rule`](/slides/python-net/th/aspose.slides.mathtext/matharray/row_spacing_rule/) | ประเภทของช่องว่างแนวตั้งระหว่างองค์ประกอบของอาเรย์<br/>            ค่าเริ่มต้น: SingleLineGap |
| [`row_spacing`](/slides/python-net/th/aspose.slides.mathtext/matharray/row_spacing/) | การเว้นระยะระหว่างแถวของอาเรย์<br/>            ใช้เฉพาะเมื่อ RowSpacingRule ถูกตั้งค่าเป็น 3 Exactly ซึ่งหน่วยวัดจะเป็น points <br/>            หรือ Multiple ซึ่งหน่วยวัดจะเป็น half-lines.<br/>            ค่าเริ่มต้น: 0 |

## วิธีการ

| วิธีการ | คำอธิบาย |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/th/aspose.slides.mathtext/matharray/join/#imathelement) | เชื่อมต่อองค์ประกอบทางคณิตศาสตร์และสร้างบล็อกทางคณิตศาสตร์ |
| [`join(self, math_text)`](/slides/python-net/th/aspose.slides.mathtext/matharray/join/#str) | เชื่อมต่อข้อความทางคณิตศาสตร์และสร้างบล็อกทางคณิตศาสตร์ |
| [`divide(self, denominator)`](/slides/python-net/th/aspose.slides.mathtext/matharray/divide/#imathelement) | สร้างเศษส่วนด้วยตัวเศษนี้และตัวส่วนที่กำหนด |
| [`divide(self, denominator)`](/slides/python-net/th/aspose.slides.mathtext/matharray/divide/#str) | สร้างเศษส่วนด้วยตัวเศษนี้และตัวส่วนที่กำหนด |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/th/aspose.slides.mathtext/matharray/divide/#imathelement-mathfractiontypes) | สร้างเศษส่วนประเภทที่กำหนดด้วยตัวเศษนี้และตัวส่วนที่กำหนด |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/th/aspose.slides.mathtext/matharray/divide/#str-mathfractiontypes) | สร้างเศษส่วนประเภทที่กำหนดด้วยตัวเศษนี้และตัวส่วนที่กำหนด |
| [`enclose(self)`](/slides/python-net/th/aspose.slides.mathtext/matharray/enclose/#) | ล้อมรอบองค์ประกอบคณิตศาสตร์ด้วยวงเล็บ |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/th/aspose.slides.mathtext/matharray/enclose/#char-char) | ล้อมรอบองค์ประกอบคณิตศาสตร์ด้วยอักขระที่กำหนด เช่น วงเล็บหรืออักขระอื่นเป็นกรอบ |
| [`function(self, function_argument)`](/slides/python-net/th/aspose.slides.mathtext/matharray/function/#imathelement) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [`function(self, function_argument)`](/slides/python-net/th/aspose.slides.mathtext/matharray/function/#str) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/th/aspose.slides.mathtext/matharray/as_argument_of_function/#imathelement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/th/aspose.slides.mathtext/matharray/as_argument_of_function/#str) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/th/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsofoneargument) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/th/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/th/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsoftwoarguments-str) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [`set_subscript(self, subscript)`](/slides/python-net/th/aspose.slides.mathtext/matharray/set_subscript/#imathelement) | สร้างตัวห้อย |
| [`set_subscript(self, subscript)`](/slides/python-net/th/aspose.slides.mathtext/matharray/set_subscript/#str) | สร้างตัวห้อย |
| [`set_superscript(self, superscript)`](/slides/python-net/th/aspose.slides.mathtext/matharray/set_superscript/#imathelement) | สร้างตัวบน |
| [`set_superscript(self, superscript)`](/slides/python-net/th/aspose.slides.mathtext/matharray/set_superscript/#str) | สร้างตัวบน |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_right/#imathelement-imathelement) | สร้างตัวห้อยและตัวบนทางด้านขวา |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_right/#str-str) | สร้างตัวห้อยและตัวบนทางด้านขวา |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_left/#imathelement-imathelement) | สร้างตัวห้อยและตัวบนทางด้านซ้าย |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_left/#str-str) | สร้างตัวห้อยและตัวบนทางด้านซ้าย |
| [`radical(self, degree)`](/slides/python-net/th/aspose.slides.mathtext/matharray/radical/#imathelement) | ระบุรูทคณิตศาสตร์ของระดับที่กำหนดจากอาร์กิวเมนต์ที่ระบุ |
| [`radical(self, degree)`](/slides/python-net/th/aspose.slides.mathtext/matharray/radical/#str) | ระบุรูทคณิตศาสตร์ของระดับที่กำหนดจากอาร์กิวเมนต์ที่ระบุ |
| [`set_upper_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/matharray/set_upper_limit/#imathelement) | รับขอบบน |
| [`set_upper_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/matharray/set_upper_limit/#str) | รับขอบบน |
| [`set_lower_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/matharray/set_lower_limit/#imathelement) | รับขอบล่าง |
| [`set_lower_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/matharray/set_lower_limit/#str) | รับขอบล่าง |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/matharray/nary/#mathnaryoperatortypes-imathelement-imathelement) | สร้างตัวดำเนินการ N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/matharray/nary/#mathnaryoperatortypes-str-str) | สร้างตัวดำเนินการ N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/th/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | รับอินทิกรัล |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-imathelement-imathelement) | รับอินทิกรัล |
| [`integral(self, integral_type)`](/slides/python-net/th/aspose.slides.mathtext/matharray/integral/#mathintegraltypes) | รับอินทิกรัลโดยไม่มีขอบ |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/th/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-str-str-mathlimitlocations) | รับอินทิกรัล |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-str-str) | รับอินทิกรัล |
| [`group(self)`](/slides/python-net/th/aspose.slides.mathtext/matharray/group/#) | วางองค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บปีกกาล่าง |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/th/aspose.slides.mathtext/matharray/group/#char-mathtopbotpositions-mathtopbotpositions) | วางองค์ประกอบนี้ในกลุ่มโดยใช้อักขระจัดกลุ่มเช่นวงเล็บปีกกาใต้หรืออักขระอื่น |
| [`to_border_box(self)`](/slides/python-net/th/aspose.slides.mathtext/matharray/to_border_box/#) | วางองค์ประกอบนี้ในกล่องขอบ |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/th/aspose.slides.mathtext/matharray/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | วางองค์ประกอบนี้ในกล่องขอบ |
| [`to_math_array(self)`](/slides/python-net/th/aspose.slides.mathtext/matharray/to_math_array/#) | ใส่ในอาเรย์แนวตั้ง |
| [`accent(self, accent_character)`](/slides/python-net/th/aspose.slides.mathtext/matharray/accent/#char) | ตั้งเครื่องหมายสำเนียง (อักขระบนสุดขององค์ประกอบนี้) |
| [`overbar(self)`](/slides/python-net/th/aspose.slides.mathtext/matharray/overbar/#) | ตั้งบาร์บนสุดขององค์ประกอบนี้ |
| [`underbar(self)`](/slides/python-net/th/aspose.slides.mathtext/matharray/underbar/#) | ตั้งบาร์ล่างขององค์ประกอบนี้ |
| [`to_box(self)`](/slides/python-net/th/aspose.slides.mathtext/matharray/to_box/#) | วางองค์ประกอบนี้ในกล่องที่ไม่ปรากฏ (การจัดกลุ่มเชิงตรรกะ) <br/>            ซึ่งใช้เพื่อจัดกลุ่มส่วนประกอบของสมการหรือข้อความทางคณิตศาสตร์อื่น.<br/>            วัตถุในกล่องสามารถ (เช่น) ทำหน้าที่เป็นตัวจำลองตัวดำเนินการพร้อมหรือไม่มีจุดจัดตำแหน่ง, <br/>            ทำหน้าที่เป็นจุดแบ่งบรรทัด, หรือจัดกลุ่มเพื่อไม่ให้มีการแบ่งบรรทัดภายใน. |
| [`get_children(self)`](/slides/python-net/th/aspose.slides.mathtext/matharray/get_children/#) | รับองค์ประกอบลูก |

### ดูเพิ่มเติม
* คลาส [`MathArray`](/slides/python-net/th/aspose.slides.mathtext/matharray)
* คลาส [`MathElementBase`](/slides/python-net/th/aspose.slides.mathtext/mathelementbase)
* โมดูล [`aspose.slides.mathtext`](/slides/python-net/th/aspose.slides.mathtext)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)