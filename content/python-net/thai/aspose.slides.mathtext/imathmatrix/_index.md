---
title: IMathMatrix class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix คลาส

ระบุออบเจ็กต์ Matrix ซึ่งประกอบด้วยอีลเมนต์ลูกที่จัดวางในหนึ่งหรือหลายแถวและคอลัมน์  
สำคัญที่ต้องทราบคือเมทริกซ์ไม่ได้มีตัวแบ่งในตัว  
เพื่อใส่เมทริกซ์ในวงเล็บคุณควรใช้วัตถุ delimiter (IMathDelimiter)  
สามารถใช้อาร์กิวเมนต์ Null เพื่อสร้างช่องว่างในเมทริกซ์ได้

ประเภท IMathMatrix เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`row_count`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/row_count/) | จำนวนแถวในเมทริกซ์ |
| [`column_count`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/column_count/) | จำนวนคอลัมน์ในเมทริกซ์ |
| [`hide_placeholders`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/hide_placeholders/) | ซ่อนตำแหน่งตัวแทนสำหรับองค์ประกอบเมทริกซ์ที่ว่างเปล่า<br/>            ค่าเริ่มต้น: false |
| [`base_justification`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/base_justification/) | ระบุการจัดแนวแนวตั้งสัมพันธ์กับข้อความโดยรอบ <br/>            ค่าที่เป็นไปได้คือ top, bottom, และ center.<br/>            ค่าเริ่มต้น: Center |
| [`min_column_width`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/min_column_width/) | ความกว้างคอลัมน์ขั้นต่ำใน twips (1/20 ของจุด)<br/>            ช่องว่างระหว่างคอลัมน์ (ยังเรียกว่า “Column Gap” หรือ “Gap Width”) จะถูกเพิ่มไปยัง<br/>            MinColumnWidth เพื่อกำหนดการเว้นระยะคอลัมน์เมทริกซ์ทั้งหมด<br/>            (ระยะห่างระหว่างขอบเดียวกันของคอลัมน์ต่าง ๆ).<br/>            ค่าเริ่มต้น: 0. |
| [`column_gap_rule`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/column_gap_rule/) | ประเภทของช่องว่างแนวนอนระหว่างคอลัมน์ของเมทริกซ์; <br/>            หน่วยช่องว่างแนวนอนสามารถเป็น ems หรือ points (เก็บเป็น twips).<br/>            ค่าเริ่มต้น: SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/column_gap/) | ค่าของช่องว่างแนวนอนระหว่างคอลัมน์ของเมทริกซ์;<br/>            หาก ColumnGapRule ถูกตั้งค่าเป็น 3 ("Exactly"), หน่วยจะถูกตีความเป็น twips (1/20 ของจุด)<br/>            หาก ColumnGapRule ถูกตั้งค่าเป็น 4 ("Multiple"), หน่วยจะถูกตีความเป็นจำนวนของการเพิ่ม 0.5 em<br/>            ในกรณีอื่นจะถูกละเว้น.<br/>            ค่าเริ่มต้น: 0 |
| [`row_gap_rule`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/row_gap_rule/) | ประเภทของช่องว่างแนวตั้งระหว่างแถวของเมทริกซ์; <br/>            หน่วยช่องว่างแนวตั้งสามารถเป็น lines หรือ points (เก็บเป็น twips).<br/>            ค่าเริ่มต้น: SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/row_gap/) | ค่าของช่องว่างแนวตั้งระหว่างแถวของเมทริกซ์;<br/>            หาก RowGapRule ถูกตั้งค่าเป็น 3 ("Exactly"), หน่วยจะตีความเป็น twips (1/20 ของจุด)<br/>            หาก RowGapRule ถูกตั้งค่าเป็น 4 ("Multiple"), หน่วยจะตีความเป็นครึ่งบรรทัด.<br/>            ค่าเริ่มต้น: 0 |

## เมธอด

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_column_alignment(self, column_index)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/get_column_alignment/#int) | รับการจัดแนวนอนของคอลัมน์ที่ระบุ |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/set_column_alignment/#int-mathhorizontalalignment) | ตั้งค่าการจัดแนวนอนของคอลัมน์ที่ระบุ |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | ตั้งค่าการจัดแนวนอนของคอลัมน์ที่ระบุหลายคอลัมน์ |
| [`insert_row_before(self, row_index)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/insert_row_before/#int) | แทรกแถวใหม่ก่อนแถวที่ระบุ<br/>            โดยเริ่มต้นทุกองค์ประกอบในแถวใหม่เป็น None. |
| [`insert_row_after(self, row_index)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/insert_row_after/#int) | แทรกแถวใหม่หลังแถวที่ระบุ<br/>            โดยเริ่มต้นทุกองค์ประกอบในแถวใหม่เป็น None. |
| [`delete_row(self, row_index)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/delete_row/#int) | ลบแถวที่ระบุ |
| [`insert_column_before(self, column_index)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/insert_column_before/#int) | แทรกคอลัมน์ใหม่ก่อนคอลัมน์ที่ระบุ<br/>            โดยเริ่มต้นทุกองค์ประกอบในคอลัมน์ใหม่เป็น None. |
| [`insert_column_after(self, column_index)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/insert_column_after/#int) | แทรกคอลัมน์ใหม่หลังคอลัมน์ที่ระบุ<br/>            โดยเริ่มต้นทุกองค์ประกอบในคอลัมน์ใหม่เป็น None. |
| [`delete_column(self, column_index)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/delete_column/#int) | ลบคอลัมน์ที่ระบุ |
| [`get_children(self)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/th/aspose.slides.mathtext/imathmatrix/to_box/#) |  |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides.mathtext`](/slides/python-net/th/aspose.slides.mathtext)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)