---
title: ToArray()
second_title: Aspose.Slides の C++ API リファレンス
description: すべてのスライドを含む配列を作成して返します。
type: docs
weight: 92
url: /ja/aspose.slides/islidecollection/toarray/
---
## ISlideCollection::ToArray() メソッド

すべてのスライドを含む配列を作成して返します。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::ToArray()=0
```

### 戻り値

[ISlide](../../islide/) の配列

## ISlideCollection::ToArray(int32_t, int32_t) メソッド

指定した範囲のスライドを含む配列を作成して返します。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::ToArray(int32_t startIndex, int32_t count)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| startIndex | **int32_t** | 追加する最初のスライドのインデックス。 |
| count | **int32_t** | 追加するスライドの数。 |

### 戻り値

[ISlide](../../islide/) の配列

## 関連項目

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [ISlide](../../islide/)
* クラス [ISlideCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)