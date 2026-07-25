---
title: get_Row()
second_title: Aspose.Slides for C++ API リファレンス
description: セルが配置されているワークシートの行のゼロベースインデックスを取得します。読み取り専用 int32_t.
type: docs
weight: 27
url: /ja/aspose.slides.excel/iexceldatacell/get_row/
---
## IExcelDataCell::get_Row() メソッド

ワークシート内でセルが配置されている行のゼロベースインデックスを取得します。読み取り専用 **int32_t**.

```cpp
virtual int32_t Aspose::Slides::Excel::IExcelDataCell::get_Row()=0
```

## 備考

例:
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Row());
```


## 参照

* クラス [IExcelDataCell](../)
* 名前空間 [Aspose::Slides::Excel](../../)
* ライブラリ [Aspose.Slides](../../../)