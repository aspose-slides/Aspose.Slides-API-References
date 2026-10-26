---
title: BulletFormat
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يمثل خصائص تنسيق نقاط الفقرة.
type: docs
weight: 248
url: /ar/aspose.slides/bulletformat/
---
## BulletFormat فئة

يمثل خصائص تنسيق نقاط الفقرة.

```cpp
class BulletFormat : public Aspose::Slides::PVIObject,
                     public Aspose::Slides::IBulletFormat
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| void [ApplyDefaultParagraphIndentsShifts](./applydefaultparagraphindentsshifts/)() override | يضبط التحولات غير الصفرية الافتراضية للمسافات الفعالة للفقرات Indent و MarginLeft عندما تكون النقاط مفعلة (كما تفعل PowerPoint إذا تم تمكين نقاط/ترقيم الفقرات فيه). إذا تم تعطيل النقاط، فإنها تعيد فقط تعيين Indent و MarginLeft للفقرات (كما تفعل PowerPoint إذا تم تعطيل نقاط/ترقيم الفقرات فيه). تُطبق تحولات المسافات بالنسبة إلى سياق النقطة الحالي - IBulletFormat::get(set)_Type، .NumberedBulletStyle و FontHeight للجزء الأول. تُطبق التحولات غير الصفرية على Indent و MarginLeft الفعليين للفقرة الحالية (لتكون القيم الناتجة قيمًا محلية). |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | يقارن مع الكائن المحدد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة نقاط عائمة بأسلوب C# حيث تُعتبر NaN اثنان متساويتين رغم أنه وفقًا لـ IEC 60559:1989 لا تكون NaN مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة نقاط عائمة بأسلوب C# حيث تُ considered NaN اثنان متساويتين رغم أنه وفقًا لـ IEC 60559:1989 لا تكون NaN مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| char16_t [get_Char](./get_char/)() override | يرجع حرف النقطة لفقرة دون توريث. قراءة **wchar_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_Color](./get_color/)() override | يرجع تنسيق اللون لنقطة فقرة دون توريث. قراءة فقط [IColorFormat](../icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_Font](./get_font/)() override | يرجع خط النقطة لفقرة دون توريث. قراءة [IFontData](../ifontdata/). |
| **float** [get_Height](./get_height/)() override | يرجع ارتفاع النقطة لفقرة دون توريث. قيمة std::numeric_limits<float>::quiet_NaN() تحدد أن النقطة تورث الارتفاع من الجزء الأول في الفقرة. قراءة **float**. |
| [NullableBool](../nullablebool/) [get_IsBulletHardColor](./get_isbullethardcolor/)() override | يحدد ما إذا كانت النقطة لها لون خاص أو ترثه من الجزء الأول في الفقرة. **[NullableBool::True](../nullablebool/)** إذا كان للنقطة لون خاص و **[NullableBool::False](../nullablebool/)** إذا كانت ترث اللون من الجزء الأول في الفقرة. قراءة [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_IsBulletHardFont](./get_isbullethardfont/)() override | يحدد ما إذا كانت النقطة لها خط خاص أو ترثه من الجزء الأول في الفقرة. **[NullableBool::True](../nullablebool/)** إذا كان للنقطة خط خاص و **[NullableBool::False](../nullablebool/)** إذا كانت ترث الخط من الجزء الأول في الفقرة. قراءة [NullableBool](../nullablebool/). |
| **int16_t** [get_NumberedBulletStartWith](./get_numberedbulletstartwith/)() override | يرجع الرقم الأول المستخدم لمجموعة من النقاط المرقمة دون توريث. قراءة **int16_t**. |
| [Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/) [get_NumberedBulletStyle](./get_numberedbulletstyle/)() override | يرجع نمط النقطة المرقمة دون توريث. قراءة [Slides::NumberedBulletStyle](../numberedbulletstyle/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | يرجع كائن Parent_Immediate. قراءة فقط [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | يرجع الـ[IPresentationComponent](../ipresentationcomponent/) الأب. قراءة فقط [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() override | يرجع الصورة المستخدمة كنقطة في فقرة دون توريث. قراءة فقط [ISlidesPicture](../islidespicture/). |
| [BulletType](../bullettype/) [get_Type](./get_type/)() override | يرجع نوع النقطة لفقرة دون توريث. قراءة [BulletType](../bullettype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبطة بالكائن. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormatEffectiveData](../ibulletformateffectivedata/)\> [GetEffective](./geteffective/)() override | يحصل على بيانات تنسيق النقطة الفعّالة مع تطبيق التوريث. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | يرجع رمز الهاش. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تماثل استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق إذا كان الكائن يمثل مثيلًا للنوع المُوصف بـ targetType. تماثل عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | يُنفّذ قفل عبارة C# lock(). نادِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تماثل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويتيح إنشاء نسخ للفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويتيح إنشاء نسخ للفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن نوع القيمة بـ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_Char](./set_char/)(char16_t) override | يضبط حرف النقطة لفقرة دون توريث. كتابة **wchar_t**. |
| void [set_Font](./set_font/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | يضبط خط النقطة لفقرة دون توريث. كتابة [IFontData](../ifontdata/). |
| void [set_Height](./set_height/)(**float**) override | يضبط ارتفاع النقطة لفقرة دون توريث. قيمة std::numeric_limits<float>::quiet_NaN() تحدد أن النقطة تورث الارتفاع من الجزء الأول في الفقرة. كتابة **float**. |
| void [set_IsBulletHardColor](./set_isbullethardcolor/)([NullableBool](../nullablebool/)) override | يحدد ما إذا كانت النقطة لها لون خاص أو ترثه من الجزء الأول في الفقرة. **[NullableBool::True](../nullablebool/)** إذا كان للنقطة لون خاص و **[NullableBool::False](../nullablebool/)** إذا كانت ترث اللون من الجزء الأول في الفقرة. كتابة [NullableBool](../nullablebool/). |
| void [set_IsBulletHardFont](./set_isbullethardfont/)([NullableBool](../nullablebool/)) override | يحدد ما إذا كانت النقطة لها خط خاص أو ترثه من الجزء الأول في الفقرة. **[NullableBool::True](../nullablebool/)** إذا كان للنقطة خط خاص و **[NullableBool::False](../nullablebool/)** إذا كانت ترث الخط من الجزء الأول في الفقرة. كتابة [NullableBool](../nullablebool/). |
| void [set_NumberedBulletStartWith](./set_numberedbulletstartwith/)(**int16_t**) override | يضبط الرقم الأول المستخدم لمجموعة من النقاط المرقمة دون توريث. كتابة **int16_t**. |
| void [set_NumberedBulletStyle](./set_numberedbulletstyle/)([Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/)) override | يضبط نمط النقطة المرقمة دون توريث. كتابة [Slides::NumberedBulletStyle](../numberedbulletstyle/). |
| void [set_Type](./set_type/)([BulletType](../bullettype/)) override | يضبط نوع النقطة لفقرة دون توريث. كتابة [BulletType](../bullettype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب الـ n كإشارة ضعيفة (بدلاً من مشتركة). يتيح تبديل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويُعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تماثل طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يفك القفل لبيان C# lock(). نادِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |
## انظر أيضًا

* الفئة [PVIObject](../pviobject/)
* الفئة [IBulletFormat](../ibulletformat/)
* النطاق [Aspose::Slides](../)
* المكتبة [Aspose.Slides](../../)