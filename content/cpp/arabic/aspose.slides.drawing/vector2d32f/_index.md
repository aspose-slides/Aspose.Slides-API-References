---
title: Vector2d32f
second_title: مرجع API Aspose.Slides للغة C++
description: متجه ثنائي الأبعاد مع مكوّنات float
type: docs
weight: 53
url: /ar/aspose.slides.drawing/vector2d32f/
---
## Vector2d32f فئة

متجه ثنائي الأبعاد مع مكوّنات **float** 

```cpp
class Vector2d32f : public System::Object,
                    public System::Details::BoxableObjectBase
```

## الطرق

| Method | Description |
| --- | --- |
| **bool** [Equals](./equals/)(const [Vector2d32f](./)\&) |  |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بنمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث يُعتبر NaNان متساوين رغم أن معيار IEC 60559:1989 يوضح أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث يُعتبر NaNان متساوين رغم أن معيار IEC 60559:1989 يوضح أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عدّاد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تماثل طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصَّصة. |
| **double** [GetLength](./getlength/)() | احصل على الطول |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تماثل استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق ما إذا كان الكائن يمثل مثيلاً للنوع الموصوف بـ targetType. تماثل عامل C# 'is'. |
| **bool** [IsNull](./isnull/)() const |  |
| void [Lock](../../system/object/lock/)() | ينفّذ عملية القفل في عبارة C# lock(). استدعِه مباشرةً أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| static [Vector2d32f](./) [Max](./max/)([Vector2d32f](./), [Vector2d32f](./)) |  |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تماثل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصَّصة. |
| static [Vector2d32f](./) [Min](./min/)([Vector2d32f](./), [Vector2d32f](./)) |  |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويُمكّن إنشاء نسخة من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويُمكّن إنشاء نسخة من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يُقلّص عدّاد المرجع المشترك بالقيمة المحددة. |
| [Vector2d32f](./) [Scale](./scale/)(**float**, **float**) | تحجيم المتجه |
| [Vector2d32f](./) [Scale](./scale/)([Vector2d32f](./)) | تحجيم المتجه |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي n كمرجع ضعيف (بدلاً من المشترك). يتيح تحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلًا من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يُنقّص ويعيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلًا من ذلك. |
| void [SwapXY](./swapxy/)() | تبديل X و Y |
| [System::String](../../system/string/) [ToString](./tostring/)() const override | تماثل طريقة C# Object.ToString(). يتيح تحويل الكائنات المخصَّصة إلى سلسلة نصية. |
| [Vector2d64d](../vector2d64d/) [ToVector2d64d](./tovector2d64d/)() | إلى [Vector2d64d](../vector2d64d/) |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ عملية فك القفل في عبارة C# lock(). استدعِه مباشرةً أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
|  [Vector2d32f](./vector2d32f/)(**float**, **float**) | منشئ |
|  [Vector2d32f](./vector2d32f/)() |  |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلًا من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يُنقّص عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلًا من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## الحقول

| Field | Description |
| --- | --- |
| static [One](./one/) |  |
| static [Zero](./zero/) |  |

## انظر أيضا

* فئة [Object](../../system/object/)
* نطاق [Aspose::Slides::Drawing](../)
* مكتبة [Aspose.Slides](../../)