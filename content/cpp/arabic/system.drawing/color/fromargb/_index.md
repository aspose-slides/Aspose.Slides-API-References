---
title: FromArgb()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يبني نسخة من فئة Color تمثِّل اللون المحدد.
type: docs
weight: 235
url: /ar/system.drawing/color/fromargb/
---
## Color::FromArgb(int) طريقة

إنشاء نسخة من فئة [Color](../) التي تمثل اللون المحدد.

```cpp
static Color System::Drawing::Color::FromArgb(int argb)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| argb | int | قيمة ARGB بعمق 32 بت للون الذي سيمثله الكائن الذي يتم إنشاؤه |

### قيمة الإرجاع

كائن يمثل اللون المحدد.

## Color::FromArgb(int, int, int, int) طريقة

إنشاء نسخة من فئة [Color](../) التي تمثل اللون المحدد.

```cpp
static Color System::Drawing::Color::FromArgb(int alpha, int red, int green, int blue)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| alpha | int | قيمة مكوّن ألفا للون |
| red | int | قيمة مكوّن الأحمر للون |
| green | int | قيمة مكوّن الأخضر للون |
| blue | int | قيمة مكوّن الأزرق للون |

### قيمة الإرجاع

كائن يمثل اللون المحدد.

## Color::FromArgb(int, int, int) طريقة


إنشاء نسخة من فئة [Color](../) التي تمثل اللون المحدد مع ضبط مكوّن ألفا إلى 0xFF.

```cpp
static Color System::Drawing::Color::FromArgb(int red, int green, int blue)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| red | int | قيمة مكوّن الأحمر للون |
| green | int | قيمة مكوّن الأخضر للون |
| blue | int | قيمة مكوّن الأزرق للون |

### قيمة الإرجاع

كائن يمثل اللون المحدد.

## Color::FromArgb(int, Color) طريقة


إنشاء نسخة من فئة [Color](../) التي تمثل اللون المحدد.

```cpp
static Color System::Drawing::Color::FromArgb(int alpha, Color base_color)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| alpha | int | قيمة مكوّن ألفا للون |
| base_color | [Color](../) | نسخة من كائن [Color](../) الذي يمثل المكوّنات الأحمر والأخضر والأزرق للون الذي سيمثله الكائن الذي يتم إنشاؤه |

### قيمة الإرجاع

كائن يمثل اللون المحدد.

## انظر أيضًا

* الفئة [Color](../)
* مساحة الاسم [System::Drawing](../../)
* المكتبة [Aspose.Slides](../../../)