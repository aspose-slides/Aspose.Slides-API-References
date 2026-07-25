---
title: GetOrCreateDataPointByIdx()
second_title: Aspose.Slides for C++ APIリファレンス
description: "コレクションにインデックス index のデータポイントがすでに含まれている場合、そのデータポイントを返します。コレクションにインデックス index ==N のデータポイントが存在しない場合（このコレクション内のデータポイント数が N 以下の場合）、不足しているデータポイントを追加し、最後の（要求されたインデックスを持つ）データポイントを返します。例えば、コレクションのインデックスは {0, 1, 2} で、要求されたインデックスは 5 です。この場合、メソッドは不足しているデータポイントを追加します: {0, 1, 2, 3, 4, 5}。そしてインデックス 5 のデータポイントを返します。"
type: docs
weight: 170
url: /ja/aspose.slides.charts/chartdatapointcollection/getorcreatedatapointbyidx/
---
## ChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t) メソッド


コレクションにインデックス *index* のデータポイントがすでに含まれている場合、そのデータポイントを返します。コレクションにインデックス *index* ==N のデータポイントが含まれていない場合（このコレクション内のデータポイント数が N 以下の場合）、不足しているデータポイントを追加し、最後の（要求されたインデックスを持つ）データポイントを返します。例えば、コレクションのインデックスは {0, 1, 2} で、要求されたインデックスは 5 です。この場合、メソッドは不足しているデータポイントを追加します: {0, 1, 2, 3, 4, 5}。そしてインデックス 5 のデータポイントを返します。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t index) override
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
* クラス [ChartDataPointCollection](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)