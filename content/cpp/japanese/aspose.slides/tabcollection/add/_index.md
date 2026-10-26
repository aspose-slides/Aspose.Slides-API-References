---
title: Add()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクションに Tab を追加します。
type: docs
weight: 53
url: /ja/aspose.slides/tabcollection/add/
---
## TabCollection::Add(double, TabAlignment) メソッド


[Tab](../../tab/) をコレクションに追加します。

```cpp
System::SharedPtr<ITab> Aspose::Slides::TabCollection::Add(double position, TabAlignment align) override
```


### 戻り値

追加されたタブ。

## TabCollection::Add(System::SharedPtr\<ITab\>) メソッド


[Tab](../../tab/) をコレクションに追加します。

```cpp
int32_t Aspose::Slides::TabCollection::Add(System::SharedPtr<ITab> value) override
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ITab](../../itab/)\> | コレクションの末尾に追加される [Tab](../../tab/) オブジェクト。 |

### 戻り値

タブが追加されたインデックス。

## 参照

* Enum [TabAlignment](../../tabalignment/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITab](../../itab/)
* Class [TabCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)