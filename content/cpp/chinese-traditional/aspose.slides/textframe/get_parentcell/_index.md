---
title: get_ParentCell()
second_title: Aspose.Slides for C++ API 參考文件
description: 若父物件未實作 ICell 介面，則傳回父儲存格或 null。唯讀 ICell。
type: docs
weight: 105
url: /zh-hant/aspose.slides/textframe/get_parentcell/
---
## TextFrame::get_ParentCell() 方法

若父物件未實作 [ICell](../../icell/) 介面，則回傳父儲存格或 null。唯讀 [ICell](../../icell/)。

```cpp
System::SharedPtr<ICell> Aspose::Slides::TextFrame::get_ParentCell() override
```

## 備註

以下程式碼範例說明
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<Table> table = System::ExplicitCast<Table>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(table->idx_get(0, 0)->get_TextFrame()->get_ParentCell() == table->idx_get(0, 0));
```

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [ICell](../../icell/)
* 類別 [TextFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)