---
title: GroupShape
second_title: Aspose.Slides के लिए Java API संदर्भ
description: एक स्लाइड पर आकृतियों के समूह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/groupshape/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IGroupShape](../../com.aspose.slides/igroupshape)
```
public class GroupShape extends Shape implements IGroupShape
```

एक स्लाइड पर आकृतियों के समूह का प्रतिनिधित्व करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | LineFormat ऑब्जेक्ट लौटाता है जिसमें shape के लिए लाइन फ़ॉर्मेटिंग गुण होते हैं। |
| [getGroupShapeLock()](#getGroupShapeLock--) | shape की लॉक लौटाता है। |
| [getShapes()](#getShapes--) | समूह के भीतर की shapes का संग्रह लौटाता है। |
### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

LineFormat ऑब्जेक्ट लौटाता है जिसमें shape के लिए लाइन फ़ॉर्मेटिंग गुण होते हैं। ध्यान दें: GroupShape ऑब्जेक्ट्स के लिए null लौटाता है क्योंकि इनके पास लाइन प्रॉपर्टीज़ नहीं होती। केवल पढ़ने योग्य [ILineFormat](../../com.aspose.slides/ilineformat)।

**वापसी:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getGroupShapeLock() {#getGroupShapeLock--}
```
public final IGroupShapeLock getGroupShapeLock()
```

shape की लॉक लौटाता है। केवल पढ़ने योग्य [IGroupShapeLock](../../com.aspose.slides/igroupshapelock)।

**वापसी:**
[IGroupShapeLock](../../com.aspose.slides/igroupshapelock)
### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```

समूह के भीतर की shapes का संग्रह लौटाता है। केवल पढ़ने योग्य [IShapeCollection](../../com.aspose.slides/ishapecollection)।

**वापसी:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)