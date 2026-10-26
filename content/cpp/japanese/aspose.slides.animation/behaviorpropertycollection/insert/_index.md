---
title: Insert()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたインデックスに新しいプロパティをコレクションへ挿入します。
type: docs
weight: 53
url: /ja/aspose.slides.animation/behaviorpropertycollection/insert/
---
## BehaviorPropertyCollection::Insert(int32_t, const System::SharedPtr\<IBehaviorProperty\>\&) メソッド

指定されたインデックスに新しいプロパティをコレクションに挿入します。

```cpp
void Aspose::Slides::Animation::BehaviorPropertyCollection::Insert(int32_t index, const System::SharedPtr<IBehaviorProperty> &item) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | 新しいプロパティを挿入するインデックス。 |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\& | 追加するプロパティ。 |

## BehaviorPropertyCollection::Insert(int32_t, System::String) メソッド

指定されたインデックスに新しいプロパティ（指定されたプロパティ値を持つ）をコレクションに挿入します。

```cpp
void Aspose::Slides::Animation::BehaviorPropertyCollection::Insert(int32_t index, System::String propertyValue) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | 新しいプロパティを挿入するインデックス。 |
| propertyValue | [System::String](../../../system/string/) | 追加するプロパティの値。 |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IBehaviorProperty](../../ibehaviorproperty/)
* クラス [BehaviorPropertyCollection](../)
* クラス [String](../../../system/string/)
* 名前空間 [Aspose::Slides::Animation](../../)
* ライブラリ [Aspose.Slides](../../../)