---
title: ISlideShowTransition
second_title: مرجع API لـ Aspose.Slides for C++
description: يمثل انتقال عرض الشرائح.
type: docs
weight: 3810
url: /ar/aspose.slides/islideshowtransition/
---
## ISlideShowTransition فئة

يمثل انتقال عرض الشرائح.

```cpp
class ISlideShowTransition : public virtual System::Object
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة مزدوجة الدقة بأسلوب C# حيث يُعتبر NaNانان متساويين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual **bool** [get_AdvanceAfter](./get_advanceafter/)() | هذه السمة تحدد ما إذا كان عرض الشرائح سيتنقل إلى الشريحة التالية بعد فترة زمنية معينة. قراءة **bool**. |
| virtual **uint32_t** [get_AdvanceAfterTime](./get_advanceaftertime/)() | يحدد الوقت، بالمللي ثانية، الذي بعده يجب أن يبدأ الانتقال. يمكن استخدام هذا الإعداد بالاقتران مع سمة advClick. إذا لم يتم تحديد هذه السمة يُفترض عدم حدوث تقدم تلقائي. قراءة **uint32_t**. |
| virtual **bool** [get_AdvanceOnClick](./get_advanceonclick/)() | يحدد ما إذا كان النقر بالماوس سيؤدي إلى تقدم الشريحة أم لا. إذا لم يتم تحديد هذه السمة يُفترض القيمة true. قراءة **bool**. |
| virtual **int32_t** [get_Duration](./get_duration/)() | يحصل على مدة تأثير انتقال الشريحة بالمللي ثانية. قراءة **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_Sound](./get_sound/)() | يعيد البيانات الصوتية المضمنة. قراءة [IAudio](../iaudio/). |
| virtual **bool** [get_SoundIsBuiltIn](./get_soundisbuiltin/)() | يحدد ما إذا كان هذا الصوت صوتًا مدمجًا أم لا. إذا تم تعيين هذه السمة إلى true يتم إبلاغ التطبيق المُنشئ للتحقق من سمة الاسم المحددة لهذا الصوت في قائمة الأصوات المدمجة الخاصة به، ويمكنه حينها عرض اسم مخصص أو واجهة مستخدم حسب الحاجة. قراءة **bool**. |
| virtual **bool** [get_SoundLoop](./get_soundloop/)() | هذه السمة تحدد ما إذا كان الصوت سيعيد التشغيل إلى أن يحدث حدث صوتي التالي في عرض الشرائح. قراءة **bool**. |
| virtual [SlideShow::TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/) [get_SoundMode](./get_soundmode/)() | يضبط أو يعيد وضع الصوت لانتقال الشريحة. قراءة [TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/). |
| virtual [System::String](../../system/string/) [get_SoundName](./get_soundname/)() | يحدد اسمًا قابلًا للقراءة من قبل الإنسان لصوت الانتقال. يجب تعيين [ISlideShowTransition::set_Sound](./set_sound/) للحصول أو لتعيين اسم الصوت. قراءة [System::String](../../system/string/). |
| virtual [SlideShow::TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/) [get_Speed](./get_speed/)() | يحدد سرعة الانتقال التي ستُستخدم عند الانتقال من الشريحة الحالية إلى التالية. قراءة [TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/). |
| virtual [SlideShow::TransitionType](../../aspose.slides.slideshow/transitiontype/) [get_Type](./get_type/)() | نوع الانتقال. قراءة [TransitionType](../../aspose.slides.slideshow/transitiontype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[SlideShow::ITransitionValueBase](../../aspose.slides.slideshow/itransitionvaluebase/)\> [get_Value](./get_value/)() | [Slide](../slide/) قيمة انتقال العرض. قراءة فقط [SlideShow::ITransitionValueBase](../../aspose.slides.slideshow/itransitionvaluebase/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تمثيل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح التجزئة للكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تمثيل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموضّح بواسطة targetType. تمثيل لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | يطبق قفل عبارة C# lock(). يُستدعى مباشرةً أو يُستخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تمثيل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويمكّن من إنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويمكّن من إنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعياً كائن نوع القيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_AdvanceAfter](./set_advanceafter/)(**bool**) | هذه السمة تحدد ما إذا كان عرض الشرائح سيتنقل إلى الشريحة التالية بعد فترة زمنية معينة. كتابة **bool**. |
| virtual void [set_AdvanceAfterTime](./set_advanceaftertime/)(**uint32_t**) | يحدد الوقت، بالمللي ثانية، الذي بعده يجب أن يبدأ الانتقال. يمكن استخدام هذا الإعداد بالاقتران مع سمة advClick. إذا لم يتم تحديد هذه السمة يُفترض عدم حدوث تقدم تلقائي. كتابة **uint32_t**. |
| virtual void [set_AdvanceOnClick](./set_advanceonclick/)(**bool**) | يحدد ما إذا كان النقر بالماوس سيؤدي إلى تقدم الشريحة أم لا. إذا لم يتم تحديد هذه السمة يُفترض القيمة true. كتابة **bool**. |
| virtual void [set_Duration](./set_duration/)(**int32_t**) | يضبط مدة تأثير انتقال الشريحة بالمللي ثانية. كتابة **int32_t**. |
| virtual void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) | يضبط البيانات الصوتية المضمنة. كتابة [IAudio](../iaudio/). |
| virtual void [set_SoundIsBuiltIn](./set_soundisbuiltin/)(**bool**) | يحدد ما إذا كان هذا الصوت صوتًا مدمجًا أم لا. إذا تم تعيين هذه السمة إلى true يتم إبلاغ التطبيق المُنشئ للتحقق من سمة الاسم المحددة لهذا الصوت في قائمة الأصوات المدمجة الخاصة به، ويمكنه حينها عرض اسم مخصص أو واجهة مستخدم حسب الحاجة. كتابة **bool**. |
| virtual void [set_SoundLoop](./set_soundloop/)(**bool**) | هذه السمة تحدد ما إذا كان الصوت سيعيد التشغيل إلى أن يحدث حدث صوتي التالي في عرض الشرائح. كتابة **bool**. |
| virtual void [set_SoundMode](./set_soundmode/)([SlideShow::TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/)) | يضبط أو يعيد وضع الصوت لانتقال الشريحة. كتابة [TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/). |
| virtual void [set_SoundName](./set_soundname/)([System::String](../../system/string/)) | يحدد اسمًا قابلًا للقراءة من قبل الإنسان لصوت الانتقال. يجب تعيين [ISlideShowTransition::set_Sound](./set_sound/) للحصول أو لتعيين اسم الصوت. كتابة [System::String](../../system/string/). |
| virtual void [set_Speed](./set_speed/)([SlideShow::TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/)) | يحدد سرعة الانتقال التي ستُستخدم عند الانتقال من الشريحة الحالية إلى التالية. كتابة [TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/). |
| virtual void [set_Type](./set_type/)([SlideShow::TransitionType](../../aspose.slides.slideshow/transitiontype/)) | نوع الانتقال. كتابة [TransitionType](../../aspose.slides.slideshow/transitiontype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي الـ n كإشارة ضعيفة (بدلاً من مشتركة). يتيح تحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص عداد المرجع المشترك ويعيده. لا يجب استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تمثيل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى نص. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يطبق بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يطبق إلغاء قفل عبارة C# lock(). يُستدعى مباشرةً أو يُستخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا يجب استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا يجب استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |

## انظر أيضا

* فئة [Object](../../system/object/)
* نطاق [Aspose::Slides](../)
* مكتبة [Aspose.Slides](../../)