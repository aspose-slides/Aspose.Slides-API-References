---
title: ICell class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/icell/
---
## ICell คลาส

แสดงถึงเซลล์ในตาราง

ประเภท ICell มีสมาชิกต่อไปนี้:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`offset_x`](/slides/python-net/th/aspose.slides/icell/offset_x/) | ส่งคืนระยะห่างจากด้านซ้ายของตารางถึงด้านซ้ายของเซลล์.<br/>            อ่านอย่างเดียว **float**. |
| [`offset_y`](/slides/python-net/th/aspose.slides/icell/offset_y/) | ส่งคืนระยะห่างจากด้านบนของตารางถึงด้านบนของเซลล์.<br/>            อ่านอย่างเดียว **float**. |
| [`first_row_index`](/slides/python-net/th/aspose.slides/icell/first_row_index/) | ส่งคืนดัชนีของแถวแรกที่เซลล์ครอบคลุม.<br/>            อ่านอย่างเดียว **int**. |
| [`first_column_index`](/slides/python-net/th/aspose.slides/icell/first_column_index/) | ส่งคืนดัชนีของคอลัมน์แรกที่เซลล์ครอบคลุม.<br/>            อ่านอย่างเดียว **int**. |
| [`width`](/slides/python-net/th/aspose.slides/icell/width/) | ส่งคืนความกว้างของเซลล์.<br/>            อ่านอย่างเดียว **float**. |
| [`height`](/slides/python-net/th/aspose.slides/icell/height/) | ส่งคืนความสูงของเซลล์.<br/>            อ่านอย่างเดียว **float**. |
| [`minimal_height`](/slides/python-net/th/aspose.slides/icell/minimal_height/) | ส่งคืนความสูงขั้นต่ำของเซลล์.<br/>            นี่คือผลรวมของความสูงต่ำสุดของทุกแถวที่เซลล์ครอบคลุม.<br/>            อ่านอย่างเดียว **float**. |
| [`margin_left`](/slides/python-net/th/aspose.slides/icell/margin_left/) | ส่งคืนหรือกำหนดระยะขอบด้านซ้ายใน TextFrame.<br/>            อ่าน/เขียน **float**. |
| [`margin_right`](/slides/python-net/th/aspose.slides/icell/margin_right/) | ส่งคืนหรือกำหนดระยะขอบด้านขวาใน TextFrame.<br/>            อ่าน/เขียน **float**. |
| [`margin_top`](/slides/python-net/th/aspose.slides/icell/margin_top/) | ส่งคืนหรือกำหนดระยะขอบด้านบนใน TextFrame.<br/>            อ่าน/เขียน **float**. |
| [`margin_bottom`](/slides/python-net/th/aspose.slides/icell/margin_bottom/) | ส่งคืนหรือกำหนดระยะขอบด้านล่างใน TextFrame.<br/>            อ่าน/เขียน **float**. |
| [`text_vertical_type`](/slides/python-net/th/aspose.slides/icell/text_vertical_type/) | ส่งคืนหรือกำหนดประเภทของข้อความแนวตั้ง.<br/>            อ่าน/เขียน [`TextVerticalType`](/slides/python-net/th/aspose.slides/textverticaltype). |
| [`text_anchor_type`](/slides/python-net/th/aspose.slides/icell/text_anchor_type/) | ส่งคืนหรือกำหนดประเภทของจุดยึดข้อความ.<br/>            อ่าน/เขียน [`TextAnchorType`](/slides/python-net/th/aspose.slides/textanchortype). |
| [`anchor_center`](/slides/python-net/th/aspose.slides/icell/anchor_center/) | กำหนดว่ากล่องข้อความอยู่ตรงกลางภายในเซลล์หรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`first_column`](/slides/python-net/th/aspose.slides/icell/first_column/) | รับคอลัมน์แรกของเซลล์.<br/>            อ่านอย่างเดียว [`IColumn`](/slides/python-net/th/aspose.slides/icolumn). |
| [`first_row`](/slides/python-net/th/aspose.slides/icell/first_row/) | รับแถวแรกของเซลล์.<br/>            อ่านอย่างเดียว [`IRow`](/slides/python-net/th/aspose.slides/irow). |
| [`col_span`](/slides/python-net/th/aspose.slides/icell/col_span/) | ส่งคืนจำนวนคอลัมน์กริดในตารางแม่ของตารางที่เซลล์ปัจจุบันจะครอบคลุม.<br/>            คุณสมบัตินี้ทำให้เซลล์ดูเหมือนถูกรวมเข้าด้วยกัน, เนื่องจากครอบขอบแนวตั้งของเซลล์อื่นในตาราง.<br/>            อ่านอย่างเดียว **int**. |
| [`row_span`](/slides/python-net/th/aspose.slides/icell/row_span/) | ส่งคืนจำนวนแถวที่เซลล์ที่รวมกันครอบคลุม. นี่ใช้ร่วมกับแอตทริบิวต์ vMerge บนเซลล์อื่นเพื่อระบุเซลล์เริ่มต้นของการรวมแนวนอน.<br/>            อ่านอย่างเดียว **int**. |
| [`text_frame`](/slides/python-net/th/aspose.slides/icell/text_frame/) | ส่งคืน TextFrame ของเซลล์.<br/>            อ่านอย่างเดียว [`ITextFrame`](/slides/python-net/th/aspose.slides/itextframe). |
| [`table`](/slides/python-net/th/aspose.slides/icell/table/) | ส่งคืนออบเจ็กต์ Table พ่อของเซลล์.<br/>            อ่านอย่างเดียว [`ITable`](/slides/python-net/th/aspose.slides/itable). |
| [`is_merged_cell`](/slides/python-net/th/aspose.slides/icell/is_merged_cell/) | ส่งคืน true หากเซลล์ถูกรวมกับเซลล์ใดที่ปรับแล้ว, มิฉะนั้น false.<br/>            อ่านอย่างเดียว **bool**. |
| [`cell_format`](/slides/python-net/th/aspose.slides/icell/cell_format/) | ส่งคืนออบเจ็กต์ CellFormat ที่มีคุณสมบัติการจัดรูปแบบสำหรับเซลล์นี้.<br/>            อ่านอย่างเดียว [`ICellFormat`](/slides/python-net/th/aspose.slides/icellformat). |
| [`slide`](/slides/python-net/th/aspose.slides/icell/slide/) |  |
| [`presentation`](/slides/python-net/th/aspose.slides/icell/presentation/) |  |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`split_by_col_span(self, index)`](/slides/python-net/th/aspose.slides/icell/split_by_col_span/#int) | แยกเซลล์เป็นสองเซลล์ตามดัชนีของคอลัมน์. |
| [`split_by_row_span(self, index)`](/slides/python-net/th/aspose.slides/icell/split_by_row_span/#int) | แยกเซลล์เป็นสองเซลล์ตามดัชนีของแถว. |
| [`split_by_height(self, height)`](/slides/python-net/th/aspose.slides/icell/split_by_height/#float) | แยกเซลล์ตามความสูง. |
| [`split_by_width(self, width)`](/slides/python-net/th/aspose.slides/icell/split_by_width/#float) | แยกเซลล์ตามความกว้าง. |


### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)