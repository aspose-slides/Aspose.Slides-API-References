---
title: BulletFormat class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/bulletformat/
---
## BulletFormat คลาส

แสดงคุณสมบัติการจัดรูปแบบหัวข้อย่อยของย่อหน้า

**การสืบทอด:**[`BulletFormat`](/slides/python-net/th/aspose.slides/bulletformat) → [`PVIObject`](/slides/python-net/th/aspose.slides/pviobject)

ประเภท BulletFormat เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/th/aspose.slides/bulletformat/type/) | Returns or sets the bullet type of a paragraph with no inheritance.<br/>            Read/write [`BulletType`](/slides/python-net/th/aspose.slides/bullettype). |
| [`char`](/slides/python-net/th/aspose.slides/bulletformat/char/) | Returns or sets the bullet char of a paragraph with no inheritance.<br/>            Read/write **System.Char**. |
| [`font`](/slides/python-net/th/aspose.slides/bulletformat/font/) | Returns or sets the bullet font of a paragraph with no inheritance.<br/>            Read/write [`IFontData`](/slides/python-net/th/aspose.slides/ifontdata). |
| [`height`](/slides/python-net/th/aspose.slides/bulletformat/height/) | Returns or sets the bullet height of a paragraph with no inheritance.<br/>            Value float.NaN determines that bullet inherits height from the first portion in the paragraph.<br/>            Read/write **float**. |
| [`color`](/slides/python-net/th/aspose.slides/bulletformat/color/) | Returns the color format of a bullet of a paragraph with no inheritance.<br/>            Read-only [`IColorFormat`](/slides/python-net/th/aspose.slides/icolorformat). |
| [`numbered_bullet_start_with`](/slides/python-net/th/aspose.slides/bulletformat/numbered_bullet_start_with/) | Returns or sets the first number which is used for group of numbered bullets with no inheritance.<br/>            Read/write **int**. |
| [`numbered_bullet_style`](/slides/python-net/th/aspose.slides/bulletformat/numbered_bullet_style/) | Returns or sets the style of a numbered bullet with no inheritance.<br/>            Read/write [`NumberedBulletStyle`](/slides/python-net/th/aspose.slides/numberedbulletstyle). |
| [`is_bullet_hard_color`](/slides/python-net/th/aspose.slides/bulletformat/is_bullet_hard_color/) | Determines whether the bullet has own color or inherits it from the first portion in the paragraph.<br/>            **NullableBool.True**  if bullet has own color and **NullableBool.False**  if bullet<br/>            inherits color from the first portion in the paragraph.<br/>            Read/write [`NullableBool`](/slides/python-net/th/aspose.slides/nullablebool). |
| [`is_bullet_hard_font`](/slides/python-net/th/aspose.slides/bulletformat/is_bullet_hard_font/) | Determines whether the bullet has own font or inherits it from the first portion in the paragraph.<br/>            **NullableBool.True**  if bullet has own font and **NullableBool.False**  if bullet<br/>            inherits font from the first portion in the paragraph.<br/>            Read/write [`NullableBool`](/slides/python-net/th/aspose.slides/nullablebool). |
| [`picture`](/slides/python-net/th/aspose.slides/bulletformat/picture/) | Returns the picture used as a bullet in a paragraph with no inheritance.<br/>            Read-only [`ISlidesPicture`](/slides/python-net/th/aspose.slides/islidespicture). |
| [`slide`](/slides/python-net/th/aspose.slides/bulletformat/slide/) |  |
| [`presentation`](/slides/python-net/th/aspose.slides/bulletformat/presentation/) |  |

## วิธีการ

| Method | Description |
| :- | :- |
| [`apply_default_paragraph_indents_shifts(self)`](/slides/python-net/th/aspose.slides/bulletformat/apply_default_paragraph_indents_shifts/#) | Sets default non-zero shifts for effective paragraph Indent and MarginLeft when bullets is enabled (like PowerPoint do if enable paragraph bullets/numbering in it). If bullets is disabled then just reset paragraph Indent and MarginLeft (like PowerPoint do if disable paragraph bullets/numbering in it). Indents shifts are applied in regard to current bullet context - IBulletFormat.Type, .NumberedBulletStyle and FontHeight of first portion. Non-zero indents shifts are applied to effective Indent and MarginLeft of current paragraph (make result values to be local values). |
| [`get_effective(self)`](/slides/python-net/th/aspose.slides/bulletformat/get_effective/#) | Gets effective bullet formatting data with the inheritance applied. |


### ดูเพิ่มเติม
* class [`BulletFormat`](/slides/python-net/th/aspose.slides/bulletformat)
* class [`PVIObject`](/slides/python-net/th/aspose.slides/pviobject)
* module [`aspose.slides`](/slides/python-net/th/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)