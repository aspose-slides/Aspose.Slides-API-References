---
title: MasterLayoutSlideCollection class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/masterlayoutslidecollection/
---
## MasterLayoutSlideCollection کلاس

نمایانگر یک مجموعه از تمام اسلایدهای طرح‌بندی اسلاید اصلی تعریف‌شده است.
            از کلاس LayoutSlideCollection ارث می‌برد و با متدهایی برای افزودن/درج/حذف/کلون/تغییر ترتیب
            اسلایدهای طرح‌بندی در زمینهٔ مجموعه‌های فردی اسلایدهای طرح‌بندی اسلاید اصلی عمل می‌کند.

**ارث‌بری:**[`MasterLayoutSlideCollection`](/slides/python-net/fa/aspose.slides/masterlayoutslidecollection) → [`LayoutSlideCollection`](/slides/python-net/fa/aspose.slides/layoutslidecollection)

نوع MasterLayoutSlideCollection اعضای زیر را در اختیار می‌گذارد:

## ایندکس‌گر

| نام | توضیح |
| :- | :- |
| [`[index]`](/slides/python-net/fa/aspose.slides/masterlayoutslidecollection/__getitem__/) |  |

## متدها

| متد | توضیح |
| :- | :- |
| [`get_by_type(self, type)`](/slides/python-net/fa/aspose.slides/masterlayoutslidecollection/get_by_type/#slidelayouttype) | اولین اسلاید طرح‌بندی از نوع مشخص‌شده را برمی‌گرداند.<br/>            نوع اسلاید طرح‌بندی برای جستجو.[`LayoutSlide`](/slides/python-net/fa/aspose.slides/layoutslide) با نوع مشخص‌شده یا None اگر هیچ طرح‌بندی‌ای پیدا نشد. |
| [`remove(self, value)`](/slides/python-net/fa/aspose.slides/masterlayoutslidecollection/remove/#ilayoutslide) | یک طرح‌بندی را از مجموعه حذف می‌کند. |
| [`remove_unused(self)`](/slides/python-net/fa/aspose.slides/masterlayoutslidecollection/remove_unused/#) | اسلایدهای طرح‌بندی استفاده‌نشده را حذف می‌کند (اسلایدهای طرح‌بندی که HasDependingSlides آن‌ها false است). |
| [`add_clone(self, source_layout)`](/slides/python-net/fa/aspose.slides/masterlayoutslidecollection/add_clone/#ilayoutslide) | یک کپی از اسلاید طرح‌بندی مشخص‌شده را به انتهای مجموعه اضافه می‌کند. |
| [`insert_clone(self, index, source_layout)`](/slides/python-net/fa/aspose.slides/masterlayoutslidecollection/insert_clone/#int-ilayoutslide) | یک کپی از اسلاید طرح‌بندی مشخص‌شده را در موقعیت مشخص‌شدهٔ مجموعه درج می‌کند. |
| [`add(self, layout_type, layout_name)`](/slides/python-net/fa/aspose.slides/masterlayoutslidecollection/add/#slidelayouttype-str) | یک اسلاید طرح‌بندی جدید را به انتهای مجموعه اضافه می‌کند. |
| [`insert(self, index, layout_type, layout_name)`](/slides/python-net/fa/aspose.slides/masterlayoutslidecollection/insert/#int-slidelayouttype-str) | یک اسلاید طرح‌بندی جدید را در موقعیت مشخص‌شدهٔ مجموعه درج می‌کند. |
| [`remove_at(self, index)`](/slides/python-net/fa/aspose.slides/masterlayoutslidecollection/remove_at/#int) | عنصر در شاخص مشخص‌شدهٔ مجموعه را حذف می‌کند. |
| [`reorder(self, index, layout_slide)`](/slides/python-net/fa/aspose.slides/masterlayoutslidecollection/reorder/#int-ilayoutslide) | اسلاید طرح‌بندی را از مجموعه به موقعیت مشخص‌ شده منتقل می‌کند. |


### موارد مرتبط
* کلاس [`LayoutSlideCollection`](/slides/python-net/fa/aspose.slides/layoutslidecollection)
* کلاس [`MasterLayoutSlideCollection`](/slides/python-net/fa/aspose.slides/masterlayoutslidecollection)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)