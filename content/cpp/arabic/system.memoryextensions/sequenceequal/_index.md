---
title: SequenceEqual()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد ما إذا كان Spanان للقراءة فقط يحتويان على عناصر متطابقة بنفس الترتيب.
type: docs
weight: 326
url: /ar/system.memoryextensions/sequenceequal/
---
## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

يحدد ما إذا كان اثنان من ReadOnlySpans يحتويان على عناصر متماثلة بنفس الترتيب.

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &first, const ReadOnlySpan<T> &second)
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### وسيطات

| Parameter | Type | Description |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The first span to compare |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The second span to compare |

### قيمة الإرجاع

true إذا كان spans لها نفس الطول وجميع العناصر متساوية، false خلاف ذلك

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

يحدد ما إذا كان [Span](../../system/span/) و [ReadOnlySpan](../../system/readonlyspan/) يحتويان على عناصر متماثلة بنفس الترتيب.

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### وسيطات

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The [Span](../../system/span/) to compare |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The [ReadOnlySpan](../../system/readonlyspan/) to compare |

### قيمة الإرجاع

true إذا كان spans لها نفس الطول وجميع العناصر متساوية، false خلاف ذلك

## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) function

يحدد ما إذا كان اثنان من ReadOnlySpans يحتويان على عناصر متساوية باستخدام مقارن مخصص.

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |
| TComparer | The type of the comparer object |

### وسيطات

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The first span to compare |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The second span to compare |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Smart pointer to comparer object for element comparison |

### قيمة الإرجاع

true إذا كان spans لها نفس الطول و comparer يعتبر جميع العناصر متساوية، false خلاف ذلك

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) function

يحدد ما إذا كان [Span](../../system/span/) و [ReadOnlySpan](../../system/readonlyspan/) يحتويان على عناصر متساوية باستخدام مقارن مخصص.

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |
| TComparer | The type of the comparer object |

### وسيطات

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The [Span](../../system/span/) to compare |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The [ReadOnlySpan](../../system/readonlyspan/) to compare |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Smart pointer to comparer object for element comparison |

### قيمة الإرجاع

true إذا كان spans لها نفس الطول و comparer يعتبر جميع العناصر متساوية، false خلاف ذلك

## انظر أيضًا

* Typedef [SharedPtr](../../system/sharedptr/)
* فئة [ReadOnlySpan](../../system/readonlyspan/)
* فئة [Span](../../system/span/)
* نطاق [System::MemoryExtensions](../)
* مكتبة [Aspose.Slides](../../)