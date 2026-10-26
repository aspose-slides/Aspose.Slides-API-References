---
title: "System::Threading"
second_title: Aspose.Slides برای C++ API Reference
description: 
type: docs
weight: 1002
url: /fa/system.threading/
---
## کلاس‌ها

| کلاس | توضیح |
| --- | --- |
| [AutoResetEvent](./autoresetevent/) | رویداد برای اطلاع‌رسانی به نخ انتظار که به‌صورت خودکار بازنشانی می‌شود. اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا نقص‌های assert می‌شود. همیشه این کلاس را در اشاره‌گر [System::SmartPtr](../system/smartptr/) بپیچید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید. |
| [CancellationToken](./cancellationtoken/) | اطلاع‌رسانی که عملیات باید لغو شوند را منتقل می‌کند. این کلاس مکانیزمی برای لغو تعاونی بین نُخ‌ها فراهم می‌کند که به یک نخ اجازه می‌دهد تا دیگران را از لغو یک عملیات مطلع کند. |
| [CancellationTokenRegistration](./cancellationtokenregistration/) | نمایانگر یک ثبت‌نام برای فراخوانی توکن لغو است. |
| [CancellationTokenSource](./cancellationtokensource/) | منبع توکن لغو که می‌تواند برای ایجاد اطلاعیه‌های لغو استفاده شود. |
| [Details_SemaphoreFullException](./details_semaphorefullexception/) |  |
| [Details_SynchronizationLockException](./details_synchronizationlockexception/) |  |
| [Details_ThreadAbortException](./details_threadabortexception/) |  |
| [Details_ThreadInterruptedException](./details_threadinterruptedexception/) |  |
| [Details_ThreadStateException](./details_threadstateexception/) |  |
| [EventWaitHandle](./eventwaithandle/) | رویدادی که می‌تواند به نخ انتظار ارسال شود. اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با عملگر new ایجاد نکنید، چون منجر به خطاهای زمان اجرا و/یا نقص‌های assert می‌شود. همیشه این کلاس را در اشاره‌گر [System::SmartPtr](../system/smartptr/) بپیچید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید. |
| [Interlocked](./interlocked/) | API برای عملیات‌های ایمن نسبت به نخ را فراهم می‌کند. این یک نوع استاتیک بدون سرویس‌های نمونه است. شما نباید به هیچ روشی نمونه‌ای از آن ایجاد کنید. |
| [ManualResetEvent](./manualresetevent/) | رویدادی برای اطلاع‌رسانی به نخ انتظار که به‌صورت خودکار بازنشانی نمی‌شود. اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا نقص‌های assert می‌شود. همیشه این کلاس را در اشاره‌گر [System::SmartPtr](../system/smartptr/) بپیچید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید. |
| [Monitor](./monitor/) | کلاس [Monitor](./monitor/) مکانیزمی فراهم می‌کند که دسترسی به اشیاء را همگام‌سازی می‌کند. |
| [Mutex](./mutex/) | پیاده‌سازی [Mutex](./mutex/). اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا نقص‌های assert می‌شود. همیشه این کلاس را در اشاره‌گر [System::SmartPtr](../system/smartptr/) بپیچید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید. |
| [Semaphore](./semaphore/) | پیاده‌سازی [Semaphore](./semaphore/). اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا نقص‌های assert می‌شود. همیشه این کلاس را در اشاره‌گر [System::SmartPtr](../system/smartptr/) بپیچید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید. |
| [SynchronizationContext](./synchronizationcontext/) | عملکرد پایه برای انتقال یک زمینه همگام‌سازی در میان عملیات‌های مختلف همگام‌سازی را فراهم می‌کند. |
| [Thread](./thread/) | پیاده‌سازی [Thread](./thread/). اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/ یا نقص‌های assert می‌شود. همیشه این کلاس را در اشاره‌گر [System::SmartPtr](../system/smartptr/) بپیچید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید. |
| [ThreadPool](./threadpool/) | API استخر [Thread](./thread/) که امکان افزودن کارها به صف را برای خوانده شدن توسط استخر نخ‌های کارگر فراهم می‌کند. این یک نوع استاتیک بدون سرویس‌های نمونه است. شما نباید به هیچ روشی نمونه‌ای از آن ایجاد کنید. |
| [ThreadPoolImpl](./threadpoolimpl/) | داده‌های داخلی استخر [Thread](./thread/). این یک نوع تک‌نمونه است که مدیریت حافظه توسط توابع دسترسی انجام می‌شود. شما نباید به‌صورت مستقیم نمونه‌ای از آن ایجاد کنید. |
| [Timer](./timer/) | کلاس [Timer](./timer/) که مورد کار را پس از تاخیر در نخ جداگانه‌ای اجرا می‌کند. اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا نقص‌های assert می‌شود. همیشه این کلاس را در اشاره‌گر [System::SmartPtr](../system/smartptr/) بپیچید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید. |
| [TimerQueue](./timerqueue/) | صفی که اشیاء [Timer](./timer/) را مدیریت می‌کند. این فقط یک پیاده‌سازی است. اشیاء [Timer](./timer/) خود به‌طور خودکار در آن ثبت می‌شوند، برای استفاده از آنها نیازی به این کار ندارید - به‌جای آن API کلاس [Timer](./timer/) را استفاده کنید. این یک نوع تک‌نمونه است که مدیریت حافظه توسط توابع دسترسی انجام می‌شود. شما نباید به‌صورت مستقیم نمونه‌ای از آن ایجاد کنید. |
| [WaitHandle](./waithandle/) | کلاس پایهٔ اولیهٔ انتظار. اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/ یا نقص‌های assert می‌شود. همیشه این کلاس را در اشاره‌گر [System::SmartPtr](../system/smartptr/) بپیچید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید. |
## ساختارها

| ساختار | توضیح |
| --- | --- |
| [Timeout](./timeout/) | [Threading](./) مقادیر ویژهٔ زمان‌سری. این یک نوع استاتیک بدون سرویس‌های نمونه است. شما نباید به هیچ روشی نمونه‌ای از آن ایجاد کنید. |
## شمارش‌ها

| شمارش | توضیح |
| --- | --- |
| [ApartmentState](./apartmentstate/) | وضعیت آپارتمان نخ را تنظیم می‌کند. |
| [EventResetMode](./eventresetmode/) | نشان می‌دهد حالت رویداد چگونه بازنشانی می‌شود. |
| [ThreadState](./threadstate/) | وضعیت نخ. |
## تعاریف‌نوع

| تعریف‌نوع | توضیح |
| --- | --- |
| [ThreadStateException](./threadstateexception/) |  |
| [SemaphoreFullException](./semaphorefullexception/) |  |
| [SynchronizationLockException](./synchronizationlockexception/) |  |
| [ThreadAbortException](./threadabortexception/) |  |
| [ThreadInterruptedException](./threadinterruptedexception/) |  |
| [SendOrPostCallback](./sendorpostcallback/) |  |
| [ParameterizedThreadStart](./parameterizedthreadstart/) | توابع [Thread](./thread/) با یک پارامتر. |
| [ThreadStart](./threadstart/) | توابع [Thread](./thread/) بدون پارامتر. |
| [WaitCallback](./waitcallback/) | مورد بازخوانی که یک‌بار هنگام وجود فضا اجرا می‌شود. |
| [TimerCallback](./timercallback/) | تابع بازخوانی که توسط زمان‌سنج فراخوانی می‌شود. |
| [wait_handle_t](./wait_handle_t/) | نوع دستگیره. |