---
title: ModernComment
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل تعليقا على شريحة.
type: docs
weight: 4512
url: /ar/aspose.slides/moderncomment/
---
## ModernComment فئة


يمثل تعليقا على شريحة.

```cpp
class ModernComment : public Aspose::Slides::Comment,
                      public Aspose::Slides::IModernComment
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام قواعد C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن الكائنات من نوع المرجع على نمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن الكائنات من نوع القيمة على نمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة على نمط C# حيث يُعتبر NaNانان متساويين على الرغم من أن IEC 60559:1989 تنص على أن NaN ليس مساويًا لأي قيمة، بما فيها NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة على نمط C# حيث يُعتبر NaNانان متساويين على الرغم من أن IEC 60559:1989 تنص على أن NaN ليس مساويًا لأي قيمة، بما فيها NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthor](../icommentauthor/)\> [get_Author](../comment/get_author/)() override | يعيد مؤلف التعليق. للقراءة فقط [ICommentAuthor](../icommentauthor/). |
| [System::DateTime](../../system/datetime/) [get_CreatedTime](../comment/get_createdtime/)() override | يعيد وقت إنشاء التعليق. ضبط هذه الخاصية إلى [DateTime::MinValue](../../system/datetime/minvalue/) يعني أنه لم يتم ضبط وقت التعليق. قراءة [System::DateTime](../../system/datetime/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\> [get_ParentComment](../comment/get_parentcomment/)() override | يحصل على التعليق الأصلي. قراءة [IComment](../icomment/). |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_Position](../comment/get_position/)() override | يعيد موضع التعليق على شريحة. قراءة [System::Drawing::PointF](../../system.drawing/pointf/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](./get_shape/)() override | يعيد الشكل المرتبط بالتعليق. للقراءة فقط [IShape](../ishape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_Slide](../comment/get_slide/)() override | يعيد الشريحة الأم للتعليق. للقراءة فقط [ISlide](../islide/). |
| [ModernCommentStatus](../moderncommentstatus/) [get_Status](./get_status/)() override | يحصل على حالة التعليق. قراءة [ModernCommentStatus](../moderncommentstatus/). |
| [System::String](../../system/string/) [get_Text](../comment/get_text/)() override | يعيد النص العادي لتعليق الشريحة. قراءة [System::String](../../system/string/). |
| **int32_t** [get_TextSelectionLength](./get_textselectionlength/)() override | يحصل على طول تحديد النص في إطار النص إذا كان التعليق مرتبطًا بـ [AutoShape](../autoshape/). قراءة **int32_t**. |
| **int32_t** [get_TextSelectionStart](./get_textselectionstart/)() override | يحصل على موضع البداية لتحديد النص في إطار النص إذا كان التعليق مرتبطًا بـ [AutoShape](../autoshape/). قراءة **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عدّاد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تماثل طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). تمكّن تجزئة الكائنات المخصَّصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تماثل استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. تماثل عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ جملة C# lock() للقفل. استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تماثل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). تمكّن استنساخ الأنواع المخصَّصة. |
|  [Object](../../system/object/object/)() | ينشئ الكائن. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | مُنشئ نسخ. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويمكّن بناؤه للصفوف الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل إسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويمكّن بناؤه للصفوف الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| void [Remove](../comment/remove/)() override | يزيل التعليق وجميع ردوده من المجموعة الأب. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدّاد المرجع المشترك بالقيمة المحددة. |
| void [set_CreatedTime](../comment/set_createdtime/)([System::DateTime](../../system/datetime/)) override | يضبط وقت إنشاء التعليق. ضبط هذه الخاصية إلى [DateTime::MinValue](../../system/datetime/minvalue/) يعني أنه لم يتم ضبط وقت التعليق. كتابة [System::DateTime](../../system/datetime/). |
| void [set_ParentComment](../comment/set_parentcomment/)([System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\>) override | يضبط التعليق الأب. كتابة [IComment](../icomment/). |
| void [set_Position](../comment/set_position/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | يضبط موضع التعليق على شريحة. كتابة [System::Drawing::PointF](../../system.drawing/pointf/). |
| void [set_Status](./set_status/)([ModernCommentStatus](../moderncommentstatus/)) override | يضبط حالة التعليق. كتابة [ModernCommentStatus](../moderncommentstatus/). |
| void [set_Text](../comment/set_text/)([System::String](../../system/string/)) override | يضبط النص العادي لتعليق الشريحة. كتابة [System::String](../../system/string/). |
| void [set_TextSelectionLength](./set_textselectionlength/)(**int32_t**) override | يضبط طول تحديد النص في إطار النص إذا كان التعليق مرتبطًا بـ [AutoShape](../autoshape/). كتابة **int32_t**. |
| void [set_TextSelectionStart](./set_textselectionstart/)(**int32_t**) override | يضبط موضع البداية لتحديد النص في إطار النص إذا كان التعليق مرتبطًا بـ [AutoShape](../autoshape/). كتابة **int32_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | اضبط الوسيط القالب الـ n'th كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتبديل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تماثل طريقة C# [Object.ToString()](../../system/object/tostring/). تمكّن تحويل الكائنات المخصَّصة إلى نص. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ جملة C# lock() لفك القفل. استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## ملاحظات



```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto newAuthor = pres->get_CommentAuthors()->AddAuthor(u"Some Author", u"SA");
auto modernComment = newAuthor->get_Comments()->AddModernComment(u"This is modern comment", slide, nullptr, PointF(100.0f, 100.0f), DateTime::get_Now());

pres->Save(u"output.pptx", SaveFormat::Pptx);
```




## انظر أيضًا

* فئة [Comment](../comment/)
* فئة [IModernComment](../imoderncomment/)
* مساحة الاسم [Aspose::Slides](../)
* مكتبة [Aspose.Slides](../../)