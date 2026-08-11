---
title: EnumeratorWrapperIterator
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: المكرّر الذي يلف المُعدِّد المُنشأ مسبقًا ويعيد توجيه جميع الاستدعاءات إليه.
type: docs
weight: 196
url: /ar/system.collections.generic/enumeratorwrapperiterator/
---
## EnumeratorWrapperIterator فئة


المُكرّر الذي يغلف المُعدِّد المُنشأ مسبقًا ويعيد توجيه جميع الاستدعاءات إليه.

```cpp
template<typename Element>class EnumeratorWrapperIterator : public System::Details::VirtualizedIteratorBase<Element>
```


### معلمات القالب

| Parameter | الوصف |
| --- | --- |
| Element | نوع العنصر. |
## الطرق

| Method | الوصف |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<Element\> * [CloneIterator](./cloneiterator/)() const override | ينسخ المُكرّر الحالي. |
|  [EnumeratorWrapperIterator](./enumeratorwrapperiterator/)(const [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<Element\>\>\&) |  |
| void [IncrementIterator](./incrementiterator/)() override | يحرك المُكرّر خطوة إلى الأمام. يجب تحديث m_is_end و m_pointer. |
| **bool** [IteratorEquals](./iteratorequals/)(System::Details::VirtualizedIteratorBase\<Element\> *) const override | يتحقق مما إذا كان المُكرّران يشيران إلى نفس العنصر. |
| virtual  [~EnumeratorWrapperIterator](./~enumeratorwrapperiterator/)() | المدمر. |

## انظر أيضًا

* نطاق [System::Collections::Generic](../)
* مكتبة [Aspose.Slides](../../)