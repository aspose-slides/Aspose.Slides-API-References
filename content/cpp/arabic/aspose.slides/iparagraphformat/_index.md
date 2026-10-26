---
title: IParagraphFormat
second_title: مرجع API لـ Aspose.Slides للغة C++
description: هذه الفئة تحتوي على خصائص تنسيق الفقرة. على عكس IParagraphFormatEffectiveData، جميع خصائص هذه الفئة قابلة للكتابة.
type: docs
weight: 3147
url: /ar/aspose.slides/iparagraphformat/
---
## IParagraphFormat فئة


هذه الفئة تحتوي على خصائص تنسيق الفقرة. على عكس [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)، جميع خصائص هذه الفئة قابلة للكتابة.

```cpp
class IParagraphFormat : public virtual System::Object
```

## طرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaNان اثنان متساويتين على الرغم من أن معيار IEC 60559:1989 يُشير إلى أن NaN لا يساوي أي قيمة، بما فيها NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaNان اثنان متساويتين على الرغم من أن معيار IEC 60559:1989 يُشير إلى أن NaN لا يساوي أي قيمة، بما فيها NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() | يُعيد محاذاة النص في فقرة دون وراثة. قراءة [TextAlignment](../textalignment/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormat](../ibulletformat/)\> [get_Bullet](./get_bullet/)() | يُعيد تنسيق الرصاص للفقرة. قراءة فقط [IBulletFormat](../ibulletformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\> [get_DefaultPortionFormat](./get_defaultportionformat/)() | يُعيد تنسيق الجزء الافتراضي لفقرة. لا يتم تطبيق الوراثة. قراءة فقط [IPortionFormat](../iportionformat/). |
| virtual **float** [get_DefaultTabSize](./get_defaulttabsize/)() | يُعيد حجم التبويب الافتراضي دون وراثة. قراءة **float**. |
| virtual **int16_t** [get_Depth](./get_depth/)() | يُعيد عمق الفقرة. القيمة 0 تعني قيمة غير معرفة. قراءة **int16_t**. |
| virtual [NullableBool](../nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() | يحدد ما إذا كان يتم استخدام فاصل سطر شرق آسيوي في الفقرة. لا يتم تطبيق الوراثة. قراءة [NullableBool](../nullablebool/). |
| virtual [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() | يُعيد محاذاة الخط في فقرة دون وراثة. قراءة [Slides::FontAlignment](../fontalignment/). |
| virtual [NullableBool](../nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() | يحدد ما إذا كان يتم استخدام علامات الترقيم المتدلية في الفقرة. لا يتم تطبيق الوراثة. قراءة [NullableBool](../nullablebool/). |
| virtual **float** [get_Indent](./get_indent/)() | يُعيد إزاحة السطر الأول/الإزاحة المتدلية للفقرة دون وراثة. يمكن تعريف الإزاحة المتدلية بقيم سلبية. قراءة **float**. |
| virtual [NullableBool](../nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() | يحدد ما إذا كان يتم استخدام فاصل سطر لاتيني في الفقرة. لا يتم تطبيق الوراثة. قراءة [NullableBool](../nullablebool/). |
| virtual **float** [get_MarginLeft](./get_marginleft/)() | يُعيد الهامش الأيسر في فقرة دون وراثة. قراءة **float**. |
| virtual **float** [get_MarginRight](./get_marginright/)() | يُعيد الهامش الأيمن في فقرة دون وراثة. قراءة **float**. |
| virtual [NullableBool](../nullablebool/) [get_RightToLeft](./get_righttoleft/)() | يحدد ما إذا كانت الكتابة من اليمين إلى اليسار تُستخدم في الفقرة. لا يتم تطبيق الوراثة. قراءة [NullableBool](../nullablebool/). |
| virtual **float** [get_SpaceAfter](./get_spaceafter/)() | يُعيد مقدار المسافة بعد السطر الأخير في فقرة دون وراثة. القيمة الإيجابية تحدد نسبة حجم الخط التي يجب أن تكون عليها المسافة البيضاء. القيمة السلبية تحدد حجم المسافة البيضاء بالنقاط. قراءة **float**. |
| virtual **float** [get_SpaceBefore](./get_spacebefore/)() | يُعيد مقدار المسافة قبل السطر الأول في فقرة دون وراثة. القيمة الإيجابية تحدد نسبة حجم الخط التي يجب أن تكون عليها المسافة البيضاء. القيمة السلبية تحدد حجم المسافة البيضاء بالنقاط. قراءة **float**. |
| virtual **float** [get_SpaceWithin](./get_spacewithin/)() | يُعيد مقدار المسافة بين الأسطر الأساسية في فقرة. القيمة الإيجابية تعني نسبة مئوية، السلبية تعني الحجم بالنقاط. لا يتم تطبيق الوراثة. قراءة **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\> [get_Tab](./get_tab/)(**int32_t**) | يُعيد التبويب لفقرة عند الفهرس المحدد. لا يتم تطبيق الوراثة. قراءة فقط [Aspose::Slides::ITab](../itab/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../itabcollection/)\> [get_Tabs](./get_tabs/)() | يُعيد تبويبات الفقرة. لا يتم تطبيق الوراثة. قراءة فقط [ITabCollection](../itabcollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على هيكل بيانات عداد المرجع المرتبط بالكائن. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)\> [GetEffective](./geteffective/)() | يحصل على بيانات تنسيق الفقرة الفعلية مع تطبيق الوراثة. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يمكّن التجزئة للكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. نظير عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل عبارة C# lock(). استدعِ مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يمكّن استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويمكّن إنشاء نسخة من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويمكّن إنشاء نسخة من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_Alignment](./set_alignment/)([TextAlignment](../textalignment/)) | يُعيّن محاذاة النص في فقرة دون وراثة. كتابة [TextAlignment](../textalignment/). |
| virtual void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) | يُعيّن حجم التبويب الافتراضي دون وراثة. كتابة **float**. |
| virtual void [set_Depth](./set_depth/)(**int16_t**) | يُعيّن عمق الفقرة. القيمة 0 تعني قيمة غير معرفة. كتابة **int16_t**. |
| virtual void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../nullablebool/)) | يحدد ما إذا كان يتم استخدام فاصل سطر شرق آسيوي في الفقرة. لا يتم تطبيق الوراثة. كتابة [NullableBool](../nullablebool/). |
| virtual void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../fontalignment/)) | يُعيّن محاذاة الخط في فقرة دون وراثة. كتابة [Slides::FontAlignment](../fontalignment/). |
| virtual void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../nullablebool/)) | يحدد ما إذا كان يتم استخدام علامات الترقيم المتدلية في الفقرة. لا يتم تطبيق الوراثة. كتابة [NullableBool](../nullablebool/). |
| virtual void [set_Indent](./set_indent/)(**float**) | يُعيّن إزاة السطر الأول/الإزاحة المتدلية للفقرة دون وراثة. يمكن تعريف الإزاحة المتدلية بقيم سلبية. كتابة **float**. |
| virtual void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../nullablebool/)) | يحدد ما إذا كان يتم استخدام فاصل سطر لاتيني في الفقرة. لا يتم تطبيق الوراثة. كتابة [NullableBool](../nullablebool/). |
| virtual void [set_MarginLeft](./set_marginleft/)(**float**) | يُعيّن الهامش الأيسر في فقرة دون وراثة. كتابة **float**. |
| virtual void [set_MarginRight](./set_marginright/)(**float**) | يُعيّن الهامش الأيمن في فقرة دون وراثة. كتابة **float**. |
| virtual void [set_RightToLeft](./set_righttoleft/)([NullableBool](../nullablebool/)) | يحدد ما إذا كانت الكتابة من اليمين إلى اليسار تُستخدم في الفقرة. لا يتم تطبيق الوراثة. كتابة [NullableBool](../nullablebool/). |
| virtual void [set_SpaceAfter](./set_spaceafter/)(**float**) | يُعيّن مقدار المسافة بعد السطر الأخير في فقرة دون وراثة. القيمة الإيجابية تحدد نسبة حجم الخط التي يجب أن تكون عليها المسافة البيضاء. القيمة السلبية تحدد حجم المسافة البيضاء بالنقاط. كتابة **float**. |
| virtual void [set_SpaceBefore](./set_spacebefore/)(**float**) | يُعيّن مقدار المسافة قبل السطر الأول في فقرة دون وراثة. القيمة الإيجابية تحدد نسبة حجم الخط التي يجب أن تكون عليها المسافة البيضاء. القيمة السلبية تحدد حجم المسافة البيضاء بالنقاط. كتابة **float**. |
| virtual void [set_SpaceWithin](./set_spacewithin/)(**float**) | يُعيّن مقدار المسافة بين الأسطر الأساسية في فقرة. القيمة الإيجابية تعني نسبة مئوية، السلبية تعني الحجم بالنقاط. لا يتم تطبيق الوراثة. كتابة **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يُعيّن الوسيط القالب الـ n كإشارة ضعيفة (بدلاً من المشتركة). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يمكّن تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل عبارة C# lock(). استدعِ مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا يجب استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا يجب استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |
## ملاحظات


تُستخدم هذه الفئة لإرجاع ومعالجة خصائص تنسيق الفقرة المحددة للفقرة المعينة. يعني هذا أنه لا يتم تطبيق الوراثة عند الحصول على القيم، لذا في معظم الحالات ستحصل على قيم تعني "غير معرفة".

للحصول على قيم معلمات التنسيق الفعالة بما في ذلك الموروثة، تحتاج إلى استخدام طريقة [IParagraphFormat::GetEffective](./geteffective/) التي تُعيد كائن [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/).

## راجع أيضًا

* فئة [Object](../../system/object/)
* نطاق [Aspose::Slides](../)
* مكتبة [Aspose.Slides](../../)