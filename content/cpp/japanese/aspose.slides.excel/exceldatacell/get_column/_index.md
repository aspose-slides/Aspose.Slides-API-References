---
title: get_Column()
second_title: Aspose.Slides for C++ API リファレンス
description: セルが配置されているワークシートの列のゼロベースインデックスを取得します。読み取り専用 int32_t。
type: docs
weight: 40
url: /ja/aspose.slides.excel/exceldatacell/get_column/
---
## ExcelDataCell::get_Column() メソッド

セルが配置されているワークシート内の列のゼロベースインデックスを取得します。読み取り専用 **int32_t**。

```cpp
int32_t Aspose::Slides::Excel::ExcelDataCell::get_Column() override
```

## 備考

例:
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Column());
```

## 参照

* クラス [ExcelDataCell](../)
* 名前空間 [Aspose::Slides::Excel](../../)
* ライブラリ [Aspose.Slides](../../../)