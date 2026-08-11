---
title: IColorSchemeEffectiveData
second_title: مرجع API Aspose.Slides للغة C++
description: كائن غير قابل للتغيير يحتوي على خصائص نظام الألوان الفعّال.
type: docs
weight: 157
url: /ar/aspose.slides.theme/icolorschemeeffectivedata/
---
## IColorSchemeEffectiveData فئة

كائن غير قابل للتغيير يحتوي على خصائص نظام الألوان الفعّال.

```cpp
class IColorSchemeEffectiveData : public virtual System::Object
```

## طرق

| طريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سلوكيات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر القيمتين NaN متساويتين حتى وإن كان وفقًا لـ IEC 60559:1989 لا يكون NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر القيمتين NaN متساويتين حتى وإن كان وفقًا لـ IEC 60559:1989 لا يكون NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لغرض داخلي فقط. |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Accent1](./get_accent1/)() | اللون الأول المميز في المخطط. للقراءة فقط [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Accent2](./get_accent2/)() | اللون الثاني المميز في المخطط. للقراءة فقط [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Accent3](./get_accent3/)() | اللون الثالث المميز في المخطط. للقراءة فقط [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Accent4](./get_accent4/)() | اللون الرابع المميز في المخطط. للقراءة فقط [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Accent5](./get_accent5/)() | اللون الخامس المميز في المخطط. للقراءة فقط [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Accent6](./get_accent6/)() | اللون السادس المميز في المخطط. للقراءة فقط [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Dark1](./get_dark1/)() | اللون الداكن الأول في المخطط. للقراءة فقط [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Dark2](./get_dark2/)() | اللون الداكن الثاني في المخطط. للقراءة فقط [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_FollowedHyperlink](./get_followedhyperlink/)() | لون الروابط التي تم زيارتها. للقراءة فقط [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Hyperlink](./get_hyperlink/)() | لون الروابط. للقراءة فقط [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Light1](./get_light1/)() | اللون الفاتح الأول في المخطط. للقراءة فقط [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Light2](./get_light2/)() | اللون الفاتح الثاني في المخطط. للقراءة فقط [System::Drawing::Color](../../system.drawing/color/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تناظر طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تناظر استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [idx_get](./idx_get/)([ColorSchemeIndex](../../aspose.slides/colorschemeindex/)) | يحصل على العنصر في الفهرس المحدد. للقراءة فقط [System::Drawing::Color](../../system.drawing/color/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. تناظر عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ تأمين عبارة C# lock(). استدعِ مباشرةً أو استخدم الكائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تناظر طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ الكائن. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بنسخ بناء الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بنسخ بناء الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بواسطة المرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بواسطة المرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن بالمرجع كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدد المراجع المشتركة بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الحجة n'th للقالب إلى مؤشر ضعيف (بدلاً من المشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المراجع المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المراجع المشتركة. لا ينبغي استدعاؤه مباشرةً؛ استخدم مؤشرات ذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويُعيد عداد المراجع المشتركة. لا ينبغي استدعاؤه مباشرةً؛ استخدم مؤشرات ذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تناظر طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ فك تأمين عبارة C# lock(). استدعِ مباشرةً أو استخدم الكائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم مؤشرات ذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم مؤشرات ذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |
## ملاحظات

تُستخدم هذه الفئة كجزء من [IThemeEffectiveData](../ithemeeffectivedata/). 
## انظر أيضاً

* فئة [Object](../../system/object/)
* نطاق [Aspose::Slides::Theme](../)
* مكتبة [Aspose.Slides](../../)