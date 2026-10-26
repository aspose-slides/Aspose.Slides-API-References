---
title: get_Value()
second_title: Aspose.Slides for C++ API リファレンス
description: "Excel セルに含まれる値を取得します。 読み取り専用 System::Object."
type: docs
weight: 1
url: /ja/aspose.slides.excel/iexceldatacell/get_value/
---
## IExcelDataCell::get_Value() メソッド


[Excel](../../) セルに含まれる値を取得します。 読み取り専用 [System::Object](../../../system/object/).

```cpp
virtual System::SharedPtr<System::Object> Aspose::Slides::Excel::IExcelDataCell::get_Value()=0
```

## 備考


例:
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```




## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Object](../../../system/object/)
* クラス [IExcelDataCell](../)
* 名前空間 [Aspose::Slides::Excel](../../)
* ライブラリ [Aspose.Slides](../../../)