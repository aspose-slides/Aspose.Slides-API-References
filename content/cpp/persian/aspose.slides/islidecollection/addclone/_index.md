---
title: AddClone()
second_title: مرجع API Aspose.Slides برای C++
description: یک نسخه از اسلاید مشخص‌شده را به انتهای مجموعه اضافه می‌کند.
type: docs
weight: 14
url: /fa/aspose.slides/islidecollection/addclone/
---
## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>) متد

یک نسخه از اسلاید مشخص‌شده را به انتهای مجموعه اضافه می‌کند.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) برای کلون. |

### مقدار بازگشت

اسلاید جدید.

## توضیحات

When cloning a slide between different presentations slide's master can be cloned too. Internal registry is used to track automatically cloned masters to prevent creation of multiple clones of the same master slide. Manual cloning of master slides will be neither prevented nor registered. If you need more control over cloning process use [AddClone(SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](./) or [AddClone(SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](./) for cloning slides, [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../igloballayoutslidecollection/addclone/) or [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) for cloning layouts and [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) for cloning masters. 

## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ISection\>) متد

یک نسخه از اسلاید مشخص‌شده را به انتهای بخش مشخص‌شده اضافه می‌کند.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ISection> section)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) برای کلون. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) برای اسلاید جدید. |

### مقدار بازگشت

اسلاید جدید.

## توضیحات

```cpp
auto presentation = MakeObject<Presentation>();
presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 200.0f, 50.0f, 300.0f, 100.0f);
presentation->get_Sections()->AddSection(u"Section 1", presentation->get_Slides()->idx_get(0));
auto section2 = presentation->get_Sections()->AppendEmptySection(u"Section 2");
presentation->get_Slides()->AddClone(presentation->get_Slides()->idx_get(0), section2);
// اکنون بخش دوم شامل یک نسخه از اسلاید اول است.
```

## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) متد

یک نسخه از اسلاید مشخص‌شده را به انتهای مجموعه اضافه می‌کند.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) برای کلون. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | اسلاید چیدمان برای اسلاید جدید. |

### مقدار بازگشت

اسلاید جدید.

## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) متد

یک نسخه از اسلاید منبع مشخص‌شده را به انتهای مجموعه اضافه می‌کند. چیدمان مناسب به‌صورت خودکار از مستر مشخص‌شده انتخاب می‌شود (چیدمان مناسب همان چیدمانی است که نوع یا نامش با چیدمان اسلاید منبع یکسان باشد). اگر چیدمان مناسب وجود نداشته باشد، چیدمان اسلاید منبع کلون می‌شود (اگر allowCloneMissingLayout درست باشد) یا PptxEditException پرتاب می‌شود (اگر allowCloneMissingLayout نادرست باشد).

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) برای کلون. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | اسلاید مستر برای اسلاید جدید. |
| allowCloneMissingLayout | **bool** | اگر چیدمان مناسب در مستر مشخص‌شده وجود نداشته باشد، چیدمان اسلاید منبع کلون می‌شود (اگر allowCloneMissingLayout درست باشد) یا PptxEditException پرتاب می‌شود (اگر allowCloneMissingLayout نادرست باشد). |

### مقدار بازگشت

اسلاید جدید.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [ISlide](../../islide/)
* کلاس [ISlideCollection](../)
* کلاس [ISection](../../isection/)
* کلاس [ILayoutSlide](../../ilayoutslide/)
* کلاس [IMasterSlide](../../imasterslide/)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)