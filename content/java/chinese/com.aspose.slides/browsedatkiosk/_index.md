---
title: BrowsedAtKiosk
second_title: Aspose.Slides Java API 参考
description: 在自助终端全屏浏览
type: docs
url: /zh/com.aspose.slides/browsedatkiosk/
---
**继承：**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class BrowsedAtKiosk extends SlideShowType
```

在自助终端浏览（全屏）

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [BrowsedAtKiosk()](#BrowsedAtKiosk--) | 初始化 BrowsedAtKiosk 类的新实例。 |
### BrowsedAtKiosk() {#BrowsedAtKiosk--}
```
public BrowsedAtKiosk()
```

初始化 BrowsedAtKiosk 类的新实例。

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```