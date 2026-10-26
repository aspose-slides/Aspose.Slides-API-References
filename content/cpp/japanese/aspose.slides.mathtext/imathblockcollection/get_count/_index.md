---
title: get_Count()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクションに実際に含まれる要素数を取得します。読み取り専用 int32_t.
type: docs
weight: 1
url: /ja/aspose.slides.mathtext/imathblockcollection/get_count/
---
## IMathBlockCollection::get_Count() メソッド


実際にコレクションに含まれる要素の数を取得します。読み取り専用 **int32_t**.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathBlockCollection::get_Count()=0
```

## 備考


例: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
int32_t blocksCount = blockCollection->get_Count();
```

## 参照

* クラス [IMathBlockCollection](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)