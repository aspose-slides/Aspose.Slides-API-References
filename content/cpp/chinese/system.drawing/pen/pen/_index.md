---
title: Pen()
second_title: Aspose.Slides for C++ API 参考
description: 构造一个表示指定颜色的 Pen 对象。
type: docs
weight: 1
url: /zh/system.drawing/pen/pen/
---
## Pen::Pen(const Color\&) 构造函数

构造一个表示指定颜色的 [Pen](../) 对象。

```cpp
System::Drawing::Pen::Pen(const Color &color)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| color | const [Color](../../color/)\& | 正在构造的对象所表示的笔的颜色 |

## Pen::Pen(const Color\&, float) 构造函数

构造一个表示指定颜色和宽度的 [Pen](../) 对象。

```cpp
System::Drawing::Pen::Pen(const Color &color, float width)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| color | const [Color](../../color/)\& | 正在构造的对象所表示的笔的颜色 |
| width | **float** | 正在构造的对象所表示的笔的宽度 |

## Pen::Pen(const SharedPtr\<Brush\>\&) 构造函数

构造一个 [Pen](../) 对象并使用指定的 [Brush](../../brush/) 对象进行初始化。

```cpp
System::Drawing::Pen::Pen(const SharedPtr<Brush> &brush)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 指定正在构造的对象所表示的笔的填充属性的 [Brush](../../brush/) 对象 |

## Pen::Pen(const SharedPtr\<Brush\>\&, float) 构造函数

构造一个 [Pen](../) 对象并使用指定的 [Brush](../../brush/) 对象进行初始化。

```cpp
System::Drawing::Pen::Pen(const SharedPtr<Brush> &brush, float width)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 指定正在构造的对象所表示的笔的填充属性的 [Brush](../../brush/) 对象 |
| width | **float** | 正在构造的对象所表示的笔的宽度 |

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [Color](../../color/)
* 类 [Pen](../)
* 类 [Brush](../../brush/)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)