---
title: SlideShowTransition
second_title: مرجع API Aspose.Slides للغة C++
description: يمثل انتقال عرض الشرائح.
type: docs
weight: 404
url: /ar/aspose.slides.slideshow/slideshowtransition/
---
## SlideShowTransition فئة

يمثل انتقال عرض الشرائح.

```cpp
class SlideShowTransition : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::BaseSlide>>,
                            public Aspose::Slides::ISlideShowTransition
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | يحدد ما إذا كان كائني [SlideShowTransition](./) متساويين. قراءة/كتابة **bool**. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يُحاكي مقارنة النقطة العائمة على نمط C# حيث تُعتبر قيمة NaN قيمتين متساويتين على الرغم من أن معيار IEC 60559:1989 يُشير إلى أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يُحاكي مقارنة النقطة العائمة على نمط C# حيث تُعتبر قيمة NaN قيمتين متساويتين على الرغم من أن معيار IEC 60559:1989 يُشير إلى أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| **bool** [get_AdvanceAfter](./get_advanceafter/)() override | تحدد هذه السمة ما إذا كان عرض الشرائح سينتقل إلى الشريحة التالية بعد فترة زمنية معينة. قراءة **bool**. |
| **uint32_t** [get_AdvanceAfterTime](./get_advanceaftertime/)() override | يحدد الوقت، بالميليثانية، الذي يجب أن يبدأ بعده الانتقال. يمكن استخدام هذا الإعداد بالاشتراك مع السمة advClick. إذا لم يتم تحديد هذه السمة، يُفترض عدم حدوث تقدم تلقائي. قراءة **uint32_t**. |
| **bool** [get_AdvanceOnClick](./get_advanceonclick/)() override | يحدد ما إذا كان النقر بالماوس سيؤدي إلى تقدم الشريحة أم لا. إذا لم يتم تحديد هذه السمة، يُفترض أن القيمة صحيحة. قراءة **bool**. |
| **int32_t** [get_Duration](./get_duration/)() override | يحصل على مدة تأثير انتقال الشريحة بالميليثانية. قراءة **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\> [get_Sound](./get_sound/)() override | يعيد بيانات الصوت المضمّنة. قراءة [IAudio](../../aspose.slides/iaudio/). |
| **bool** [get_SoundIsBuiltIn](./get_soundisbuiltin/)() override | يحدد ما إذا كان هذا الصوت مدمجًا أم لا. إذا تم تعيين هذه السمة إلى true فإن التطبيق المولد يتم إنذاره للتحقق من سمة الاسم المحددة لهذا الصوت في قائمته من الأصوات المدمجة ويمكنه حينها عرض اسم مخصص أو واجهة مستخدم حسب الحاجة. يقرأ **bool**. |
| **bool** [get_SoundLoop](./get_soundloop/)() override | تحدد هذه السمة ما إذا كان الصوت سيعيد تشغيل نفسه حتى يحدث حدث صوتي التالي في عرض الشرائح. قراءة **bool**. |
| [TransitionSoundMode](../transitionsoundmode/) [get_SoundMode](./get_soundmode/)() override | يضبط أو يعيد وضع الصوت لانتقال الشريحة. قراءة [TransitionSoundMode](../transitionsoundmode/). |
| [System::String](../../system/string/) [get_SoundName](./get_soundname/)() override | يحدد اسمًا قابلًا للقراءة البشرية لصوت الانتقال. يجب تعيين [ISlideShowTransition::set_Sound](../../aspose.slides/islideshowtransition/set_sound/) للحصول على اسم الصوت أو تعيينه. يقرأ [System::String](../../system/string/). |
| [TransitionSpeed](../transitionspeed/) [get_Speed](./get_speed/)() override | يحدد سرعة الانتقال التي ستُستخدم عند الانتقال من الشريحة الحالية إلى التالية. قراءة [TransitionSpeed](../transitionspeed/). |
| [TransitionType](../transitiontype/) [get_Type](./get_type/)() override | نوع الانتقال. قراءة [TransitionType](../transitiontype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITransitionValueBase](../itransitionvaluebase/)\> [get_Value](./get_value/)() override | [Slide](../../aspose.slides/slide/) عرض قيمة الانتقال. قراءة فقط [ITransitionValueBase](../itransitionvaluebase/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | يعمل كدالة تجزئة لنوع معين، مناسبة للاستخدام في خوارزميات التجزئة وهياكل البيانات مثل جدول التجزئة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. مماثل لمشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل تعبير C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مقابل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع الهياكل الداخلية للبيانات. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن بالمرجعية كائن نوع قيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالات السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجعية المشتركة بالقيمة المحددة. |
| void [set_AdvanceAfter](./set_advanceafter/)(**bool**) override | تحدد هذه السمة ما إذا كان عرض الشرائح سينتقل إلى الشريحة التالية بعد فترة زمنية معينة. كتابة **bool**. |
| void [set_AdvanceAfterTime](./set_advanceaftertime/)(**uint32_t**) override | يحدد الوقت، بالميليثانية، الذي يجب أن يبدأ بعده الانتقال. يمكن استخدام هذا الإعداد بالاشتراك مع السمة advClick. إذا لم يتم تحديد هذه السمة، يُفترض عدم حدوث تقدم تلقائي. كتابة **uint32_t**. |
| void [set_AdvanceOnClick](./set_advanceonclick/)(**bool**) override | يحدد ما إذا كان النقر بالماوس سيؤدي إلى تقدم الشريحة أم لا. إذا لم يتم تحديد هذه السمة، يُفترض أن القيمة صحيحة. كتابة **bool**. |
| void [set_Duration](./set_duration/)(**int32_t**) override | يضبط مدة تأثير انتقال الشريحة بالميليثانية. كتابة **int32_t**. |
| void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\>) override | يضبط بيانات الصوت المضمّنة. كتابة [IAudio](../../aspose.slides/iaudio/). |
| void [set_SoundIsBuiltIn](./set_soundisbuiltin/)(**bool**) override | يحدد ما إذا كان هذا الصوت مدمجًا أم لا. إذا تم تعيين هذه السمة إلى true فإن التطبيق المولد يتم إنذاره للتحقق من سمة الاسم المحددة لهذا الصوت في قائمته من الأصوات المدمجة ويمكنه حينها عرض اسم مخصص أو واجهة مستخدم حسب الحاجة. يكتب **bool**. |
| void [set_SoundLoop](./set_soundloop/)(**bool**) override | تحدد هذه السمة ما إذا كان الصوت سيعيد تشغيل نفسه حتى يحدث حدث صوتي التالي في عرض الشرائح. كتابة **bool**. |
| void [set_SoundMode](./set_soundmode/)([TransitionSoundMode](../transitionsoundmode/)) override | يضبط أو يعيد وضع الصوت لانتقال الشريحة. كتابة [TransitionSoundMode](../transitionsoundmode/). |
| void [set_SoundName](./set_soundname/)([System::String](../../system/string/)) override | يحدد اسمًا قابلًا للقراءة البشرية لصوت الانتقال. يجب تعيين [ISlideShowTransition::set_Sound](../../aspose.slides/islideshowtransition/set_sound/) للحصول على اسم الصوت أو تعيينه. يكتب [System::String](../../system/string/). |
| void [set_Speed](./set_speed/)([TransitionSpeed](../transitionspeed/)) override | يحدد سرعة الانتقال التي ستُستخدم عند الانتقال من الشريحة الحالية إلى التالية. كتابة [TransitionSpeed](../transitionspeed/). |
| void [set_Type](./set_type/)([TransitionType](../transitiontype/)) override | نوع الانتقال. كتابة [TransitionType](../transitiontype/). |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | يضبط الوسيط القالب الـ n't على مؤشر ضعيف (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجعية المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجعية المشتركة. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجعية المشتركة. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مقابل طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى نص. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل تعبير C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجعية الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجعية الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع الهياكل الداخلية للبيانات. |

## أنظر أيضًا

* الفئة [DomObject](../../aspose.slides/domobject/)
* الفئة [ISlideShowTransition](../../aspose.slides/islideshowtransition/)
* مساحة الاسم [Aspose::Slides::SlideShow](../)
* المكتبة [Aspose.Slides](../../)