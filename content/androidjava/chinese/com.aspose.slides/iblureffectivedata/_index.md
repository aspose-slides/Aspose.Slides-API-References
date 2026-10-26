---
title: IBlurEffectiveData
second_title: 适用于 Android 的 Aspose.Slides Java API 参考
description: 不可变对象，表示应用于整个形状（包括其填充）的 Blur 效果。
type: docs
url: /zh/com.aspose.slides/iblureffectivedata/
---
**所有实现的接口：**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBlurEffectiveData extends IEffectEffectiveData
```

不可变对象，表示应用于整个形状（包括其填充）的 Blur 效果。所有颜色通道，包括 alpha，都会受到影响。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getRadius()](#getRadius--) | 返回或设置 blur 半径。 |
| [getGrow()](#getGrow--) | 确定对象的边界是否应因模糊而扩大。 |

### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

返回或设置 blur 半径。只读 double.

**返回：**
double

### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

确定对象的边界是否应因模糊而扩大。True 表示边界被扩大，false 表示未被扩大。只读 boolean。

**返回：**
boolean