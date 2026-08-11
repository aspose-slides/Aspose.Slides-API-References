---
title: Font()
second_title: مرجع API Aspose.Slides للغة C++
description: ينشئ مثيلاً جديدًا من فئة Font التي تمثل الخط الموجود المحدد مع نمط الخط المحدد.
type: docs
weight: 1
url: /ar/system.drawing/font/font/
---
## Font::Font(const SharedPtr\<Font\>\&, FontStyle) مُنشئ

ينشئ مثيلاً جديدًا من فئة [Font](../) التي تمثل الخط الموجود المحدد مع نمط الخط المحدد.

```cpp
System::Drawing::Font::Font(const SharedPtr<Font> &prototype, FontStyle new_style)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| prototype | const [SharedPtr](../../../system/sharedptr/)\<[Font](../)\>\& | الخط الموجود لإنشاء الخط الجديد منه |
| new_style | [FontStyle](../../fontstyle/) | نمط الخط لتطبيقه على الخط الجديد |

## Font::Font(const SharedPtr\<FontFamily\>\&, float, FontStyle, GraphicsUnit, uint8_t, bool) مُنشئ

ينشئ مثيلاً جديدًا من فئة [Font](../).

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../fontfamily/)\>\& | عائلة الخط للخط الجديد |
| em_size | **float** | حجم الـ em للخط الجديد بوحدات **unit** |
| style | [FontStyle](../../fontstyle/) | نمط الخط الجديد |
| unit | [GraphicsUnit](../../graphicsunit/) | وحدات قياس الخط الجديد |
| gdi_charset | **uint8_t** | مجموعة أحرف GDI لاستخدامها مع الخط الجديد |
| gdi_vertical_font | **bool** | صحيح إذا كان الخط الجديد مشتقًا من خط GDI عمودي |

## Font::Font(const SharedPtr\<FontFamily\>\&, float, GraphicsUnit) مُنشئ

ينشئ مثيلاً جديدًا من فئة [Font](../).

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../fontfamily/)\>\& | عائلة الخط للخط الجديد |
| em_size | **float** | حجم الـ em للخط الجديد بوحدات **unit** |
| unit | [GraphicsUnit](../../graphicsunit/) | وحدات قياس الخط الجديد |

## Font::Font(const String\&, float, FontStyle, GraphicsUnit, uint8_t, bool) مُنشئ

ينشئ مثيلاً جديدًا من فئة [Font](../).

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| family_name | const [String](../../../system/string/)\& | اسم عائلة الخط للخط الجديد |
| em_size | **float** | حجم الـ em للخط الجديد بوحدات **unit** |
| style | [FontStyle](../../fontstyle/) | نمط الخط الجديد |
| unit | [GraphicsUnit](../../graphicsunit/) | وحدات قياس الخط الجديد |
| gdi_charset | **uint8_t** | مجموعة أحرف GDI لاستخدامها مع الخط الجديد |
| gdi_vertical_font | **bool** | صحيح إذا كان الخط الجديد مشتقًا من خط GDI عمودي |

## Font::Font(const String\&, float, GraphicsUnit) مُنشئ

ينشئ مثيلاً جديدًا من فئة [Font](../).

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| family_name | const [String](../../../system/string/)\& | اسم عائلة الخط للخط الجديد |
| em_size | **float** | حجم الـ em للخط الجديد بوحدات **unit** |
| unit | [GraphicsUnit](../../graphicsunit/) | وحدات قياس الخط الجديد |

## انظر أيضًا

* Enum [FontStyle](../../fontstyle/)
* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../)
* Class [FontFamily](../../fontfamily/)
* Class [String](../../../system/string/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)