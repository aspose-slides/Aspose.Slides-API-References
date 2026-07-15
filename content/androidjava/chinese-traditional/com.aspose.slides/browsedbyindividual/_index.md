---
title: BrowsedByIndividual
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 個人瀏覽視窗
type: docs
url: /zh-hant/com.aspose.slides/browsedbyindividual/
---
**繼承：**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class BrowsedByIndividual extends SlideShowType
```

以個人方式瀏覽（視窗）

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [BrowsedByIndividual()](#BrowsedByIndividual--) | 初始化 BrowsedByIndividual 類別的新執行個體。 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getShowScrollbar()](#getShowScrollbar--) | 在視窗中顯示捲動條 |
| [setShowScrollbar(boolean value)](#setShowScrollbar-boolean-) | 在視窗中顯示捲動條 |
### BrowsedByIndividual() {#BrowsedByIndividual--}
```
public BrowsedByIndividual()
```

初始化 BrowsedByIndividual 類別的新執行個體。

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

### getShowScrollbar() {#getShowScrollbar--}
```
public final boolean getShowScrollbar()
```

在視窗中顯示捲動條

**傳回值：**
boolean
### setShowScrollbar(boolean value) {#setShowScrollbar-boolean-}
```
public final void setShowScrollbar(boolean value)
```

在視窗中顯示捲動條

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |