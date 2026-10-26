---
title: IColorReplaceEffectiveData
second_title: Aspose.Slides Java API 参考
description: 表示颜色替换效果的不可变对象。
type: docs
url: /zh/com.aspose.slides/icolorreplaceeffectivedata/
---
**所有已实现的接口:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IColorReplaceEffectiveData extends IEffectEffectiveData
```

表示颜色替换效果的不可变对象。所有效果颜色都被更改为固定颜色。Alpha 值不受影响。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getColor()](#getColor--) | 返回用于替换每个像素颜色的颜色格式。 |
### getColor() {#getColor--}
```
public abstract Color getColor()
```

返回用于替换每个像素颜色的颜色格式。只读 java.awt.Color.

**返回:**
java.awt.Color