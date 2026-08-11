---
title: Rectangle()
second_title: مرجع API Aspose.Slides برای C++
description: یک نمونه جدید از شیء Rectangle می‌سازد که مستطیلی با مختصات X و Y و مقادیر width و hegiht برابر 0 را نشان می‌دهد.
type: docs
weight: 1
url: /fa/system.drawing/rectangle/rectangle/
---
## Rectangle::Rectangle() سازنده

یک نمونه جدید از شیء [Rectangle](../) می‌سازد که مستطیلی با مختصات X و Y و مقادیر width و hegiht برابر 0 را نشان می‌دهد.

```cpp
System::Drawing::Rectangle::Rectangle()
```

## Rectangle::Rectangle(int, int, int, int) سازنده

یک نمونه جدید از شیء [Rectangle](../) می‌سازد که مستطیلی با مختصات تعیین‌شدهٔ گوشهٔ بالاِ سمت چپ و عرض و ارتفاع مشخص را نشان می‌دهد.

```cpp
System::Drawing::Rectangle::Rectangle(int x, int y, int width, int height)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | int | مقداری از مختصات X گوشهٔ بالاِ سمت چپ مستطیل |
| y | int | مقداری از مختصات Y گوشهٔ بالاِ سمت چپ مستطیل |
| width | int | width مستطیل |
| height | int | height مستطیل |

## Rectangle::Rectangle(const Point\&, const Size\&) سازنده

یک نمونه جدید از شیء [Rectangle](../) می‌سازد که مستطیلی با مختصات گوشهٔ بالاِ سمت چپ که به صورت یک نمونه از کلاس [Point](../../point/) تعریف شده است و عرض و ارتفاع آن به عنوان یک نمونه از کلاس [Size](../../size/) تعریف می‌شود.

```cpp
System::Drawing::Rectangle::Rectangle(const Point &location, const Size &size)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| location | const [Point](../../point/)\& | محل قرارگیری گوشهٔ بالاِ سمت چپ مستطیل را مشخص می‌کند |
| size | const [Size](../../size/)\& | width و hegiht مستطیل را مشخص می‌کند |

## Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle_\&) سازنده

یک نمونه جدید از شیء [Rectangle](../) می‌سازد که مستطیلی برابر با مورد مشخص‌شده را نمایندگی می‌کند.

```cpp
System::Drawing::Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle_ &rect)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| rect | const **System::Windows::Forms::Screen::Rectangle_**\& | یک نمونه از کلاس **System::Windows::Forms::Screen::Rectangle_** که موقعیت و ابعاد مستطیلی که قرار است توسط شیء ساخته‌شده نمایان شود را مشخص می‌کند |

## موارد مرتبط

* کلاس [Rectangle](../)
* کلاس [Point](../../point/)
* کلاس [Size](../../size/)
* فضای نام [System::Drawing](../../)
* کتابخانه [Aspose.Slides](../../../)