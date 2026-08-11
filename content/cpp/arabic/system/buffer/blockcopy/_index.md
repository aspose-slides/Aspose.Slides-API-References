---
title: BlockCopy()
second_title: مرجع API Aspose.Slides للغة C++
description: ينسخ عددًا محددًا من البايتات من المخزن المؤقت المصدر إلى المخزن المؤقت الوجهة.
type: docs
weight: 1
url: /ar/system/buffer/blockcopy/
---
## Buffer::BlockCopy(const uint8_t *, int, uint8_t *, int, int) طريقة


ينسخ عددًا محددًا من البايتات من المخزن المؤقت المصدر إلى المخزن المؤقت الوجهة.

```cpp
static void System::Buffer::BlockCopy(const uint8_t *src, int srcOffset, uint8_t *dst, int dstOffset, int count)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| src | const **uint8_t** * | مؤشر إلى المخزن المؤقت المصدر |
| srcOffset | int | إزاحة بايت في المخزن المؤقت المصدر التي يبدأ النسخ عندها |
| dst | **uint8_t** * | مؤشر إلى المخزن المؤقت الوجهة |
| dstOffset | int | إزاحة بايت في المخزن المؤقت الوجهة التي يبدأ عندها إدراج البيانات |
| count | int | عدد البايتات المراد نسخها |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) طريقة


يفسر مصفوفتين محددتين من الأنواع كمصفوفات خام من البايتات وينسخ البيانات من إحداهما إلى الأخرى.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| TSrc | نوع عناصر المصفوفة المصدر |
| TDst | نوع عناصر المصفوفة الوجهة |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | المصفوفة المصدر |
| srcOffset | int | إزاحة بايت في مصفوفة المصدر التي يبدأ النسخ عندها |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | المصفوفة الوجهة |
| dstOffset | int | إزاحة بايت في المصفوفة الوجهة التي يبدأ عندها إدراج البيانات |
| count | int | عدد البايتات المراد نسخها |

## Buffer::BlockCopy(const SharedPtr\<ArrayBase\>\&, int, const SharedPtr\<ArrayBase\>\&, int, int) طريقة


يفسر مصفوفتين محددتين كمصفوفات خام من البايتات وينسخ البيانات من إحداهما إلى الأخرى.

```cpp
static void System::Buffer::BlockCopy(const SharedPtr<ArrayBase> &src, int srcOffset, const SharedPtr<ArrayBase> &dst, int dstOffset, int count)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[ArrayBase](../../arraybase/)\>\& | المصفوفة المصدر |
| srcOffset | int | إزاحة بايت في مصفوفة المصدر التي يبدأ النسخ عندها |
| dst | const [SharedPtr](../../sharedptr/)\<[ArrayBase](../../arraybase/)\>\& | المصفوفة الوجهة |
| dstOffset | int | إزاحة بايت في المصفوفة الوجهة التي يبدأ عندها إدراج البيانات |
| count | int | عدد البايتات المراد نسخها |

## Buffer::BlockCopy(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) طريقة


يفسر مصفوفتين محددتين من الأنواع كمصفوفات خام من البايتات وينسخ البيانات من إحداهما إلى الأخرى.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const System::Details::ArrayView<TSrc> &src, int srcOffset, const System::Details::ArrayView<TDst> &dst, int dstOffset, int count)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| TSrc | نوع عناصر عرض المصفوفة المصدر |
| TDst | نوع عناصر عرض المصفوفة الوجهة |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| src | const System::Details::ArrayView\<TSrc\>\& | عرض المصفوفة المصدر |
| srcOffset | int | إزاحة بايت في عرض المصفوفة المصدر التي يبدأ النسخ عندها |
| dst | const System::Details::ArrayView\<TDst\>\& | عرض المصفوفة الوجهة |
| dstOffset | int | إزاحة بايت في عرض المصفوفة الوجهة التي يبدأ عندها إدراج البيانات |
| count | int | عدد البايتات المراد نسخها |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) طريقة


يفسر مصفوفتين محددتين من الأنواع كمصفوفات خام من البايتات وينسخ البيانات من إحداهما إلى الأخرى.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const System::Details::ArrayView<TDst> &dst, int dstOffset, int count)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| TSrc | نوع عناصر المصفوفة المصدر |
| TDst | نوع عناصر عرض المصفوفة الوجهة |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | المصفوفة المصدر |
| srcOffset | int | إزاحة بايت في المصفوفة المصدر التي يبدأ النسخ عندها |
| dst | const System::Details::ArrayView\<TDst\>\& | عرض المصفوفة الوجهة |
| dstOffset | int | إزاحة بايت في عرض المصفوفة الوجهة التي يبدأ عندها إدراج البيانات |
| count | int | عدد البايتات المراد نسخها |

