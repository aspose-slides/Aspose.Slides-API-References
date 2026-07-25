---
title: get_ParentShape()
second_title: Aspose.Slides for C++ API リファレンス
description: 親シェイプを返します。親オブジェクトが IShape インターフェイスを実装していない場合は null を返します。読み取り専用 IShape。
type: docs
weight: 66
url: /ja/aspose.slides/itextframe/get_parentshape/
---
## ITextFrame::get_ParentShape() メソッド


親シェイプを返します。親オブジェクトが [IShape](../../ishape/) インターフェイスを実装していない場合は null を返します。読み取り専用 [IShape](../../ishape/)。

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::ITextFrame::get_ParentShape()=0
```

## 備考


以下のコードサンプルは次のことを示します
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<AutoShape> autoShape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(autoShape->get_TextFrame()->get_ParentShape() == autoShape);
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IShape](../../ishape/)
* クラス [ITextFrame](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)