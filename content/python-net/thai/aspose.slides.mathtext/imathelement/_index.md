---
title: IMathElement class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API อ้างอิง
description: 
type: docs
url: /th/aspose.slides.mathtext/imathelement/
---
## IMathElement คลาส

อินเทอร์เฟซพื้นฐานขององค์ประกอบคณิตศาสตร์ใด ๆ: 
            เศษส่วน, ข้อความคณิตศาสตร์, ฟังก์ชัน, นิพจน์ที่มีหลายองค์ประกอบ ฯลฯ

ประเภท IMathElement เปิดเผยสมาชิกต่อไปนี้:

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/join/#imathelement) | รวมองค์ประกอบคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| [`join(self, math_text)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/join/#str) | รวมข้อความคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| [`divide(self, denominator)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/divide/#imathelement) | สร้างเศษส่วนด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| [`divide(self, denominator)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/divide/#str) | สร้างเศษส่วนด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/divide/#imathelement-mathfractiontypes) | สร้างเศษส่วนประเภทที่ระบุด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/divide/#str-mathfractiontypes) | สร้างเศษส่วนประเภทที่ระบุด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| [`enclose(self)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/enclose/#) | ใส่องค์ประกอบคณิตศาสตร์ในวงเล็บ |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/enclose/#char-char) | ใส่องค์ประกอบนี้ในอักขระที่ระบุ เช่น วงเล็บหรืออักขระอื่นเป็นกรอบ |
| [`function(self, function_argument)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/function/#imathelement) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [`function(self, function_argument)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/function/#str) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/as_argument_of_function/#imathelement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/as_argument_of_function/#str) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/as_argument_of_function/#mathfunctionsofoneargument) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/as_argument_of_function/#mathfunctionsoftwoarguments-str) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [`set_subscript(self, subscript)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/set_subscript/#imathelement) | สร้างตัวห้อย |
| [`set_subscript(self, subscript)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/set_subscript/#str) | สร้างตัวห้อย |
| [`set_superscript(self, superscript)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/set_superscript/#imathelement) | สร้างตัวยกกำลัง |
| [`set_superscript(self, superscript)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/set_superscript/#str) | สร้างตัวยกกำลัง |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/set_sub_superscript_on_the_right/#imathelement-imathelement) | สร้างตัวห้อยและตัวยกกำลังทางขวา |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/set_sub_superscript_on_the_right/#str-str) | สร้างตัวห้อยและตัวยกกำลังทางขวา |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/set_sub_superscript_on_the_left/#imathelement-imathelement) | สร้างตัวห้อยและตัวยกกำลังทางซ้าย |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/set_sub_superscript_on_the_left/#str-str) | สร้างตัวห้อยและตัวยกกำลังทางซ้าย |
| [`radical(self, degree)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/radical/#imathelement) | ระบุรากคณิตศาสตร์ของดีกรีที่กำหนดจากอาร์กิวเมนต์ที่ระบุ |
| [`radical(self, degree)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/radical/#str) | ระบุรากคณิตศาสตร์ของดีกรีที่กำหนดจากอาร์กิวเมนต์ที่ระบุ |
| [`set_upper_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/set_upper_limit/#imathelement) | รับขอบบน |
| [`set_upper_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/set_upper_limit/#str) | รับขอบบน |
| [`set_lower_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/set_lower_limit/#imathelement) | รับขอบล่าง |
| [`set_lower_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/set_lower_limit/#str) | รับขอบล่าง |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/nary/#mathnaryoperatortypes-imathelement-imathelement) | สร้างตัวดำเนินการแบบ N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/nary/#mathnaryoperatortypes-str-str) | สร้างตัวดำเนินการแบบ N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | รับอินทิกรัล |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/integral/#mathintegraltypes-imathelement-imathelement) | รับอินทิกรัล |
| [`integral(self, integral_type)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/integral/#mathintegraltypes) | รับอินทิกรัลโดยไม่มีขอบเขต |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/integral/#mathintegraltypes-str-str-mathlimitlocations) | รับอินทิกรัล |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/integral/#mathintegraltypes-str-str) | รับอินทิกรัล |
| [`group(self)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/group/#) | ใส่องค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บโค้งล่าง |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/group/#char-mathtopbotpositions-mathtopbotpositions) | ใส่องค์ประกอบนี้ในกลุ่มโดยใช้อักขระการจัดกลุ่มเช่นวงเล็บโค้งล่างหรืออักขระอื่น |
| [`to_border_box(self)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/to_border_box/#) | ใส่องค์ประกอบนี้ในกล่องขอบ |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | ใส่องค์ประกอบนี้ในกล่องขอบ |
| [`get_children(self)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/get_children/#) | รับองค์ประกอบลูก |
| [`to_math_array(self)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/to_math_array/#) | ใส่ในอาเรย์แนวตั้ง |
| [`accent(self, accent_character)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/accent/#char) | ตั้งเครื่องหมายสำเนียง (อักขระที่ด้านบนขององค์ประกอบนี้) |
| [`overbar(self)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/overbar/#) | ตั้งบาร์ที่ด้านบนขององค์ประกอบนี้ |
| [`underbar(self)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/underbar/#) | ตั้งบาร์ที่ด้านล่างขององค์ประกอบนี้ |
| [`to_box(self)`](/slides/python-net/th/aspose.slides.mathtext/imathelement/to_box/#) | ใส่องค์ประกอบนี้ในกล่องที่ไม่แสดงผล (การจัดกลุ่มเชิงตรรกะ) <br/>            ซึ่งใช้เพื่อจัดกลุ่มส่วนประกอบของสมการหรือข้อความคณิตศาสตร์อื่น ๆ<br/>            วัตถุที่อยู่ในกล่องสามารถ (เช่น) ทำหน้าที่เป็นตัวจำลองตัวดำเนินการที่มีหรือไม่มีจุดจัดแนว,<br/>            ทำหน้าที่เป็นจุดตัดบรรทัด, หรือจัดกลุ่มเพื่อไม่ให้มีการตัดบรรทัดภายใน. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides.mathtext`](/slides/python-net/th/aspose.slides.mathtext)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)