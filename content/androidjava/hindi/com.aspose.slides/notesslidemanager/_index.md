---
title: NotesSlideManager
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: नोट्स स्लाइड प्रबंधक।
type: docs
url: /hi/com.aspose.slides/notesslidemanager/
---
**विरासत:**  
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफेस:**  
[com.aspose.slides.INotesSlideManager](../../com.aspose.slides/inotesslidemanager)  
```
public final class NotesSlideManager extends DomObject<Slide> implements INotesSlideManager
```

नोट्स स्लाइड प्रबंधक।

--------------------

> ```
> The following example shows how to Add Notes to specific ProwerPoint Presentation slide.
>  
>  // एक Presentation ऑब्जेक्ट बनाता है जो प्रस्तुति फ़ाइल का प्रतिनिधित्व करता है
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // पहले स्लाइड पर नोट्स जोड़ें
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
>  // एक Presentation ऑब्जेक्ट बनाता है जो प्रस्तुति फ़ाइल का प्रतिनिधित्व करता है
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
## विधियां

| विधि | विवरण |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | वर्तमान स्लाइड के लिए नोट्स स्लाइड लौटाता है। |
| [addNotesSlide()](#addNotesSlide--) | वर्तमान स्लाइड के लिए नोट्स स्लाइड लौटाता है, यदि नहीं है तो एक नई बनाता है। |
| [removeNotesSlide()](#removeNotesSlide--) | वर्तमान स्लाइड की नोट्स स्लाइड को हटाता है। |
### getNotesSlide() {#getNotesSlide--}
```
public final INotesSlide getNotesSlide()
```


वर्तमान स्लाइड के लिए नोट्स स्लाइड लौटाता है। यदि स्लाइड में नोट्स स्लाइड नहीं है तो यह null लौटाता है। केवल पढ़ने योग्य [INotesSlide](../../com.aspose.slides/inotesslide)।

**वापसी:**  
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public final INotesSlide addNotesSlide()
```


वर्तमान स्लाइड के लिए नोट्स स्लाइड लौटाता है, यदि नहीं है तो एक नई बनाता है।

**वापसी:**  
[INotesSlide](../../com.aspose.slides/inotesslide) - [NotesSlide](../../com.aspose.slides/notesslide)(\#getNotesSlide.getNotesSlide) इस स्लाइड के लिए।
### removeNotesSlide() {#removeNotesSlide--}
```
public final void removeNotesSlide()
```


वर्तमान स्लाइड की नोट्स स्लाइड को हटाता है।