---
title: Split()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقسم السلسلة حسب حرف.
type: docs
weight: 768
url: /ar/system/string/split/
---
## String::Split(char_t, StringSplitOptions) const طريقة

يقسم السلسلة حسب حرف.

```cpp
ArrayPtr<String> System::String::Split(char_t separator=u' ', StringSplitOptions opt=StringSplitOptions::None) const
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| separator | char_t | حرف لتقسيم السلسلة به. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | خيارات التقسيم. |

### قيمة الإرجاع

[Array](../../array/) من السلاسل الفرعية.

## String::Split(char_t, int32_t, StringSplitOptions) const طريقة

يقسم السلسلة حسب حرف.

```cpp
ArrayPtr<String> System::String::Split(char_t separator, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| separator | char_t | حرف لتقسيم السلسلة به. |
| count | **int32_t** | الحد الأقصى لعدد السلاسل الفرعية التي سيتم إرجاعها. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | خيارات التقسيم. |

### قيمة الإرجاع

[Array](../../array/) من السلاسل الفرعية.

## String::Split(char_t, char_t, StringSplitOptions) const طريقة

يقسم السلسلة حسب أحد حرفين.

```cpp
ArrayPtr<String> System::String::Split(char_t separatorA, char_t separatorB, StringSplitOptions opt=StringSplitOptions::None) const
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| separatorA | char_t | الحرف الأول لتقسيم السلسلة به. |
| separatorB | char_t | الحرف الثاني لتقسيم السلسلة به. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | خيارات التقسيم. |

### قيمة الإرجاع

[Array](../../array/) من السلاسل الفرعية.

## String::Split(const ArrayPtr\<char_t\>\&, StringSplitOptions) const طريقة

يقسم السلسلة حسب أحد الأحرف المحددة.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) من أحرف الفاصل. إذا كان فارغًا، يُعتبر أي حرف فراغ كفاصل. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | خيارات التقسيم. |

### قيمة الإرجاع

[Array](../../array/) من السلاسل الفرعية.

## String::Split(const ArrayPtr\<char_t\>\&, int32_t, StringSplitOptions) const طريقة

يقسم السلسلة حسب أحد الأحرف المحددة.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) من أحرف الفاصل. إذا كان فارغًا، يُعتبر أي حرف فراغ كفاصل. |
| count | **int32_t** | الحد الأقصى لعدد السلاسل الفرعية التي سيتم إرجاعها. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | خيارات التقسيم. |

### قيمة الإرجاع

[Array](../../array/) من السلاسل الفرعية.

## String::Split(const String\&, StringSplitOptions) const طريقة

يقسم السلسلة حسب سلسلة فرعية.

```cpp
ArrayPtr<String> System::String::Split(const String &separator, StringSplitOptions opt=StringSplitOptions::None) const
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| separator | const [String](../)\& | سلسلة فرعية تعمل كفاصل. إذا كان فارغًا، يُعتبر حرف الفراغ فاصلًا. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | خيارات التقسيم. |

### قيمة الإرجاع

[Array](../../array/) من السلاسل الفرعية.

## String::Split(const String\&, int, StringSplitOptions) const طريقة

يقسم السلسلة حسب سلسلة فرعية.

```cpp
ArrayPtr<String> System::String::Split(const String &separator, int count, StringSplitOptions opt=StringSplitOptions::None) const
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| separator | const [String](../)\& | سلسلة فرعية تعمل كفاصل. إذا كان فارغًا، يُعتبر حرف الفراغ فاصلًا. |
| count | int | الحد الأقصى لعدد العناصر في مصفوفة الأقسام. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | خيارات التقسيم. |

### قيمة الإرجاع

[Array](../../array/) من السلاسل الفرعية.

## String::Split(const ArrayPtr\<String\>\&, StringSplitOptions) const طريقة

يقسم السلسلة حسب سلسلة فرعية.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) من سلاسل الفاصل. إذا كان فارغًا، لا يتم أي تقسيم. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | خيارات التقسيم. |

### قيمة الإرجاع

[Array](../../array/) من السلاسل الفرعية.

## String::Split(const ArrayPtr\<String\>\&, int, StringSplitOptions) const طريقة

يقسم السلسلة حسب سلسلة فرعية. حاليًا، يدعم فقط مصفوفة الفواصل التي تحتوي صفر أو عنصر واحد.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, int count, StringSplitOptions opt=StringSplitOptions::None) const
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) من سلاسل الفاصل. إذا كان فارغًا، لا يتم أي تقسيم. |
| count | int | الحد الأقصى لعدد العناصر في مصفوفة الأقسام. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | خيارات التقسيم. |

### قيمة الإرجاع

[Array](../../array/) من السلاسل الفرعية.

## انظر أيضًا

* Enum [StringSplitOptions](../../stringsplitoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* فئة [String](../)
* النطاق [System](../../)
* المكتبة [Aspose.Slides](../../../)