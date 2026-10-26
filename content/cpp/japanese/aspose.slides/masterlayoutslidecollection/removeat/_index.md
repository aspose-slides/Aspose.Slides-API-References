---
title: RemoveAt()
second_title: Aspose.Slides の C++ API リファレンス
description: コレクションの指定されたインデックスにある要素を削除します。
type: docs
weight: 53
url: /ja/aspose.slides/masterlayoutslidecollection/removeat/
---
## MasterLayoutSlideCollection::RemoveAt(int32_t) メソッド

コレクションの指定されたインデックスにある要素を削除します。

```cpp
void Aspose::Slides::MasterLayoutSlideCollection::RemoveAt(int32_t index) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | コレクションから削除する要素の 0 ベースインデックス。 |

## 備考

1) PptxEditException のスローを回避するため、事前に layout の HasDependingSlides プロパティを確認してください。 2) コードを簡素化するために、[ILayoutSlide::Remove](../../ilayoutslide/remove/) メソッドも使用できます。

## 参照

* クラス [MasterLayoutSlideCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)