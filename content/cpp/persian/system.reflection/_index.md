---
title: "System::Reflection"
second_title: مرجع API Aspose.Slides برای C++
description: 
type: docs
weight: 755
url: /fa/system.reflection/
---
## کلاس‌ها

| کلاس | توضیح |
| --- | --- |
| [Assembly](./assembly/) | [Reflection](./) کلاس توصیف‌کننده‌ی assembly. پشتیبانی محدود است زیرا قواعد بین C# و C++ به‌طرز قابل‌توجهی متفاوت هستند. اشیاء این کلاس باید فقط با استفاده از [System::MakeObject()](../system/makeobject/) تابع اختصاص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای ادعا می‌شود. همیشه این کلاس را در یک [System::SmartPtr](../system/smartptr/) اشاره‌گر بپیچید و از این اشاره‌گر برای ارسال به توابع به‌عنوان آرگومان استفاده کنید. |
| [AssemblyName](./assemblyname/) | نام assembly را تعریف می‌کند. اشیاء این کلاس باید فقط با استفاده از [System::MakeObject()](../system/makeobject/) تابع اختصاص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای ادعا می‌شود. همیشه این کلاس را در یک [System::SmartPtr](../system/smartptr/) اشاره‌گر بپیچید و از این اشاره‌گر برای ارسال به توابع به‌عنوان آرگومان استفاده کنید. |
| [AssemblyTypeRegistration](./assemblytyperegistration/) | تک‌نمونه برای ثبت نوع در assembly اجرایی. |
| [AssemblyTypeRegistrationBase](./assemblytyperegistrationbase/) | نوع پایه برای تک‌نمونه‌ها جهت ثبت نوع در assembly اجرایی. |
| [ConstructorInfo](./constructorinfo/) | دسترسی به متادیتای سازنده را فراهم می‌کند. |
| [Details_ReflectionTypeLoadException](./details_reflectiontypeloadexception/) | ReflectionTypeLoadException توسط متد Module.GetTypes پرتاب می‌شود اگر هر یک از کلاس‌های موجود در یک ماژول بارگذاری نشوند. هرگز نمونه‌های این کلاس را به‌صورت دستی ایجاد نکنید. به‌جای آن از کلاس ReflectionTypeLoadException استفاده کنید. هرگز نمونه‌های کلاس ReflectionTypeLoadException را در [System::SmartPtr](../system/smartptr/) بپیچید. |
| [Details_TargetInvocationException](./details_targetinvocationexception/) | TargetInvocationException توسط روش‌هایی که از طریق بازتاب فراخوانی می‌شوند پرتاب می‌شود. هرگز نمونه‌های این کلاس را به‌صورت دستی ایجاد نکنید. به‌جای آن از کلاس TargetInvocationException استفاده کنید. هرگز نمونه‌های کلاس TargetInvocationException را در [System::SmartPtr](../system/smartptr/) بپیچید. |
| [FieldInfo](./fieldinfo/) | ویژگی‌های یک فیلد را کشف می‌کند و دسترسی به متادیتای فیلد را فراهم می‌کند. |
| [MemberInfo](./memberinfo/) | اطلاعات بازتابی دربارهٔ اعضا را فراهم می‌کند. اشیاء این کلاس باید فقط با استفاده از [System::MakeObject()](../system/makeobject/) تابع اختصاص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای ادعا می‌شود. همیشه این کلاس را در یک [System::SmartPtr](../system/smartptr/) اشاره‌گر بپیچید و از این اشاره‌گر برای ارسال به توابع به‌عنوان آرگومان استفاده کنید. |
| [MethodBase](./methodbase/) | اطلاعات پایه دربارهٔ متد. اشیاء این کلاس باید فقط با استفاده از [System::MakeObject()](../system/makeobject/) تابع اختصاص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای ادعا می‌شود. همیشه این کلاس را در یک [System::SmartPtr](../system/smartptr/) اشاره‌گر بپیچید و از این اشاره‌گر برای ارسال به توابع به‌عنوان آرگومان استفاده کنید. |
| [MethodInfo](./methodinfo/) | اطلاعات مربوط به متد کلاس را نشان می‌دهد. |
| [PropertyInfo](./propertyinfo/) | اطلاعات مربوط به ویژگی را نشان می‌دهد. |
## شمارش‌ها

| شمارش | توضیح |
| --- | --- |
| [BindingFlags](./bindingflags/) | اعضا و حالت‌های جستجوی انواع و بایندها را تعریف می‌کند. |
| [FieldAttributes](./fieldattributes/) | ویژگی‌های فیلد بازتابی. |
| [MemberTypes](./membertypes/) | هر نوع عضو را علامت‌گذاری می‌کند. |
## تعاریف نوع

| تعریف نوع | توضیح |
| --- | --- |
| [ReflectionTypeLoadException](./reflectiontypeloadexception/) | ReflectionTypeLoadException توسط متد Module.GetTypes پرتاب می‌شود اگر هر یک از کلاس‌های موجود در یک ماژول بارگذاری نشوند. هرگز نمونه‌های کلاس ReflectionTypeLoadException را در [System::SmartPtr](../system/smartptr/) بپیچید. |
| [TargetInvocationException](./targetinvocationexception/) | TargetInvocationException توسط روش‌هایی که از طریق بازتاب فراخوانی می‌شوند پرتاب می‌شود. هرگز نمونه‌های کلاس TargetInvocationException را در [System::SmartPtr](../system/smartptr/) بپیچید. |