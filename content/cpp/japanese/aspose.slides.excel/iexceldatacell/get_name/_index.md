---
title: get_Name()
second_title: Aspose.Slides for C++ API リファレンス
description: "チャート データセルの名前を取得します。読み取り専用 System::Stringです。"
type: docs
weight: 14
url: /ja/aspose.slides.excel/iexceldatacell/get_name/
---
## IExcelDataCell::get_Name() メソッド


チャート データセルの名前を取得します。読み取り専用 [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Excel::IExcelDataCell::get_Name()=0
```

## 備考


例: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Name());
```




## 参照

* クラス [String](../../../system/string/)
* クラス [IExcelDataCell](../)
* 名前空間 [Aspose::Slides::Excel](../../)
* ライブラリ [Aspose.Slides](../../../)