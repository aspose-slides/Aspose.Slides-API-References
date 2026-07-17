---
title: "System::Drawing"
second_title: Aspose.Slides C++ API 参考
description: 
type: docs
weight: 482
url: /zh/system.drawing/
---
## 类

| 类 | 描述 |
| --- | --- |
| [Bitmap](./bitmap/) | 表示一个 GDI+ 位图图像。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上创建此类型的实例或使用 operator new，因为这会导致运行时错误和/或断言错误。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [Brush](./brush/) | 用于表示用于填充图形形状内部的填充器的基类。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上创建此类型的实例或使用 operator new，因为这会导致运行时错误和/或断言错误。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [Brushes](./brushes/) | 提供一组预先创建的 [SolidBrush](./solidbrush/) 对象。这是一个没有实例服务的静态类型。绝不应以任何方式创建其实例。 |
| [CharacterRange](./characterrange/) | 表示字符串中字符位置的范围。此类型应在栈上分配，并通过值或引用传递给函数。切勿使用 [System::SmartPtr](../system/smartptr/) 类来管理此类型的对象。 |
| [Color](./color/) | 表示一种颜色。此类型应在栈上分配，并通过值或引用传递给函数。切勿使用 [System::SmartPtr](../system/smartptr/) 类来管理此类型的对象。 |
| [ColorTranslator](./colortranslator/) | 执行颜色转换。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上创建此类型的实例或使用 operator new，因为这会导致运行时错误和/或断言错误。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [Font](./font/) | 表示文本的特定格式，包括字体、大小和样式。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上创建此类型的实例或使用 operator new，因为这会导致运行时错误和/或断言错误。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [FontConverter](./fontconverter/) | 将 [Font](./font/) 对象从一种数据类型转换为另一种数据类型。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上创建此类型的实例或使用 operator new，因为这会导致运行时错误和/或断言错误。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [FontFamily](./fontfamily/) | 表示一组拥有相似基本设计的字体族。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上创建此类型的实例或使用 operator new，因为这会导致运行时错误和/或断言错误。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [Graphics](./graphics/) | 表示绘图表面。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上创建此类型的实例或使用 operator new，因为这会导致运行时错误和/或断言错误。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [Icon](./icon/) | 表示一个 [Windows](../system.windows/) 图标。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上创建此类型的实例或使用 operator new，因为这会导致运行时错误和/或断言错误。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [Image](./image/) | 为 [System::Drawing::Bitmap](./bitmap/) 和 System::Drawing::Metafile 类提供基本功能的基类。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上创建此类型的实例或使用 operator new，因为这会导致运行时错误和/或断言错误。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [ImageConverter](./imageconverter/) | 将 [Image](./image/) 对象从一种数据类型转换为另一种数据类型。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上创建此类型的实例或使用 operator new，因为这会导致运行时错误和/或断言错误。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [ImageFormatConverter](./imageformatconverter/) | 将 ImageFormat 对象从一种数据类型转换为另一种数据类型。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上创建此类型的实例或使用 operator new，因为这会导致运行时错误和/或断言错误。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [Pen](./pen/) | 表示绘制的线条和曲线的属性，例如颜色、宽度等。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上创建此类型的实例或使用 operator new，因为这会导致运行时错误和/或断言错误。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [Pens](./pens/) | 提供一组预先创建的 [Pen](./pen/) 对象。这是一个没有实例服务的静态类型。绝不应以任何方式创建其实例。 |
| [Point](./point/) | 表示二维平面上点的整数 X、Y 坐标对。此类型应在栈上分配，并通过值或引用传递给函数。切勿使用 [System::SmartPtr](../system/smartptr/) 类来管理此类型的对象。 |
| [PointF](./pointf/) | 表示二维平面上点的单精度浮点数 X、Y 坐标对。此类型应在栈上分配，并通过值或引用传递给函数。切勿使用 [System::SmartPtr](../system/smartptr/) 类来管理此类型的对象。 |
| [Rectangle](./rectangle/) | 表示图像的矩形区域，定义为其左上角的整数 X、Y 坐标以及宽度和高度。此类型应在栈上分配，并通过值或引用传递给函数。切勿使用 [System::SmartPtr](../system/smartptr/) 类来管理此类型的对象。 |
| [RectangleF](./rectanglef/) | 表示图像的矩形区域，定义为其左上角的单精度浮点数 X、Y 坐标以及宽度和高度。此类型应在栈上分配，并通过值或引用传递给函数。切勿使用 [System::SmartPtr](../system/smartptr/) 类来管理此类型的对象。 |
| [Region](./region/) | 表示图形形状的内部。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上创建此类型的实例或使用 operator new，因为这会导致运行时错误和/或断言错误。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [Size](./size/) | 表示图像宽度和高度的整数值对。此类型应在栈上分配，并通过值或引用传递给函数。切勿使用 [System::SmartPtr](../system/smartptr/) 类来管理此类型的对象。 |
| [SizeF](./sizef/) | 表示图像宽度和高度的单精度浮点数值对。此类型应在栈上分配，并通过值或引用传递给函数。切勿使用 [System::SmartPtr](../system/smartptr/) 类来管理此类型的对象。 |
| [SolidBrush](./solidbrush/) | 表示单色画刷。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上创建此类型的实例或使用 operator new，因为这会导致运行时错误和/或断言错误。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [StringFormat](./stringformat/) | 封装文本布局信息、显示操作和 OpenType 特性。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上创建此类型的实例或使用 operator new，因为这会导致运行时错误和/或断言错误。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [SystemColors](./systemcolors/) | 提供一组预先创建的 [Color](./color/) 对象，这些对象表示 [Windows](../system.windows/) 显示元素的颜色。这是一个没有实例服务的静态类型。绝不应以任何方式创建其实例。 |
| [SystemFonts](./systemfonts/) | 提供一组预先创建的 [Font](./font/) 对象，这些对象表示在 [Windows](../system.windows/) 显示元素中用于显示文本的字体。这是一个没有实例服务的静态类型。绝不应以任何方式创建其实例。 |
| [TextureBrush](./texturebrush/) | 表示使用图像填充形状内部的画刷。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上创建此类型的实例或使用 operator new，因为这会导致运行时错误和/或断言错误。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |

