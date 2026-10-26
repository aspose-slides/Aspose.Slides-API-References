---
title: AddSection()
second_title: Aspose.Slides for C++ APIリファレンス
description: 特定のスライドから開始するスライド セクションを追加します。
type: docs
weight: 53
url: /ja/aspose.slides/sectioncollection/addsection/
---
## SectionCollection::AddSection(System::String, System::SharedPtr\<ISlide\>) メソッド

特定のスライドから開始するスライド セクションを追加します。

```cpp
System::SharedPtr<ISection> Aspose::Slides::SectionCollection::AddSection(System::String name, System::SharedPtr<ISlide> startedFromSlide) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | セクションの名前 |
| startedFromSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | セクションの最初のスライド |

### 戻り値

追加されたセクション。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISection](../../isection/)
* Class [String](../../../system/string/)
* Class [ISlide](../../islide/)
* Class [SectionCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)