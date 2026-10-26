---
title: ColorTranslator
second_title: Aspose.Slides for C++ API 参考
description: "执行颜色转换。此类的对象应仅使用 System::MakeObject() 函数分配。不要在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误和/或断言错误。始终将此类包装成 System::SmartPtr 指针，并使用该指针将其作为参数传递给函数。"
type: docs
weight: 66
url: /zh/system.drawing/colortranslator/
---
## ColorTranslator 类

执行颜色转换。此类的对象应只能使用 [System::MakeObject()](../../system/makeobject/) 函数分配。不要在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误和/或断言错误。始终将此类包装成 [System::SmartPtr](../../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。

```cpp
class ColorTranslator
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static [Color](../color/) [FromHtml](./fromhtml/)(const [System::String](../../system/string/)\&) | 将指定的 HTML 颜色表示转换为等效的 [Color](../color/) 对象。 |
| static [Color](../color/) [FromWin32](./fromwin32/)(int) | 将指定的 [Windows](../../system.windows/) 颜色转换为等效的 [Color](../color/) 对象。 |
| static [String](../../system/string/) [ToHtml](./tohtml/)(const [Color](../color/)\&) | 将指定的 [Color](../color/) 对象转换为等效 HTML 颜色的字符串表示。 |
## 另请参阅

* 命名空间 [System::Drawing](../)
* 库 [Aspose.Slides](../../)