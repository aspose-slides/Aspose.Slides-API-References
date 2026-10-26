---
title: IBulletFormat
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل خصائص تنسيق رصاص الفقرة.
type: docs
weight: 1561
url: /ar/aspose.slides/ibulletformat/
---
## IBulletFormat فئة

Represents paragraph bullet formatting properties.

```cpp
class IBulletFormat : public virtual System::Object
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual void [ApplyDefaultParagraphIndentsShifts](./applydefaultparagraphindentsshifts/)() | يحدد الإزاحات غير الصفرية الافتراضية للمسافة البادئة الفعالة والهوامش اليسرى للفقرة عندما تكون الرصاصات مفعلة (مثل ما يفعله PowerPoint إذا تم تفعيل رصاصات/ترقيم الفقرة فيه). إذا تم تعطيل الرصاصات فقم بإعادة تعيين المسافة البادئة والهوامش اليسرى للفقرة فقط (مثل ما يفعله PowerPoint إذا تم تعطيل رصاصات/ترقيم الفقرة فيه). يتم تطبيق إزاحات البادئة فيما يتعلق بسياق الرصاص الحالي - IBulletFormat::get(set)_Type ، .NumberedBulletStyle و FontHeight للجزء الأول. يتم تطبيق إزاحات البادئة غير الصفرية على المسافة البادئة الفعالة والهوامش اليسرى للفقرة الحالية (جعل القيم الناتجة قيمًا محلية). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي على طراز C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي على طراز C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة على نمط C# حيث يُعتبر NaNانان متساويين على الرغم من أن IEC 60559:1989 تقول إن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة على نمط C# حيث يُعتبر NaNانان متساويين على الرغم من أن IEC 60559:1989 تقول إن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual char16_t [get_Char](./get_char/)() | يرجع حرف الرصاصة لفقرة دون وراثة. اقرأ **wchar_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_Color](./get_color/)() | يرجع تنسيق اللون لرصاصة فقرة دون وراثة. للقراءة فقط [IColorFormat](../icolorformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_Font](./get_font/)() | يرجع خط الرصاصة لفقرة دون وراثة. اقرأ [IFontData](../ifontdata/). |
| virtual **float** [get_Height](./get_height/)() | يرجع ارتفاع الرصاصة لفقرة دون وراثة. قيمة std::numeric_limits<float>::quiet_NaN() تحدد أن الرصاصة ترث الارتفاع من الجزء الأول في الفقرة. اقرأ **float**. |
| virtual [NullableBool](../nullablebool/) [get_IsBulletHardColor](./get_isbullethardcolor/)() | يحدّد ما إذا كانت الرصاصة لها لون خاص أو ترثه من الجزء الأول في الفقرة. **[NullableBool::True](../nullablebool/)** إذا كان للرصاصة لون خاص و **[NullableBool::False](../nullablebool/)** إذا ورثت الرصاصة اللون من الجزء الأول في الفقرة. اقرأ [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_IsBulletHardFont](./get_isbullethardfont/)() | يحدّد ما إذا كانت الرصاصة لها خط خاص أو ترثه من الجزء الأول في الفقرة. **[NullableBool::True](../nullablebool/)** إذا كان للرصاصة خط خاص و **[NullableBool::False](../nullablebool/)** إذا ورثت الرصاصة الخط من الجزء الأول في الفقرة. اقرأ [NullableBool](../nullablebool/). |
| virtual **int16_t** [get_NumberedBulletStartWith](./get_numberedbulletstartwith/)() | يرجع الرقم الأول المستخدم لمجموعة من الرصاصات المرقمة دون وراثة. اقرأ **int16_t**. |
| virtual [Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/) [get_NumberedBulletStyle](./get_numberedbulletstyle/)() | يرجع نمط الرصاصة المرقمة دون وراثة. اقرأ [NumberedBulletStyle](../numberedbulletstyle/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() | يرجع الصورة المستخدمة كرصاصة في فقرة دون وراثة. للقراءة فقط [ISlidesPicture](../islidespicture/). |
| virtual [BulletType](../bullettype/) [get_Type](./get_type/)() | يرجع نوع الرصاصة لفقرة دون وراثة. اقرأ [BulletType](../bullettype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormatEffectiveData](../ibulletformateffectivedata/)\> [GetEffective](./geteffective/)() | يحصل على بيانات تنسيق الرصاصة الفعّالة مع تطبيق الوراثة. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح إنشاء تجزئة للكائنات المخصّصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. نظير عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | يُنفّذ قفل جملة C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح نسخ الأنواع المخصّصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | بناء نسخة. لا ينسخ شيئًا، في الواقع، فقط يهيئ كائنًا جديدًا ويُمكّن بناء نسخ الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا، في الواقع، فقط يهيئ كائنًا جديدًا ويُمكّن بناء نسخ الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات حسب المرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات حسب المرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن نوع قيم مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدد المراجع المشتركة بالقيمة المحددة. |
| virtual void [set_Char](./set_char/)(char16_t) | يحدد حرف الرصاصة لفقرة دون وراثة. اكتب **wchar_t**. |
| virtual void [set_Font](./set_font/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | يحدد خط الرصاصة لفقرة دون وراثة. اكتب [IFontData](../ifontdata/). |
| virtual void [set_Height](./set_height/)(**float**) | يحدد ارتفاع الرصاصة لفقرة دون وراثة. قيمة std::numeric_limits<float>::quiet_NaN() تحدد أن الرصاصة ترث الارتفاع من الجزء الأول في الفقرة. اكتب **float**. |
| virtual void [set_IsBulletHardColor](./set_isbullethardcolor/)([NullableBool](../nullablebool/)) | يحدّد ما إذا كانت الرصاصة لها لون خاص أو ترثه من الجزء الأول في الفقرة. **[NullableBool::True](../nullablebool/)** إذا كان للرصاصة لون خاص و **[NullableBool::False](../nullablebool/)** إذا ورثت الرصاصة اللون من الجزء الأول في الفقرة. اكتب [NullableBool](../nullablebool/). |
| virtual void [set_IsBulletHardFont](./set_isbullethardfont/)([NullableBool](../nullablebool/)) | يحدّد ما إذا كانت الرصاصة لها خط خاص أو ترثه من الجزء الأول في الفقرة. **[NullableBool::True](../nullablebool/)** إذا كان للرصاصة خط خاص و **[NullableBool::False](../nullablebool/)** إذا ورثت الرصاصة الخط من الجزء الأول في الفقرة. اكتب [NullableBool](../nullablebool/). |
| virtual void [set_NumberedBulletStartWith](./set_numberedbulletstartwith/)(**int16_t**) | يحدد الرقم الأول المستخدم لمجموعة من الرصاصات المرقمة دون وراثة. اكتب **int16_t**. |
| virtual void [set_NumberedBulletStyle](./set_numberedbulletstyle/)([Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/)) | يحدد نمط الرصاصة المرقمة دون وراثة. اكتب [NumberedBulletStyle](../numberedbulletstyle/). |
| virtual void [set_Type](./set_type/)([BulletType](../bullettype/)) | يحدد نوع الرصاصة لفقرة دون وراثة. اكتب [BulletType](../bullettype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط النمطي الـ n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتبديل الإشارات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعدد المراجع المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدد المراجع المشتركة. لا يجب استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عدد المراجع المشتركة. لا يجب استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصّصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يُنفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يُنفّذ إلغاء قفل جملة C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدد المراجع الضعيفة. لا يجب استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عدد المراجع الضعيفة. لا يجب استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |
## انظر أيضًا

* الفئة [Object](../../system/object/)
* مساحة الاسم [Aspose::Slides](../)
* المكتبة [Aspose.Slides](../../)