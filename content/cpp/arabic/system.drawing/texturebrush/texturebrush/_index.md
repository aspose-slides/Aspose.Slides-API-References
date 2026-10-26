---
title: TextureBrush()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ مثيلاً جديدًا لفئة TextureBrush التي تستخدم الصورة المحددة.
type: docs
weight: 1
url: /ar/system.drawing/texturebrush/texturebrush/
---
## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode) منشئ

ينشئ مثيلاً جديدًا لفئة [TextureBrush](../) التي تستخدم الصورة المحددة.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode=Drawing2D::WrapMode::Tile)
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | صورة يستخدمها الفرش لتعبئة داخل الشكل |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | يحدد كيفية تجانب كائن الفرش |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, RectangleF, const SharedPtr\<Imaging::ImageAttributes\>\&) منشئ

ينشئ مثيلاً جديدًا لفئة [TextureBrush](../) التي تستخدم الصورة المحددة.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, RectangleF dst_rect, const SharedPtr<Imaging::ImageAttributes> &image_attrs=nullptr)
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | صورة يستخدمها الفرش لتعبئة داخل الشكل |
| dst_rect | [RectangleF](../../rectanglef/) | يحدد المستطيل الحدودي للفرش |
| image_attrs | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | سمات الصورة |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Rectangle, const SharedPtr\<Imaging::ImageAttributes\>\&) منشئ

ينشئ مثيلاً جديدًا لفئة [TextureBrush](../) التي تستخدم الصورة المحددة.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Rectangle dst_rect, const SharedPtr<Imaging::ImageAttributes> &image_attrs=nullptr)
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | صورة يستخدمها الفرش لتعبئة داخل الشكل |
| dst_rect | [Rectangle](../../rectangle/) | يحدد المستطيل الحدودي للفرش |
| image_attrs | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | سمات الصورة |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode, RectangleF) منشئ

ينشئ مثيلاً جديدًا لفئة [TextureBrush](../) التي تستخدم الصورة المحددة.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode, RectangleF dst_rect)
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | صورة يستخدمها الفرش لتعبئة داخل الشكل |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | يحدد كيفية تجانب كائن الفرش |
| dst_rect | [RectangleF](../../rectanglef/) | يحدد المستطيل الحدودي للفرش |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode, Rectangle) منشئ

ينشئ مثيلاً جديدًا لفئة [TextureBrush](../) التي تستخدم الصورة المحددة.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode, Rectangle dst_rect)
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | صورة يستخدمها الفرش لتعبئة داخل الشكل |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | يحدد كيفية تجانب كائن الفرش |
| dst_rect | [Rectangle](../../rectangle/) | يحدد المستطيل الحدودي للفرش |

## راجع أيضًا

* Enum [WrapMode](../../../system.drawing.drawing2d/wrapmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../../image/)
* Class [TextureBrush](../)
* Class [RectangleF](../../rectanglef/)
* Class [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* Class [Rectangle](../../rectangle/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)