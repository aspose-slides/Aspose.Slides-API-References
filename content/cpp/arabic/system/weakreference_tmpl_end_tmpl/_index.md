---
title: WeakReference<>
second_title: مرجع Aspose.Slides لـ C++ API
description: يمثل مرجعًا ضعيفًا، يشير إلى كائن مع السماح بحذف ذلك الكائن.
type: docs
weight: 1522
url: /ar/system/weakreference_tmpl_end_tmpl/
---
## فئة WeakReference<> 

يمثل مرجعًا ضعيفًا، يشير إلى كائن مع السماح بحذف ذلك الكائن.

```cpp
class WeakReference<> : public WeakReference<System::Object>
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| **bool** [get_IsAlive](./get_isalive/)() const | يحصل على إشارة ما إذا كان الكائن المشار إليه بواسطة كائن WeakReference الحالي قد تم حذفه. |
| const [WeakPtr](../weakptr/)\<[Object](../object/)\>\& [get_Target](./get_target/)() const | يحصل على الكائن (الهدف) المشار إليه بواسطة كائن WeakReference الحالي. |
| void [set_Target](./set_target/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | يحدد الكائن (الهدف) المشار إليه بواسطة كائن WeakReference الحالي. |
|  [WeakReference](./weakreference/)() | منشئ افتراضي. |
|  [WeakReference](./weakreference/)(std::nullptr_t) | منشئ من nullptr. |
|  [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | ينشئ نسخة جديدة من فئة WeakReference، يشير إلى الكائن المحدد. |
|  [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&, **bool**) | ينشئ نسخة جديدة من فئة WeakReference، يشير إلى الكائن المحدد. |
## انظر أيضًا

* مساحة الاسم [System](../)
* المكتبة [Aspose.Slides](../../)