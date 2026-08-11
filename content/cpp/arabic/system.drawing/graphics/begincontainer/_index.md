---
title: BeginContainer()
second_title: مرجع API Aspose.Slides للغة C++
description: يقوم بحفظ حاوية بالحالة الحالية لهذا الكائن، يفتح ويستخدم حاوية جديدة ويعيد الحاوية المحفوظة.
type: docs
weight: 976
url: /ar/system.drawing/graphics/begincontainer/
---
## Graphics::BeginContainer() طريقة

يحفظ حاوية بالحالة الحالية لهذا الكائن، يفتح ويستخدم حاوية جديدة ويعيد الحاوية المحفوظة.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer()
```

## Graphics::BeginContainer(Rectangle, Rectangle, GraphicsUnit) طريقة

يحفظ حاوية بالحالة الحالية لهذا الكائن، يفتح ويستخدم حاوية جديدة ويعيد الحاوية المحفوظة.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(Rectangle dstrect, Rectangle srcrect, GraphicsUnit unit)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| dstrect | [Rectangle](../../rectangle/) | المستطيل الذي يحدد تحويل مقياس الحاوية الجديدة. يُستخدم مع **srcrect** |
| srcrect | [Rectangle](../../rectangle/) | المستطيل الذي يحدد تحويل مقياس الحاوية الجديدة. يُستخدم مع **dstrect** |
| unit | [GraphicsUnit](../../graphicsunit/) | القيمة التي تحدد وحدة قياس الحاوية الجديدة |

## Graphics::BeginContainer(RectangleF, RectangleF, GraphicsUnit) طريقة

يحفظ حاوية بالحالة الحالية لهذا الكائن، يفتح ويستخدم حاوية جديدة ويعيد الحاوية المحفوظة.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(RectangleF dstrect, RectangleF srcrect, GraphicsUnit unit)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| dstrect | [RectangleF](../../rectanglef/) | المستطيل الذي يحدد تحويل مقياس الحاوية الجديدة. يُستخدم مع **srcrect** |
| srcrect | [RectangleF](../../rectanglef/) | المستطيل الذي يحدد تحويل مقياس الحاوية الجديدة. يُستخدم مع **dstrect** |
| unit | [GraphicsUnit](../../graphicsunit/) | القيمة التي تحدد وحدة قياس الحاوية الجديدة |

## راجع أيضًا

* تعداد [GraphicsUnit](../../graphicsunit/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [GraphicsContainer](../../../system.drawing.drawing2d/graphicscontainer/)
* فئة [Graphics](../)
* فئة [Rectangle](../../rectangle/)
* فئة [RectangleF](../../rectanglef/)
* مساحة اسم [System::Drawing](../../)
* مكتبة [Aspose.Slides](../../../)