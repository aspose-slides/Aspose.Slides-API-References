---
title: BrowsedAtKiosk
second_title: Aspose.Slides για Android μέσω Java API Reference
description: Περιήγηση σε περίπτερο σε πλήρη οθόνη
type: docs
url: /el/com.aspose.slides/browsedatkiosk/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class BrowsedAtKiosk extends SlideShowType
```

Browsed at a kiosk (full screen)

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
## Κατασκευαστές

| Constructor | Περιγραφή |
| --- | --- |
| [BrowsedAtKiosk()](#BrowsedAtKiosk--) | Αρχικοποιεί μια νέα περίπτωση της κλάσης BrowsedAtKiosk. |
### BrowsedAtKiosk() {#BrowsedAtKiosk--}
```
public BrowsedAtKiosk()
```


Αρχικοποιεί μια νέα στιγμή της κλάσης BrowsedAtKiosk.

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