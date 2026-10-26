---
title: RemoveAt()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクションの指定されたインデックスにある要素を削除します。
type: docs
weight: 53
url: /ja/aspose.slides/imasterlayoutslidecollection/removeat/
---
## IMasterLayoutSlideCollection::RemoveAt(int32_t) メソッド

削除対象の要素をコレクションの指定インデックスから削除します。

```cpp
virtual void Aspose::Slides::IMasterLayoutSlideCollection::RemoveAt(int32_t index)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | 削除する要素のゼロベースインデックス。 |
## 備考

1) PptxEditException のスローを回避するために、事前に layout の HasDependingSlides プロパティを確認してください。 2) コードを簡素化するために、[ILayoutSlide::Remove](../../ilayoutslide/remove/) メソッドも使用できます。 
## 参照

* クラス [IMasterLayoutSlideCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)