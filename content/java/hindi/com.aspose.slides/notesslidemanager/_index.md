---
title: NotesSlideManager
second_title: Aspose.Slides के लिए Java API संदर्भ
description: नोट्स स्लाइड मैनेजर।
type: docs
url: /hi/com.aspose.slides/notesslidemanager/
---
**विरासत:**  
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.INotesSlideManager](../../com.aspose.slides/inotesslidemanager)  
```
public final class NotesSlideManager extends DomObject<Slide> implements INotesSlideManager
```

Notes slide manager.

--------------------

> ```
> The following example shows how to Add Notes to specific ProwerPoint Presentation slide.
>  
>  // एक Presentation ऑब्जेक्ट बनाएं जो प्रस्तुति फ़ाइल का प्रतिनिधित्व करता है
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // पहले स्लाइड में नोट्स जोड़ें
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      INotesSlide noteSlide = mgr.addNotesSlide();
>      noteSlide.getNotesTextFrame().setText("Your Notes");
>      // प्रस्तुति को डिस्क पर सहेजें
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to remove Notes from PowerPoint Presentation's specific slide.
>  
>  // एक Presentation ऑब्जेक्ट बनाएं जो प्रस्तुति फ़ाइल का प्रतिनिधित्व करता है
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // पहले स्लाइड के नोट्स हटाना
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      mgr.removeNotesSlide();
>      // प्रस्तुति को डिस्क पर सहेजें
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | Returns the notes slide for the current slide. |
| [addNotesSlide()](#addNotesSlide--) | Returns the notes slide for the current slide, creating one if there isn't. |
| [removeNotesSlide()](#removeNotesSlide--) | Removes notes slide of the current slide. |
### getNotesSlide() {#getNotesSlide--}
```
public final INotesSlide getNotesSlide()
```

वर्तमान स्लाइड के लिए नोट्स स्लाइड लौटाता है। यदि स्लाइड में नोट्स स्लाइड नहीं है तो null लौटाता है। केवल-पढ़ने योग्य [INotesSlide](../../com.aspose.slides/inotesslide)।

**रिटर्न:**  
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public final INotesSlide addNotesSlide()
```

वर्तमान स्लाइड के लिए नोट्स स्लाइड लौटाता है, यदि नहीं है तो नई बनाता है।

**रिटर्न:**  
[INotesSlide](../../com.aspose.slides/inotesslide) - [NotesSlide](../../com.aspose.slides/notesslide)(\#getNotesSlide.getNotesSlide) इस स्लाइड के लिए।
### removeNotesSlide() {#removeNotesSlide--}
```
public final void removeNotesSlide()
```

वर्तमान स्लाइड की नोट्स स्लाइड को हटाता है।