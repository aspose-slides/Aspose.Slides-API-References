---
title: IMathDelimiter class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.mathtext/imathdelimiter/
---
## IMathDelimiter คลาส

ระบุวัตถุกำหนดขอบเขตที่ประกอบด้วยอักขระเปิดและปิด (เช่น วงเล็บ, ปีกกา, วงกลมเหลี่ยม, และบาร์แนวตั้ง) และหนึ่งหรือหลายองค์ประกอบคณิตศาสตร์ภายใน แยกด้วยอักขระที่กำหนด
            ตัวอย่าง: (𝑥2); [𝑥2|𝑦2]

The IMathDelimiter type exposes the following members:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`arguments`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/arguments/) | หนึ่งหรือหลายองค์ประกอบคณิตศาสตร์ที่แยกด้วยอักขระขอบเขต |
| [`beginning_character`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/beginning_character/) | Delimiter Beginning Character ระบุอักขระขอบเขตที่เป็นจุดเริ่มต้นหรืออักขระเปิด <br/>            ตัวกำหนดขอบเขตทางคณิตศาสตร์คืออักขระที่ล้อมรอบเช่น วงเล็บ, วงกลมเหลี่ยม, และปีกกา.<br/>            ค่าเริ่มต้น: '(' |
| [`separator_character`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/separator_character/) | Delimiter Separator Character ระบุอักขระที่ใช้แยกอาร์กิวเมนต์ในวัตถุกำหนดขอบเขต <br/>            ค่าเริ่มต้น: '\|' |
| [`ending_character`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/ending_character/) | Delimiter Ending Character ระบุอักขระขอบเขตที่เป็นจุดสิ้นสุดหรืออักขระปิด <br/>            ตัวกำหนดขอบเขตทางคณิตศาสตร์คืออักขระที่ล้อมรอบเช่น วงเล็บ, วงกลมเหลี่ยม, และปีกกา.<br/>            ค่าเริ่มต้น: ')' |
| [`grow_to_match_operand_height`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/grow_to_match_operand_height/) | ระบุการขยายของ BeginningCharacter, SeparatorCharacter, EndingCharacter<br/>            เมื่อเป็น true, ขอบเขตจะขยายแนวตั้งเพื่อให้ตรงกับความสูงของออปเปอร์แดนด์<br/>            ค่าเริ่มต้นคือ true |
| [`delimiter_shape`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/delimiter_shape/) | ระบุรูปร่างของขอบเขตในวัตถุกำหนดขอบเขต <br/>            เมื่อเป็น MathDelimiterShape.Centered, ขอบเขตจะถูกจัดตำแหน่งกึ่งกลางตามแกนคณิตศาสตร์ของข้อความคณิตศาสตร์ <br/>            และยังคงปรับให้พอดีกับความสูงทั้งหมดของเนื้อหา<br/>            เมื่อเป็น MathDelimiterShape.Match, ความสูงและรูปร่างจะถูกปรับให้ตรงกับเนื้อหาอย่างพอดิบพอดี |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`delimit(self, separator_character)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/delimit/#char) | จำกัดอาร์กิวเมนต์โดยใช้อักขระขอบเขตที่ระบุ |
| [`get_children(self)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/th/aspose.slides.mathtext/imathdelimiter/to_box/#) |  |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides.mathtext`](/slides/python-net/th/aspose.slides.mathtext)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)