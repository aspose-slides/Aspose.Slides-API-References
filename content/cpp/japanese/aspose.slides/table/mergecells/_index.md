---
title: MergeCells()
second_title: Aspose.Slides for C++ API リファレンス
description: 隣接するセルをマージします。
type: docs
weight: 274
url: /ja/aspose.slides/table/mergecells/
---
## Table::MergeCells(System::SharedPtr\<ICell\>, System::SharedPtr\<ICell\>, bool) メソッド

隣接するセルをマージします。

```cpp
System::SharedPtr<ICell> Aspose::Slides::Table::MergeCells(System::SharedPtr<ICell> cell1, System::SharedPtr<ICell> cell2, bool allowSplitting) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| cell1 | [System::SharedPtr](../../../system/sharedptr/)\<[ICell](../../icell/)\> | [Cell](../../cell/) をマージします。 |
| cell2 | [System::SharedPtr](../../../system/sharedptr/)\<[ICell](../../icell/)\> | [Cell](../../cell/) をマージします。 |
| allowSplitting | **bool** | セルの分割を許可する場合は True。 |

### 戻り値

マージされたセル。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [ICell](../../icell/)
* クラス [Table](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)