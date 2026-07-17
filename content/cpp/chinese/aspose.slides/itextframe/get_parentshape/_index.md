---
title: get_ParentShape()
second_title: Aspose.Slides C++ API 参考
description: 返回父形状；如果父对象未实现 IShape 接口，则返回 null。只读 IShape。
type: docs
weight: 66
url: /zh/aspose.slides/itextframe/get_parentshape/
---
## ITextFrame::get_ParentShape() 方法

返回父形状；如果父对象未实现 [IShape](../../ishape/) 接口，则返回 null。只读 [IShape](../../ishape/)。

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::ITextFrame::get_ParentShape()=0
```

## 备注

以下代码示例显示
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<AutoShape> autoShape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(autoShape->get_TextFrame()->get_ParentShape() == autoShape);
```

## 参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IShape](../../ishape/)
* 类 [ITextFrame](../)
* 命名空间 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)