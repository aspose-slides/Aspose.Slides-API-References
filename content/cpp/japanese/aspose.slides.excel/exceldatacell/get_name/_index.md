---
title: get_Name()
second_title: Aspose.Slides for C++ API リファレンス
description: チャート データ セルの名前を取得します。
type: docs
weight: 14
url: /ja/aspose.slides.excel/exceldatacell/get_name/
---
## ExcelDataCell::get_Name() メソッド


チャート データ セルの名前を取得します。

```cpp
System::String Aspose::Slides::Excel::ExcelDataCell::get_Name() override
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
* クラス [ExcelDataCell](../)
* 名前空間 [Aspose::Slides::Excel](../../)
* ライブラリ [Aspose.Slides](../../../)