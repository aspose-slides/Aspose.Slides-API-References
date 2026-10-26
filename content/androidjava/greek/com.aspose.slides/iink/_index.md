---
title: IInk
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
description: Αναπαριστά ένα αντικείμενο μελάνης σε μια διαφάνεια.
type: docs
url: /el/com.aspose.slides/iink/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IInk extends IGraphicalObject
```

Αναπαριστά ένα αντικείμενο μελάνης σε μια διαφάνεια.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getTraces()](#getTraces--) | Λαμβάνει όλα τα ίχνη που περιέχονται στο στοιχείο IInk [IInkTrace](../../com.aspose.slides/iinktrace). |
### getTraces() {#getTraces--}
```
public abstract IInkTrace[] getTraces()
```


Λαμβάνει όλα τα ίχνη που περιέχονται στο στοιχείο IInk [IInkTrace](../../com.aspose.slides/iinktrace). Μόνο για ανάγνωση.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
com.aspose.slides.IInkTrace[]