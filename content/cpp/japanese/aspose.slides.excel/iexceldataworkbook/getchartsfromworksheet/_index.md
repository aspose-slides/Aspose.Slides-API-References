---
title: GetChartsFromWorksheet()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された Excel ワークブックのワークシート内にあるすべてのチャートのインデックスと名前を含む辞書を取得します。
type: docs
weight: 27
url: /ja/aspose.slides.excel/iexceldataworkbook/getchartsfromworksheet/
---
## IExcelDataWorkbook::GetChartsFromWorksheet(System::String) メソッド

[Excel](../../) ワークブックの指定されたワークシート内のすべてのチャートのインデックスと名前を含む辞書を取得します。

```cpp
virtual System::SharedPtr<System::Collections::Generic::IDictionary<int32_t, System::String>> Aspose::Slides::Excel::IExcelDataWorkbook::GetChartsFromWorksheet(System::String worksheetName)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | チャートを検索するワークシートの名前です。 |

### 戻り値

キーがチャートのインデックス、値がチャート名である辞書です。

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

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IDictionary](../../../system.collections.generic/idictionary/)
* クラス [String](../../../system/string/)
* クラス [IExcelDataWorkbook](../)
* 名前空間 [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)