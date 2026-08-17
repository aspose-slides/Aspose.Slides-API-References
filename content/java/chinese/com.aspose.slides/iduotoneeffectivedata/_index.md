---
title: IDuotoneEffectiveData
second_title: Aspose.Slides Java API 参考
description: 不可变对象，表示双色调效果。
type: docs
url: /zh/com.aspose.slides/iduotoneeffectivedata/
---
**所有实现的接口：**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IDuotoneEffectiveData extends IEffectEffectiveData
```

不可变对象，表示双色调效果。对于每个像素，通过线性插值将 clr1 和 clr2 组合，以确定该像素的新颜色。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getColor1()](#getColor1--) | 返回暗像素的目标颜色格式。 |
| [getColor2()](#getColor2--) | 返回亮像素的目标颜色格式。 |
### getColor1() {#getColor1--}
```
public abstract Color getColor1()
```

返回暗像素的目标颜色格式。只读 java.awt.Color.

**返回:**
java.awt.Color
### getColor2() {#getColor2--}
```
public abstract Color getColor2()
```

返回亮像素的目标颜色格式。只读 java.awt.Color.

**返回:**
java.awt.Color