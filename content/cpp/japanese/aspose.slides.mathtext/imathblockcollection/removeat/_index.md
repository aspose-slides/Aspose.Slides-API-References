---
title: RemoveAt()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクションの指定されたインデックスにある項目を削除します。
type: docs
weight: 53
url: /ja/aspose.slides.mathtext/imathblockcollection/removeat/
---
## IMathBlockCollection::RemoveAt(int32_t) メソッド


コレクションの指定されたインデックスにある項目を削除します。

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::RemoveAt(int32_t index)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | 削除する項目のゼロベースインデックスです。 |
## 備考



例: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
blockCollection->RemoveAt(0);
```

## 関連項目

* クラス [IMathBlockCollection](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)