---
title: BinaryReader()
second_title: مرجع API Aspose.Slides برای C++
description: یک نمونه از کلاس BinaryReader ایجاد می‌کند که داده‌ها را از جریان مشخص شده با استفاده از کدگذاری UTF-8 می‌خواند.
type: docs
weight: 1
url: /fa/system.io/binaryreader/binaryreader/
---
## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&) constructor

یک نمونه از کلاس [BinaryReader](../) ایجاد می‌کند که داده‌ها را از جریان مشخص شده با استفاده از کدگذاری UTF-8 می‌خواند.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | جریان ورودی |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&) constructor

یک نمونه از کلاس [BinaryReader](../) ایجاد می‌کند که داده‌ها را از جریان مشخص شده با استفاده از کدگذاری مشخص‌شده می‌خواند.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | جریان ورودی |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | کدگذاری مورد استفاده |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&, bool) constructor

یک نمونه از کلاس [BinaryReader](../) ایجاد می‌کند که داده‌ها را از جریان مشخص شده با استفاده از کدگذاری مشخص‌شده می‌خواند.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding, bool leaveOpen)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | جریان ورودی |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | کدگذاری مورد استفاده |
| leaveOpen | **bool** | مشخص می‌کند آیا جریان **input** پس از از بین رفتن شیء جاری باز بماند (true) یا نه (false) |

## مراجع

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [Stream](../../stream/)
* کلاس [BinaryReader](../)
* کلاس [Encoding](../../../system.text/encoding/)
* فضای‌نام [System::IO](../../)
* Library [Aspose.Slides](../../../)