---
title: MathBlock class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.mathtext/mathblock/
---
## MathBlock คลาส

ระบุอินสแตนซ์ของข้อความคณิตศาสตร์ที่อยู่ภายใน MathParagraph และเริ่มต้นบนบรรทัดของมันเอง. ทั้งโซนคณิตศาสตร์ ได้แก่ สมการ, นิพจน์, อาเรย์ของสมการหรือ นิพจน์, และสูตร แทนด้วย math block.

**การสืบทอด:**[`MathBlock`](/slides/python-net/th/aspose.slides.mathtext/mathblock) → [`MathElementBase`](/slides/python-net/th/aspose.slides.mathtext/mathelementbase)

ประเภท MathBlock เปิดเผยสมาชิกต่อไปนี้:

## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| :- | :- |
| [`__init__(self)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/__init__/#) | สร้างอินสแตนซ์ใหม่ของคลาส MathBlock. |
| [`__init__(self, math_element)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/__init__/#imathelement) | สร้างบล็อกคณิตศาสตร์ใหม่และใส่องค์ประกอบที่ระบุเข้าไป |
| [`__init__(self, math_elements)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/__init__/#iterableimathelement) |  |

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`count`](/slides/python-net/th/aspose.slides.mathtext/mathblock/count/) | รับจำนวนของ child math elements ที่จริง ๆ มีอยู่ในคอลเลกชัน.<br/>            อ่านอย่างเดียว **int**. |
| [`is_read_only`](/slides/python-net/th/aspose.slides.mathtext/mathblock/is_read_only/) | คืนค่า false เพราะคอลเลกชันของ child elements สามารถถูกแก้ไขได้. |

รับหรือกำหนด IMathElement ที่ดัชนีที่ระบุ.

## ดัชนี

| ชื่อ | คำอธิบาย |
| :- | :- |
| [`[index]`](/slides/python-net/th/aspose.slides.mathtext/mathblock/__getitem__/) | ดัชนีแบบศูนย์ฐานของรายการ |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/join/#imathelement) | เชื่อมต่อองค์ประกอบคณิตศาสตร์กับบล็อกคณิตศาสตร์นี้ |
| [`join(self, math_text)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/join/#str) | เชื่อมต่อข้อความคณิตศาสตร์กับบล็อกคณิตศาสตร์นี้ |
| [`divide(self, denominator)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/divide/#imathelement) | สร้างส่วนที่มีตัวเศษนี้และตัวหารที่ระบุ |
| [`divide(self, denominator)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/divide/#str) | สร้างส่วนที่มีตัวเศษนี้และตัวหารที่ระบุ |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/divide/#imathelement-mathfractiontypes) | สร้างส่วนของประเภทที่ระบุโดยมีตัวเศษนี้และตัวหารที่ระบุ |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/divide/#str-mathfractiontypes) | สร้างส่วนของประเภทที่ระบุโดยมีตัวเศษนี้และตัวหารที่ระบุ |
| [`enclose(self)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/enclose/#) | ทำให้ส่วนคณิตศาสตร์อยู่ในวงเล็บ |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/enclose/#char-char) | ทำให้ child elements ของบล็อกนี้อยู่ในอักขระที่ระบุ เช่น วงเล็บหรืออักขระอื่นเป็นกรอบ |
| [`enclose(self, beginning_character, ending_character, separator_character)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/enclose/#char-char-char) | ทำให้ child elements ของบล็อกนี้อยู่ในอักขระที่ระบุ เช่น วงเล็บหรืออักขระอื่นเป็นกรอบ<br/>            และแยกด้วยอักขระตัวแบ่ง |
| [`function(self, function_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/function/#imathelement) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [`function(self, function_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/function/#str) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/as_argument_of_function/#imathelement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/as_argument_of_function/#str) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsofoneargument) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-str) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [`set_subscript(self, subscript)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/set_subscript/#imathelement) | สร้าง subscript |
| [`set_subscript(self, subscript)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/set_subscript/#str) | สร้าง subscript |
| [`set_superscript(self, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/set_superscript/#imathelement) | สร้าง superscript |
| [`set_superscript(self, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/set_superscript/#str) | สร้าง superscript |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#imathelement-imathelement) | สร้าง subscript และ superscript ทางขวา |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#str-str) | สร้าง subscript และ superscript ทางขวา |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#imathelement-imathelement) | สร้าง subscript และ superscript ทางซ้าย |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#str-str) | สร้าง subscript และ superscript ทางซ้าย |
| [`radical(self, degree)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/radical/#imathelement) | ระบุรากคณิตศาสตร์ของระดับที่กำหนดจากอาร์กิวเมนต์ที่ระบุ. |
| [`radical(self, degree)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/radical/#str) | ระบุรากคณิตศาสตร์ของระดับที่กำหนดจากอาร์กิวเมนต์ที่ระบุ. |
| [`set_upper_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/set_upper_limit/#imathelement) | รับ upper limit |
| [`set_upper_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/set_upper_limit/#str) | รับ upper limit |
| [`set_lower_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/set_lower_limit/#imathelement) | รับ lower limit |
| [`set_lower_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/set_lower_limit/#str) | รับ lower limit |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-imathelement-imathelement) | สร้าง N-ary operator |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-str-str) | สร้าง N-ary operator |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | รับ integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement) | รับ integral |
| [`integral(self, integral_type)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes) | รับ integral โดยไม่มีขอบเขต |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str-mathlimitlocations) | รับ integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str) | รับ integral |
| [`group(self)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/group/#) | วางองค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บปีกกาล่าง |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/group/#char-mathtopbotpositions-mathtopbotpositions) | วางองค์ประกอบนี้ในกลุ่มโดยใช้อักขระการจัดกลุ่ม เช่น วงเล็บปีกกาล่างหรืออื่น |
| [`to_border_box(self)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/to_border_box/#) | วางองค์ประกอบนี้ในกล่องขอบ |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | วางองค์ประกอบนี้ในกล่องขอบ |
| [`to_math_array(self)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/to_math_array/#) | วาง child elements ในแถวแนวตั้ง |
| [`accent(self, accent_character)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/accent/#char) | ตั้งค่าเครื่องหมายสำเนียง (อักขระบนสุดขององค์ประกอบนี้) |
| [`overbar(self)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/overbar/#) | ตั้งค่า bar บนสุดขององค์ประกอบนี้ |
| [`underbar(self)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/underbar/#) | ตั้งค่า bar ใต้สุดขององค์ประกอบนี้ |
| [`to_box(self)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/to_box/#) | วางองค์ประกอบนี้ในกล่องที่ไม่แสดงผล (การจัดกลุ่มเชิงตรรกะ) <br/>            ซึ่งใช้เพื่อจัดกลุ่มส่วนประกอบของสมการหรือข้อความคณิตศาสตร์อื่น.<br/>            วัตถุที่อยู่ในกล่องอาจ (เช่น) ทำหน้าที่เป็นตัวจำลอง operator ที่มีหรือไม่มีจุดจัดแนว, <br/>            ทำหน้าที่เป็นจุดตัดบรรทัด, หรือจัดกลุ่มเพื่อไม่ให้มีการตัดบรรทัดภายใน. |
| [`get_children(self)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/get_children/#) | รับ child elements |
| [`add(self, item)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/add/#imathelement) | เพิ่ม math element ไปยังท้ายคอลเลกชัน. |
| [`clear(self)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/clear/#) | ลบทุกองค์ประกอบจากคอลเลกชัน. |
| [`contains(self, item)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/contains/#imathelement) | ตรวจสอบว่าคอลเลกชันประกอบด้วยค่าที่ระบุหรือไม่. |
| [`copy_to(self, array, array_index)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/copy_to/#listimathelement-int) | คัดลอกไปยังอาร์เรย์ที่ระบุ. |
| [`remove(self, item)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/remove/#imathelement) | ลบการปรากฏครั้งแรกของอ็อบเจ็กต์ที่ระบุจากคอลเลกชัน. |
| [`index_of(self, item)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/index_of/#imathelement) | ตรวจสอบดัชนีของ math element ที่ระบุในคอลเลกชัน. |
| [`insert(self, index, item)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/insert/#int-imathelement) | แทรก MathElement ลงในคอลเลกชันที่ดัชนีที่ระบุ. |
| [`remove_at(self, index)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/remove_at/#int) | ลบองค์ประกอบที่ดัชนีที่ระบุจากคอลเลกชัน. |
| [`join_block(self, other)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/join_block/#imathblock) | เชื่อมต่อบล็อกคณิตศาสตร์อื่นกับบล็อกนี้ |
| [`delimit(self, separator_character)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/delimit/#char) | แยก child elements ด้วยอักขระตัวแบ่ง (โดยไม่มีวงเล็บ) |
| [`write_as_math_ml(self, stream)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/write_as_math_ml/#iorawiobase) | บันทึกเนื้อหาของ [`MathBlock`](/slides/python-net/th/aspose.slides.mathtext/mathblock) นี้เป็น MathML |


### ดูเพิ่มเติม
* คลาส [`MathBlock`](/slides/python-net/th/aspose.slides.mathtext/mathblock)
* คลาส [`MathElementBase`](/slides/python-net/th/aspose.slides.mathtext/mathelementbase)
* โมดูล [`aspose.slides.mathtext`](/slides/python-net/th/aspose.slides.mathtext)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)