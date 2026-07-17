---
title: Equals()
second_title: Aspose.Slides C++ API 参考
description: 确定指定的区域是否与当前对象在指定绘图表面上表示的区域相同。
type: docs
weight: 157
url: /zh/system.drawing/region/equals/
---
## Region::Equals(const SharedPtr\<Region\>\&, const SharedPtr\<Graphics\>\&) 方法

确定指定的区域是否与当前对象在指定绘图表面上表示的区域相同。

```cpp
bool System::Drawing::Region::Equals(const SharedPtr<Region> &r, const SharedPtr<Graphics> &g)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| r | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | 用于将此区域与之比较的区域 |
| g | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | 绘图表面 |

### 返回值

如果在应用与 **g** 参数关联的变换后，指定区域的内部与当前 objcet 表示的区域的内部相同则为 True；否则为 false

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Region](../)
* 类 [Graphics](../../graphics/)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)