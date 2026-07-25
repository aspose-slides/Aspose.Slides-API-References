---
title: MergeCells()
second_title: Aspose.Slides for C++ API リファレンス
description: 隣接するセルを結合します。
type: docs
weight: 261
url: /ja/aspose.slides/itable/mergecells/
---
## ITable::MergeCells(System::SharedPtr\<ICell\>, System::SharedPtr\<ICell\>, bool) メソッド

隣接するセルを結合します。

```cpp
virtual System::SharedPtr<ICell> Aspose::Slides::ITable::MergeCells(System::SharedPtr<ICell> cell1, System::SharedPtr<ICell> cell2, bool allowSplitting)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| cell1 | [System::SharedPtr](../../../system/sharedptr/)\<[ICell](../../icell/)\> | [Cell](../../cell/) をマージする。 |
| cell2 | [System::SharedPtr](../../../system/sharedptr/)\<[ICell](../../icell/)\> | [Cell](../../cell/) をマージする。 |
| allowSplitting | **bool** | セルの分割を許可する場合は True。 |

### Return Value

結合されたセル。

## See Also

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [ICell](../../icell/)
* クラス [ITable](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)