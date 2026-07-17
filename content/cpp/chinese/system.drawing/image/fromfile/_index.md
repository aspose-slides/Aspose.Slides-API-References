---
title: FromFile()
second_title: Aspose.Slides for C++ API 参考
description: 从指定文件创建 Image 对象。
type: docs
weight: 352
url: /zh/system.drawing/image/fromfile/
---
## Image::FromFile(const String\&, bool) 方法

从指定文件创建一个 [Image](../) 对象。

```cpp
static SharedPtr<Image> System::Drawing::Image::FromFile(const String &filename, bool use_embedded_color_management=false)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 包含图像数据的文件名 |
| use_embedded_color_management | **bool** | 已忽略 |

### 返回值

指向已创建的 [Image](../) 对象的共享指针。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Image](../)
* 类 [String](../../../system/string/)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)