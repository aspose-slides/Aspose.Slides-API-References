---
title: GetCells()
second_title: Aspose.Slides لواجهة برمجة التطبيقات C++
description: يسترجع مجموعة من الخلايا من المصنف التي تتطابق مع الصيغة المحددة.
type: docs
weight: 14
url: /ar/aspose.slides.excel/exceldataworkbook/getcells/
---
## ExcelDataWorkbook::GetCells(System::String, bool) طريقة


يسترجع مجموعة من الخلايا من المصنف التي تتطابق مع الصيغة المحددة.

```cpp
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> Aspose::Slides::Excel::ExcelDataWorkbook::GetCells(System::String formula, bool skipHiddenCells) override
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | صيغة أو تعبير نطاق (مثال: "Sheet1!A1:B3") يستخدم لتحديد الخلايا المستهدفة. |
| skipHiddenCells | **bool** | إذا كان **true**, سيتم استبعاد الخلايا المخفية (مثل الخلايا في الصفوف أو الأعمدة المخفية) من النتيجة. |

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

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [ReadOnlyCollection](../../../system.collections.objectmodel/readonlycollection/)
* فئة [IExcelDataCell](../../iexceldatacell/)
* فئة [String](../../../system/string/)
* فئة [ExcelDataWorkbook](../)
* مساحة الاسم [Aspose::Slides::Excel](../../)
* مكتبة [Aspose.Slides](../../../)