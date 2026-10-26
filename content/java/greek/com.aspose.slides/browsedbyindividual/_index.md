---
title: BrowsedByIndividual
second_title: Αναφορά API Aspose.Slides για Java
description: Παράθυρο περιήγησης ανά άτομο
type: docs
url: /el/com.aspose.slides/browsedbyindividual/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class BrowsedByIndividual extends SlideShowType
```

Περιήγηση ανά άτομο (παράθυρο)

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
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [BrowsedByIndividual()](#BrowsedByIndividual--) | Αρχικοποιεί ένα νέο παράδειγμα της κλάσης BrowsedByIndividual. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getShowScrollbar()](#getShowScrollbar--) | Εμφάνιση γραμμής κύλισης στο παράθυρο |
| [setShowScrollbar(boolean value)](#setShowScrollbar-boolean-) | Εμφάνιση γραμμής κύλισης στο παράθυρο |
### BrowsedByIndividual() {#BrowsedByIndividual--}
```
public BrowsedByIndividual()
```

Αρχικοποιεί ένα νέο παράδειγμα της κλάσης BrowsedByIndividual.

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

Εμφάνιση γραμμής κύλισης στο παράθυρο

**Επιστρέφει:**
boolean
### setShowScrollbar(boolean value) {#setShowScrollbar-boolean-}
```
public final void setShowScrollbar(boolean value)
```

Εμφάνιση γραμμής κύλισης στο παράθυρο

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |