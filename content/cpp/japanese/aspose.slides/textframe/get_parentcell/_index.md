---
title: get_ParentCell()
second_title: Aspose.Slides for C++ API リファレンス
description: 親オブジェクトが ICell インターフェイスを実装していない場合は、親セルまたは null を返します。読み取り専用 ICell.
type: docs
weight: 105
url: /ja/aspose.slides/textframe/get_parentcell/
---
## TextFrame::get_ParentCell() メソッド


親セルまたは、親オブジェクトが [ICell](../../icell/) インターフェイスを実装していない場合は null を返します。読み取り専用 [ICell](../../icell/).

```cpp
System::SharedPtr<ICell> Aspose::Slides::TextFrame::get_ParentCell() override
```

## 備考


以下のコードサンプルは示しています
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<Table> table = System::ExplicitCast<Table>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(table->idx_get(0, 0)->get_TextFrame()->get_ParentCell() == table->idx_get(0, 0));
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [ICell](../../icell/)
* クラス [TextFrame](../)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)