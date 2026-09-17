---
title: IFillFormatEffectiveData class
second_title: Aspose.Slides for Python via .NET API 参考文档
description: 
type: docs
url: /zh/aspose.slides/ifillformateffectivedata/
---
## IFillFormatEffectiveData 类

不可变对象，包含实际填充格式属性。

IFillFormatEffectiveData 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`fill_type`](/slides/python-net/zh/aspose.slides/ifillformateffectivedata/fill_type/) | 返回填充的类型。<br/>            只读 [`FillType`](/slides/python-net/zh/aspose.slides/filltype)。 |
| [`solid_fill_color`](/slides/python-net/zh/aspose.slides/ifillformateffectivedata/solid_fill_color/) | 返回填充颜色。<br/>            只读 **aspose.slides.Color**。 |
| [`solid_fill_scheme_color`](/slides/python-net/zh/aspose.slides/ifillformateffectivedata/solid_fill_scheme_color/) | 获取由配色方案定义的填充颜色。<br/>            [`SchemeColor.NOT_DEFINED`](/slides/python-net/zh/aspose.slides/schemecolor/NOT_DEFINED) 值指示 [`IFillFormatEffectiveData.solid_fill_color`](/slides/python-net/zh/aspose.slides/ifillformateffectivedata/solid_fill_color) <br/>            不是方案颜色。<br/>            只读 [`SchemeColor`](/slides/python-net/zh/aspose.slides/schemecolor)。 |
| [`gradient_format`](/slides/python-net/zh/aspose.slides/ifillformateffectivedata/gradient_format/) | 返回渐变填充格式。<br/>            只读 [`IGradientFormatEffectiveData`](/slides/python-net/zh/aspose.slides/igradientformateffectivedata)。 |
| [`pattern_format`](/slides/python-net/zh/aspose.slides/ifillformateffectivedata/pattern_format/) | 返回图案填充格式。<br/>            只读 [`IPatternFormatEffectiveData`](/slides/python-net/zh/aspose.slides/ipatternformateffectivedata)。 |
| [`picture_fill_format`](/slides/python-net/zh/aspose.slides/ifillformateffectivedata/picture_fill_format/) | 返回图片填充格式。<br/>            只读 [`IPictureFillFormatEffectiveData`](/slides/python-net/zh/aspose.slides/ipicturefillformateffectivedata)。 |
| [`rotate_with_shape`](/slides/python-net/zh/aspose.slides/ifillformateffectivedata/rotate_with_shape/) | 确定填充是否应随形状旋转。<br/>            只读 **bool**。 |

### 备注

此接口与 [`IFillFormat`](/slides/python-net/zh/aspose.slides/ifillformat) 接口一起使用，以返回已应用继承的实际格式值。

### 另请参见
* 类 [`IFillFormat`](/slides/python-net/zh/aspose.slides/ifillformat)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)