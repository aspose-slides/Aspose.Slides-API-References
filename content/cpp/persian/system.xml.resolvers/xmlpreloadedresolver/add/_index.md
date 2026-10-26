---
title: Add()
second_title: Aspose.Slides برای C++ مرجع API
description: یک آرایه بایت را به مخزن XmlPreloadedResolver اضافه می‌کند و آن را به یک URI نگاشت می‌دهد. اگر مخزن قبلاً نگاشتی برای همان URI داشته باشد، نگاشت موجود بازنویسی می‌شود.
type: docs
weight: 79
url: /fa/system.xml.resolvers/xmlpreloadedresolver/add/
---
## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&) متد

یک آرایه بایت را به مخزن [XmlPreloadedResolver](../) اضافه می‌کند و آن را به یک URI نگاشت می‌دهد. اگر مخزن قبلاً نگاشتی برای همان URI داشته باشد، نگاشت موجود بازنویسی می‌شود.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | URI داده‌ای که به مخزن [XmlPreloadedResolver](../) اضافه می‌شود. |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | یک آرایه بایت حاوی داده‌ای که با URI ارائه‌شده مرتبط است. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) متد

یک آرایه بایت را به مخزن [XmlPreloadedResolver](../) اضافه می‌کند و آن را به یک URI نگاشت می‌دهد. اگر مخزن قبلاً نگاشتی برای همان URI داشته باشد، نگاشت موجود بازنویسی می‌شود.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value, int32_t offset, int32_t count)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | URI داده‌ای که به مخزن [XmlPreloadedResolver](../) اضافه می‌شود. |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | یک آرایه بایت حاوی داده‌ای که با URI ارائه‌شده مرتبط است. |
| offset | **int32_t** | جابجایی در آرایه بایت ارائه‌شده که در آن داده شروع می‌شود. |
| count | **int32_t** | تعداد بایت‌هایی که از آرایه بایت، ابتداء از جابجایی ارائه‌شده، خوانده می‌شود. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const SharedPtr\<IO::Stream\>\&) متد

یک Stream را به مخزن [XmlPreloadedResolver](../) اضافه می‌کند و آن را به یک URI نگاشت می‌دهد. اگر مخزن قبلاً نگاشتی برای همان URI داشته باشد، نگاشت موجود بازنویسی می‌شود.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const SharedPtr<IO::Stream> &value)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | URI داده‌ای که به مخزن [XmlPreloadedResolver](../) اضافه می‌شود. |
| value | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | یک Stream شامل داده‌ای که با URI ارائه‌شده مرتبط است. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const String\&) متد

یک رشته با داده‌های پیش‌بارگذاری‌شده را به مخزن [XmlPreloadedResolver](../) اضافه می‌کند و آن را به یک URI نگاشت می‌دهد. اگر مخزن قبلاً نگاشتی برای همان URI داشته باشد، نگاشت موجود بازنویسی می‌شود.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const String &value)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | URI داده‌ای که به مخزن [XmlPreloadedResolver](../) اضافه می‌شود. |
| value | const [String](../../../system/string/)\& | یک [String](../../../system/string/) حاوی داده‌ای که با URI ارائه‌شده مرتبط است. |

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Uri](../../../system/uri/)
* Class [XmlPreloadedResolver](../)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)