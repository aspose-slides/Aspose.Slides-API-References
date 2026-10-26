---
title: get_Row()
second_title: Aspose.Slides for C++ API リファレンス
description: セルが配置されているワークシートの行のゼロベースインデックスを取得します。読み取り専用 int32_t。
type: docs
weight: 27
url: /ja/aspose.slides.excel/exceldatacell/get_row/
---
## ExcelDataCell::get_Row() メソッド

セルが配置されているワークシートの行のゼロベースのインデックスを取得します。読み取り専用 **int32_t**。

```cpp
int32_t Aspose::Slides::Excel::ExcelDataCell::get_Row() override
```

## 備考


例: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Row());
```




## 参照

* クラス [ExcelDataCell](../)
* 名前空間 [Aspose::Slides::Excel](../../)
* ライブラリ [Aspose.Slides](../../../)