---
title: Convert.GetOutPathCallback
second_title: Aspose.Slides for Java API Reference
description: 
type: docs
url: /zh-hant/com.aspose.slides/convert.getoutpathcallback/
---```
public static interface Convert.GetOutPathCallback
```
## 方法

| 方法 | 說明 |
| --- | --- |
| [invoke(Slide slide, int index)](#invoke-com.aspose.slides.Slide-int-) | 針對每個 [Slide](../../com.aspose.slides/slide) 觸發的回呼，預期回傳輸出路徑。 |
### invoke(Slide slide, int index) {#invoke-com.aspose.slides.Slide-int-}
```
public abstract String invoke(Slide slide, int index)
```

針對每個 [Slide](../../com.aspose.slides/slide) 觸發的回呼，預期回傳輸出路徑。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| slide | [Slide](../../com.aspose.slides/slide) | 目前正在迭代的投影片 |
| index | int | 目前投影片的索引 |

**傳回值:**
java.lang.String