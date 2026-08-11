---
title: AddClone()
second_title: Aspose.Slides برای C++ مرجع API
description: یک نسخه از اسلاید لایه‌بندی مشخص شده را به انتهای مجموعه اضافه می‌کند.
type: docs
weight: 1
url: /fa/aspose.slides/masterlayoutslidecollection/addclone/
---
## MasterLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) متد


یک کپی از اسلاید layout مشخص شده را به انتهای collection اضافه می‌کند.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout) override
```


### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) برای تکثیر. |

### مقدار بازگشتی

اسلاید اضافه‌شده.

## توضیحات



1) لایه‌بندی جدید با اسلاید اصلی والد برای این مجموعه اسلایدهای layout لینک خواهد شد. بنابراین این مشابه عمل copy/paste با گزینه "Use Destination Theme" در PowerPoint است. 2) مشابه این متد، متد [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) است که از طریق ویژگی [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/) قابل دسترسی است. 

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [ILayoutSlide](../../ilayoutslide/)
* کلاس [MasterLayoutSlideCollection](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)