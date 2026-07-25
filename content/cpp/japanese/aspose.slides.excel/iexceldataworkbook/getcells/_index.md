---
title: GetCells()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された数式に一致するワークブックからセルのコレクションを取得します。
type: docs
weight: 1
url: /ja/aspose.slides.excel/iexceldataworkbook/getcells/
---
## IExcelDataWorkbook::GetCells(System::String, bool) メソッド

指定された数式に一致するセルのコレクションをワークブックから取得します。

```cpp
virtual System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> Aspose::Slides::Excel::IExcelDataWorkbook::GetCells(System::String formula, bool skipHiddenCells)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | 対象セルを特定するために使用される、数式または範囲式（例: "Sheet1!A1:B3"）です。 |
| skipHiddenCells | **bool** | **true** の場合、隠しセル（例: 非表示の行や列にあるセル）が結果から除外されます。 |

### 戻り値

指定された数式に一致するセルの読み取り専用リストです。

## 備考

例:
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> cells = wb->GetCells(u"Sheet1!A2:A6", false);
System::Console::WriteLine(cells->get_Count());
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [ReadOnlyCollection](../../../system.collections.objectmodel/readonlycollection/)
* クラス [IExcelDataCell](../../iexceldatacell/)
* クラス [String](../../../system/string/)
* クラス [IExcelDataWorkbook](../)
* 名前空間 [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)