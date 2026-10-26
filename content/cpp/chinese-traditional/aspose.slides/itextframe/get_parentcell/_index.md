---
title: get_ParentCell()
second_title: Aspose.Slides C++ API 參考
description: 傳回父儲存格；如果父物件未實作 ICell 介面，則傳回 null。唯讀 ICell。
type: docs
weight: 79
url: /zh-hant/aspose.slides/itextframe/get_parentcell/
---
## ITextFrame::get_ParentCell() 方法

Returns the parent cell or null if the parent object does not implement the [ICell](../../icell/) interface. Read-only [ICell](../../icell/).

```cpp
virtual System::SharedPtr<ICell> Aspose::Slides::ITextFrame::get_ParentCell()=0
```

## 備註

The following code sample shows 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<Table> table = System::ExplicitCast<Table>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(table->idx_get(0, 0)->get_TextFrame()->get_ParentCell() == table->idx_get(0, 0));
```

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [ICell](../../icell/)
* 類別 [ITextFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)