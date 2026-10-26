---
title: get_ParentShape()
second_title: Aspose.Slides for C++ API 參考
description: 返回父形狀或 null，如果父物件未實作 IShape 介面，唯讀 IShape。
type: docs
weight: 66
url: /zh-hant/aspose.slides/itextframe/get_parentshape/
---
## ITextFrame::get_ParentShape() 方法


返回父形狀或 null，如果父物件未實作 [IShape](../../ishape/) 介面，唯讀 [IShape](../../ishape/)。

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::ITextFrame::get_ParentShape()=0
```

## 備註


以下程式範例顯示
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<AutoShape> autoShape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(autoShape->get_TextFrame()->get_ParentShape() == autoShape);
```

## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IShape](../../ishape/)
* 類別 [ITextFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)