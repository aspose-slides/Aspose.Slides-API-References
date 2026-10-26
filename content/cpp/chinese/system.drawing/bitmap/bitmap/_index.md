---
title: Bitmap()
second_title: Aspose.Slides for C++ API 参考
description: 从指定的现有图像构造一个新的 Bitmap 对象。
type: docs
weight: 1
url: /zh/system.drawing/bitmap/bitmap/
---
## Bitmap::Bitmap(const SharedPtr\<Image\>\&) 构造函数

构造一个新的 [Bitmap](../) 对象, 该对象源自指定的现有图像。

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 用于创建位图图像的已有图像 |

## Bitmap::Bitmap(const SharedPtr\<System::IO::Stream\>\&, bool) 构造函数

构造一个新的 [Bitmap](../) 对象, 该对象源自指定的流。

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<System::IO::Stream> &stream, bool useIcm=false)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | 包含图像数据的流 |
| useIcm | **bool** | 已忽略 |

## Bitmap::Bitmap(const String\&) 构造函数

构造一个新的 [Bitmap](../) 对象, 该对象源自指定的文件。

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 包含图像数据的文件名 |

## Bitmap::Bitmap(const String\&, bool) 构造函数

构造一个新的 [Bitmap](../) 对象, 该对象源自指定的文件。

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename, bool useIcm)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 包含图像数据的文件名 |
| useIcm | **bool** | 已忽略 |

## Bitmap::Bitmap(int, int, Imaging::PixelFormat) 构造函数

构造一个新的 [Bitmap](../) 对象, 该对象表示具有指定宽度、长度、像素格式和像素数据的位图图像。

```cpp
System::Drawing::Bitmap::Bitmap(int width, int height, Imaging::PixelFormat format=Imaging::PixelFormat::Format32bppArgb)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| width | int | 图像的宽度 |
| height | int | 图像的高度 |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | 图像的像素格式 |

## Bitmap::Bitmap(const SharedPtr\<Image\>\&, const Size\&) 构造函数

构造一个新的 [Bitmap](../) 对象, 该对象源自指定的已有图像, 并按指定尺寸进行缩放。

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, const Size &size)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 用于创建位图图像的已有图像 |
| size | const [Size](../../size/)\& | 新图像的尺寸 |

## Bitmap::Bitmap(const SharedPtr\<Image\>\&, int, int) 构造函数

构造一个新的 [Bitmap](../) 对象, 该对象源自指定的已有图像, 并将宽度和长度缩放至指定数值。

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, int width, int height)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 用于创建位图图像的已有图像 |
| width | int | 新图像的宽度 |
| height | int | 新图像的高度 |

## 参见

* 枚举 [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Image](../../image/)
* 类 [Bitmap](../)
* 类 [Stream](../../../system.io/stream/)
* 类 [String](../../../system/string/)
* 类 [Size](../../size/)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)