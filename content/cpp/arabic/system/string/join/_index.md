---
title: Join()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يجمع المصفوفة باستخدام السلسلة كفاصل.
type: docs
weight: 846
url: /ar/system/string/join/
---
## String::Join(const String\&, const ArrayPtr\<String\>\&, int, int) طريقة

يجمع المصفوفة باستخدام السلسلة كفاصل.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<String> &parts, int startIndex=0, int count=-1)
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) لوضعه بين عناصر المصفوفة عند الجمع. |
| parts | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) الأجزاء للدمج. |
| startIndex | int | الفهرس الأول في المصفوفة للبدء بالدمج منه. |
| count | int | عدد عناصر المصفوفة التي سيتم دمجها. -1 يعني 'حتى نهاية المصفوفة'. |

### قيمة الإرجاع

[String](../) تمثّل عناصر المصفوفة المدمجة.

## String::Join(const String\&, const System::Details::ArrayView\<String\>\&, int, int) طريقة

يجمع المصفوفة باستخدام السلسلة كفاصل.

```cpp
static String System::String::Join(const String &separator, const System::Details::ArrayView<String> &parts, int startIndex=0, int count=-1)
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) لوضعه بين عناصر المصفوفة عند الجمع. |
| parts | const System::Details::ArrayView\<[String](../)\>\& | عرض ArrayView للأجزاء للدمج. |
| startIndex | int | الفهرس الأول في المصفوفة للبدء بالدمج منه. |
| count | int | عدد عناصر المصفوفة التي سيتم دمجها. -1 يعني 'حتى نهاية المصفوفة'. |

### قيمة الإرجاع

[String](../) تمثّل عناصر المصفوفة المدمجة.

## String::Join(const String\&, const SharedPtr\<System::Collections::Generic::IEnumerable\<String\>\>\&) طريقة

يجمع المصفوفة باستخدام السلسلة كفاصل.

```cpp
static String System::String::Join(const String &separator, const SharedPtr<System::Collections::Generic::IEnumerable<String>> &parts)
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) لوضعه بين عناصر المصفوفة عند الجمع. |
| parts | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../)\>\>\& | - كائن قابل للتعداد من الأجزاء |

### قيمة الإرجاع

[String](../) تمثّل العناصر المدمجة.

## String::Join(const String\&, const ArrayPtr\<SharedPtr\<Object\>\>\&) طريقة

يجمع المصفوفة باستخدام السلسلة كفاصل.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<SharedPtr<Object>> &parts)
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) لوضعه بين عناصر المصفوفة عند الجمع. |
| parts | const [ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\>\& | [Array](../../array/) للأجزاء للدمج. |

### قيمة الإرجاع

[String](../) تمثّل العناصر المدمجة.

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../arrayptr/)
* تعريف نوع [SharedPtr](../../sharedptr/)
* فئة [String](../)
* فئة [IEnumerable](../../../system.collections.generic/ienumerable/)
* فئة [Object](../../object/)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)