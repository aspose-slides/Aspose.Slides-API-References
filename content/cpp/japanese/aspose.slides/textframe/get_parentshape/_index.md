---
title: get_ParentShape()
second_title: Aspose.Slides の C++ API リファレンス
description: 親シェイプまたは、親オブジェクトが IShape インターフェイスを実装していない場合は null を返します。読み取り専用 IShape。
type: docs
weight: 92
url: /ja/aspose.slides/textframe/get_parentshape/
---
## TextFrame::get_ParentShape() メソッド

親シェイプまたは、親オブジェクトが [IShape](../../ishape/) インターフェイスを実装していない場合は null を返します。読み取り専用 [IShape](../../ishape/)。

```cpp
System::SharedPtr<IShape> Aspose::Slides::TextFrame::get_ParentShape() override
```

## 備考

以下のコードサンプルは示しています
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<AutoShape> autoShape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(autoShape->get_TextFrame()->get_ParentShape() == autoShape);
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IShape](../../ishape/)
* クラス [TextFrame](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)