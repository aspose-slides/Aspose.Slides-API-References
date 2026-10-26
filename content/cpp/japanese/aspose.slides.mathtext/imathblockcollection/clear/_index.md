---
title: Clear()
second_title: Aspose.Slides の C++ API リファレンス
description: コレクションからすべての要素を削除します。
type: docs
weight: 118
url: /ja/aspose.slides.mathtext/imathblockcollection/clear/
---
## IMathBlockCollection::Clear() メソッド

コレクションからすべての要素を削除します。

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Clear()=0
```

## 備考

例: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
blockCollection->Clear();
```

## 参照

* クラス [IMathBlockCollection](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)