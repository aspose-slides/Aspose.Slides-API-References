---
title: IDuotoneEffectiveData
second_title: Aspose.Slides for Android 的 Java API 参考
description: 表示 Duotone 效果的不可变对象。
type: docs
url: /zh/com.aspose.slides/iduotoneeffectivedata/
---
**所有已实现的接口：**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IDuotoneEffectiveData extends IEffectEffectiveData
```

表示 Duotone 效果的不可变对象。对于每个像素，通过线性插值将 clr1 和 clr2 组合，以确定该像素的新颜色。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getColor1()](#getColor1--) | 返回暗像素的目标颜色格式。 |
| [getColor2()](#getColor2--) | 返回亮像素的目标颜色格式。 |
### getColor1() {#getColor1--}
```
public abstract Integer getColor1()
```


返回暗像素的目标颜色格式。只读 java.lang.Integer.

**返回：**
java.lang.Integer
### getColor2() {#getColor2--}
```
public abstract Integer getColor2()
```


返回亮像素的目标颜色格式。只读 java.lang.Integer.

**返回：**
java.lang.Integer