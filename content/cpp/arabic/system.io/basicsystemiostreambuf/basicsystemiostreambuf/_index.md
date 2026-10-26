---
title: BasicSystemIOStreamBuf()
second_title: Aspose.Slides لـ C++ مرجع API
description: ينشئ مثالًا جديدًا من BasicSystemIOStreamBuf.
type: docs
weight: 14
url: /ar/system.io/basicsystemiostreambuf/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf() منشئ

ينشئ مثالًا جديدًا من [BasicSystemIOStreamBuf](../).

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf()
```

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(const SharedPtr\<Stream\>\&, SystemIOStreamWrappingMode, const std::locale\&) منشئ

ينشئ مثالًا جديدًا من [BasicSystemIOStreamBuf](../).

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(const SharedPtr<Stream> &str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary, const std::locale &locale=std::locale())
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| str | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | مؤشر ذكي إلى الدفق |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | وضع التغليف |
| locale | const std::locale\& | المحلي الخاص بـ [Stream](../../stream/) |

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(const BasicSystemIOStreamBuf\&) منشئ

منشئ النسخ. محذوف.

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(const BasicSystemIOStreamBuf &)=delete
```

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(BasicSystemIOStreamBuf\&&) منشئ

منشئ النقل.

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(BasicSystemIOStreamBuf &&right) noexcept
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| right | [BasicSystemIOStreamBuf](../)\&& | [Object](../../../system/object/) ليتم نقله |

## انظر أيضاً

* عدد [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [BasicSystemIOStreamBuf](../)
* فئة [Stream](../../stream/)
* نطاق الاسم [System::IO](../../)
* مكتبة [Aspose.Slides](../../../)