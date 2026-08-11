---
title: get_HeaderFooterManager()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يرجع مدير HeaderFooter الفعلي. للقراءة فقط IPresentationHeaderFooterManager.
type: docs
weight: 27
url: /ar/aspose.slides/presentation/get_headerfootermanager/
---
## Presentation::get_HeaderFooterManager() طريقة


إرجاع مدير HeaderFooter الفعلي. للقراءة فقط [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/).

```cpp
System::SharedPtr<IPresentationHeaderFooterManager> Aspose::Slides::Presentation::get_HeaderFooterManager() override
```

## ملاحظات


المثال التالي يوضح كيفية ضبط رؤية التذييل داخل [Slide](../../slide/) من PowerPoint [Presentation](../). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
auto slide = presentation->get_Slides()->idx_get(0);

System::SharedPtr<IBaseSlideHeaderFooterManager> headerFooterManager = slide->get_HeaderFooterManager();
// الخاصية IsFooterVisible تُستخدم للإشارة إلى أن عنصر نِسْقَة التذييل في الشريحة غير موجود.
if (!headerFooterManager->get_IsFooterVisible())
{
    // الطريقة SetFooterVisibility تُستخدم لجعل عنصر نِسْقَة التذييل في الشريحة مرئيًا.
    headerFooterManager->SetFooterVisibility(true);
}

// الخاصية IsSlideNumberVisible تُستخدم للإشارة إلى أن عنصر رقم الصفحة في الشريحة غير موجود.
if (!headerFooterManager->get_IsSlideNumberVisible())
{
    // الطريقة SetSlideNumberVisibility تُستخدم لجعل عنصر رقم الصفحة في الشريحة مرئيًا.
    headerFooterManager->SetSlideNumberVisibility(true);
}

// الخاصية IsDateTimeVisible تُستخدم للإشارة إلى أن عنصر التاريخ والوقت في الشريحة غير موجود.
if (!headerFooterManager->get_IsDateTimeVisible())
{
    // الطريقة SetFooterVisibility تُستخدم لجعل عنصر التاريخ والوقت في الشريحة مرئيًا.
    headerFooterManager->SetDateTimeVisibility(true);
}

// الطريقة SetFooterText تُستخدم لتعيين نص إلى عنصر نِسْقَة التذييل في الشريحة.
headerFooterManager->SetFooterText(u"Footer text");
// الطريقة SetDateTimeText تُستخدم لتعيين نص إلى عنصر التاريخ والوقت في الشريحة.
headerFooterManager->SetDateTimeText(u"Date and time text");
presentation->Save(u"Presentation.ppt", SaveFormat::Ppt);
```
 المثال التالي يوضح كيفية ضبط رؤية تذييل الطفل داخل [Slide](../../slide/). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
System::SharedPtr<IMasterSlideHeaderFooterManager> headerFooterManager = presentation->get_Masters()->idx_get(0)->get_HeaderFooterManager();

// الطريقة SetFooterAndChildFootersVisibility تُستخدم لجعل شريحة الرئيسة وجميع عناصر نِسْقَة التذييل الفرعية مرئية.
headerFooterManager->SetFooterAndChildFootersVisibility(true);

// الطريقة SetSlideNumberAndChildSlideNumbersVisibility تُستخدم لجعل شريحة الرئيسة وجميع عناصر أرقام الصفحات الفرعية مرئية.
headerFooterManager->SetSlideNumberAndChildSlideNumbersVisibility(true);

// الطريقة SetDateTimeAndChildDateTimesVisibility تُستخدم لجعل شريحة الرئيسة وجميع عناصر التاريخ والوقت الفرعية مرئية.
headerFooterManager->SetDateTimeAndChildDateTimesVisibility(true);

// الطريقة SetFooterAndChildFootersText تُستخدم لتعيين النص إلى شريحة الرئيسة وجميع عناصر نِسْقَة التذييل الفرعية.
headerFooterManager->SetFooterAndChildFootersText(u"Footer text");

// الطريقة SetDateTimeAndChildDateTimesText تُستخدم لتعيين النص إلى شريحة الرئيسة وجميع عناصر التاريخ والوقت الفرعية.
headerFooterManager->SetDateTimeAndChildDateTimesText(u"Date and time text");
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* الفئة [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/)
* الفئة [Presentation](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)