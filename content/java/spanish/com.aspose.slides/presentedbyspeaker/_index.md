---
title: PresentedBySpeaker
second_title: Referencia de API de Aspose.Slides para Java
description: Presentado por un ponente en pantalla completa
type: docs
url: /es/com.aspose.slides/presentedbyspeaker/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class PresentedBySpeaker extends SlideShowType
```

Presentado por un ponente (pantalla completa)

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
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PresentedBySpeaker()](#PresentedBySpeaker--) | Inicializa una nueva instancia de la clase PresentedBySpeaker. |
### PresentedBySpeaker() {#PresentedBySpeaker--}
```
public PresentedBySpeaker()
```


Inicializa una nueva instancia de la clase PresentedBySpeaker.

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