---
title: MathBlock class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.mathtext/mathblock/
---
## MathBlock คลาส

ระบุอินสแตนซ์ของข้อความทางคณิตศาสตร์ที่อยู่ภายใน MathParagraph และเริ่มบนบรรทัดของมันเอง
All math zones, including equations, expressions, arrays of equations or expressions, and formulas are represented by บล็อกคณิตศาสตร์.

**Inheritance:**[`MathBlock`](/slides/python-net/th/aspose.slides.mathtext/mathblock) → [`MathElementBase`](/slides/python-net/th/aspose.slides.mathtext/mathelementbase)

ประเภท MathBlock แสดงสมาชิกต่อไปนี้:

## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| :- | :- |
| [`__init__(self)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/__init__/#) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส MathBlock. |
| [`__init__(self, math_element)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/__init__/#imathelement) | สร้างบล็อกคณิตศาสตร์ใหม่และวางองค์ประกอบที่ระบุไว้ลงในบล็อก |
| [`__init__(self, math_elements)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/__init__/#iterableimathelement) |  |

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`count`](/slides/python-net/th/aspose.slides.mathtext/mathblock/count/) | รับจำนวนของ child math elements ที่อยู่จริงในคอลเลกชัน.<br/>            อ่านอย่างเดียว **int**. |
| [`is_read_only`](/slides/python-net/th/aspose.slides.mathtext/mathblock/is_read_only/) | คืนค่า false เนื่องจากคอลเลกชัน child elements สามารถแก้ไขได้. |

รับหรือกำหนด IMathElement ที่ดัชนีที่ระบุ.

## ตัวกำหนดดัชนี

| ชื่อ | คำอธิบาย |
| :- | :- |
| [`[index]`](/slides/python-net/th/aspose.slides.mathtext/mathblock/__getitem__/) | ดัชนีที่เริ่มจากศูนย์ของรายการ |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/join/#imathelement) | รวมองค์ประกอบทางคณิตศาสตร์กับบล็อกคณิตศาสตร์นี้ |
| [`join(self, math_text)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/join/#str) | รวมข้อความทางคณิตศาสตร์กับบล็อกคณิตศาสตร์นี้ |
| [`divide(self, denominator)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/divide/#imathelement) | สร้างเศษส่วนด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| [`divide(self, denominator)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/divide/#str) | สร้างเศษส่วนด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/divide/#imathelement-mathfractiontypes) | สร้างเศษส่วนของประเภทที่ระบุด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/divide/#str-mathfractiontypes) | สร้างเศษส่วนของประเภทที่ระบุด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/enclose/#char-char) | ล้อมรอบ child elements ของบล็อกนี้ด้วยอักขระที่ระบุ เช่น วงเล็บหรืออักขระอื่นเป็นกรอบ |
| [`enclose(self, beginning_character, ending_character, separator_character)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/enclose/#char-char-char) | ล้อมรอบ child elements ของบล็อกนี้ด้วยอักขระที่ระบุ เช่น วงเล็บหรืออื่นเป็นกรอบ<br/>            และคั่นด้วยอักขระตัวแบ่ง |
| [`enclose(self)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/enclose/#) | ล้อมรอบ math element ด้วยวงเล็บ |
| [`function(self, function_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/function/#imathelement) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [`function(self, function_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/function/#str) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/as_argument_of_function/#imathelement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/as_argument_of_function/#str) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsofoneargument) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-str) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [`set_subscript(self, subscript)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/set_subscript/#imathelement) | สร้างตัวห้อย |
| [`set_subscript(self, subscript)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/set_subscript/#str) | สร้างตัวห้อย |
| [`set_superscript(self, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/set_superscript/#imathelement) | สร้างตัวหัวยก |
| [`set_superscript(self, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/set_superscript/#str) | สร้างตัวหัวยก |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#imathelement-imathelement) | สร้างตัวห้อยและตัวหัวยกด้านขวา |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#str-str) | สร้างตัวห้อยและตัวหัวยกด้านขวา |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#imathelement-imathelement) | สร้างตัวห้อยและตัวหัวยกด้านซ้าย |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#str-str) | สร้างตัวห้อยและตัวหัวยกด้านซ้าย |
| [`radical(self, degree)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/radical/#imathelement) | ระบุรากคณิตศาสตร์ของระดับที่กำหนดจากอาร์กิวเมนต์ที่ระบุ |
| [`radical(self, degree)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/radical/#str) | ระบุรากคณิตศาสตร์ของระดับที่กำหนดจากอาร์กิวเมนต์ที่ระบุ |
| [`set_upper_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/set_upper_limit/#imathelement) | รับขอบบน |
| [`set_upper_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/set_upper_limit/#str) | รับขอบบน |
| [`set_lower_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/set_lower_limit/#imathelement) | รับขอบล่าง |
| [`set_lower_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/set_lower_limit/#str) | รับขอบล่าง |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-imathelement-imathelement) | สร้างตัวดำเนินการ N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-str-str) | สร้างตัวดำเนินการ N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | รับอินทิกรัล |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement) | รับอินทิกรัล |
| [`integral(self, integral_type)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes) | รับอินทิกรัลโดยไม่มีขอบจำกัด |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str-mathlimitlocations) | รับอินทิกรัล |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str) | รับอินทิกรัล |
| [`group(self)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/group/#) | ใส่องค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บโค้งล่าง |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/group/#char-mathtopbotpositions-mathtopbotpositions) | ใส่องค์ประกอบนี้ในกลุ่มโดยใช้อักขระการจัดกลุ่ม เช่น วงเล็บโค้งล่างหรืออื่น |
| [`to_border_box(self)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/to_border_box/#) | ใส่องค์ประกอบนี้ในกล่องขอบ |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | ใส่องค์ประกอบนี้ในกล่องขอบ |
| [`to_math_array(self)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/to_math_array/#) | วาง child elements เป็นแถวแนวตั้ง |
| [`accent(self, accent_character)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/accent/#char) | ตั้งเครื่องหมายสำเนียง (อักขระบนสุดขององค์ประกอบนี้) |
| [`overbar(self)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/overbar/#) | ตั้งเส้นบาร์บนสุดขององค์ประกอบนี้ |
| [`underbar(self)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/underbar/#) | ตั้งเส้นบาร์ด้านล่างขององค์ประกอบนี้ |
| [`to_box(self)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/to_box/#) | ใส่องค์ประกอบนี้ในกล่องที่ไม่มองเห็น (การจัดกลุ่มเชิงตรรกะ) <br/>            ซึ่งใช้เพื่อจัดกลุ่มส่วนประกอบของสมการหรืออินสแตนซ์อื่นของข้อความคณิตศาสตร์.<br/>            วัตถุในกล่องสามารถ (เช่น) ทำหน้าที่เป็นอิมูเลเตอร์ของออเปอเรเตอร์พร้อมหรือไม่พร้อมจุดจัดแนว, <br/>            ทำหน้าที่เป็นจุดตัดบรรทัด, หรือจัดกลุ่มเพื่อไม่ให้มีการตัดบรรทัดภายใน. |
| [`get_children(self)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/get_children/#) | รับ child elements |
| [`add(self, item)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/add/#imathelement) | เพิ่ม math element ไปยังส่วนท้ายของคอลเลกชัน. |
| [`clear(self)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/clear/#) | ลบทั้งหมดจากคอลเลกชัน. |
| [`contains(self, item)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/contains/#imathelement) | ตรวจสอบว่าคอลเลกชันมีค่าที่ระบุหรือไม่. |
| [`copy_to(self, array, array_index)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/copy_to/#listimathelement-int) | คัดลอกไปยังอาเรย์ที่ระบุ. |
| [`remove(self, item)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/remove/#imathelement) | ลบการเกิดขึ้นแรกของอ็อบเจ็กต์ที่ระบุจากคอลเลกชัน. |
| [`index_of(self, item)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/index_of/#imathelement) | หาดัชนีของ math element ที่ระบุในคอลเลกชัน. |
| [`insert(self, index, item)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/insert/#int-imathelement) | แทรก MathElement ลงในคอลเลกชันที่ดัชนีที่ระบุ. |
| [`remove_at(self, index)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/remove_at/#int) | ลบองค์ประกอบที่ดัชนีที่ระบุจากคอลเลกชัน. |
| [`join_block(self, other)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/join_block/#imathblock) | รวมบล็อกคณิตศาสตร์อื่นกับบล็อกนี้ |
| [`delimit(self, separator_character)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/delimit/#char) | คั่น child elements ด้วยอักขระตัวแบ่ง (โดยไม่มีวงเล็บ) |
| [`write_as_math_ml(self, stream)`](/slides/python-net/th/aspose.slides.mathtext/mathblock/write_as_math_ml/#iorawiobase) | บันทึกเนื้อหาของ [`MathBlock`](/slides/python-net/th/aspose.slides.mathtext/mathblock) นี้เป็น MathML |

### ดูเพิ่มเติม
* คลาส [`MathBlock`](/slides/python-net/th/aspose.slides.mathtext/mathblock)
* คลาส [`MathElementBase`](/slides/python-net/th/aspose.slides.mathtext/mathelementbase)
* โมดูล [`aspose.slides.mathtext`](/slides/python-net/th/aspose.slides.mathtext)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)