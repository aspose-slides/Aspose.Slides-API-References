---
title: Convert.GetOutPathCallback
second_title: Aspose.Slides 适用于 Android 的 Java API 参考
description: 
type: docs
url: /zh/com.aspose.slides/convert.getoutpathcallback/
---```
public static interface Convert.GetOutPathCallback
```
## 方法

| 方法 | 描述 |
| --- | --- |
| [invoke(Slide slide, int index)](#invoke-com.aspose.slides.Slide-int-) | 回调将在每个 [Slide](../../com.aspose.slides/slide) 时被调用，返回预期的输出路径。 |
### invoke(Slide slide, int index) {#invoke-com.aspose.slides.Slide-int-}
```
public abstract String invoke(Slide slide, int index)
```

回调将在每个 [Slide](../../com.aspose.slides/slide) 时被调用，返回预期的输出路径。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| slide | [Slide](../../com.aspose.slides/slide) | 当前迭代的幻灯片 |
| index | int | 当前幻灯片的索引 |

**返回:**
java.lang.String