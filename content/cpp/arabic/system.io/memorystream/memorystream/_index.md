---
title: MemoryStream()
second_title: مرجع API Aspose.Slides للغة C++
description: ينشئ مثيلًا جديدًا من الفئة MemoryStream بسعة أولية تساوي 0.
type: docs
weight: 1
url: /ar/system.io/memorystream/memorystream/
---
## MemoryStream::MemoryStream() منشئ

إنشاء مثيل جديد من الفئة [MemoryStream](../) بسعة أولية تساوي 0.

```cpp
System::IO::MemoryStream::MemoryStream()
```

## MemoryStream::MemoryStream(int) منشئ

إنشاء مثيل جديد من الفئة [MemoryStream](../) الذي يمثل تدفقًا يعتمد على مخزن ذاكرة بالحجم المحدد.

```cpp
System::IO::MemoryStream::MemoryStream(int capacity_)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| capacity_ | int | حجم بايتات مخزن الذاكرة المرتبط بالتدفق الذي يمثله الكائن الذي يتم إنشاؤه |

## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, bool) منشئ

إنشاء مثيل جديد من الفئة [MemoryStream](../) الذي يمثل تدفقًا ذا ذاكرة متصلًا بالمخزن المحدد. معلمة تحدد ما إذا كان التدفق قابلًا للكتابة.

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, bool writable=1)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | مصفوفة بايت تُستخدم كمخزن ذاكرة سيُستند إليه التدفق الذي يمثله الكائن الذي يتم إنشاؤه |
| writable | **bool** | يحدد ما إذا كان يجب أن يكون التدفق قابلًا للكتابة |

## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, int, int, bool, bool) منشئ

إنشاء مثيل جديد من الفئة [MemoryStream](../) الذي يمثل تدفقًا ذا ذاكرة متصلًا بقطاع من المخزن المحدد يبدأ عند الفهرس المحدد ويشمل عددًا محددًا من العناصر. المعلمات تحدد ما إذا كان التدفق قابلًا للكتابة وما إذا كان يمكن استدعاء الطريقة GetBytes().

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, int index, int count, bool writable=1, bool publiclyVisible=false)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | مصفوفة بايت يُستخدم جزء منها كمخزن ذاكرة سيُستند إليه التدفق الذي يمثله الكائن الذي يتم إنشاؤه |
| index | int | فهرس يبدأ من الصفر للعنصر في **content** الذي يبدأ عنده القطاع |
| count | int | عدد العناصر في **content** المشمولة في القطاع |
| writable | **bool** | يحدد ما إذا كان يجب أن يكون التدفق قابلًا للكتابة |
| publiclyVisible | **bool** | يحدد ما إذا كان ينبغي إتاحة مخزن الذاكرة الأساسي للمتصل بطريقة GetByte() |

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* الفئة [MemoryStream](../)
* مساحة الأسماء [System::IO](../../)
* المكتبة [Aspose.Slides](../../../)