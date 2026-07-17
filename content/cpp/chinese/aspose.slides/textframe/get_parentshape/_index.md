---
title: get_ParentShape()
second_title: Aspose.Slides for C++ API 参考
description: 如果父对象未实现 IShape 接口，则返回父形状或 null。只读 IShape。
type: docs
weight: 92
url: /zh/aspose.slides/textframe/get_parentshape/
---
## TextFrame::get_ParentShape() 方法

返回父形状或 null，如果父对象未实现 [IShape](../../ishape/) 接口。只读 [IShape](../../ishape/)。

```cpp
System::SharedPtr<IShape> Aspose::Slides::TextFrame::get_ParentShape() override
```

## 备注

以下代码示例展示 ```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<AutoShape> autoShape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(autoShape->get_TextFrame()->get_ParentShape() == autoShape);
```

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IShape](../../ishape/)
* 类 [TextFrame](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)