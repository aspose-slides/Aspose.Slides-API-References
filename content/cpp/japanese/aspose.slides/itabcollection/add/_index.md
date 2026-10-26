---
title: Add()
second_title: Aspose.Slides for C++ APIリファレンス
description: コレクションにタブを追加します。
type: docs
weight: 14
url: /ja/aspose.slides/itabcollection/add/
---
## ITabCollection::Add(double, TabAlignment) メソッド

コレクションに [Tab](../../tab/) を追加します。

```cpp
virtual System::SharedPtr<ITab> Aspose::Slides::ITabCollection::Add(double position, TabAlignment align)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| position | **double** | [Tab](../../tab/) 位置。 |
| align | [TabAlignment](../../tabalignment/) | [Tab](../../tab/) 配置。 |

### 戻り値

追加されたタブ。

## ITabCollection::Add(System::SharedPtr\<ITab\>) メソッド

コレクションに [Tab](../../tab/) を追加します。

```cpp
virtual int32_t Aspose::Slides::ITabCollection::Add(System::SharedPtr<ITab> value)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ITab](../../itab/)\> | コレクションの末尾に追加される [Tab](../../tab/) オブジェクト。 |

### 戻り値

タブが追加されたインデックス。

## 参照

* 列挙型 [TabAlignment](../../tabalignment/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITab](../../itab/)
* Class [ITabCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)