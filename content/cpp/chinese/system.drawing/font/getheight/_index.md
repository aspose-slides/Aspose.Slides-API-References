---
title: GetHeight()
second_title: Aspose.Slides C++ API 参考
description: 返回当前对象所表示的字体的行间距，以指定的 Graphics 对象的当前单位为准。
type: docs
weight: 14
url: /zh/system.drawing/font/getheight/
---
## Font::GetHeight(const SharedPtr\<Graphics\>\&) 方法

返回当前对象所表示的字体的行间距，以指定的 [Graphics](../../graphics/) 对象的当前单位为准。

```cpp
float System::Drawing::Font::GetHeight(const SharedPtr<Graphics> &graphics)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | 指定度量单位的 [Graphics](../../graphics/) 对象 |

## Font::GetHeight(float) 方法

返回当前对象所表示的字体在使用指定垂直分辨率的显示设备上绘制时的高度。

```cpp
float System::Drawing::Font::GetHeight(float dpi=DEFAULT_FONT_OPERATIONS_DPI)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dpi | **float** | 显示设备的垂直分辨率 |

### 返回值

字体的高度（像素）

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [Graphics](../../graphics/)
* 类 [Font](../)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)