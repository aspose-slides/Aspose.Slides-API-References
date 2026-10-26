---
title: get_Value()
second_title: Aspose.Slides for C++ API リファレンス
description: Excel セルに含まれる値を取得します。
type: docs
weight: 1
url: /ja/aspose.slides.excel/exceldatacell/get_value/
---
## ExcelDataCell::get_Value() メソッド

[Excel](../../) セルに含まれる値を取得します。

```cpp
System::SharedPtr<System::Object> Aspose::Slides::Excel::ExcelDataCell::get_Value() override
```

## 備考

例: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Object](../../../system/object/)
* クラス [ExcelDataCell](../)
* 名前空間 [Aspose::Slides::Excel](../../)
* ライブラリ [Aspose.Slides](../../../)