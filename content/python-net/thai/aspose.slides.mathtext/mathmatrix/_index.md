---
title: MathMatrix class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix คลาส

ระบุวัตถุ Matrix ซึ่งประกอบด้วยองค์ประกอบย่อยที่จัดเรียงเป็นหนึ่งหรือหลายแถวและคอลัมน์. 
            ควรสังเกตว่ามัทริกซ์ไม่มีตัวคั่นในตัว. 
            เพื่อตั้งมัทริกซ์ในวงเล็บคุณควรใช้วัตถุ delimiter (IMathDelimiter). 
            สามารถใช้อาร์กิวเมนต์ Null เพื่อสร้างช่องว่างในมัทริกซ์.

**การสืบทอด:**[`MathMatrix`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix) → [`MathElementBase`](/slides/python-net/th/aspose.slides.mathtext/mathelementbase)

ประเภท MathMatrix เปิดเผยสมาชิกต่อไปนี้:

## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| :- | :- |
| [`__init__(self, row_count, column_count)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/__init__/#int-int) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส MathMatrix. |

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`row_count`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/row_count/) | จำนวนแถวในมัทริกซ์ |
| [`column_count`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/column_count/) | จำนวนคอลัมน์ในมัทริกซ์ |
| [`hide_placeholders`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/hide_placeholders/) | ซ่อนตัวแสดงตำแหน่งสำหรับองค์ประกอบมัทริกซ์ที่ว่าง<br/>            Default: false |
| [`base_justification`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/base_justification/) | ระบุการจัดแนวแนวตั้งสัมพันธ์กับข้อความโดยรอบ.<br/>            Possible values are top, bottom, and center.<br/>            Default: Center |
| [`min_column_width`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/min_column_width/) | ความกว้างคอลัมน์ขั้นต่ำในหน่วย twips (1/20 ของจุด)<br/>            ระยะห่างช่องว่าง (ซึ่งเรียกว่า “Column Gap” หรือ “Gap Width”) จะถูกเพิ่มไปยัง MinColumnWidth เพื่อกำหนดระยะห่างคอลัมน์ของ Matrix ทั้งหมด (ระยะห่างระหว่างขอบเดียวกันของคอลัมน์ต่างๆ).<br/>            Default: 0. |
| [`column_gap_rule`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/column_gap_rule/) | ประเภทของระยะห่างแนวนอนระหว่างคอลัมน์ของมัทริกซ์;<br/>            หน่วยของระยะห่างแนวนอนสามารถเป็น ems หรือ points (เก็บเป็นหน่วย twips).<br/>            Default: SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/column_gap/) | ค่าของระยะห่างแนวนอนระหว่างคอลัมน์ของมัทริกซ์;<br/>            หาก ColumnGapRule ถูกตั้งค่าเป็น 3 ("Exactly"), หน่วยจะถูกตีความเป็น twips (1/20 ของจุด)<br/>            หาก ColumnGapRule ถูกตั้งค่าเป็น 4 ("Multiple"), หน่วยจะถูกตีความเป็นจำนวนของการเพิ่ม 0.5 em<br/>            ในกรณีอื่นจะถูกละเลย.<br/>            Default: 0 |
| [`row_gap_rule`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/row_gap_rule/) | ประเภทของระยะห่างแนวตั้งระหว่างแถวของมัทริกซ์;<br/>            หน่วยของระยะห่างแนวตั้งสามารถเป็น lines หรือ points (เก็บเป็น twips).<br/>            Default: SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/row_gap/) | ค่าของระยะห่างแนวตั้งระหว่างแถวของมัทริกซ์;<br/>            หาก RowGapRule ถูกตั้งค่าเป็น 3 ("Exactly"), หน่วยจะถูกตีความเป็น twips (1/20 ของจุด)<br/>            หาก RowGapRule ถูกตั้งค่าเป็น 4 ("Multiple"), หน่วยจะถูกตีความเป็น half-lines.<br/>            Default: 0 |

## วิธีการ

| วิธีการ | คำอธิบาย |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/join/#imathelement) | รวมองค์ประกอบคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| [`join(self, math_text)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/join/#str) | รวมข้อความคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์ |
| [`divide(self, denominator)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/divide/#imathelement) | สร้างเศษส่วนด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| [`divide(self, denominator)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/divide/#str) | สร้างเศษส่วนด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/divide/#imathelement-mathfractiontypes) | สร้างเศษส่วนประเภทที่ระบุด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/divide/#str-mathfractiontypes) | สร้างเศษส่วนประเภทที่ระบุด้วยตัวเศษนี้และตัวส่วนที่ระบุ |
| [`enclose(self)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/enclose/#) | ล้อมรอบองค์ประกอบคณิตศาสตร์ด้วยวงเล็บ |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/enclose/#char-char) | ล้อมรอบองค์ประกอบคณิตศาสตร์ด้วยอักขระที่ระบุ เช่น วงเล็บหรืออักขระอื่นเป็นกรอบ |
| [`function(self, function_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/function/#imathelement) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [`function(self, function_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/function/#str) | รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#imathelement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#str) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsofoneargument) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์ |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) | รับฟังก์ชันที่ระบุโดยใช้อินสแตนซ์นี้เป็นอาร์กิวเมนต์และอาร์กิวเมนต์เพิ่มเติมที่ระบุ |
| [`set_subscript(self, subscript)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/set_subscript/#imathelement) | สร้างตัวห้อย |
| [`set_subscript(self, subscript)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/set_subscript/#str) | สร้างตัวห้อย |
| [`set_superscript(self, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/set_superscript/#imathelement) | สร้างตัวยก |
| [`set_superscript(self, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/set_superscript/#str) | สร้างตัวยก |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) | สร้างตัวห้อยและตัวยกทางด้านขวา |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#str-str) | สร้างตัวห้อยและตัวยกทางด้านขวา |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) | สร้างตัวห้อยและตัวยกทางด้านซ้าย |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#str-str) | สร้างตัวห้อยและตัวยกทางด้านซ้าย |
| [`radical(self, degree)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/radical/#imathelement) | ระบุรากคณิตศาสตร์ของดีกรีที่กำหนดจากอาร์กิวเมนต์ที่ระบุ. |
| [`radical(self, degree)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/radical/#str) | ระบุรากคณิตศาสตร์ของดีกรีที่กำหนดจากอาร์กิวเมนต์ที่ระบุ. |
| [`set_upper_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/set_upper_limit/#imathelement) | รับขอบบน |
| [`set_upper_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/set_upper_limit/#str) | รับขอบบน |
| [`set_lower_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/set_lower_limit/#imathelement) | รับขอบล่าง |
| [`set_lower_limit(self, limit)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/set_lower_limit/#str) | รับขอบล่าง |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) | สร้างโอเปอร์เรเตอร์ N-ary |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-str-str) | สร้างโอเปอร์เรเตอร์ N-ary |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | รับอินทิกรัล |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement) | รับอินทิกรัล |
| [`integral(self, integral_type)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes) | รับอินทิกรัลโดยไม่มีขอบ |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) | รับอินทิกรัล |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str) | รับอินทิกรัล |
| [`group(self)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/group/#) | วางองค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บปีกกาแบบล่าง |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) | วางองค์ประกอบนี้ในกลุ่มโดยใช้ตัวอักษรการจัดกลุ่ม เช่น วงเล็บปีกกาแบบล่างหรืออักขระอื่น |
| [`to_border_box(self)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/to_border_box/#) | วางองค์ประกอบนี้ในกล่องขอบ |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | วางองค์ประกอบนี้ในกล่องขอบ |
| [`to_math_array(self)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/to_math_array/#) | ใส่ในอาเรย์แนวตั้ง |
| [`accent(self, accent_character)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/accent/#char) | ตั้งเครื่องหมายสำเนียง (อักขระบนส่วนบนขององค์ประกอบนี้) |
| [`overbar(self)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/overbar/#) | ตั้งบาร์บนส่วนบนขององค์ประกอบนี้ |
| [`underbar(self)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/underbar/#) | ตั้งบาร์บนส่วนล่างขององค์ประกอบนี้ |
| [`to_box(self)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/to_box/#) | วางองค์ประกอบนี้ในกล่องที่ไม่มองเห็น (การจัดกลุ่มเชิงตรรกะ) <br/>            ซึ่งใช้เพื่อจัดกลุ่มส่วนประกอบของสมการหรือข้อความคณิตศาสตร์อื่น.<br/>            วัตถุที่อยู่ในกรอบสามารถ (เช่น) ทำหน้าที่เป็นอิมูเลเตอร์ของโอเปอร์เรเตอร์พร้อมหรือไม่มีจุดจัดแนว,<br/>            ทำหน้าที่เป็นจุดตัดบรรทัด, หรือจัดกลุ่มเพื่อไม่ให้มีการตัดบรรทัดภายใน. |
| [`get_column_alignment(self, column_index)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/get_column_alignment/#int) | รับการจัดแนวแนวนอนของคอลัมน์ที่ระบุ |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/set_column_alignment/#int-mathhorizontalalignment) | ตั้งการจัดแนวแนวนอนของคอลัมน์ที่ระบุ |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | ตั้งการจัดแนวแนวนอนของคอลัมน์ที่ระบุ |
| [`insert_row_before(self, row_index)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/insert_row_before/#int) | แทรกแถวใหม่ก่อนแถวที่ระบุ<br/>            โดยเริ่มต้นองค์ประกอบทั้งหมดในแถวใหม่เป็น None. |
| [`insert_row_after(self, row_index)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/insert_row_after/#int) | แทรกแถวใหม่หลังจากแถวที่ระบุ<br/>            โดยเริ่มต้นองค์ประกอบทั้งหมดในแถวใหม่เป็น None. |
| [`delete_row(self, row_index)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/delete_row/#int) | ลบแถวที่ระบุ |
| [`insert_column_before(self, column_index)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/insert_column_before/#int) | แทรกคอลัมน์ใหม่ก่อนคอลัมน์ที่ระบุ<br/>            โดยเริ่มต้นองค์ประกอบทั้งหมดในคอลัมน์ใหม่เป็น None. |
| [`insert_column_after(self, column_index)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/insert_column_after/#int) | แทรกคอลัมน์ใหม่หลังจากคอลัมน์ที่ระบุ<br/>            โดยเริ่มต้นองค์ประกอบทั้งหมดในคอลัมน์ใหม่เป็น None. |
| [`delete_column(self, column_index)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/delete_column/#int) | ลบคอลัมน์ที่ระบุ |
| [`get_children(self)`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix/get_children/#) | รับองค์ประกอบลูก |

### ดูเพิ่มเติม
* คลาส [`MathElementBase`](/slides/python-net/th/aspose.slides.mathtext/mathelementbase)
* คลาส [`MathMatrix`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix)
* โมดูล [`aspose.slides.mathtext`](/slides/python-net/th/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)