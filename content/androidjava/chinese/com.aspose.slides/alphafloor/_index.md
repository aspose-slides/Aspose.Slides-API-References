---
title: AlphaFloor
second_title: Aspose.Slides for Android via Java API 参考
description: 表示 Alpha Floor 效果。
type: docs
url: /zh/com.aspose.slides/alphafloor/
---
**继承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**所有实现的接口:**
[com.aspose.slides.IAlphaFloor](../../com.aspose.slides/ialphafloor), com.aspose.slides.IVisualEffect
```
public final class AlphaFloor extends ImageTransformOperation implements IAlphaFloor, IVisualEffect
```

表示 Alpha Floor 效果。小于 100% 的 Alpha（不透明度）值将被更改为零。换句话说，任何部分透明的内容都会变为完全透明。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getEffective()](#getEffective--) | 获取在应用继承后的有效 Alpha Floor 效果数据。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 [AlphaFloor](../../com.aspose.slides/alphafloor) 是否等于当前的 [AlphaFloor](../../com.aspose.slides/alphafloor)。 |
| [hashCode()](#hashCode--) | 充当特定类型的哈希函数。 |
### getEffective() {#getEffective--}
```
public final IAlphaFloorEffectiveData getEffective()
```

获取在应用继承后的有效 Alpha Floor 效果数据。

**返回:**
[IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata) - 一个 [IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata)。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

确定指定的 [AlphaFloor](../../com.aspose.slides/alphafloor) 是否等于当前的 [AlphaFloor](../../com.aspose.slides/alphafloor)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要比较的 [AlphaFloor](../../com.aspose.slides/alphafloor)。 |

**返回:**
boolean - 如果对象相等则为 true；否则为 false。
### hashCode() {#hashCode--}
```
public int hashCode()
```

充当特定类型的哈希函数。

**返回:**
int - 当前对象的哈希码。