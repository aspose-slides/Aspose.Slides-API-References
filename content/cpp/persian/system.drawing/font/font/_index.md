---
title: Font()
second_title: Aspose.Slides برای C++ مرجع API
description: یک نمونه جدید از کلاس Font ایجاد می‌کند که فونت موجود مشخص‌شده را با سبک فونت مشخص‌شده نشان می‌دهد.
type: docs
weight: 1
url: /fa/system.drawing/font/font/
---
## Font::Font(const SharedPtr\<Font\>\&, FontStyle) سازنده

یک نمونه جدید از کلاس [Font](../) را که فونت موجود مشخص‌شده را با سبک فونت مشخص‌شده نشان می‌دهد، می‌سازد.

```cpp
System::Drawing::Font::Font(const SharedPtr<Font> &prototype, FontStyle new_style)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| prototype | const [SharedPtr](../../../system/sharedptr/)\<[Font](../)\>\& | فونت موجودی که از آن‌جا فونت جدید ایجاد می‌شود |
| new_style | [FontStyle](../../fontstyle/) | یک سبک فونت برای اعمال به فونت جدید |

## Font::Font(const SharedPtr\<FontFamily\>\&, float, FontStyle, GraphicsUnit, uint8_t, bool) سازنده

یک نمونه جدید از کلاس [Font](../) می‌سازد.

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../fontfamily/)\>\& | خانواده فونت فونت جدید |
| em_size | **float** | اندازه em فونت جدید بر حسب واحدهایی که توسط پارامتر **unit** مشخص شده‌اند |
| style | [FontStyle](../../fontstyle/) | سبک فونت جدید |
| unit | [GraphicsUnit](../../graphicsunit/) | واحدهای اندازه‌گیری فونت جدید |
| gdi_charset | **uint8_t** | یک مجموعه کاراکتر GDI که برای فونت جدید استفاده می‌شود |
| gdi_vertical_font | **bool** | درست اگر فونت جدید از یک فونت عمودی GDI مشتق شده باشد |

## Font::Font(const SharedPtr\<FontFamily\>\&, float, GraphicsUnit) سازنده

یک نمونه جدید از کلاس [Font](../) می‌سازد.

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../fontfamily/)\>\& | خانواده فونت فونت جدید |
| em_size | **float** | اندازه em فونت جدید بر حسب واحدهایی که توسط پارامتر **unit** مشخص شده‌اند |
| unit | [GraphicsUnit](../../graphicsunit/) | واحدهای اندازه‌گیری فونت جدید |

## Font::Font(const String\&, float, FontStyle, GraphicsUnit, uint8_t, bool) سازنده

یک نمونه جدید از کلاس [Font](../) می‌سازد.

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| family_name | const [String](../../../system/string/)\& | نام خانواده فونت جدید |
| em_size | **float** | اندازه em فونت جدید بر حسب واحدهایی که توسط پارامتر **unit** مشخص شده‌اند |
| style | [FontStyle](../../fontstyle/) | سبک فونت جدید |
| unit | [GraphicsUnit](../../graphicsunit/) | واحدهای اندازه‌گیری فونت جدید |
| gdi_charset | **uint8_t** | یک مجموعه کاراکتر GDI که برای فونت جدید استفاده می‌شود |
| gdi_vertical_font | **bool** | درست اگر فونت جدید از یک فونت عمودی GDI مشتق شده باشد |

## Font::Font(const String\&, float, GraphicsUnit) سازنده

یک نمونه جدید از کلاس [Font](../) می‌سازد.

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| family_name | const [String](../../../system/string/)\& | نام خانواده فونت جدید |
| em_size | **float** | اندازه em فونت جدید بر حسب واحدهایی که توسط پارامتر **unit** مشخص شده‌اند |
| unit | [GraphicsUnit](../../graphicsunit/) | واحدهای اندازه‌گیری فونت جدید |

## موارد مرتبط

* Enum [FontStyle](../../fontstyle/)
* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [Font](../)
* کلاس [FontFamily](../../fontfamily/)
* کلاس [String](../../../system/string/)
* فضای‌نام [System::Drawing](../../)
* کتابخانه [Aspose.Slides](../../../)