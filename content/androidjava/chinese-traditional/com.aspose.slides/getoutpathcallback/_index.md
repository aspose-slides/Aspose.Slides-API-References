---
title: Convert.GetOutPathCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /zh-hant/com.aspose.slides/convert.getoutpathcallback/
---```
public static interface Convert.GetOutPathCallback
```
## 方法

| 方法 | 說明 |
| --- | --- |
| [invoke(Slide slide, int index)](#invoke-com.aspose.slides.Slide-int-) | 回呼會在每個[Slide](../../com.aspose.slides/slide)時被呼叫，預期返回輸出路徑。 |
### invoke(Slide slide, int index) {#invoke-com.aspose.slides.Slide-int-}
```
public abstract String invoke(Slide slide, int index)
```

回呼會在每個[Slide](../../com.aspose.slides/slide)時被呼叫，預期返回輸出路徑。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| slide | [Slide](../../com.aspose.slides/slide) | 目前迭代的投影片 |
| index | int | 目前投影片的索引 |

**返回值:**
java.lang.String