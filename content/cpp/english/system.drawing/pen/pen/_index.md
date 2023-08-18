---
title: Pen()
second_title: Aspose.Slides for C++ API Reference
description: Constructs a new Pen object representing the specified color.
type: docs
weight: 1
url: /system.drawing/pen/pen/
---
## Pen::Pen(const Color\&) constructor


Constructs a new [Pen](../) object representing the specified color.

```cpp
System::Drawing::Pen::Pen(const Color &color)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| color | const [Color](../../color/)\& | The color of the pen represented by the object being constructed |

## Pen::Pen(const Color\&, float) constructor


Constructs a new [Pen](../) object representing the specified color and width.

```cpp
System::Drawing::Pen::Pen(const Color &color, float width)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| color | const [Color](../../color/)\& | The color of the pen represented by the object being constructed |
| width | **float** | The width of the pen represented by the object being constructed |

## Pen::Pen(const SharedPtr\<Brush\>\&) constructor


Constructs a new [Pen](../) object and initializes it with the specified [Brush](../../brush/) object.

```cpp
System::Drawing::Pen::Pen(const SharedPtr<Brush> &brush)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | The [Brush](../../brush/) object that specifies the fill properties of the pen represented by the object being constructed |

## Pen::Pen(const SharedPtr\<Brush\>\&, float) constructor


Constructs a new [Pen](../) object and initializes it with the specified [Brush](../../brush/) object.

```cpp
System::Drawing::Pen::Pen(const SharedPtr<Brush> &brush, float width)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | The [Brush](../../brush/) object that specifies the fill properties of the pen represented by the object being constructed |
| width | **float** | The width of the pen represented by the object being constructed |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Color](../../color/)
* Class [Pen](../)
* Class [Brush](../../brush/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)