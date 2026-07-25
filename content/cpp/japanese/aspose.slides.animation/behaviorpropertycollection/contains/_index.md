---
title: Contains()
second_title: Aspose.Slides for C++ APIリファレンス
description: ICollection に特定の値が含まれているかどうかを判定します。
type: docs
weight: 118
url: /ja/aspose.slides.animation/behaviorpropertycollection/contains/
---
## BehaviorPropertyCollection::Contains(const System::SharedPtr\<IBehaviorProperty\>\&) const method


[ICollection](../../../system.collections.generic/icollection/) に特定の値が含まれているかどうかを判定します。

```cpp
bool Aspose::Slides::Animation::BehaviorPropertyCollection::Contains(const System::SharedPtr<IBehaviorProperty> &item) const override
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\& | [ICollection](../../../system.collections.generic/icollection/) 内で検索するプロパティ。 |

### 戻り値

*item* が [ICollection](../../../system.collections.generic/icollection/) に見つかった場合は true、それ以外の場合は false。

## BehaviorPropertyCollection::Contains(const System::String\&) const method


[ICollection](../../../system.collections.generic/icollection/) に特定の値が含まれているかどうかを判定します。

```cpp
bool Aspose::Slides::Animation::BehaviorPropertyCollection::Contains(const System::String &propertyValue) const override
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| propertyValue | const [System::String](../../../system/string/)\& | [ICollection](../../../system.collections.generic/icollection/) 内で検索するプロパティの値。 |

### 戻り値

*propertyValue* が [ICollection](../../../system.collections.generic/icollection/) に見つかった場合は true、それ以外の場合は false。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IBehaviorProperty](../../ibehaviorproperty/)
* クラス [BehaviorPropertyCollection](../)
* クラス [String](../../../system/string/)
* 名前空間 [Aspose::Slides::Animation](../../)
* ライブラリ [Aspose.Slides](../../../)