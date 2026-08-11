---
title: AddTable()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة C++
description: ينشئ جدولًا جديدًا ويضيفه إلى نهاية مجموعة الأشكال.
type: docs
weight: 430
url: /ar/aspose.slides/ishapecollection/addtable/
---
## IShapeCollection::AddTable(float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) طريقة

Creates a new table and adds it to the end of the shape collection.

```cpp
virtual System::SharedPtr<ITable> Aspose::Slides::IShapeCollection::AddTable(float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights)=0
```

### Arguments

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | **float** | إحداثي السيني للجدول، بالنقاط. |
| y | **float** | إحداثي الصادي للجدول، بالنقاط. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | مصفوفة من القيم المزدوجة تمثل عرض أعمدة الجدول، بالنقاط. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | مصفوفة من القيم المزدوجة تمثل ارتفاع صفوف الجدول، بالنقاط. |

### Return Value

الكائن [ITable](../../itable/) الذي تم إنشاؤه حديثًا.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* فئة [ITable](../../itable/)
* فئة [IShapeCollection](../)
* نطاق [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)