---
title: ObjectExt
second_title: مرجع API Aspose.Slides برای C++
description: متدهای استاتیک را فراهم می‌کند که روش‌های Object در C# را برای انواع غیر-Object C++ (رشته‌ها، اعداد و غیره) شبیه‌سازی می‌کند. این یک نوع استاتیک بدون سرویس‌های نمونه است. شما هرگز نباید به هیچ وجه نمونه‌ای از آن ایجاد کنید.
type: docs
weight: 1145
url: /fa/system/objectext/
---
## ObjectExt کلاس

متدهای استاتیک را فراهم می‌کند که روش‌های C# [Object](../object/) را که برای انواع غیر-Object C++ (رشته‌ها، اعداد و غیره) فراخوانی می‌شوند، شبیه‌سازی می‌کند. این یک نوع استاتیک بدون سرویس‌های نمونه است. شما هرگز نباید به هیچ وجه نمونه‌ای از آن ایجاد کنید.

```cpp
class ObjectExt : public System::ObjectType
```

## متدها

| متد | توضیح |
| --- | --- |
| static std::enable_if<(std::is_fundamental\<To\>::value), std::array\<To, sizeof...(From)>\>::type [ArrayInitializerCast](./arrayinitializercast/)(From ...) | مقادیر بنیادی آرایه را تبدیل می‌کند (که C# به‌صورت ضمنی انجام می‌دهد اما C++ ظاهراً این کار را نمی‌کند). |
| static std::enable_if\<std::is_enum\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | مقدارهای نوع ارزش‌دار را برای تبدیل به [Object](../object/) جعبه می‌کند. پیاده‌سازی برای انواع enum. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | مقدارهای نوع ارزش‌دار را برای تبدیل به [Object](../object/) جعبه می‌کند. پیاده‌سازی برای انواع غیر-enum. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | نوع [Nullable](../nullable/) را برای تبدیل به [Object](../object/) جعبه می‌کند. |
| static [SmartPtr](../smartptr/)\<[Object](../object/)\> [Box](./box/)(const [String](../string/)\&) | مقادیر رشته‌ای را جعبه می‌کند. |
| static [SmartPtr](../smartptr/)\<[System::BoxedValueBase](../boxedvaluebase/)\> [BoxEnum](./boxenum/)(T) | انواع enum را برای انتشار به عنوان [Object](../object/) جعبه می‌کند. |
| static [SmartPtr](../smartptr/)\<[System::Collections::IList](../../system.collections/ilist/)\> [CastToIList](./casttoilist/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) |  |
| static auto [Coalesce](./coalesce/)(T0, T1) | پیاده‌سازی ترجمهٔ عملگر '??' برای انواع غیر قابل‌نول. |
| static T0 [Coalesce](./coalesce/)([System::Nullable](../nullable/)\<T0\>, T1) | پیاده‌سازی ترجمهٔ عملگر '??' برای انواع نال‌پذیر. |
| static auto [CoalesceAssign](./coalesceassign/)(T0\&, T1) | پیاده‌سازی ترجمهٔ عملگر '??=' . |
| static std::conditional\<std::is_convertible\<RT2, RT1\>::value, RT1, RT2\>::type [CoalesceInternal](./coalesceinternal/)(RT1, F) | پیاده‌سازی ترجمهٔ عملگر '??' برای انواع غیر قابل‌نول. بارگذاری مجدد برای حالت‌ اگر RT2 به RT1 قابل تبدیل باشد. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) |  |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) | جایگزینی برای فراخوانی‌های C# [Object.Equals](../object/equals/) که برای هر نوعی در C++ کار می‌کند. بارگذاری مجدد برای انواع اشاره‌گر هوشمند. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value, **bool**\>::type [Equals](./equals/)(T, const T2\&) | جایگزینی برای فراخوانی‌های C# [Object.Equals](../object/equals/) که برای هر نوعی در C++ کار می‌کند. بارگذاری مجدد برای انواع ساختاری. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) | جایگزینی برای فراخوانی‌های C# [Object.Equals](../object/equals/) که برای هر نوعی در C++ کار می‌کند. بارگذاری مجدد برای انواع اسکالار. |
| static **bool** [Equals](./equals/)(const char_t(&), [String](../string/)) | جایگزینی برای فراخوانی‌های C# [Object.Equals](../object/equals/) که برای هر نوعی در C++ کار می‌کند. بارگذاری مجدد برای رشته‌های ثابت با مقایسهٔ رشته‌ای. |
| static **bool** [Equals](./equals/)(const **float**\&, const **float**\&) | مقایسهٔ نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](./equals/)(const **double**\&, const **double**\&) | مقایسهٔ نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value, [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>\>::type [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static std::enable_if\<[System::IsSmartPtr](../issmartptr/)\<T\>::value, [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>\>::type [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static int [GetHashCode](./gethashcode/)(const T\&) | پیاده‌سازی فراخوانی‌های [GetHashCode()](./gethashcode/)؛ بر روی هر دو زیرکلاس‌های [Object](../object/) و انواع نامرتبط کار می‌کند. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | پیاده‌سازی ترجمهٔ typeof(). بارگذاری مجدد برای اشاره‌گرهای هوشمند. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | پیاده‌سازی ترجمهٔ typeof(). بارگذاری مجدد برای ساختارها. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | پیاده‌سازی ترجمهٔ typeof(). بارگذاری مجدد برای استثناها. |
| static std::enable_if\<std::is_fundamental\<T\>::value||std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T) | پیاده‌سازی ترجمهٔ typeof(). بارگذاری مجدد برای انواع اولیه. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T) | پیاده‌سازی ترجمهٔ typeof(). بارگذاری مجدد برای انواع [Nullable](../nullable/). |
| static std::enable_if\<std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | پیاده‌سازی ترجمهٔ typeof(). بارگذاری مجدد برای انواع اولیه. |
| static std::enable_if\<std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | پیاده‌سازی ترجمهٔ typeof(). بارگذاری مجدد برای انواع enum. |
| static std::enable_if<(\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsBoxable](../isboxable/)\<T\>::value)||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | پیاده‌سازی ترجمهٔ typeof(). بارگذاری مجدد برای ساختارها و اشاره‌گرها. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | پیاده‌سازی ترجمهٔ typeof(). بارگذاری مجدد برای [Nullable](../nullable/). |
| static std::enable_if\<detail::is_a\<T, MulticastDelegate\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | پیاده‌سازی ترجمهٔ typeof(). بارگذاری مجدد برای MutlicastDelegate. |
| static std::enable_if<\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&[IsBoxable](../isboxable/)\<T\>::value\&&\!detail::is_a\<T, MulticastDelegate\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | پیاده‌سازی ترجمهٔ typeof(). بارگذاری مجدد برای ساختارها و اشاره‌گرها. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)(const [String](../string/)\&) | پیاده‌سازی ترجمهٔ typeof(). بارگذاری مجدد برای نوع رشته. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | پیاده‌سازی ترجمهٔ typeof(). بارگذاری مجدد برای **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | پیاده‌سازی ترجمهٔ typeof(). بارگذاری مجدد برای **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | پیاده‌سازی ترجمهٔ typeof(). بارگذاری مجدد برای **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | پیاده‌سازی ترجمهٔ typeof(). بارگذاری مجدد برای **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | پیاده‌سازی ترجمهٔ typeof(). بارگذاری مجدد برای **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | پیاده‌سازی ترجمهٔ typeof(). بارگذاری مجدد برای **uint8_t**. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value, **bool**\>::type [Is](./is/)(const T\&) | پیاده‌سازی ترجمهٔ عملگر 'is'. تخصص برای انواع قابل جعبه‌گذاری (ارزشی) که دقیقاً همان هستند. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value\&&std::is_final\<T\>::value\&&\![System::IsBoxable](../isboxable/)\<T\>::value\&&[System::IsSmartPtr](../issmartptr/)\<U\>::value, **bool**\>::type [Is](./is/)(const U\&) | پیاده‌سازی ترجمهٔ عملگر 'is'. تخصص برای انواع اشاره‌گر بهینه‌سازی‌شده برای کلاس‌های 'final'. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value\&&\!std::is_final\<T\>::value\&&\![System::IsBoxable](../isboxable/)\<T\>::value\&&[System::IsSmartPtr](../issmartptr/)\<U\>::value, **bool**\>::type [Is](./is/)(const U\&) | پیاده‌سازی ترجمهٔ عملگر 'is'. تخصص برای انواع اشاره‌گر. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [Object](../object/)\&) | پیاده‌سازی ترجمهٔ عملگر 'is'. تخصص برای انواع ارزش‌دار. |
| static std::enable_if<\!std::is_convertible\<T, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [Object](../object/)\&) | پیاده‌سازی ترجمهٔ عملگر 'is'. تخصص برای انواع غیرقابل تبدیل. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<U\>\&) | پیاده‌سازی ترجمهٔ عملگر 'is'. تخصص برای انواع اشاره‌گر. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, **bool**\>::type [Is](./is/)(const [ExceptionWrapper](../exceptionwrapper/)\<U\>\&) | پیاده‌سازی ترجمهٔ عملگر 'is'. تخصص برای انواع بسته‌بندی استثنا. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | پیاده‌سازی ترجمهٔ عملگر 'is'. تخصص برای انواع nullable. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&detail::has_operator_equal\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | پیاده‌سازی ترجمهٔ عملگر 'is'. تخصص برای انواع قابل جعبه‌گذاری که عملگر == تعریف شده است. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&\!detail::has_operator_equal\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | پیاده‌سازی ترجمهٔ عملگر 'is'. تخصص برای انواع قابل جعبه‌گذاری که == تعریف نشده است. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&\!std::is_same\<V, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<V\>\&) | پیاده‌سازی ترجمهٔ عملگر 'is'. تخصص برای انواع ارزش‌دار جعبه‌شده به اینترفیس‌ها. |
| static std::enable_if\<std::is_enum\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<U\>\&) | پیاده‌سازی ترجمهٔ عملگر 'is'. تخصص برای انواع enum. |
| static std::enable_if\<std::is_enum\<T\>::value, **bool**\>::type [Is](./is/)(const [WeakPtr](../weakptr/)\<U\>\&) | پیاده‌سازی ترجمهٔ عملگر 'is'. تخصص برای انواع enum در مقابل اشاره‌گرهای ضعیف. |
| static **bool** [Is](./is/)(const [Nullable](../nullable/)\<U\>\&) | پیاده‌سازی ترجمهٔ عملگر 'is'. تخصص برای نوع [Nullable](../nullable/). |
| static **bool** [Is](./is/)(const char16_t *) | پیاده‌سازی ترجمهٔ عملگر 'is'. تخصص برای رشتهٔ ثابت. |
| static **bool** [Is](./is/)(**int32_t**) | پیاده‌سازی ترجمهٔ عملگر 'is'. تخصص برای عدد صحیح ثابت. |
| static **bool** [IsBoxedValue](./isboxedvalue/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | بررسی می‌کند که آیا شیء یک مقدار جعبه‌شده است یا خیر. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, T\>::type [ObjectToUnknown](./objecttounknown/)([SmartPtr](../smartptr/)\<[Object](../object/)\>) | [Object](../object/) را به نوع ناشناخته تبدیل می‌کند، هم حالت نوع اشاره‌گر هوشمند و هم وضعیت مقدار جعبه‌شده را مدیریت می‌کند. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, T\>::type [ObjectToUnknown](./objecttounknown/)([SmartPtr](../smartptr/)\<[Object](../object/)\>) | [Object](../object/) را به نوع ناشناخته تبدیل می‌کند، هم حالت نوع اشاره‌گر هوشمند و هم وضعیت مقدار جعبه‌شده را مدیریت می‌کند. |
| static [String](../string/) [ToString](./tostring/)(const char_t *) | جایگزینی برای متد C# ToString برای کار با هر نوع C++. |
| static [String](../string/) [ToString](./tostring/)(const [Nullable](../nullable/)\<T\>\&) | جایگزینی برای متد C# ToString برای کار با هر نوع C++. |
| static std::enable_if\<std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | جایگزینی برای متد C# ToString برای کار با هر نوع C++. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | جایگزینی برای متد C# ToString برای کار با هر نوع C++. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value||std::is_pointer\<T\>::value||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | جایگزینی برای متد C# ToString برای کار با هر نوع C++. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value\&&\!std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | جایگزینی برای متد C# ToString برای کار با هر نوع C++. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value\&&\!std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&&) | جایگزینی برای متد C# ToString برای کار با هر نوع C++. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | جایگزینی برای متد C# ToString برای کار با هر نوع C++. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | جایگزینی برای متد C# ToString برای کار با هر نوع C++. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_reference\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&&) | جایگزینی برای متد C# ToString برای کار با هر نوع C++. |
| static std::enable_if\<std::is_enum\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | مقادیر نوع ارزش‌دار را پس از تبدیل به [Object](../object/) از جعبه خارج می‌کند. پیاده‌سازی برای انواع enum. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&detail::has_operator_equal\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | مقادیر نوع ارزش‌دار را پس از تبدیل به [Object](../object/) از جعبه خارج می‌کند. پیاده‌سازی برای انواع غیر-enum و غیر-nullable. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&\!detail::has_operator_equal\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | مقادیر نوع ارزش‌دار را پس از تبدیل به [Object](../object/) از جعبه خارج می‌کند. پیاده‌سازی برای انواع غیر-enum و غیر-nullable. |
| static std::enable_if\<std::is_enum\<E\>::value\&&std::numeric_limits\<T\>::is_integer, T\>::type [Unbox](./unbox/)(E) | انواع enum را به عدد صحیح تبدیل می‌کند. |
| static std::enable_if\<std::is_enum\<E\>::value\&&std::is_enum\<T\>::value, T\>::type [Unbox](./unbox/)(E) | انواع enum را تبدیل می‌کند. |
| static [String](../string/) [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | مقادیر رشته‌ای را از جعبه خارج می‌کند. |
| static [String](../string/) [UnboxStringSafe](./unboxstringsafe/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | رشته را از مقدار جعبه‌شده خارج می‌کند. |
| static [Nullable](../nullable/)\<T\> [UnboxToNullable](./unboxtonullable/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&, **bool**) | شیء را به نوع nullable از جعبه خارج می‌کند. |
| static std::enable_if<\!std::is_scalar\<T\>::value, **bool**\>::type [UnknownIsNull](./unknownisnull/)(T) | بررسی می‌کند که آیا شیء از نوع ناشناخته nullptr است. بارگذاری مجدد برای انواع غیر اسکالار. |
| static std::enable_if\<std::is_scalar\<T\>::value, **bool**\>::type [UnknownIsNull](./unknownisnull/)(T) | بررسی می‌کند که آیا شیء از نوع ناشناخته nullptr است. بارگذاری مجدد برای انواع اسکالار. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[Object](../object/)\>\>::type [UnknownToObject](./unknowntoobject/)(T) | نوع ناشناخته را به [Object](../object/) تبدیل می‌کند، هم حالت نوع اشاره‌گر هوشمند و هم وضعیت نوع ارزش‌دار را مدیریت می‌کند. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[Object](../object/)\>\>::type [UnknownToObject](./unknowntoobject/)(const T\&) | نوع ناشناخته را به [Object](../object/) تبدیل می‌کند، هم حالت نوع اشاره‌گر هوشمند و هم وضعیت نوع ارزش‌دار را مدیریت می‌کند. |

## موارد مرتبط

* کلاس [ObjectType](../objecttype/)
* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)