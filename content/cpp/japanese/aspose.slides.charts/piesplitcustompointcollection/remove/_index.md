---
title: Remove()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクションから項目を削除します。
type: docs
weight: 79
url: /ja/aspose.slides.charts/piesplitcustompointcollection/remove/
---
## PieSplitCustomPointCollection::Remove(const System::SharedPtr\<IChartDataPoint\>\&) メソッド

コレクションから項目を削除します。

```cpp
bool Aspose::Slides::Charts::PieSplitCustomPointCollection::Remove(const System::SharedPtr<IChartDataPoint> &dataPoint) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| dataPoint | const [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataPoint](../../ichartdatapoint/)\>\& | 削除対象のデータポイント。 |

### 戻り値

アイテムが正常に削除された場合は true、そうでない場合は false を返します。このメソッドは、[System::Collections::Generic::List](../../../system.collections.generic/list/){T} でアイテムが見つからなかった場合も false を返します。

## PieSplitCustomPointCollection::Remove(int32_t) メソッド

親シリーズのポイントコレクション内のインデックスにより、コレクションから項目を削除します。

```cpp
void Aspose::Slides::Charts::PieSplitCustomPointCollection::Remove(int32_t dataPointIndex) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| dataPointIndex | **int32_t** | 親シリーズのポイントコレクション内のデータポイントのインデックス。 |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IChartDataPoint](../../ichartdatapoint/)
* クラス [PieSplitCustomPointCollection](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)