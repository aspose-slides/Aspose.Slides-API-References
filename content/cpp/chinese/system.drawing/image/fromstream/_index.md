---
title: FromStream()
second_title: Aspose.Slides C++ API 参考
description: 从指定的流创建一个 Image 对象。
type: docs
weight: 339
url: /zh/system.drawing/image/fromstream/
---
## Image::FromStream(const SharedPtr\<System::IO::Stream\>\&, bool, bool) 方法

从指定的流创建一个 [Image](../) 对象。

```cpp
static SharedPtr<Image> System::Drawing::Image::FromStream(const SharedPtr<System::IO::Stream> &stream, bool use_embedded_color_management=false, bool validate_image_data=1)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | 包含图像数据的流 |
| use_embedded_color_management | **bool** | IGNORED |
| validate_image_data | **bool** | IGNORED |

### 返回值

指向创建的 [Image](../) 对象的共享指针。

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)