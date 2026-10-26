---
title: ILegacyDiagram
second_title: Aspose.Slides के लिए Java API संदर्भ
description: एक लीगेसी डाइग्राम ऑब्जेक्ट का प्रतिनिधित्व करता है
type: docs
url: /hi/com.aspose.slides/ilegacydiagram/
---
**सभी लागू इंटरफ़ेस:** 
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ILegacyDiagram extends IGraphicalObject
```

एक लीगेसी डाइग्राम ऑब्जेक्ट का प्रतिनिधित्व करता है
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | लीगेसी डाइग्राम को संपादनीय SmartArt ऑब्जेक्ट में परिवर्तित करता है। |
| [convertToGroupShape()](#convertToGroupShape--) | लीगेसी डाइग्राम को संपादनीय समूह आकार में परिवर्तित करता है। |
### convertToSmartArt() {#convertToSmartArt--}
```
public abstract ISmartArt convertToSmartArt()
```

लीगेसी डाइग्राम को संपादनीय SmartArt ऑब्जेक्ट में परिवर्तित करता है। बनाया गया SmartArt ऑब्जेक्ट पैरेंट समूह आकार में उसी स्थिति पर जोड़ता है।

**रिटर्न:** 
[ISmartArt](../../com.aspose.slides/ismartart) - बनाया गया SmartArt ऑब्जेक्ट।
### convertToGroupShape() {#convertToGroupShape--}
```
public abstract IGroupShape convertToGroupShape()
```

लीगेसी डाइग्राम को संपादनीय समूह आकार में परिवर्तित करता है। बनाया गया GroupShape ऑब्जेक्ट पैरेंट समूह आकार में उसी स्थिति पर जोड़ता है।

**रिटर्न:** 
[IGroupShape](../../com.aspose.slides/igroupshape) - बनाया गया GroupShape ऑब्जेक्ट।