---
title: BrowsedByIndividual
second_title: Aspose.Slides for Android via Java API 参考
description: 个人浏览窗口
type: docs
url: /zh/com.aspose.slides/browsedbyindividual/
---
**继承:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class BrowsedByIndividual extends SlideShowType
```

个人浏览（窗口）

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
## Constructors

| Constructor | Description |
| --- | --- |
| [BrowsedByIndividual()](#BrowsedByIndividual--) | Initializes a new instance of the BrowsedByIndividual class. |
## Methods

| Method | Description |
| --- | --- |
| [getShowScrollbar()](#getShowScrollbar--) | Show Scroll Bar in Window |
| [setShowScrollbar(boolean value)](#setShowScrollbar-boolean-) | Show Scroll Bar in Window |
### BrowsedByIndividual() {#BrowsedByIndividual--}
```
public BrowsedByIndividual()
```

Initializes a new instance of the BrowsedByIndividual class.

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

Show Scroll Bar in Window

**Returns:**
boolean
### setShowScrollbar(boolean value) {#setShowScrollbar-boolean-}
```
public final void setShowScrollbar(boolean value)

Show Scroll Bar in Window

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |