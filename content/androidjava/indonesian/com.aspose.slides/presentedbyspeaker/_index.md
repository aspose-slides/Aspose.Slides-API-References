---
title: PresentedBySpeaker
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Ditampilkan oleh pembicara layar penuh
type: docs
url: /id/com.aspose.slides/presentedbyspeaker/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class PresentedBySpeaker extends SlideShowType
```

Ditampilkan oleh pembicara (layar penuh)

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
## Konstruktor

| Constructor | Deskripsi |
| --- | --- |
| [PresentedBySpeaker()](#PresentedBySpeaker--) | Menginisialisasi instance baru dari kelas PresentedBySpeaker. |
### PresentedBySpeaker() {#PresentedBySpeaker--}
```
public PresentedBySpeaker()
```


Menginisialisasi instance baru dari kelas PresentedBySpeaker.

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