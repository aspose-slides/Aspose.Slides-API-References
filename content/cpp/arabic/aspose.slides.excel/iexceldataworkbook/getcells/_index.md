---
title: GetCells()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يسترجع مجموعة من الخلايا من المصنف التي تطابق الصيغة المحددة.
type: docs
weight: 1
url: /ar/aspose.slides.excel/iexceldataworkbook/getcells/
---
## IExcelDataWorkbook::GetCells(System::String, bool) طريقة


يسترجع مجموعة من الخلايا من المصنف التي تطابق الصيغة المحددة.

```cpp
virtual System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> Aspose::Slides::Excel::IExcelDataWorkbook::GetCells(System::String formula, bool skipHiddenCells)=0
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | صيغة أو تعبير نطاق (مثال: \"Sheet1!A1:B3\") يُستخدم لتحديد الخلايا المستهدفة. |
| skipHiddenCells | **bool** | إذا **true**، سيتم استبعاد الخلايا المخفية (مثال: في الصفوف أو الأعمدة المخفية) من النتيجة. |

### قيمة الإرجاع

قائمة للقراءة فقط من الخلايا التي تطابق الصيغة المحددة.
## ملاحظات



مثال: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> cells = wb->GetCells(u"Sheet1!A2:A6", false);
System::Console::WriteLine(cells->get_Count());
```

## انظر أيضًا

* نوع معرف [SharedPtr](../../../system/sharedptr/)
* فئة [ReadOnlyCollection](../../../system.collections.objectmodel/readonlycollection/)
* فئة [IExcelDataCell](../../iexceldatacell/)
* فئة [String](../../../system/string/)
* فئة [IExcelDataWorkbook](../)
* مساحة الاسم [Aspose::Slides::Excel](../../)
* مكتبة [Aspose.Slides](../../../)