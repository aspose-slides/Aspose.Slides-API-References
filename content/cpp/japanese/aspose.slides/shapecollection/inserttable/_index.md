---
title: InsertTable()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しいテーブルを作成し、指定されたインデックスで shape collection に挿入します。
type: docs
weight: 482
url: /ja/aspose.slides/shapecollection/inserttable/
---
## ShapeCollection::InsertTable(int32_t, float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) method


新しいテーブルを作成し、指定されたインデックスで shape collection に挿入します。

```cpp
System::SharedPtr<ITable> Aspose::Slides::ShapeCollection::InsertTable(int32_t index, float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | テーブルを挿入するゼロベースのインデックスです。 |
| x | **float** | テーブルの x 座標（ポイント単位）です。 |
| y | **float** | テーブルの y 座標（ポイント単位）です。 |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | テーブルの列幅をポイントで表す **double** の配列です。 |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | テーブルの行の高さをポイントで表す **double** の配列です。 |

### 戻り値

新しく作成された[ITable](../../itable/)です。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ITable](../../itable/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)