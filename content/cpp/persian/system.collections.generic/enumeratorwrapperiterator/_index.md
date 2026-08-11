---
title: EnumeratorWrapperIterator
second_title: Aspose.Slides برای C++ مرجع API
description: Iterator که enumerator پیش‌ساخته را می‌پیچد و تمام فراخوانی‌ها را به آن هدایت می‌کند.
type: docs
weight: 196
url: /fa/system.collections.generic/enumeratorwrapperiterator/
---
## EnumeratorWrapperIterator کلاس


Iterator که enumerator پیش‌ساخته را می‌پیچد و تمام فراخوانی‌ها را به آن هدایت می‌کند.

```cpp
template<typename Element>class EnumeratorWrapperIterator : public System::Details::VirtualizedIteratorBase<Element>
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Element | نوع Element. |
## متدها

| متد | توضیح |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<Element\> * [CloneIterator](./cloneiterator/)() const override | یک نسخهٔ کپی از تکرارگر فعلی ایجاد می‌کند. |
|  [EnumeratorWrapperIterator](./enumeratorwrapperiterator/)(const [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<Element\>\>\&) |  |
| void [IncrementIterator](./incrementiterator/)() override | تکرارگر را یک قدم به جلو منتقل می‌کند. باید m_is_end و m_pointer را به‌روز کند. |
| **bool** [IteratorEquals](./iteratorequals/)(System::Details::VirtualizedIteratorBase\<Element\> *) const override | بررسی می‌کند دو تکرارگر به یک آیتم اشاره می‌کنند یا نه. |
| virtual  [~EnumeratorWrapperIterator](./~enumeratorwrapperiterator/)() | Destructor. |

## موارد مرتبط

* Namespace [System::Collections::Generic](../)
* Library [Aspose.Slides](../../)