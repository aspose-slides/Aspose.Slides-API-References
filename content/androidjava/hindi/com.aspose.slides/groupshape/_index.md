---
title: GroupShape
second_title: Aspose.Slides for Android के माध्यम से Java API संदर्भ
description: एक स्लाइड पर आकारों के समूह का प्रतिनिधित्व करता है।
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

एक स्लाइड पर आकारों के समूह का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | एक आकार के लिए रेखा स्वरूपण गुणों को समाहित करने वाले LineFormat ऑब्जेक्ट को लौटाता है। |
| [getGroupShapeLock()](#getGroupShapeLock--) | आकार के लॉक को लौटाता है। |
| [getShapes()](#getShapes--) | समूह के भीतर स्थित आकारों के संग्रह को लौटाता है। |
### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```


एक आकार के लिए रेखा स्वरूपण गुणों को समाहित करने वाले LineFormat ऑब्जेक्ट को लौटाता है। नोट: GroupShape ऑब्जेक्ट्स के लिए null लौटाता है क्योंकि उनके पास रेखा गुण नहीं होते। केवल पढ़ने योग्य [ILineFormat](../../com.aspose.slides/ilineformat).

**वापसी:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getGroupShapeLock() {#getGroupShapeLock--}
```
public final IGroupShapeLock getGroupShapeLock()
```


आकार के लॉक को लौटाता है। केवल पढ़ने योग्य [IGroupShapeLock](../../com.aspose.slides/igroupshapelock).

**वापसी:**
[IGroupShapeLock](../../com.aspose.slides/igroupshapelock)
### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```


समूह के भीतर स्थित आकारों के संग्रह को लौटाता है। केवल पढ़ने योग्य [IShapeCollection](../../com.aspose.slides/ishapecollection).

**वापसी:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)