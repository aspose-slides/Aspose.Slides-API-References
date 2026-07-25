---
title: IndexOf()
second_title: Aspose.Slides for C++ API リファレンス
description: IList 内の特定の項目のインデックスを決定します。
type: docs
weight: 40
url: /ja/aspose.slides.animation/behaviorpropertycollection/indexof/
---
## BehaviorPropertyCollection::IndexOf(const System::SharedPtr\<IBehaviorProperty\>\&) const method

特定の項目のインデックスを [IList](../../../system.collections.generic/ilist/) で決定します。

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::SharedPtr<IBehaviorProperty> &item) const override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\& | [IList](../../../system.collections.generic/ilist/) で検索するオブジェクト |

### 戻り値

リストで *item* が見つかった場合はそのインデックス、見つからなければ -1 を返します。

## BehaviorPropertyCollection::IndexOf(const System::String\&) const method

プロパティ値で特定の項目のインデックスを [IList](../../../system.collections.generic/ilist/) から決定します。

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::String &propertyValue) const override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| propertyValue | const [System::String](../../../system/string/)\& | プロパティの値 |

### 戻り値

指定された値を持つプロパティのインデックスを返します。

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IBehaviorProperty](../../ibehaviorproperty/)
* クラス [BehaviorPropertyCollection](../)
* クラス [String](../../../system/string/)
* 名前空間 [Aspose::Slides::Animation](../../)
* ライブラリ [Aspose.Slides](../../../)