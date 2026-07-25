---
title: get_ParentCell()
second_title: Aspose.Slides for C++ API リファレンス
description: 親セルを返します。親オブジェクトがICellインターフェイスを実装していない場合はnullを返します。読み取り専用 ICell。
type: docs
weight: 79
url: /ja/aspose.slides/itextframe/get_parentcell/
---
## ITextFrame::get_ParentCell() メソッド

親セルを返します。親オブジェクトが[ICell](../../icell/)インターフェイスを実装していない場合はnullを返します。読み取り専用 [ICell](../../icell/)。

```cpp
virtual System::SharedPtr<ICell> Aspose::Slides::ITextFrame::get_ParentCell()=0
```

## 備考

以下のコードサンプルは示しています
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<Table> table = System::ExplicitCast<Table>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(table->idx_get(0, 0)->get_TextFrame()->get_ParentCell() == table->idx_get(0, 0));
```

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [ICell](../../icell/)
* クラス [ITextFrame](../)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)