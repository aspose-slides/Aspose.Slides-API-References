---
title: IGroupShape
second_title: Aspose.Slides for Java API संदर्भ
description: एक स्लाइड पर शेप्स के समूह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/igroupshape/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IShape](../../com.aspose.slides/ishape)
```
public interface IGroupShape extends IShape
```

एक स्लाइड पर शेप्स के समूह का प्रतिनिधित्व करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getGroupShapeLock()](#getGroupShapeLock--) | शेप के लॉक लौटाता है। |
| [getShapes()](#getShapes--) | समूह के भीतर के शेप्स का संग्रह लौटाता है। |
### getGroupShapeLock() {#getGroupShapeLock--}
```
public abstract IGroupShapeLock getGroupShapeLock()
```


शेप के लॉक लौटाता है। केवल-पढ़ने योग्य [IGroupShapeLock](../../com.aspose.slides/igroupshapelock)।

**वापसी:**
[IGroupShapeLock](../../com.aspose.slides/igroupshapelock)
### getShapes() {#getShapes--}
```
public abstract IShapeCollection getShapes()
```


समूह के भीतर के शेप्स का संग्रह लौटाता है। केवल-पढ़ने योग्य [IShapeCollection](../../com.aspose.slides/ishapecollection)।

**वापसी:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)