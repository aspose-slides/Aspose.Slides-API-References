---
title: BrowsedAtKiosk
second_title: Aspose.Slides для Android через справочник Java API
description: Просмотр в режиме киоска на полном экране
type: docs
url: /ru/com.aspose.slides/browsedatkiosk/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class BrowsedAtKiosk extends SlideShowType
```

Просмотр в режиме киоска (полный экран)

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
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [BrowsedAtKiosk()](#BrowsedAtKiosk--) | Инициализирует новый экземпляр класса BrowsedAtKiosk. |
### BrowsedAtKiosk() {#BrowsedAtKiosk--}
```
public BrowsedAtKiosk()
```


Инициализирует новый экземпляр класса BrowsedAtKiosk.

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