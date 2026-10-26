---
title: TypeInfo
second_title: مرجع API Aspose.Slides برای C++
description: نوع خاصی را نشان می‌دهد و اطلاعاتی درباره آن فراهم می‌کند.
type: docs
weight: 1379
url: /fa/system/typeinfo/
---
## TypeInfo کلاس

نوع خاصی را نشان می‌دهد و اطلاعاتی درباره آن فراهم می‌کند.

```cpp
class TypeInfo
```

## متدها

| Method | Description |
| --- | --- |
| void [AddAttribute](./addattribute/)(const [ObjectPtr](../smartptr/)\&) | ویژگی مشخص شده را به فهرست ویژگی‌های این نوع اضافه می‌کند. |
| void [AddDefaultConstructor](./adddefaultconstructor/)() | سازنده پیش‌فرض برای نوع T را تنظیم می‌کند. |
| void [AddDefaultConstructor](./adddefaultconstructor/)([DefaultConstructor](./defaultconstructor/)) | سازنده پیش‌فرض را با فانکتوری که نمونه کلاس را می‌سازد تنظیم می‌کند. |
| void [AddMember](./addmember/)(const [SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\&) | عضو مشخص شده را به فهرست اعضای این نوع اضافه می‌کند. |
| static const [TypeInfo](./)\& [BoxedValueType](./boxedvaluetype/)() | ساختار یکتا [TypeInfo](./) را برای نوع **BoxedValue** فراهم می‌کند تا توسط کلاس‌های متعدد Boxed* به اشتراک گذاشته شود. |
| **bool** [Equals](./equals/)(const [TypeInfo](./)\&) const |  |
| [System::SharedPtr](../sharedptr/)\<[System::Reflection::Assembly](../../system.reflection/assembly/)\> [get_Assembly](./get_assembly/)() const | پیاده‌سازی نشده. اشاره‌گری به اسمبلی که نوع نمایان‌سازی‌شده توسط شیء جاری در آن تعریف شده است برمی‌گرداند. |
| [String](../string/) [get_AssemblyQualifiedName](./get_assemblyqualifiedname/)() const | پیاده‌سازی نشده. نام کامل شامل نام اسمبلی نوع نمایان‌سازی‌شده توسط شیء جاری را برمی‌گرداند. |
| [TypeInfo](./) [get_BaseType](./get_basetype/)() const | توصیف‌گر نوع پایه را برمی‌گرداند. |
| **bool** [get_ContainsGenericParameters](./get_containsgenericparameters/)() const | مقدار نشان‌دهنده این‌که آیا شیء Type جاری پارامترهای نوع دارد که با نوع‌های خاص جایگزین نشده‌اند را برمی‌گرداند. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [get_DeclaredMember](./get_declaredmember/)(const [String](../string/)\&) const | فهرستی از اعضایی با نام مشخص شده را برمی‌گرداند. |
| [String](../string/) [get_FullName](./get_fullname/)() const | نام کامل (بدون نام اسمبلی) نوع نمایان‌سازی‌شده توسط شیء جاری را برمی‌گرداند. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [get_GenericTypeArguments](./get_generictypearguments/)() const | آرایه‌ای از پارامترهای نوع جنریک برای این نوع را برمی‌گرداند. |
| **bool** [get_IsAbstract](./get_isabstract/)() const | مقدار نشان‌دهنده این‌که آیا نوع انتزاعی است و باید بازنویسی شود را برمی‌گرداند. |
| **bool** [get_IsArray](./get_isarray/)() const | مقداری که نشان می‌دهد نوع یک آرایه است را برمی‌گرداند. |
| **bool** [get_IsClass](./get_isclass/)() const | مقدار نشان‌دهنده این‌که آیا نوع یک کلاس یا نمایندگی است؛ یعنی نه یک نوع مقدار و نه یک واسط. |
| **bool** [get_IsEnum](./get_isenum/)() const | مقدار نشان‌دهنده این‌که آیا Type جاری یک شمارش (enumeration) است را برمی‌گرداند. |
| **bool** [get_IsGenericType](./get_isgenerictype/)() const |  |
| **bool** [get_IsGenericTypeDefinition](./get_isgenerictypedefinition/)() const | مقداری که نشان می‌دهد Type جاری یک تعریف نوع جنریک است که از آن می‌توان نوع‌های جنریک دیگر ساخت را برمی‌گرداند. |
| **bool** [get_IsInterface](./get_isinterface/)() const | مقدار نشان‌دهنده این‌که آیا Type یک واسط است؛ یعنی نه یک کلاس و نه یک نوع مقدار. |
| **bool** [get_IsSealed](./get_issealed/)() const | مقدار نشان‌دهنده این‌که آیا Type به صورت sealed تعریف شده است را برمی‌گرداند. |
| **bool** [get_IsValueType](./get_isvaluetype/)() const | مقدار نشان‌دهنده این‌که آیا Type یک نوع مقدار است را برمی‌گرداند. |
| **bool** [get_IsVisible](./get_isvisible/)() const | مقدار نشان‌دهنده این‌که آیا Type می‌تواند توسط کد خارج از اسمبلی دسترسی پیدا کند را برمی‌گرداند. |
| [String](../string/) [get_Name](./get_name/)() const | نام نوع نمایان‌سازی‌شده توسط شیء جاری را برمی‌گرداند. |
| [String](../string/) [get_Namespace](./get_namespace/)() const | فضای‌نام Type را برمی‌گرداند. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\> [GetConstructor](./getconstructor/)(const [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\>\&) const | به دنبال سازندهٔ نمونه‌ای عمومی می‌گردد که پارامترهای آن با انواع موجود در آرایهٔ مشخص شده مطابقت داشته باشد. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | به دنبال سازنده‌های تعریف‌شده برای Type جاری می‌گردد، با استفاده از Flagهای Binding مشخص‌شده. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)() const | تمام سازنده‌های عمومی تعریف‌شده برای Type جاری را برمی‌گرداند. |
| [ObjectPtr](../smartptr/) [GetCustomAttribute](./getcustomattribute/)(const [TypeInfo](./)\&) const | به دنبال ویژگی سفارشی با نوع مشخص‌شده که بر روی Type نمایان‌سازی‌شده توسط شیء جاری اعمال شده است می‌گردد. |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)() const | آرایه‌ای شامل اشیایی که تمام ویژگی‌های سفارشی اعمال‌شده بر نوع را نشان می‌دهند برمی‌گرداند. |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)(const [TypeInfo](./)\&, **bool**) const | آرایه‌ای شامل اشیایی که ویژگی‌های خاصی که بر نوع اعمال شده‌اند را برمی‌گرداند. |
| [TypeInfo](./) [GetElementType](./getelementtype/)() const | پیاده‌سازی نشده. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\> [GetField](./getfield/)(const [System::String](../string/)\&, [System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | به دنبال فیلد مشخص‌شده می‌گردد، با استفاده از محدودیت‌های binding داده‌شده. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\>\> [GetFields](./getfields/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | به دنبال فیلدهای تعریف‌شده برای Type جاری می‌گردد، با استفاده از محدودیت‌های binding داده‌شده. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetGenericArguments](./getgenericarguments/)() const | آرایه‌ای از پارامترهای نوع جنریک برای این نوع را برمی‌گرداند. |
| int [GetHashCode](./gethashcode/)() const | کد هش مرتبط با این نمونه را برمی‌گرداند. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetInterfaces](./getinterfaces/)() const | تمام واسط‌هایی که توسط Type جاری پیاده‌سازی یا به ارث برده شده‌اند را برمی‌گرداند. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [GetMember](./getmember/)(const [String](../string/)\&) const | فهرستی از اعضایی با نام مشخص‌شده را برمی‌گرداند. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::MethodInfo](../../system.reflection/methodinfo/)\> [GetMethod](./getmethod/)(const [String](../string/)\&) const | متدی با نام مشخص‌شده را برمی‌گرداند. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)() const | تمام ویژگی‌های عمومی Type جاری را برمی‌گرداند. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | به دنبال ویژگی‌های Type جاری می‌گردد، با استفاده از محدودیت‌های binding داده‌شده. |
| [TypeInfo](./) [GetTemplParamType](./gettemplparamtype/)() const | توصیف‌گر پارامتر نوع قالب را برمی‌گرداند. |
| **uint32_t** [Hash](./hash/)() const | مقدار هش مربوط به نوع نمایان‌سازی‌شده توسط شیء جاری را برمی‌گرداند. |
| **bool** [IsAssignableFrom](./isassignablefrom/)(const [TypeInfo](./)\&) const | تعیین می‌کند آیا یک نمونه از نوع مشخص‌شده می‌تواند به متغیری از نوع جاری اختصاص یابد. |
| **bool** [IsDefined](./isdefined/)(const [TypeInfo](./)\&, **bool**) const | پیاده‌سازی نشده. نشان می‌دهد آیا یک یا چند ویژگی از نوع مشخص‌شده یا انواع مشتق‌شده آن بر این عضو اعمال شده‌اند. |
| **bool** [IsInstanceOfType](./isinstanceoftype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | تعیین می‌کند آیا شیء مشخص‌شده نمونه‌ای از نوع جاری است. |
| **bool** [IsSubclassOf](./issubclassof/)(const [TypeInfo](./)\&) const | تعیین می‌کند آیا نوع نمایان‌سازی‌شده توسط شیء جاری زیرکلاس کلاس مشخص‌شده است. |
| **bool** [operator!=](./operator_not_equal/)(const [TypeInfo](./)\&) const | تعیین می‌کند آیا دو شیء [TypeInfo](./) جاری و مشخص‌شده برابر نیستند. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | تعیین می‌کند آیا شیء [TypeInfo](./) جاری یک شیء تهی نیست، یعنی نمایانگر برخی نوع است. |
| **bool** [operator==](./operator_equal_equal/)(const [TypeInfo](./)\&) const | تعیین می‌کند آیا دو شیء [TypeInfo](./) جاری و مشخص‌شده برابر هستند. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | تعیین می‌کند آیا شیء [TypeInfo](./) جاری یک شیء تهی است؛ یعنی نمایانگر هیچ نوعی نیست. |
| void [reset](./reset/)() | [TypeInfo](./) را به تهی (null) تنظیم می‌کند. |
| void [set_IsValueType](./set_isvaluetype/)(**bool**) | مقدار نشان‌دهنده این‌که آیا Type یک نوع مقدار است را تنظیم می‌کند. |
| void [SetBaseType](./setbasetype/)(GetTypeInfoFunPtr) | توصیف‌گر نوع پایه را تنظیم می‌کند. |
| void [SetTemplParamType](./settemplparamtype/)(const [TypeInfo](./)\&) | توصیف‌گر پارامتر نوع قالب را تنظیم می‌کند. |
| static **uint32_t** [StringHash](./stringhash/)(const char_t *) | هش برای رشتهٔ مشخص‌شده را محاسبه می‌کند. |
| [String](../string/) [ToString](./tostring/)() const | رشته‌ای شامل نام نوع نمایان‌سازی‌شده توسط شیء جاری را برمی‌گرداند. |
| static const [TypeInfo](./)\& [Type](./type/)() | شیء [TypeInfo](./) را برمی‌گرداند که کلاس [TypeInfo](./) را نشان می‌دهد. |
|  [TypeInfo](./typeinfo/)() | سازندهٔ پیش‌فرض (هیچ نوعی تنظیم نشده است). |
|  [TypeInfo](./typeinfo/)(std::nullptr_t) | سازندهٔ شیء تهی (هیچ نوعی تنظیم نشده است). |
|  [TypeInfo](./typeinfo/)(const char_t *) | سازنده. |
|  [TypeInfo](./typeinfo/)(const char_t *, **uint32_t**) | سازنده. |
|  [TypeInfo](./typeinfo/)(const std::type_info\&) | سازنده. |
## فیلدها

| Field | Description |
| --- | --- |
| static [EmptyType](./emptytype/) | ثابت نمایانگر لیست خالی [TypeInfo](./). |
| static [EmptyTypes](./emptytypes/) | ثابت نمایانگر لیست خالی [TypeInfo](./). |
## تعاریف نوع

| Typedef | Description |
| --- | --- |
| [DefaultConstructor](./defaultconstructor/) | اشاره‌گر تابع برای ساختن نوع. |
## مراجع

* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)