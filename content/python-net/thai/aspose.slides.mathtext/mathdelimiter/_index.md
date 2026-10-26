---
title: MathDelimiter class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter คลาส

กำหนดวัตถุตัวคั่นซึ่งประกอบด้วยอักขระเปิดและปิด (เช่น วงเล็บ, โค้ง, วงเกลียว, และแท่งแนวตั้ง) และหนึ่งหรือหลายองค์ประกอบทางคณิตศาสตร์ภายในที่แยกด้วยอักขระที่ระบุ
            ตัวอย่าง: (𝑥2); [𝑥2|𝑦2]

**Inheritance:**[`MathDelimiter`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter) → [`MathElementBase`](/slides/python-net/th/aspose.slides.mathtext/mathelementbase)

ประเภท MathDelimiter เปิดเผยสมาชิกต่อไปนี้:

## คอนสตรัคเตอร์

| Constructor | Description |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/__init__/#imathelement) | กำหนดค่าเริ่มต้น MathDelimiter ด้วยองค์ประกอบที่ระบุเป็นอากิวเมนต์ฐานเดียว |

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`arguments`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/arguments/) | หนึ่งหรือหลายองค์ประกอบทางคณิตศาสตร์ที่แยกด้วยอักขระตัวคั่น |
| [`beginning_character`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/beginning_character/) | อักขระเริ่มต้นของตัวคั่นระบุอักขระเริ่มต้นหรืออักขระเปิดของตัวคั่น. <br/> ตัวคั่นทางคณิตศาสตร์เป็นอักขระที่ล้อมรอบเช่นวงเล็บ, วงเกลียว, และโค้ง.<br/> ค่าเริ่มต้น: '('. |
| [`separator_character`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/separator_character/) | อักขระคั่นของตัวคั่นระบุอักขระที่แยกอากิวเมนต์ในวัตถุตัวคั่น. <br/> ค่าเริ่มต้น: '\|'. |
| [`ending_character`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/ending_character/) | อักขระสิ้นสุดของตัวคั่นระบุอักขระปิดหรือสิ้นสุดของตัวคั่น. <br/> ตัวคั่นทางคณิตศาสตร์เป็นอักขระที่ล้อมรอบเช่นวงเล็บ, วงเกลียว, และโค้ง.<br/> ค่าเริ่มต้น: ')'. |
| [`grow_to_match_operand_height`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/grow_to_match_operand_height/) | ระบุการขยายของ BeginningCharacter, SeparatorCharacter, EndingCharacter<br/> เมื่อเป็น true, ตัวคั่นจะขยายในแนวตั้งเพื่อให้ตรงกับความสูงของตัวรับค่า.<br/> ค่าตั้งต้นคือ true |
| [`delimiter_shape`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/delimiter_shape/) | ระบุรูปแบบของตัวคั่นในวัตถุตัวคั่น. <br/> เมื่อเป็น MathDelimiterShape.Centered, ตัวคั่นจะถูกจัดศูนย์รอบแกนคณิตศาสตร์ของข้อความคณิตศาสตร์ <br/> และยังคงทำให้เข้ากับความสูงทั้งหมดของเนื้อหา.<br/> เมื่อเป็น MathDelimiterShape.Match, ความสูงและรูปแบบของมันจะถูกปรับให้ตรงกับเนื้อหาอย่างแม่นยำ. |

