---
title: AddSummaryZoomSection()
second_title: مرجع Aspose.Slides لواجهة برمجة التطبيقات C++
description: ينشئ كائن Summary Zoom Section جديد ويضيفه إلى المجموعة
type: docs
weight: 14
url: /ar/aspose.slides/isummaryzoomsectioncollection/addsummaryzoomsection/
---
## ISummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr\<ISection\>) طريقة

ينشئ كائن Summary Zoom [Section](../../section/) جديد ويضيفه إلى المجموعة

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr<ISection> section)=0
```

### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) لعنصر Summary Zoom [Section](../../section/) جديد [ISection](../../isection/) |

### قيمة الإرجاع

تمت إضافة العنصر [ISummaryZoomFrame](../../isummaryzoomframe/)

## ملاحظات

إذا كان هناك عنصر لهذا القسم موجود بالفعل في المجموعة، يتم إرجاع العنصر الموجود. 

يوضح المثال كيفية الحصول على عنصر Summary Zoom [Section](../../section/) حسب الفهرس: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto newZoomSection = collection->AddSummaryZoomSection(pres->get_Sections()->idx_get(3));
```

## راجع أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [ISummaryZoomSection](../../isummaryzoomsection/)
* فئة [ISection](../../isection/)
* فئة [ISummaryZoomSectionCollection](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)