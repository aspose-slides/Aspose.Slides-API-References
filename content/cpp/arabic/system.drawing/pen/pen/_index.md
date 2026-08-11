---
title: Pen()
second_title: مرجع API ل Aspose.Slides للغة C++
description: ينشئ كائن Pen جديدًا يمثل اللون المحدد.
type: docs
weight: 1
url: /ar/system.drawing/pen/pen/
---
## Pen::Pen(const Color\&) منشئ

ينشئ كائنًا جديدًا من نوع [Pen](../) يمثل اللون المحدد.

```cpp
System::Drawing::Pen::Pen(const Color &color)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| color | const [Color](../../color/)\& | لون القلم الممثل بالكائن الذي يتم بناؤه |

## Pen::Pen(const Color\&, float) منشئ

ينشئ كائنًا جديدًا من نوع [Pen](../) يمثل اللون والعرض المحددين.

```cpp
System::Drawing::Pen::Pen(const Color &color, float width)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| color | const [Color](../../color/)\& | لون القلم الممثل بالكائن الذي يتم بناؤه |
| width | **float** | عرض القلم الممثل بالكائن الذي يتم بناؤه |

## Pen::Pen(const SharedPtr\<Brush\>\&) منشئ

ينشئ كائنًا جديدًا من نوع [Pen](../) ويُهيئه باستخدام الكائن [Brush](../../brush/) المحدد.

```cpp
System::Drawing::Pen::Pen(const SharedPtr<Brush> &brush)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | الكائن [Brush](../../brush/) الذي يحدّد خصائص التعبئة للقلم الممثل بالكائن الذي يتم بناؤه |

## Pen::Pen(const SharedPtr\<Brush\>\&, float) منشئ

ينشئ كائنًا جديدًا من نوع [Pen](../) ويُهيئه باستخدام الكائن [Brush](../../brush/) المحدد.

```cpp
System::Drawing::Pen::Pen(const SharedPtr<Brush> &brush, float width)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | الكائن [Brush](../../brush/) الذي يحدّد خصائص التعبئة للقلم الممثل بالكائن الذي يتم بناؤه |
| width | **float** | عرض القلم الممثل بالكائن الذي يتم بناؤه |

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [Color](../../color/)
* فئة [Pen](../)
* فئة [Brush](../../brush/)
* نطاق [System::Drawing](../../)
* مكتبة [Aspose.Slides](../../../)