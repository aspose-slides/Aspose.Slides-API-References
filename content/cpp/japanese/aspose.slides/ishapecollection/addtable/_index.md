---
title: AddTable()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しいテーブルを作成し、シェイプ コレクションの末尾に追加します。
type: docs
weight: 430
url: /ja/aspose.slides/ishapecollection/addtable/
---
## IShapeCollection::AddTable(float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) メソッド

新しいテーブルを作成し、シェイプ コレクションの末尾に追加します。

```cpp
virtual System::SharedPtr<ITable> Aspose::Slides::IShapeCollection::AddTable(float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | **float** | テーブルの x 座標（ポイント単位）。 |
| y | **float** | テーブルの y 座標（ポイント単位）。 |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | テーブルの列の幅をポイント単位で表す double の配列。 |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | テーブルの行の高さをポイント単位で表す double の配列。 |

### 戻り値

新しく作成された [ITable](../../itable/)。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [ITable](../../itable/)
* クラス [IShapeCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)