---
title: Object
second_title: Aspose.Slides لواجهة برمجة التطبيقات للـ C++
description: فئة أساسية تتيح استخدام الطرق المتاحة لفئة System.Object في C#. يجب أن ترث جميع الفئات غير البسيطة المستخدمة في بيئة الترجمة منها.
type: docs
weight: 1132
url: /ar/system/object/
---
## فئة الكائن


الفئة الأساسية التي تتيح استخدام الطرق المتاحة لفئة [System.Object](./) في C#. يجب أن ترث جميع الفئات غير البسيطة المستخدمة في بيئة الترجمة منها.

```cpp
class Object
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](./equals/)([ptr](./ptr/)) | Compares objects using C# [Object.Equals](./equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](./equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](./equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](./fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| Detail::SmartPtrCounter * [GetCounter](./getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](./gethashcode/)() const | Analog of C# [Object.GetHashCode()](./gethashcode/) method. Enables hashing of custom objects. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](./gettype/) call. |
| virtual **bool** [Is](./is/)(const [TypeInfo](../typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| void [Lock](./lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../lockcontext/) sentry object. |
| virtual [ptr](./ptr/) [MemberwiseClone](./memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](./memberwiseclone/) method. Enables cloning custom types. |
|  [Object](./object/)() | Creates object. Initializes all internal data structures. |
|  [Object](./object/)([Object](./) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Object](./)\& [operator=](./operator_equal/)([Object](./) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| static **bool** [ReferenceEquals](./referenceequals/)([ptr](./ptr/) const\&, [ptr](./ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](./referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specialization of [Object::ReferenceEquals](./referenceequals/) for case of strings. |
| int [RemovedSharedRefs](./removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| virtual void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](./sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](./) * [SharedRefAdded](./sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](./sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual [String](../string/) [ToString](./tostring/)() const | Analog of C# [Object.ToString()](./tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Implements C# typeof([System.Object](./)) construct. |
| void [Unlock](./unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](./weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](./weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual  [~Object](./~object/)() | Destroys object. Frees all internal data structures. |

## تعريفات الأنواع

| تعريف النوع | الوصف |
| --- | --- |
| [ptr](./ptr/) | Alias for smart pointer type. |

## ملاحظات


بالإضافة إلى الطرق المتاحة في فئة C# [System.Object](./)، فإنها تتيح أيضًا دعم بعض المفاهيم الخاصة ببيئة الكود المترجمة. يشمل ذلك عدّ المراجع المستخدم من قبل فئات المؤشرات الذكية ([System::SmartPtr](../smartptr/), [System::WeakPtr](../weakptr/), [System::DynamicWeakPtr](../dynamicweakptr/)) وخدمات أخرى متعلقة بإدارة الذاكرة، التصحيح، إلخ.

كل [Object](./) يحتوي على عدّادين للمرجع: عدّاد مرجع مشترك وعدّاد مرجع ضعيف. يُخزن عدّاد المرجع الضعيف دائمًا في هيكل بيانات منفصل بدلاً من داخل [Object](./) نفسه، مما يسمح للمؤشرات الضعيفة بالبقاء بعد حذف الكائن المشار إليه. يُخزن عدّاد المرجع الذكي إما داخل الكائن نفسه أو في نفس الهيكل المنفصل، حسب حالة الماكرو ENABLE_EXTERNAL_REFCOUNT. بشكل افتراضي، يكون مُفعلاً في بنى التصحيح ومُعطلاً في بنى الإصدار. إذا كان عدّاد المؤشر الذكي مخزنًا داخل الكائن نفسه، يتم إنشاء هيكل البيانات المنفصل فقط إذا وجدت مؤشرات ضعيفة إلى الكائن. وإلا، يتم إنشاؤه بجانب الكائن نفسه.

جميع المؤشرات الذكية تستخدم هذين عدّادي المرجع وتساهم في مجموعة الملكية الواحدة والفريدة.

إذا تم إنشاء فئة فرعية [Object](./) على المكدس، لا يمكن إنشاء مؤشرات ذكية لها، وإلا ستظهر مشكلة حذف من المكدس.

يمكن تخصيص هذا النوع إما على المكدس كنوع قيمة أو على الكومة باستخدام الدالة [System::MakeObject()](../makeobject/). بمجرد تخصيص الكائن، لا تخلط بين هاتين الحالتين: وجود مؤشرات [SmartPtr](../smartptr/) إلى كائنات مخصصة على المكدس محظور تمامًا. 

## انظر أيضا

* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)