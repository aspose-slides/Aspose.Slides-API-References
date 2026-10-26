---
title: INotesSlideManager
second_title: Aspose.Slides for Android via Java API Reference
description: Notes slide manager.
type: docs
url: /hi/com.aspose.slides/inotesslidemanager/
---```
public interface INotesSlideManager
```

नोट्स स्लाइड मैनेजर।
## मेथड्स

| विधि | विवरण |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | वर्तमान स्लाइड के लिए नोट्स स्लाइड लौटाता है। |
| [addNotesSlide()](#addNotesSlide--) | वर्तमान स्लाइड के लिए नोट्स स्लाइड लौटाता है, यदि नहीं है तो एक बनाता है। |
| [removeNotesSlide()](#removeNotesSlide--) | वर्तमान स्लाइड की नोट्स स्लाइड हटाता है। |
### getNotesSlide() {#getNotesSlide--}
```
public abstract INotesSlide getNotesSlide()
```


वर्तमान स्लाइड के लिए नोट्स स्लाइड लौटाता है। यदि स्लाइड के पास नोट्स स्लाइड नहीं है तो null लौटाता है। केवल-पढ़ने योग्य [INotesSlide](../../com.aspose.slides/inotesslide)।

**वापसी:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public abstract INotesSlide addNotesSlide()
```


वर्तमान स्लाइड के लिए नोट्स स्लाइड लौटाता है, यदि नहीं है तो एक बनाता है।

**वापसी:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [INotesSlide](../../com.aspose.slides/inotesslide) इस स्लाइड के लिए।
### removeNotesSlide() {#removeNotesSlide--}
```
public abstract void removeNotesSlide()
```


वर्तमान स्लाइड की नोट्स स्लाइड हटाता है।