---
title: ILegacyDiagram
second_title: Java API संदर्भ के माध्यम से Android के लिए Aspose.Slides
description: लेगसी डायग्राम ऑब्जेक्ट का प्रतिनिधित्व करता है
type: docs
url: /hi/com.aspose.slides/ilegacydiagram/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ILegacyDiagram extends IGraphicalObject
```

लेगसी डायग्राम ऑब्जेक्ट का प्रतिनिधित्व करता है
## विधियां

| विधि | विवरण |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | लेगसी डायग्राम को संपादन योग्य SmartArt ऑब्जेक्ट में परिवर्तित करता है। |
| [convertToGroupShape()](#convertToGroupShape--) | लेगसी डायग्राम को संपादन योग्य समूह आकार में परिवर्तित करता है। |
### convertToSmartArt() {#convertToSmartArt--}
```
public abstract ISmartArt convertToSmartArt()
```

लेगसी डायग्राम को संपादन योग्य SmartArt ऑब्जेक्ट में परिवर्तित करता है। बनाया गया SmartArt ऑब्जेक्ट उसी स्थिति में पैरेंट समूह आकार में जोड़ता है।

**वापसी:**
[ISmartArt](../../com.aspose.slides/ismartart) - बनाया गया SmartArt ऑब्जेक्ट।
### convertToGroupShape() {#convertToGroupShape--}
```
public abstract IGroupShape convertToGroupShape()
```

लेगसी डायग्राम को संपादन योग्य समूह आकार में परिवर्तित करता है। बनाया गया GroupShape ऑब्जेक्ट उसी स्थिति में पैरेंट समूह आकार में जोड़ता है।

**वापसी:**
[IGroupShape](../../com.aspose.slides/igroupshape) - बनाया गया GroupShape ऑब्जेक्ट।