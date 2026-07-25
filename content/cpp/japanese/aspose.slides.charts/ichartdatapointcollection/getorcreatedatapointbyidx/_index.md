---
title: GetOrCreateDataPointByIdx()
second_title: Aspose.Slides for C++ API リファレンス
description: "コレクションにインデックス index のデータポイントがすでに含まれている場合は、そのデータポイントを返します。コレクションにインデックス index ==N のデータポイントが含まれていない場合（このコレクション内のデータポイント数が N 以下の場合）、不足しているデータポイントを追加し、要求されたインデックスを持つ最後のデータポイントを返します。例えば、コレクションのインデックスは {0, 1, 2} で、要求されたインデックスは 5 です。このときメソッドは不足しているデータポイントを追加します: {0, 1, 2, 3, 4, 5}。そしてインデックス 5 のデータポイントを返します。"
type: docs
weight: 131
url: /ja/aspose.slides.charts/ichartdatapointcollection/getorcreatedatapointbyidx/
---
## IChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t) メソッド


コレクションにインデックス *index* のデータポイントがすでに含まれている場合は、そのデータポイントを返します。コレクションにインデックス *index* ==N のデータポイントが含まれていない場合（このコレクション内のデータポイント数が N 以下の場合）、不足しているデータポイントを追加し、要求されたインデックスを持つ最後のデータポイントを返します。例えば、コレクションのインデックスは {0, 1, 2} で、要求されたインデックスは 5 です。この場合、メソッドは不足しているデータポイントを追加します: {0, 1, 2, 3, 4, 5}。そしてインデックス 5 のデータポイントを返します。

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t index)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **uint32_t** | インデックス。 |

### 戻り値

要求されたインデックスのデータポイントを返します。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IChartDataPoint](../../ichartdatapoint/)
* クラス [IChartDataPointCollection](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)