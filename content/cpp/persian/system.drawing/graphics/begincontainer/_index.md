---
title: BeginContainer()
second_title: مرجع API Aspose.Slides برای C++
description: یک کانتینر را با وضعیت فعلی این شی ذخیره می‌کند، یک کانتینر جدید را باز و استفاده می‌نماید و کانتینر ذخیره‌شده را برمی‌گرداند.
type: docs
weight: 976
url: /fa/system.drawing/graphics/begincontainer/
---
## Graphics::BeginContainer() متد

یک کانتینر را با وضعیت فعلی این شی ذخیره می‌کند، یک کانتینر جدید را باز و استفاده می‌نماید و کانتینر ذخیره‌شده را باز می‌گرداند.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer()
```

## Graphics::BeginContainer(Rectangle, Rectangle, GraphicsUnit) متد

یک کانتینر را با وضعیت فعلی این شی ذخیره می‌کند، یک کانتینر جدید را باز و استفاده می‌نماید و کانتینر ذخیره‌شده را باز می‌گرداند.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(Rectangle dstrect, Rectangle srcrect, GraphicsUnit unit)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| dstrect | [Rectangle](../../rectangle/) | مستطیلی که تبدیل مقیاس کانتینر جدید را مشخص می‌کند. همراه با **srcrect** استفاده می‌شود |
| srcrect | [Rectangle](../../rectangle/) | مستطیلی که تبدیل مقیاس کانتینر جدید را مشخص می‌کند. همراه با **dstrect** استفاده می‌شود |
| unit | [GraphicsUnit](../../graphicsunit/) | مقداری که واحد اندازه‌گیری کانتینر جدید را مشخص می‌کند |

## Graphics::BeginContainer(RectangleF, RectangleF, GraphicsUnit) متد

یک کانتینر را با وضعیت فعلی این شی ذخیره می‌کند، یک کانتینر جدید را باز و استفاده می‌نماید و کانتینر ذخیره‌شده را باز می‌گرداند.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(RectangleF dstrect, RectangleF srcrect, GraphicsUnit unit)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| dstrect | [RectangleF](../../rectanglef/) | مستطیلی که تبدیل مقیاس کانتینر جدید را مشخص می‌کند. همراه با **srcrect** استفاده می‌شود |
| srcrect | [RectangleF](../../rectanglef/) | مستطیلی که تبدیل مقیاس کانتینر جدید را مشخص می‌کند. همراه با **dstrect** استفاده می‌شود |
| unit | [GraphicsUnit](../../graphicsunit/) | مقداری که واحد اندازه‌گیری کانتینر جدید را مشخص می‌کند |

## موارد مرتبط

* نوع شمارشی [GraphicsUnit](../../graphicsunit/)
* نوع تعریف شده [SharedPtr](../../../system/sharedptr/)
* کلاس [GraphicsContainer](../../../system.drawing.drawing2d/graphicscontainer/)
* کلاس [Graphics](../)
* کلاس [Rectangle](../../rectangle/)
* کلاس [RectangleF](../../rectanglef/)
* فضای‌نام [System::Drawing](../../)
* کتابخانه [Aspose.Slides](../../../)