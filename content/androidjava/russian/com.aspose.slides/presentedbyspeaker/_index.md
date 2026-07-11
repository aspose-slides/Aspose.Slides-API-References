---
title: PresentedBySpeaker
second_title: Справочник API Aspose.Slides для Android через Java
description: Представлено спикером в полноэкранном режиме
type: docs
url: /ru/com.aspose.slides/presentedbyspeaker/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class PresentedBySpeaker extends SlideShowType
```

Представлено спикером (полный экран)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PresentedBySpeaker()](#PresentedBySpeaker--) | Инициализирует новый экземпляр класса PresentedBySpeaker. |
### PresentedBySpeaker() {#PresentedBySpeaker--}
```
public PresentedBySpeaker()
```


Инициализирует новый экземпляр класса PresentedBySpeaker.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```