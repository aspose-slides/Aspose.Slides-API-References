---
title: BulletFormat
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/bulletformat/
---


BulletFormat class

Represents paragraph bullet formatting properties.

**Inheritance:**[`BulletFormat`](/slides/python-net/aspose.slides/bulletformat) → [`PVIObject`](/slides/python-net/aspose.slides/pviobject)

The BulletFormat type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [as_i_presentation_component](/slides/python-net/aspose.slides/bulletformat/as_i_presentation_component/) | Allows to get base IPresentationComponent interface.<br/>            Read-only <br/>[`IPresentationComponent`](/slides/python-net/aspose.slides/ipresentationcomponent)<br/>. |
| [type](/slides/python-net/aspose.slides/bulletformat/type/) | Returns or sets the bullet type of a paragraph with no inheritance.<br/>            Read/write <br/>[`BulletType`](/slides/python-net/aspose.slides/bullettype)<br/>. |
| [char](/slides/python-net/aspose.slides/bulletformat/char/) | Returns or sets the bullet char of a paragraph with no inheritance.<br/>            Read/write <br/>.NET type System.Char<br/>. |
| [font](/slides/python-net/aspose.slides/bulletformat/font/) | Returns or sets the bullet font of a paragraph with no inheritance.<br/>            Read/write <br/>[`IFontData`](/slides/python-net/aspose.slides/ifontdata)<br/>. |
| [height](/slides/python-net/aspose.slides/bulletformat/height/) | Returns or sets the bullet height of a paragraph with no inheritance.<br/>            Value float.NaN determines that bullet inherits height from the first portion in the paragraph.<br/>            Read/write <br/>.NET type System.Single<br/>. |
| [color](/slides/python-net/aspose.slides/bulletformat/color/) | Returns the color format of a bullet of a paragraph with no inheritance.<br/>            Read-only <br/>[`IColorFormat`](/slides/python-net/aspose.slides/icolorformat)<br/>. |
| [numbered_bullet_start_with](/slides/python-net/aspose.slides/bulletformat/numbered_bullet_start_with/) | Returns or sets the first number which is used for group of numbered bullets with no inheritance.<br/>            Read/write <br/>.NET type System.Int16<br/>. |
| [numbered_bullet_style](/slides/python-net/aspose.slides/bulletformat/numbered_bullet_style/) | Returns or sets the style of a numbered bullet with no inheritance.<br/>            Read/write <br/>[`NumberedBulletStyle`](/slides/python-net/aspose.slides/numberedbulletstyle)<br/>. |
| [is_bullet_hard_color](/slides/python-net/aspose.slides/bulletformat/is_bullet_hard_color/) | Determines whether the bullet has own color or inherits it from the first portion in the paragraph.<br/>            <br/>**<br/>NullableBool.True<br/>** <br/> if bullet has own color and <br/>**<br/>NullableBool.False<br/>** <br/> if bullet<br/>            inherits color from the first portion in the paragraph.<br/>            Read/write <br/>[`NullableBool`](/slides/python-net/aspose.slides/nullablebool)<br/>. |
| [is_bullet_hard_font](/slides/python-net/aspose.slides/bulletformat/is_bullet_hard_font/) | Determines whether the bullet has own font or inherits it from the first portion in the paragraph.<br/>            <br/>**<br/>NullableBool.True<br/>** <br/> if bullet has own font and <br/>**<br/>NullableBool.False<br/>** <br/> if bullet<br/>            inherits font from the first portion in the paragraph.<br/>            Read/write <br/>[`NullableBool`](/slides/python-net/aspose.slides/nullablebool)<br/>. |
| [picture](/slides/python-net/aspose.slides/bulletformat/picture/) | Returns the picture used as a bullet in a paragraph with no inheritance.<br/>            Read-only <br/>[`ISlidesPicture`](/slides/python-net/aspose.slides/islidespicture)<br/>. |
| [slide](/slides/python-net/aspose.slides/bulletformat/slide/) |  |
| [presentation](/slides/python-net/aspose.slides/bulletformat/presentation/) |  |

## Methods

| Method | Description |
| :- | :- |
| [apply_default_paragraph_indents_shifts](/slides/python-net/aspose.slides/bulletformat/bulletformat/#/) | Sets default non-zero shifts for effective paragraph Indent and MarginLeft when bullets is enabled (like PowerPoint do if enable paragraph bullets/numbering in it). If bullets is disabled then just reset paragraph Indent and MarginLeft (like PowerPoint do if disable paragraph bullets/numbering in it). Indents shifts are applied in regard to current bullet context - IBulletFormat.Type, .NumberedBulletStyle and FontHeight of first portion. Non-zero indents shifts are applied to effective Indent and MarginLeft of current paragraph (make result values to be local values). |
| [get_effective](/slides/python-net/aspose.slides/bulletformat/bulletformat/#/) | Gets effective bullet formatting data with the inheritance applied. |

