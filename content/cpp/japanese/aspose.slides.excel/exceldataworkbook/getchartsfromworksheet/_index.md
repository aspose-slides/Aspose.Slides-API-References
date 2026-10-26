---
title: GetChartsFromWorksheet()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された Excel ワークブックのワークシート内のすべてのチャートのインデックスと名前を含む辞書を取得します。
type: docs
weight: 40
url: /ja/aspose.slides.excel/exceldataworkbook/getchartsfromworksheet/
---
## ExcelDataWorkbook::GetChartsFromWorksheet(System::String) メソッド

指定されたワークシートにあるすべてのチャートのインデックスと名前を含む辞書を取得します。[Excel](../../) ワークブック。

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<int32_t, System::String>> Aspose::Slides::Excel::ExcelDataWorkbook::GetChartsFromWorksheet(System::String worksheetName) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | チャートを検索するワークシートの名前。 |

### 戻り値

キーがチャートのインデックスで、値がチャート名である辞書。

## 備考



例:
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetCharts = wb->GetChartsFromWorksheet(u"worksheetName");
for (auto&& chart : sheetCharts)
{
    System::Console::WriteLine(System::Convert::ToString(chart.get_Key()) + u" : " + chart.get_Value());
}
```

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IDictionary](../../../system.collections.generic/idictionary/)
* クラス [String](../../../system/string/)
* クラス [ExcelDataWorkbook](../)
* 名前空間 [Aspose::Slides::Excel](../../)
* ライブラリ [Aspose.Slides](../../../)