## 函数

| 函数 | 描述 |
| --- | --- |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, [Color](./color/)) | 使用 UTF-8 编码将数据插入流中。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, [Color](./color/)) | 将数据插入流中。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [Point](./point/)\&) | 使用 UTF-8 编码将数据插入流中。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [Point](./point/)\&) | 将数据插入流中。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [PointF](./pointf/)\&) | 使用 UTF-8 编码将数据插入流中。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [PointF](./pointf/)\&) | 将数据插入流中。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [Rectangle](./rectangle/)\&) | 使用 UTF-8 编码将数据插入流中。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [Rectangle](./rectangle/)\&) | 将数据插入流中。 |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [RectangleF](./rectanglef/)\&) | 使用 UTF-8 编码将数据插入流中。 |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [RectangleF](./rectanglef/)\&) | 将数据插入流中。 |

## 枚举

| 枚举 | 描述 |
| --- | --- |
| [ContentAlignment](./contentalignment/) | 指定内容对齐方式。 |
| [CopyPixelOperation](./copypixeloperation/) | 指定在像素复制操作中，源颜色与目标颜色的组合方式，以得到最终颜色。 |
| [FontStyle](./fontstyle/) | 表示字体样式。 |
| [GraphicsUnit](./graphicsunit/) | 表示计量单位。 |
| [KnownColor](./knowncolor/) | 指定已知的系统颜色。 |
| [RotateFlipType](./rotatefliptype/) | 指定旋转和/或翻转操作的类型。 |
| [StringAlignment](./stringalignment/) | 指定字符串相对于其布局矩形的对齐方式。 |
| [StringDigitSubstitute](./stringdigitsubstitute/) | 指定根据地区或语言对字符串中的数字进行替换的方式。 |
| [StringFormatFlags](./stringformatflags/) | 指定文本字符串的显示和布局信息。 |
| [StringTrimming](./stringtrimming/) | 指定当字符串不适配布局形状时应如何修剪字符。 |