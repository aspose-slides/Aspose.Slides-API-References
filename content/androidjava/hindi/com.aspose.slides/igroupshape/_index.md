---
title: IGroupShape
second_title: Aspose.Slides एंड्रॉइड के लिए जावा API रेफ़रेंस के माध्यम से
description: स्लाइड पर आकृतियों के समूह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/igroupshape/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IShape](../../com.aspose.slides/ishape)
```
public interface IGroupShape extends IShape
```

एक स्लाइड पर आकृतियों के समूह का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getGroupShapeLock()](#getGroupShapeLock--) | shape के लॉक लौटाता है। |
| [getShapes()](#getShapes--) | समूह के भीतर आकृतियों का संग्रह लौटाता है। |
### getGroupShapeLock() {#getGroupShapeLock--}
```
public abstract IGroupShapeLock getGroupShapeLock()
```

shape के लॉक लौटाता है। केवल-पढ़ने योग्य [IGroupShapeLock](../../com.aspose.slides/igroupshapelock)।

**वापसी:**
[IGroupShapeLock](../../com.aspose.slides/igroupshapelock)
### getShapes() {#getShapes--}
```
public abstract IShapeCollection getShapes()
```

समूह के भीतर आकृतियों का संग्रह लौटाता है। केवल-पढ़ने योग्य [IShapeCollection](../../com.aspose.slides/ishapecollection)।

**वापसी:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)