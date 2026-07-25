---
title: GetCells()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された数式に一致するワークブックからセルのコレクションを取得します。
type: docs
weight: 14
url: /ja/aspose.slides.excel/exceldataworkbook/getcells/
---
## ExcelDataWorkbook::GetCells(System::String, bool) メソッド


指定された数式に一致するワークブックからセルのコレクションを取得します。

```cpp
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> Aspose::Slides::Excel::ExcelDataWorkbook::GetCells(System::String formula, bool skipHiddenCells) override
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | 対象セルを特定するために使用する数式または範囲式（例: "Sheet1!A1:B3"）。 |
| skipHiddenCells | **bool** | **true** の場合、非表示の行や列にあるセルは結果から除外されます。 |

### 戻り値

指定された数式に一致するセルの読み取り専用リスト。

## 備考



例: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> cells = wb->GetCells(u"Sheet1!A2:A6", false);
System::Console::WriteLine(cells->get_Count());
```

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [ReadOnlyCollection](../../../system.collections.objectmodel/readonlycollection/)
* クラス [IExcelDataCell](../../iexceldatacell/)
* クラス [String](../../../system/string/)
* クラス [ExcelDataWorkbook](../)
* 名前空間 [Aspose::Slides::Excel](../../)
* ライブラリ [Aspose.Slides](../../../)