## Buffer::BlockCopy(const System::Details::ArrayView\<TSrc\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) طريقة


يفسر مصفوفتين محددتين من الأنواع كمصفوفات خام من البايتات وينسخ البيانات من إحداهما إلى الأخرى.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const System::Details::ArrayView<TSrc> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| TSrc | نوع عناصر عرض المصفوفة المصدر |
| TDst | نوع عناصر المصفوفة الوجهة |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| src | const System::Details::ArrayView\<TSrc\>\& | عرض المصفوفة المصدر |
| srcOffset | int | إزاحة بايت في عرض المصفوفة المصدر التي يبدأ النسخ عندها |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | المصفوفة الوجهة |
| dstOffset | int | إزاحة بايت في المصفوفة الوجهة التي يبدأ عندها إدراج البيانات |
| count | int | عدد البايتات المراد نسخها |

## Buffer::BlockCopy(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) طريقة


يفسر مصفوفتين محددتين من الأنواع كمصفوفات خام من البايتات وينسخ البيانات من إحداهما إلى الأخرى.

```cpp
template<typename TSrc,std::size_t,typename TDst,std::size_t> static void System::Buffer::BlockCopy(const System::Details::StackArray<TSrc, NS> &src, int srcOffset, const System::Details::StackArray<TDst, ND> &dst, int dstOffset, int count)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| TSrc | نوع عناصر المصفوفة المكدسة المصدر |
| NS | حجم المصفوفة المكدسة المصدر |
| TDst | نوع عناصر المصفوفة المكدسة الوجهة |
| ND | حجم المصفوفة المكدسة الوجهة |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| src | const System::Details::StackArray\<TSrc, NS\>\& | المصفوفة المكدسة المصدر |
| srcOffset | int | إزاحة بايت في المصفوفة المكدسة المصدر التي يبدأ النسخ عندها |
| dst | const System::Details::StackArray\<TDst, ND\>\& | المصفوفة المكدسة الوجهة |
| dstOffset | int | إزاحة بايت في المصفوفة المكدسة الوجهة التي يبدأ عندها إدراج البيانات |
| count | int | عدد البايتات المراد نسخها |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) طريقة


يفسر مصفوفتين محددتين من الأنواع كمصفوفات خام من البايتات وينسخ البيانات من إحداهما إلى الأخرى.

```cpp
template<typename TSrc,typename TDst,std::size_t> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const System::Details::StackArray<TDst, ND> &dst, int dstOffset, int count)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| TSrc | نوع عناصر المصفوفة المصدر |
| TDst | نوع عناصر المصفوفة المكدسة الوجهة |
| ND | حجم المصفوفة المكدسة الوجهة |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | المصفوفة المصدر |
| srcOffset | int | إزاحة بايت في المصفوفة المصدر التي يبدأ النسخ عندها |
| dst | const System::Details::StackArray\<TDst, ND\>\& | المصفوفة المكدسة الوجهة |
| dstOffset | int | إزاحة بايت في المصفوفة المكدسة الوجهة التي يبدأ عندها إدراج البيانات |
| count | int | عدد البايتات المراد نسخها |

## Buffer::BlockCopy(const System::Details::StackArray\<TSrc, NS\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) طريقة


يفسر مصفوفتين محددتين من الأنواع كمصفوفات خام من البايتات وينسخ البيانات من إحداهما إلى الأخرى.

```cpp
template<typename TSrc,std::size_t,typename TDst> static void System::Buffer::BlockCopy(const System::Details::StackArray<TSrc, NS> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| TSrc | نوع عناصر المصفوفة المكدسة المصدر |
| NS | حجم المصفوفة المكدسة المصدر |
| TDst | نوع عناصر المصفوفة الوجهة |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| src | const System::Details::StackArray\<TSrc, NS\>\& | المصفوفة المكدسة المصدر |
| srcOffset | int | إزاحة بايت في المصفوفة المكدسة المصدر التي يبدأ النسخ عندها |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | المصفوفة الوجهة |
| dstOffset | int | إزاحة بايت في المصفوفة الوجهة التي يبدأ عندها إدراج البيانات |
| count | int | عدد البايتات المراد نسخها |

## انظر أيضاً

* تعريف النوع [SharedPtr](../../sharedptr/)
* فئة [Buffer](../)
* فئة [Array](../../array/)
* فئة [ArrayBase](../../arraybase/)
* مساحة اسم [System](../../)
* مكتبة [Aspose.Slides](../../../)