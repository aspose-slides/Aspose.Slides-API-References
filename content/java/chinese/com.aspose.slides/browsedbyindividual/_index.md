---
title: BrowsedByIndividual
second_title: Aspose.Slides Java API 参考
description: 个人浏览窗口
type: docs
url: /zh/com.aspose.slides/browsedbyindividual/
---
**继承:**  
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)  
```
public class BrowsedByIndividual extends SlideShowType
```

按个人浏览（窗口）

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
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [BrowsedByIndividual()](#BrowsedByIndividual--) | 初始化 BrowsedByIndividual 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getShowScrollbar()](#getShowScrollbar--) | 在窗口中显示滚动条 |
| [setShowScrollbar(boolean value)](#setShowScrollbar-boolean-) | 在窗口中显示滚动条 |
### BrowsedByIndividual() {#BrowsedByIndividual--}
```
public BrowsedByIndividual()
```

初始化 BrowsedByIndividual 类的新实例。

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

在窗口中显示滚动条

**返回:**  
boolean
### setShowScrollbar(boolean value) {#setShowScrollbar-boolean-}
```
public final void setShowScrollbar(boolean value)
```

在窗口中显示滚动条

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |