---
title: LockBits()
second_title: Aspose.Slides C++ API 参考
description: 将 Bitmap 锁定到系统内存中。
type: docs
weight: 118
url: /zh/system.drawing/bitmap/lockbits/
---
## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat) 方法

将 [Bitmap](../) 锁定到系统内存。

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | 指定要锁定的图像区域的矩形 |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | 指定位图的访问级别 |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | 此位图的数据格式 |

### 返回值

一个指向 BitmapData 对象的共享指针，该对象包含有关已执行锁定操作的信息

## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat, const Imaging::BitmapDataPtr\&) 方法

将 [Bitmap](../) 锁定到系统内存。

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format, const Imaging::BitmapDataPtr &bitmap_data)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | 指定要锁定的图像区域的矩形 |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | 指定位图的访问级别 |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | 此位图的数据格式 |
| bitmap_data | const [Imaging::BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)\& | 包含有关锁定操作的信息 |

### 返回值

一个指向 BitmapData 对象的共享指针，该对象包含有关已执行锁定操作的信息

## 另请参阅

* 枚举 [ImageLockMode](../../../system.drawing.imaging/imagelockmode/)
* 枚举 [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* 类型别名 [BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)
* 类 [Rectangle](../../rectangle/)
* 类 [Bitmap](../)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)