---
title: SmartArtShape
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: SmartArt आकार का प्रतिनिधित्व करता है
type: docs
url: /hi/com.aspose.slides/smartartshape/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.ISmartArtShape](../../com.aspose.slides/ismartartshape)
```
public class SmartArtShape extends GeometryShape implements ISmartArtShape
```

SmartArt आकार का प्रतिनिधित्व करता है
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getShapeType()](#getShapeType--) | ज्यमिति प्रीसेट प्रकार को लौटाता है या सेट करता है। |
| [setShapeType(int value)](#setShapeType-int-) | ज्यमिति प्रीसेट प्रकार को लौटाता है या सेट करता है। |
| [getTextFrame()](#getTextFrame--) | SmartArt आकार का टेक्स्ट लौटाता है। |
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

ज्यमिति प्रीसेट प्रकार को लौटाता है या सेट करता है। नोट: मान बदलने पर सभी समायोजन मान डिफ़ॉल्ट मानों पर रीसेट हो जाएंगे। पढ़ें/लिखें [ShapeType](../../com.aspose.slides/shapetype).

**रिटर्न मान:**  
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

ज्यमिति प्रीसेट प्रकार को लौटाता है या सेट करता है। नोट: मान बदलने पर सभी समायोजन मान डिफ़ॉल्ट मानों पर रीसेट हो जाएंगे। पढ़ें/लिखें [ShapeType](../../com.aspose.slides/shapetype).

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

SmartArt आकार का टेक्स्ट लौटाता है। केवल पढ़ने योग्य [ITextFrame](../../com.aspose.slides/itextframe).

**रिटर्न मान:**  
[ITextFrame](../../com.aspose.slides/itextframe)