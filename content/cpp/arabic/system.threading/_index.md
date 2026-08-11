---
title: "System::Threading"
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للغة C++
description: 
type: docs
weight: 1002
url: /ar/system.threading/
---
## الفئات

| الفئة | الوصف |
| --- | --- |
| [AutoResetEvent](./autoresetevent/) | حدث لإخطار الخيط المنتظر الذي يعيد الضبط تلقائيًا. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثيل لهذا النوع على المكدس أو باستخدام المشغل new، لأن ذلك سيسبّب أخطاء وقت التشغيل أو أخطاء تأكيد. احفظ دائمًا هذه الفئة داخل مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [CancellationToken](./cancellationtoken/) | ينشر إشعارًا بأن العمليات يجب إلغاؤها. توفر هذه الفئة آلية للإلغاء التعاوني بين الخيوط، مما يسمح لخيط واحد بإخطار الآخرين بأن العملية يجب إلغاؤها. |
| [CancellationTokenRegistration](./cancellationtokenregistration/) | تمثل تسجيلًا لاستدعاء رد نداء رمز الإلغاء. |
| [CancellationTokenSource](./cancellationtokensource/) | مصدر رمز إلغاء يمكن استخدامه لإطلاق إشعارات الإلغاء. |
| [Details_SemaphoreFullException](./details_semaphorefullexception/) |  |
| [Details_SynchronizationLockException](./details_synchronizationlockexception/) |  |
| [Details_ThreadAbortException](./details_threadabortexception/) |  |
| [Details_ThreadInterruptedException](./details_threadinterruptedexception/) |  |
| [Details_ThreadStateException](./details_threadstateexception/) |  |
| [EventWaitHandle](./eventwaithandle/) | حدث يمكن إرساله إلى الخيط المنتظر. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثيل لهذا النوع على المكدس أو باستخدام المشغل new، لأن ذلك سيسبّب أخطاء وقت التشغيل أو أخطاء تأكيد. احفظ دائمًا هذه الفئة داخل مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [Interlocked](./interlocked/) | يوفر واجهة برمجة تطبيقات للعمليات الآمنة المتعددة الخيوط. هذا نوع ثابت لا يحتوي على خدمات مثيل. يجب ألا تنشئ مثيلات له بأي وسيلة. |
| [ManualResetEvent](./manualresetevent/) | حدث لإخطار الخيط المنتظر الذي لا يعيد الضبط تلقائيًا. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثيل لهذا النوع على المكدس أو باستخدام المشغل new، لأن ذلك سيسبّب أخطاء وقت التشغيل أو أخطاء تأكيد. احفظ دائمًا هذه الفئة داخل مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [Monitor](./monitor/) | الفئة [Monitor](./monitor/) توفر آلية تُزامِن الوصول إلى الكائنات. |
| [Mutex](./mutex/) | تنفيذ [Mutex](./mutex/). يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثيل لهذا النوع على المكدس أو باستخدام المشغل new، لأن ذلك سيسبّب أخطاء وقت التشغيل أو أخطاء تأكيد. احفظ دائمًا هذه الفئة داخل مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [Semaphore](./semaphore/) | تنفيذ [Semaphore](./semaphore/). يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثيل لهذا النوع على المكدس أو باستخدام المشغل new، لأن ذلك سيسبّب أخطاء وقت التشغيل أو أخطاء تأكيد. احفظ دائمًا هذه الفئة داخل مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [SynchronizationContext](./synchronizationcontext/) | يوفر الوظيفة الأساسية لنشر سياق المزامنة عبر عمليات المزامنة المختلفة. |
| [Thread](./thread/) | تنفيذ [Thread](./thread/). يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثيل لهذا النوع على المكدس أو باستخدام المشغل new، لأن ذلك سيسبّب أخطاء وقت التشغيل أو أخطاء تأكيد. احفظ دائمًا هذه الفئة داخل مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [ThreadPool](./threadpool/) | واجهة برمجة تطبيقات مجموعة [Thread](./thread/) تسمح بدفع الوظائف إلى قائمة الانتظار لتُقرأ بواسطة مجموعة من خيوط العاملين. هذا نوع ثابت لا يحتوي على خدمات مثيل. يجب ألا تنشئ مثيلات له بأي وسيلة. |
| [ThreadPoolImpl](./threadpoolimpl/) | بيانات داخلية لمجموعة [Thread](./thread/). هذا نوع مفرد (Singleton) تُدار ذاكرته عبر دوال الوصول. يجب ألا تنشئ مثيلات له مباشرة. |
| [Timer](./timer/) | الفئة [Timer](./timer/) التي تُنفذ عنصر وظيفة في خيط منفصل بعد التأخير. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثيل لهذا النوع على المكدس أو باستخدام المشغل new، لأن ذلك سيسبّب أخطاء وقت التشغيل أو أخطاء تأكيد. احفظ دائمًا هذه الفئة داخل مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [TimerQueue](./timerqueue/) | طابور يتعامل مع كائنات [Timer](./timer/). هذا مجرد تنفيذ. تسجل كائنات [Timer](./timer/) هناك بنفسها، لا تحتاج إلى القيام بذلك لاستخدامها – استخدم واجهة برمجة تطبيقات الفئة [Timer](./timer/) بدلاً من ذلك. هذا نوع مفرد تُدار ذاكرته عبر دوال الوصول. يجب ألا تنشئ مثيلات له مباشرة. |
| [WaitHandle](./waithandle/) | فئة أساسية للبدء الانتظارية. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثيل لهذا النوع على المكدس أو باستخدام المشغل new، لأن ذلك سيسبّب أخطاء وقت التشغيل أو أخطاء تأكيد. احفظ دائمًا هذه الفئة داخل مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
## الهياكل

| الهيكل | الوصف |
| --- | --- |
| [Timeout](./timeout/) | [Threading](./) قيم خاصة بالمهلة. هذا نوع ثابت لا يحتوي على خدمات مثيل. يجب ألا تنشئ مثيلات له بأي وسيلة. |
## التعدادات

| التعداد | الوصف |
| --- | --- |
| [ApartmentState](./apartmentstate/) | يضبط حالة الشقة للخيط. |
| [EventResetMode](./eventresetmode/) | يشير إلى طريقة إعادة ضبط حالة الحدث. |
| [ThreadState](./threadstate/) | حالة الخيط. |
## الأنواع التعريفية

| نوع تعريف | الوصف |
| --- | --- |
| [ThreadStateException](./threadstateexception/) |  |
| [SemaphoreFullException](./semaphorefullexception/) |  |
| [SynchronizationLockException](./synchronizationlockexception/) |  |
| [ThreadAbortException](./threadabortexception/) |  |
| [ThreadInterruptedException](./threadinterruptedexception/) |  |
| [SendOrPostCallback](./sendorpostcallback/) |  |
| [ParameterizedThreadStart](./parameterizedthreadstart/) | دالة [Thread](./thread/) بمعامل واحد. |
| [ThreadStart](./threadstart/) | دالة [Thread](./thread/) بدون معاملات. |
| [WaitCallback](./waitcallback/) | عنصر رد نداء يُنفّذ عندما يتوفر موقع. |
| [TimerCallback](./timercallback/) | دالة رد نداء تُستدعى بواسطة المؤقت. |
| [wait_handle_t](./wait_handle_t/) | نوع المقابض. |