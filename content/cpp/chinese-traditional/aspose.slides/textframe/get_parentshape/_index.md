---
title: get_ParentShape()
second_title: Aspose.Slides C++ API 參考
description: 傳回父形狀或 null；如果父物件未實作 IShape 介面，則傳回 null。唯讀 IShape。
type: docs
weight: 92
url: /zh-hant/aspose.slides/textframe/get_parentshape/
---
## TextFrame::get_ParentShape() 方法

傳回父形狀或 null；如果父物件未實作 [IShape](../../ishape/) 介面，則傳回 null。唯讀 [IShape](../../ishape/)。

```cpp
System::SharedPtr<IShape> Aspose::Slides::TextFrame::get_ParentShape() override
```

## 備註

以下程式碼範例顯示 ```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<AutoShape> autoShape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(autoShape->get_TextFrame()->get_ParentShape() == autoShape);
```

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IShape](../../ishape/)
* 類別 [TextFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)