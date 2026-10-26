---
title: Pen()
second_title: Aspose.Slides برای C++ مرجع API
description: یک شیء جدید Pen می‌سازد که رنگ مشخص‌شده را نشان می‌دهد.
type: docs
weight: 1
url: /fa/system.drawing/pen/pen/
---
## Pen::Pen(const Color\&) سازنده

یک شیء جدید [Pen](../) که رنگ مشخص‌شده را نشان می‌دهد می‌سازد.

```cpp
System::Drawing::Pen::Pen(const Color &color)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| color | const [Color](../../color/)\& | رنگ قلم که توسط شیء در حال ساخت نمایان می‌شود |

## Pen::Pen(const Color\&, float) سازنده

یک شیء جدید [Pen](../) که رنگ و عرض مشخص‌شده را نشان می‌دهد می‌سازد.

```cpp
System::Drawing::Pen::Pen(const Color &color, float width)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| color | const [Color](../../color/)\& | رنگ قلم که توسط شیء در حال ساخت نمایان می‌شود |
| width | **float** | عرض قلم که توسط شیء در حال ساخت نمایان می‌شود |

## Pen::Pen(const SharedPtr\<Brush\>\&) سازنده

یک شیء جدید [Pen](../) می‌سازد و آن را با شیء [Brush](../../brush/) مشخص‌شده مقداردهی اولیه می‌کند.

```cpp
System::Drawing::Pen::Pen(const SharedPtr<Brush> &brush)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | شیء [Brush](../../brush/) که خصوصیات پر کردن قلم را که توسط شیء در حال ساخت نمایان می‌شود، مشخص می‌کند |

## Pen::Pen(const SharedPtr\<Brush\>\&, float) سازنده

یک شیء جدید [Pen](../) می‌سازد و آن را با شیء [Brush](../../brush/) مشخص‌شده مقداردهی اولیه می‌کند.

```cpp
System::Drawing::Pen::Pen(const SharedPtr<Brush> &brush, float width)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | شیء [Brush](../../brush/) که خصوصیات پر کردن قلم را که توسط شیء در حال ساخت نمایان می‌شود، مشخص می‌کند |
| width | **float** | عرض قلم که توسط شیء در حال ساخت نمایان می‌شود |

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Color](../../color/)
* Class [Pen](../)
* Class [Brush](../../brush/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)