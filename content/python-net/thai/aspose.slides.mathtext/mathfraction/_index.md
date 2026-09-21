---
title: MathFraction class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.mathtext/mathfraction/
---
## MathFraction คลาส

ระบุวัตถุส่วนเศษ ซึ่งประกอบด้วยตัวเศษและตัวส่วนโดยแยกด้วยแถบส่วน
แถบส่วนสามารถเป็นแนวนอนหรือแนวทแยงตามคุณสมบัติของส่วน
วัตถุส่วนยังใช้แทนฟังก์ชัน stack ซึ่งวางองค์ประกอบหนึ่งเหนืออีกองค์ประกอบหนึ่งโดยไม่มีแถบส่วน

**Inheritance:**[`MathFraction`](/slides/python-net/th/aspose.slides.mathtext/mathfraction) → [`MathElementBase`](/slides/python-net/th/aspose.slides.mathtext/mathelementbase)

ประเภท MathFraction แสดงสมาชิกต่อไปนี้:

## ตัวสร้าง

| Constructor | Description |
| :- | :- |
| [`__init__(self, numerator, denominator, fraction_type)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/__init__/#imathelement-imathelement-mathfractiontypes) | เริ่มต้น MathFraction ด้วยตัวเศษ ตัวส่วนและประเภทที่ระบุ |
| [`__init__(self, numerator, denominator)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/__init__/#imathelement-imathelement) | เริ่มต้น MathFraction ที่มีประเภท 'Bar' ด้วยตัวเศษและตัวส่วนที่ระบุ |

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`fraction_type`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/fraction_type/) | ประเภทของส่วน<br/>            ค่าเริ่มต้น: Bar |
| [`numerator`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/numerator/) | ตัวเศษ |
| [`denominator`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/denominator/) | ตัวส่วน |

## เมธอด

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/join/#imathelement) | เชื่อมต่อองค์ประกอบคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| [`join(self, math_text)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/join/#str) | เชื่อมต่อข้อความคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| [`divide(self, denominator)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/divide/#imathelement) | สร้างส่วนที่มีตัวเศษนี้และตัวส่วนตามที่ระบุ |
| [`divide(self, denominator)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/divide/#str) | สร้างส่วนที่มีตัวเศษนี้และตัวส่วนตามที่ระบุ |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/divide/#imathelement-mathfractiontypes) | สร้างส่วนของประเภทที่ระบุด้วยตัวเศษนี้และตัวส่วนตามที่ระบุ |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/divide/#str-mathfractiontypes) | สร้างส่วนของประเภทที่ระบุด้วยตัวเศษนี้และตัวส่วนตามที่ระบุ |
| [`enclose(self)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/enclose/#) | ล้อมรอบองค์ประกอบคณิตศาสตร์ด้วยวงเล็บ |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/enclose/#char-char) | ล้อมรอบองค์ประกอบคณิตศาสตร์ด้วยอักขระที่ระบุ เช่น วงเล็บหรืออักขระอื่นเป็นกรอบ |
| [`function(self, function_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/function/#imathelement) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [`function(self, function_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/function/#str) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/as_argument_of_function/#imathelement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/as_argument_of_function/#str) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/as_argument_of_function/#mathfunctionsofoneargument) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/as_argument_of_function/#mathfunctionsoftwoarguments-str) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [`set_subscript(self, subscript)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/set_subscript/#imathelement) | สร้างตัวห้อย |
| [`set_subscript(self, subscript)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/set_subscript/#str) | สร้างตัวห้อย |
| [`set_superscript(self, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/set_superscript/#imathelement) | สร้างตัวบน |
| [`set_superscript(self, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/set_superscript/#str) | สร้างตัวบน |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_right/#imathelement-imathelement) | สร้างตัวห้อยและตัวบนที่ด้านขวา |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_right/#str-str) | สร้างตัวห้อยและตัวบนที่ด้านขวา |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_left/#imathelement-imathelement) | สร้างตัวห้อยและตัวบนที่ด้านซ้าย |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_left/#str-str) | สร้างตัวห้อยและตัวบนที่ด้านซ้าย |
| [`radical(self, degree)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/radical/#imathelement) | ระบุรากคณิตศาสตร์ของดีกรีที่กำหนดจากอาร์กิวเมนต์ที่ระบุ |
| [`radical(self, degree)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/radical/#str) | ระบุรากคณิตศาสตร์ของดีกรีที่กำหนดจากอาร์กิวเมนต์ที่ระบุ |
| [`set_upper_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/set_upper_limit/#imathelement) | รับขอบบน |
| [`set_upper_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/set_upper_limit/#str) | รับขอบบน |
| [`set_lower_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/set_lower_limit/#imathelement) | รับขอบล่าง |
| [`set_lower_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/set_lower_limit/#str) | รับขอบล่าง |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/nary/#mathnaryoperatortypes-imathelement-imathelement) | สร้างตัวดำเนินการ N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/nary/#mathnaryoperatortypes-str-str) | สร้างตัวดำเนินการ N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | รับอินทิกรัล |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-imathelement-imathelement) | รับอินทิกรัล |
| [`integral(self, integral_type)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes) | รับอินทิกรัลโดยไม่มีขอบ |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-str-str-mathlimitlocations) | รับอินทิกรัล |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-str-str) | รับอินทิกรัล |
| [`group(self)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/group/#) | วางองค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บปีกกาตัวล่าง |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/group/#char-mathtopbotpositions-mathtopbotpositions) | วางองค์ประกอบนี้ในกลุ่มโดยใช้อักขระการจัดกลุ่มเช่นวงเล็บปีกกาตัวล่างหรืออักขระอื่น |
| [`to_border_box(self)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/to_border_box/#) | วางองค์ประกอบนี้ในกล่องขอบ |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | วางองค์ประกอบนี้ในกล่องขอบ |
| [`to_math_array(self)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/to_math_array/#) | ใส่ในอาเรย์แนวตั้ง |
| [`accent(self, accent_character)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/accent/#char) | ตั้งเครื่องหมายสำเนียง (อักขระที่ด้านบนขององค์ประกอบนี้) |
| [`overbar(self)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/overbar/#) | ตั้งแถบที่ด้านบนขององค์ประกอบนี้ |
| [`underbar(self)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/underbar/#) | ตั้งแถบที่ด้านล่างขององค์ประกอบนี้ |
| [`to_box(self)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/to_box/#) | วางองค์ประกอบนี้ในกล่องที่ไม่แสดงผล (การจัดกลุ่มเชิงตรรกะ) <br/>            ซึ่งใช้เพื่อจัดกลุ่มส่วนประกอบของสมการหรือข้อความคณิตศาสตร์อื่น ๆ<br/>            วัตถุที่อยู่ในกล่องสามารถ (เช่น) ทำหน้าที่เป็นตัวจำลองตัวดำเนินการพร้อมหรือไม่มีจุดจัดตำแหน่ง, <br/>            ทำหน้าที่เป็นจุดตัดบรรทัด, หรือจัดกลุ่มเพื่อไม่ให้มีการตัดบรรทัดภายใน. |
| [`get_children(self)`](/slides/python-net/th/aspose.slides.mathtext/mathfraction/get_children/#) | รับองค์ประกอบลูก |

### ดูเพิ่มเติม
* คลาส [`MathElementBase`](/slides/python-net/th/aspose.slides.mathtext/mathelementbase)
* คลาส [`MathFraction`](/slides/python-net/th/aspose.slides.mathtext/mathfraction)
* โมดูล [`aspose.slides.mathtext`](/slides/python-net/th/aspose.slides.mathtext)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)