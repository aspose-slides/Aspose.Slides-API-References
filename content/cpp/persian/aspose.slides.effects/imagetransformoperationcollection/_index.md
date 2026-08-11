---
title: ImageTransformOperationCollection
second_title: Aspose.Slides برای C++ مرجع API
description: نمایانگر یک مجموعه از اثرهای اعمال‌شده بر یک تصویر.
type: docs
weight: 846
url: /fa/aspose.slides.effects/imagetransformoperationcollection/
---
## ImageTransformOperationCollection کلاس

نمایانگر یک مجموعه از اثرهای اعمال‌شده بر یک تصویر است.

```cpp
class ImageTransformOperationCollection : public Aspose::Slides::PVIObject,
                                          public Aspose::Slides::Effects::IImageTransformOperationCollection
```

## متدها

| متد | توضیح |
| --- | --- |
| void [Add](./add/)(const [System::SharedPtr](../../system/sharedptr/)\<[IImageTransformOperation](../iimagetransformoperation/)\>\&) override | افکت تصویر جدید را به انتهای مجموعه اضافه می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAlphaBiLevel](../ialphabilevel/)\> [AddAlphaBiLevelEffect](./addalphabileveleffect/)(**float**) override | افکت آلفا دو-سطحی جدید را به انتهای مجموعه اضافه می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAlphaCeiling](../ialphaceiling/)\> [AddAlphaCeilingEffect](./addalphaceilingeffect/)() override | افکت آلفا سقفی جدید را به انتهای مجموعه اضافه می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAlphaFloor](../ialphafloor/)\> [AddAlphaFloorEffect](./addalphaflooreffect/)() override | افکت آلفا کف جدید را به انتهای مجموعه اضافه می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAlphaInverse](../ialphainverse/)\> [AddAlphaInverseEffect](./addalphainverseeffect/)() override | افکت آلفا معکوس جدید را به انتهای مجموعه اضافه می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAlphaModulate](../ialphamodulate/)\> [AddAlphaModulateEffect](./addalphamodulateeffect/)() override | افکت آلفا مدوله جدید را به انتهای مجموعه اضافه می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAlphaModulateFixed](../ialphamodulatefixed/)\> [AddAlphaModulateFixedEffect](./addalphamodulatefixedeffect/)(**float**) override | افکت آلفا مدوله ثابت جدید را به انتهای مجموعه اضافه می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAlphaReplace](../ialphareplace/)\> [AddAlphaReplaceEffect](./addalphareplaceeffect/)(**float**) override | افکت آلفا جایگزینی جدید را به انتهای مجموعه اضافه می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBiLevel](../ibilevel/)\> [AddBiLevelEffect](./addbileveleffect/)(**float**) override | افکت دو-سطحی (سیاه/سفید) جدید را به انتهای مجموعه اضافه می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBlur](../iblur/)\> [AddBlurEffect](./addblureffect/)(**double**, **bool**) override | افکت جدید [Blur](../blur/) را به انتهای مجموعه اضافه می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBrightnessContrast](../ibrightnesscontrast/)\> [AddBrightnessContrastEffect](./addbrightnesscontrasteffect/)(**float**, **float**) override | افکت جدید [BrightnessContrast](../brightnesscontrast/) را به انتهای مجموعه اضافه می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorChange](../icolorchange/)\> [AddColorChangeEffect](./addcolorchangeeffect/)() override | افکت تغییر رنگ جدید را به انتهای مجموعه اضافه می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorReplace](../icolorreplace/)\> [AddColorReplaceEffect](./addcolorreplaceeffect/)() override | افکت جایگزینی رنگ جدید را به انتهای مجموعه اضافه می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IDuotone](../iduotone/)\> [AddDuotoneEffect](./addduotoneeffect/)() override | افکت جدید [Duotone](../duotone/) را به انتهای مجموعه اضافه می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillOverlay](../ifilloverlay/)\> [AddFillOverlayEffect](./addfilloverlayeffect/)() override | افکت پوشش پر کردن جدید را به انتهای مجموعه اضافه می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IGrayScale](../igrayscale/)\> [AddGrayScaleEffect](./addgrayscaleeffect/)() override | افکت مقیاس‌خاکستری جدید را به انتهای مجموعه اضافه می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHSL](../ihsl/)\> [AddHSLEffect](./addhsleffect/)(**float**, **float**, **float**) override | افکت رنگ/اشباع/روشنایی جدید را به انتهای مجموعه اضافه می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILuminance](../iluminance/)\> [AddLuminanceEffect](./addluminanceeffect/)(**float**, **float**) override | افکت جدید [Luminance](../luminance/) را به انتهای مجموعه اضافه می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITint](../itint/)\> [AddTintEffect](./addtinteffect/)(**float**, **float**) override | افکت جدید [Tint](../tint/) را به انتهای مجموعه اضافه می‌کند. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | دست‌دار را برمی‌گرداند که به اولین عنصر (در صورت وجود) مجموعه اشاره می‌کند. این دست‌دار نمی‌تواند برای تغییر شیء مرجع استفاده شود زیرا [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) یک شیء کپی از T برمی‌گرداند. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | دست‌دار را برمی‌گرداند که به اولین عنصر (در صورت وجود) نمونه‌ی دارای const مجموعه اشاره می‌کند. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | دست‌دار را برمی‌گرداند که به اولین عنصر دارای const (در صورت وجود) مجموعه اشاره می‌کند. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | دست‌دار را برمی‌گرداند که درست پس از آخرین عنصر دارای const (در صورت وجود) مجموعه اشاره می‌کند. |
| void [Clear](./clear/)() override | تمام اثرهای تصویر را از یک مجموعه حذف می‌کند. |
| **bool** [Contains](./contains/)(const [System::SharedPtr](../../system/sharedptr/)\<[IImageTransformOperation](../iimagetransformoperation/)\>\&) const override | تعیین می‌کند که آیا [ICollection](../../system.collections.generic/icollection/) شامل مقدار مشخصی است یا خیر. |
| void [CopyTo](./copyto/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImageTransformOperation](../iimagetransformoperation/)\>\>, **int32_t**) override | عناصر [ICollection](../../system.collections.generic/icollection/) را به یک [System::Array](../../system/array/) کپی می‌کند، شروع از اندیس [System::Array](../../system/array/) خاص. |
| virtual void [CopyTo](../../system.collections.generic/icollection/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) | تمام عناصر مجموعه را به عناصر آرایه موجود کپی می‌کند. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | دست‌دار را برمی‌گرداند که درست پس از آخرین عنصر (در صورت وجود) مجموعه اشاره می‌کند. این دست‌دار نمی‌تواند برای تغییر شیء مرجع استفاده شود زیرا [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) یک شیء کپی از T برمی‌گرداند. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | دست‌دار را برمی‌گرداند که درست پس از آخرین عنصر (در صورت وجود) نمونه‌ی دارای const مجموعه اشاره می‌کند. |
| **bool** [Equals](../../aspose.slides/pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | با شیء مشخص‌شده مقایسه می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ عددی شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ عددی شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| **int32_t** [get_Count](./get_count/)() const override | تعداد اثرهای تصویر در یک مجموعه را برمی‌گرداند. فقط خواندنی **int32_t**. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const override | مقداری را برمی‌گرداند که نشان می‌دهد آیا [ICollection](../../system.collections.generic/icollection/) فقط‌خواندنی است یا خیر. فقط‌خواندنی **bool**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../../aspose.slides/idomobject/)\> [get_Parent_Immediate](../../aspose.slides/idomobject/get_parent_immediate/)() | شیء Parent_Immediate را برمی‌گرداند. فقط‌خواندنی [IDOMObject](../../aspose.slides/idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | والد [IPresentationComponent](../../aspose.slides/ipresentationcomponent/) را برمی‌گرداند. فقط‌خواندنی [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | شیئی را که مجموعه از طریق آن همگام‌سازی می‌شود، برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارندهٔ مرجع مرتبط با شیء را برمی‌گرداند. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImageTransformOperation](../iimagetransformoperation/)\>\>\> [GetEnumerator](./getenumerator/)() override | یک enumerator را برمی‌گرداند که از طریق مجموعه تکرار می‌کند. |
| **int32_t** [GetHashCode](../../aspose.slides/pviobject/gethashcode/)() const override | کد هش را برمی‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را برمی‌گرداند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ICollection](../../system.collections.generic/icollection/icollection/)() | سازنده پیش‌فرض. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | سازندهٔ کپی. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | سازندهٔ جابجایی. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImageTransformOperation](../iimagetransformoperation/)\> [idx_get](./idx_get/)(**int32_t**) override | یک [ImageTransformOperation](../imagetransformoperation/) را از مجموعه بر اساس ایندکس آن برمی‌گرداند. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر یک نمونه از نوع توصیف‌شده توسط targetType است یا خیر. معادل عملگر C# 'is'. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | یک تابع انباشتگر را بر روی یک دنباله اعمال می‌کند. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | تعیین می‌کند که آیا تمام عناصر یک دنباله شرطی را برآورده می‌کنند یا خیر. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | تعیین می‌کند که آیا یک دنباله شامل هر عنصر یا نه. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | تعیین می‌کند که آیا هر عنصری در دنباله وجود دارد یا شرطی را برآورده می‌کند. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | متوسط یک دنباله از مقادیر عددی را محاسبه می‌کند. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | متوسط یک دنباله از مقادیری را که با فراخوانی یک تابع تبدیل بر هر عنصر دنباله ورودی به دست می‌آید، محاسبه می‌کند. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | عناصر را به نوع مشخص‌شده تبدیل می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | دو دنباله را به هم می‌پیوندد. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | تعیین می‌کند که آیا دنباله شامل مقدار مشخصی است یا خیر. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | تعداد عناصر در دنباله را برمی‌گرداند (محاسبه‌شده از طریق شمارش مستقیم). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | تعداد عناصر در دنباله که شرط مشخص‌شده را برآورده می‌کنند را برمی‌گرداند. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | عنصر موجود در ایندکس مشخص در یک دنباله را برمی‌گرداند. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | عنصر موجود در ایندکس مشخص در یک دنباله را برمی‌گرداند. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | اولین عنصر یک دنباله را برمی‌گرداند. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | اولین عنصر دنباله که شرط مشخص‌شده را برآورده می‌کند را برمی‌گرداند. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | اولین عنصر یک دنباله را برمی‌گرداند، یا مقدار پیش‌فرض اگر دنباله خالی باشد. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | اولین عنصر دنباله که شرطی را برآورده می‌کند را برمی‌گرداند یا مقدار پیش‌فرض اگر چنین عنصری یافت نشود. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | عناصر یک دنباله را گروه‌بندی می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | عناصر یک دنباله را گروه‌بندی می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | آخرین عنصر یک دنباله را برمی‌گرداند. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | آخرین عنصر یک دنباله را برمی‌گرداند یا مقدار پیش‌فرض اگر دنباله خالی باشد. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | یک تابع تبدیل را بر هر عنصر یک دنبالهٔ عمومی اعمال می‌کند و حداکثری مقدار به دست آمده را برمی‌گرداند. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | یک تابع تبدیل را بر هر عنصر یک دنبالهٔ عمومی اعمال می‌کند و حداقل مقدار به دست آمده را برمی‌گرداند. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | عناصر دنباله را بر اساس نوع مشخص‌شده فیلتر می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | عناصر یک دنباله را به ترتیب صعودی بر اساس مقادیر کلید انتخاب‌شده توسط keySelector مرتب می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | عناصر یک دنباله را به ترتیب نزولی بر اساس مقادیر کلید انتخاب‌شده توسط keySelector مرتب می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | ترتیب عناصر یک دنباله را وارونه می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | عناصر یک دنباله را تبدیل می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | هر عنصر یک دنباله را به شکل جدیدی تبدیل می‌کند با دربرگیری ایندکس عنصر. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | هر عنصر دنباله را پروژه می‌کند و دنباله‌های حاصل را در یک دنباله ترکیب می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | تعداد مشخصی از عناصر متصل را از ابتدای دنباله رد می‌کند و بقیه را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | تعداد مشخصی از عناصر متصل را از ابتدای دنباله برمی‌گرداند. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | یک آرایه از یک دنباله ایجاد می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | یک List<T> از یک دنباله ایجاد می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | دنباله را بر اساس تابع شرطی مشخص‌شده فیلتر می‌کند. |
| void [Lock](../../system/object/lock/)() | اجرای قفل () در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی کرده و امکان ساختن زیرکلاس‌ها به‌صورت کپی را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی کرده و امکان ساختن زیرکلاس‌ها به‌صورت کپی را فراهم می‌کند. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | اپراتور انتساب جابجایی. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | اپراتور انتساب جابجایی. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مرجع-مقایسه شیء نوع مقداری با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصصی از [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصصی از [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| **bool** [Remove](./remove/)(const [System::SharedPtr](../../system/sharedptr/)\<[IImageTransformOperation](../iimagetransformoperation/)\>\&) override | اولین رخداد یک شیء خاص را از [ICollection](../../system.collections.generic/icollection/) حذف می‌کند. |
| void [RemoveAt](./removeat/)(**int32_t**) override | یک افکت تصویر را از مجموعه در اندیس مشخص حذف می‌کند. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را برمی‌گرداند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید مستقیم صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش داده و مقدار آن را برمی‌گرداند. نباید مستقیم صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرای بازکردن قفل () در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | پیاده‌سازی begin iterator ثابت را برای کانتینر فعلی برمی‌گرداند. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | پیاده‌سازی begin iterator را برای کانتینر فعلی برمی‌گرداند. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | پیاده‌سازی end iterator ثابت را برای کانتینر فعلی برمی‌گرداند. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | پیاده‌سازی end iterator را برای کانتینر فعلی برمی‌گرداند. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیم صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیم صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../../aspose.slides/pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | تخریب‌کننده. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## مراجع

* کلاس [PVIObject](../../aspose.slides/pviobject/)
* کلاس [IImageTransformOperationCollection](../iimagetransformoperationcollection/)
* فضای نام [Aspose::Slides::Effects](../)
* کتابخانه [Aspose.Slides](../../)