---
title: GetWorksheetNames()
second_title: Aspose.Slides の C++ 用 API リファレンス
description: Excel ワークブックに含まれるすべてのワークシートの名前を取得します。
type: docs
weight: 40
url: /ja/aspose.slides.excel/iexceldataworkbook/getworksheetnames/
---
## IExcelDataWorkbook::GetWorksheetNames() メソッド


[Excel](../../) ワークブックに含まれるすべてのワークシートの名前を取得します。

```cpp
virtual System::SharedPtr<System::Collections::Generic::IList<System::String>> Aspose::Slides::Excel::IExcelDataWorkbook::GetWorksheetNames()=0
```


### 戻り値

ワークシート名の一覧
## 備考



例: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetNames = wb->GetWorksheetNames();
for (auto&& name : sheetNames)
{
    System::Console::WriteLine(name);
}
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IList](../../../system.collections.generic/ilist/)
* クラス [String](../../../system/string/)
* クラス [IExcelDataWorkbook](../)
* 名前空間 [Aspose::Slides::Excel](../../)
* ライブラリ [Aspose.Slides](../../../)