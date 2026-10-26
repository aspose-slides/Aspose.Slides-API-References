---
title: IBlurEffectiveData
second_title: Aspose.Slides for Java API 参考
description: 不可变对象，表示对整个形状（包括填充）应用的模糊效果。
type: docs
url: /zh/com.aspose.slides/iblureffectivedata/
---
**所有已实现的接口：**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBlurEffectiveData extends IEffectEffectiveData
```

表示对整个形状（包括填充）应用的模糊效果的不可变对象。所有颜色通道，包括 alpha，都会受到影响。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getRadius()](#getRadius--) | 返回或设置模糊半径。 |
| [getGrow()](#getGrow--) | 确定是否应因模糊而扩大对象的边界。 |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

返回或设置模糊半径。只读 double.

**返回:**  
double
### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

确定是否应因模糊而扩大对象的边界。True 表示边界会被扩大，false 表示不会。只读 boolean.

**返回:**  
boolean