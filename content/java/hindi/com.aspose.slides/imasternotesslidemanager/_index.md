---
title: IMasterNotesSlideManager
second_title: Aspose.Slides for Java API Reference
description: Master notes slide manager.
type: docs
url: /hi/com.aspose.slides/imasternotesslidemanager/
---```
public interface IMasterNotesSlideManager
```

मुख्य नोट्स स्लाइड प्रबंधक।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getMasterNotesSlide()](#getMasterNotesSlide--) | यदि कोई मौजूद है तो इस प्रस्तुतिकरण की सभी नोट्स स्लाइडों के लिए एक मास्टर लौटाता है, अन्यथा null लौटाता है। |
| [setDefaultMasterNotesSlide()](#setDefaultMasterNotesSlide--) | संबंधित नोट्स स्लाइड के लिए डिफ़ॉल्ट मास्टर नोट्स स्लाइड सेट करता है। |
| [removeMasterNotesSlide()](#removeMasterNotesSlide--) | मास्टर नोट्स स्लाइड को हटाता है। |
### getMasterNotesSlide() {#getMasterNotesSlide--}
```
public abstract IMasterNotesSlide getMasterNotesSlide()
```

यदि कोई उपलब्ध है तो इस प्रस्तुतिकरण की सभी नोट्स स्लाइडों के लिए एक मास्टर लौटाता है, अन्यथा null लौटाता है। केवल-पढ़ने योग्य [IMasterNotesSlide](../../com.aspose.slides/imasternotesslide)।

**रिटर्न:**  
[IMasterNotesSlide](../../com.aspose.slides/imasternotesslide)
### setDefaultMasterNotesSlide() {#setDefaultMasterNotesSlide--}
```
public abstract IMasterNotesSlide setDefaultMasterNotesSlide()
```

संबंधित नोट्स स्लाइड के लिए डिफ़ॉल्ट मास्टर नोट्स स्लाइड सेट करता है।

**रिटर्न:**  
[IMasterNotesSlide](../../com.aspose.slides/imasternotesslide) - डिफ़ॉल्ट मास्टर नोट्स स्लाइड [IMasterNotesSlide](../../com.aspose.slides/imasternotesslide)
### removeMasterNotesSlide() {#removeMasterNotesSlide--}
```
public abstract void removeMasterNotesSlide()
```

मास्टर नोट्स स्लाइड को हटाता है।