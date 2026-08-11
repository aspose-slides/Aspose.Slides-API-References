---
title: BufferedStream()
second_title: Aspose.Slides للغة C++ مرجع API
description: يقوم بإنشاء كائن BufferedStream يغلف الدفق المحدد ويستخدم مخزنًا مؤقتًا طوله 4096 بايت.
type: docs
weight: 1
url: /ar/system.io/bufferedstream/bufferedstream/
---
## BufferedStream::BufferedStream(const SharedPtr\<Stream\>\&) المُنشئ

يقوم بإنشاء كائن [BufferedStream](../) يغلف الدفق المحدد ويستخدم مخزنًا مؤقتًا بطول 4096 بايت.

```cpp
System::IO::BufferedStream::BufferedStream(const SharedPtr<Stream> &stream)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | الكائن الأساسي [Stream](../../stream/) |
| bufferSize | int | حجم المخزن المؤقت بالبايت |

## BufferedStream::BufferedStream(const SharedPtr\<Stream\>\&, int) المُنشئ

يقوم بإنشاء كائن [BufferedStream](../) يغلف الدفق المحدد ويستخدم مخزنًا مؤقتًا بالحجم المحدد.

```cpp
System::IO::BufferedStream::BufferedStream(const SharedPtr<Stream> &stream, int bufferSize)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | الكائن الأساسي [Stream](../../stream/) |
| bufferSize | int | حجم المخزن المؤقت بالبايت |

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* الفئة [Stream](../../stream/)
* الفئة [BufferedStream](../)
* النطاق [System::IO](../../)
* المكتبة [Aspose.Slides](../../../)