## เมธอด

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/join/#imathelement) | เชื่อมต่อองค์ประกอบทางคณิตศาสตร์และสร้างบล็อกทางคณิตศาสตร์ |
| [`join(self, math_text)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/join/#str) | เชื่อมต่อข้อความทางคณิตศาสตร์และสร้างบล็อกทางคณิตศาสตร์ |
| [`divide(self, denominator)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/divide/#imathelement) | สร้างเศษส่วนโดยใช้ตัวเศษนี้และตัวส่วนที่ระบุ |
| [`divide(self, denominator)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/divide/#str) | สร้างเศษส่วนโดยใช้ตัวเศษนี้และตัวส่วนที่ระบุ |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/divide/#imathelement-mathfractiontypes) | สร้างเศษส่วนประเภทที่ระบุด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/divide/#str-mathfractiontypes) | สร้างเศษส่วนประเภทที่ระบุด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/enclose/#char-char) | ล้อมรอบองค์ประกอบทางคณิตศาสตร์ด้วยอักขระที่ระบุเช่นวงเล็บหรืออักขระอื่นเป็นกรอบ |
| [`enclose(self)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/enclose/#) | ล้อมรอบองค์ประกอบทางคณิตศาสตร์ด้วยวงเล็บ |
| [`function(self, function_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/function/#imathelement) | รับฟังก์ชันของอากิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [`function(self, function_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/function/#str) | รับฟังก์ชันของอากิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#imathelement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอากิวเมนต์ |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#str) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอากิวเมนต์ |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsofoneargument) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอากิวเมนต์ |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอากิวเมนต์และอากิวเมนต์เพิ่มเติมที่ระบุ |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอากิวเมนต์และอากิวเมนต์เพิ่มเติมที่ระบุ |
| [`set_subscript(self, subscript)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/set_subscript/#imathelement) | สร้างตัวห้อย |
| [`set_subscript(self, subscript)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/set_subscript/#str) | สร้างตัวห้อย |
| [`set_superscript(self, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/set_superscript/#imathelement) | สร้างตัวบน |
| [`set_superscript(self, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/set_superscript/#str) | สร้างตัวบน |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#imathelement-imathelement) | สร้างตัวห้อยและตัวบนทางด้านขวา |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#str-str) | สร้างตัวห้อยและตัวบนทางด้านขวา |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#imathelement-imathelement) | สร้างตัวห้อยและตัวบนทางด้านซ้าย |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#str-str) | สร้างตัวห้อยและตัวบนทางด้านซ้าย |
| [`radical(self, degree)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/radical/#imathelement) | ระบุรากคณิตศาสตร์ของระดับที่กำหนดจากอากิวเมนต์ที่ระบุ. |
| [`radical(self, degree)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/radical/#str) | ระบุรากคณิตศาสตร์ของระดับที่กำหนดจากอากิวเมนต์ที่ระบุ. |
| [`set_upper_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#imathelement) | รับค่าขอบบน |
| [`set_upper_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#str) | รับค่าขอบบน |
| [`set_lower_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#imathelement) | รับค่าขอบล่าง |
| [`set_lower_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#str) | รับค่าขอบล่าง |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-imathelement-imathelement) | สร้างตัวดำเนินการ N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-str-str) | สร้างตัวดำเนินการ N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | รับอินทิกรัล |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement) | รับอินทิกรัล |
| [`integral(self, integral_type)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes) | รับอินทิกรัลโดยไม่มีขอบ |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str-mathlimitlocations) | รับอินทิกรัล |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str) | รับอินทิกรัล |
| [`group(self)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/group/#) | วางองค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บปีกกาด้านล่าง |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/group/#char-mathtopbotpositions-mathtopbotpositions) | วางองค์ประกอบนี้ในกลุ่มโดยใช้อักขระการจัดกลุ่มเช่นวงเล็บปีกกาด้านล่างหรืออักขระอื่น |
| [`to_border_box(self)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/to_border_box/#) | วางองค์ประกอบนี้ในกล่องขอบ |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | วางองค์ประกอบนี้ในกล่องขอบ |
| [`to_math_array(self)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/to_math_array/#) | ใส่ในอาร์เรย์แนวตั้ง |
| [`accent(self, accent_character)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/accent/#char) | ตั้งเครื่องหมายสำเนียง (อักขระบนสุดขององค์ประกอบนี้) |
| [`overbar(self)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/overbar/#) | ตั้งบาร์บนสุดขององค์ประกอบนี้ |
| [`underbar(self)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/underbar/#) | ตั้งบาร์ล่างขององค์ประกอบนี้ |
| [`to_box(self)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/to_box/#) | วางองค์ประกอบนี้ในกล่องที่ไม่แสดงผล (การจัดกลุ่มเชิงตรรกะ) <br/> ที่ใช้เพื่อจัดกลุ่มส่วนประกอบของสมการหรือข้อความคณิตศาสตร์อื่น ๆ.<br/> วัตถุที่อยู่ในกล่องสามารถ (เช่น) ทำหน้าที่เป็นตัวจำลองตัวดำเนินการโดยมีหรือไม่มีจุดจัดแนว, <br/> ทำหน้าที่เป็นจุดตัดบรรทัด, หรือจัดกลุ่มเพื่อไม่ให้มีการตัดบรรทัดภายใน. |
| [`delimit(self, separator_character)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/delimit/#char) | คั่นอากิวเมนต์โดยใช้ตัวคั่นที่ระบุ |
| [`get_children(self)`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter/get_children/#) | รับองค์ประกอบลูก |

### ดูเพิ่มเติม
* คลาส [`MathDelimiter`](/slides/python-net/th/aspose.slides.mathtext/mathdelimiter)
* คลาส [`MathElementBase`](/slides/python-net/th/aspose.slides.mathtext/mathelementbase)
* โมดูล [`aspose.slides.mathtext`](/slides/python-net/th/aspose.slides.mathtext)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)