---
title: GeometryShape
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: सभी ज्यामितीय आकारों के लिए पैरेंट क्लास का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/geometryshape/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)  
```
public abstract class GeometryShape extends Shape implements IGeometryShape
```

सभी ज्यामितीय आकृतियों के लिए पैरेंट क्लास को दर्शाता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getGeometryPaths()](#getGeometryPaths--) | ज्यामितीय आकृति के पथ की प्रतिलिपि लौटाता है। |
| [setGeometryPath(IGeometryPath geometryPath)](#setGeometryPath-com.aspose.slides.IGeometryPath-) | [IGeometryPath](../../com.aspose.slides/igeometrypath) ऑब्जेक्ट से आकृति ज्यामिति को अपडेट करता है। |
| [setGeometryPaths(IGeometryPath[] geometryPaths)](#setGeometryPaths-com.aspose.slides.IGeometryPath---) | [IGeometryPath](../../com.aspose.slides/igeometrypath) के array से आकृति ज्यामिति को अपडेट करता है। |
| [getShapeStyle()](#getShapeStyle--) | आकृति की शैली वस्तु लौटाता है। |
| [getShapeType()](#getShapeType--) | ज्यामितीय प्रीसेट प्रकार को लौटाता या सेट करता है। |
| [setShapeType(int value)](#setShapeType-int-) | ज्यामितीय प्रीसेट प्रकार को लौटाता या सेट करता है। |
| [getAdjustments()](#getAdjustments--) | आकृति के समायोजन मानों का संग्रह लौटाता है। |
| [createShapeElements()](#createShapeElements--) | आकृति के तत्वों का array बनाता और लौटाता है। |

### getGeometryPaths() {#getGeometryPaths--}
```
public final IGeometryPath[] getGeometryPaths()
```

ज्यामितीय आकृति के पथ की प्रतिलिपि लौटाता है। निर्देशांक आकृति के बाएँ-ऊपर कोने के सापेक्ष होते हैं।

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      GeometryShape shape = (GeometryShape) pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 200, 100);
>      IGeometryPath geometryPath = shape.getGeometryPaths()[0];
>      geometryPath.lineTo(100, 50, 1);
>      geometryPath.lineTo(100, 50, 4);
>      shape.setGeometryPath(geometryPath);
>      pres.save("output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**  
com.aspose.slides.IGeometryPath[] - Array of [IGeometryPath](../../com.aspose.slides/igeometrypath)

### setGeometryPath(IGeometryPath geometryPath) {#setGeometryPath-com.aspose.slides.IGeometryPath-}
```
public final void setGeometryPath(IGeometryPath geometryPath)
```

[IGeometryPath](../../com.aspose.slides/igeometrypath) ऑब्जेक्ट से आकृति ज्यामिति को अपडेट करता है। निर्देशांक आकृति के बाएँ-ऊपर कोने के सापेक्ष होने चाहिए। आकृति के प्रकार (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) को [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom) में बदलता है।

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      GeometryShape shape = (GeometryShape) pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 200, 100);
>      GeometryPath geometryPath0 = new GeometryPath();
>      geometryPath0.moveTo(0, 0);
>      geometryPath0.lineTo(shape.getWidth(), 0);
>      geometryPath0.lineTo(shape.getWidth(), shape.getHeight()/3);
>      geometryPath0.lineTo(0, shape.getHeight() / 3);
>      geometryPath0.closeFigure();
>      GeometryPath geometryPath1 = new GeometryPath();
>      geometryPath1.moveTo(0, shape.getHeight()/3 * 2);
>      geometryPath1.lineTo(shape.getWidth(), shape.getHeight() / 3 * 2);
>      geometryPath1.lineTo(shape.getWidth(), shape.getHeight());
>      geometryPath1.lineTo(0, shape.getHeight());
>      geometryPath1.closeFigure();
>      shape.setGeometryPaths(new GeometryPath[] { geometryPath0, geometryPath1});
>      pres.save("output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| geometryPath | [IGeometryPath](../../com.aspose.slides/igeometrypath) | ज्यामितीय पथ |

### setGeometryPaths(IGeometryPath[] geometryPaths) {#setGeometryPaths-com.aspose.slides.IGeometryPath---}
```
public final void setGeometryPaths(IGeometryPath[] geometryPaths)
```

[IGeometryPath](../../com.aspose.slides/igeometrypath) के array से आकृति ज्यामिति को अपडेट करता है। निर्देशांक आकृति के बाएँ-ऊपर कोने के सापेक्ष होने चाहिए। आकृति के प्रकार (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) को [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom) में बदलता है।

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      GeometryShape shape = (GeometryShape)pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 200, 100);
>      IGeometryPath geometryPath = shape.getGeometryPaths()[0];
>      geometryPath.lineTo(100, 50, 1);
>      geometryPath.lineTo(100, 50, 4);
>      shape.setGeometryPath(geometryPath);
>      pres.save("output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| geometryPaths | [IGeometryPath\[\]](../../com.aspose.slides/igeometrypath) | ज्यामितीय पथों का array |

### getShapeStyle() {#getShapeStyle--}
```
public final IShapeStyle getShapeStyle()
```

आकृति की शैली वस्तु लौटाता है। केवल-पढ़ने-योग्य [IShapeStyle](../../com.aspose.slides/ishapestyle)।

**Returns:**  
[IShapeStyle](../../com.aspose.slides/ishapestyle)

### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

ज्यामितीय प्रीसेट प्रकार को लौटाता या सेट करता है। नोट: मान बदलने पर सभी समायोजन मान अपने डिफ़ॉल्ट मानों पर रीसेट हो जाएंगे। पढ़ें/लिखें [ShapeType](../../com.aspose.slides/shapetype)।

**Returns:**  
int

### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

ज्यामितीय प्रीसेट प्रकार को लौटाता या सेट करता है। नोट: मान बदलने पर सभी समायोजन मान अपने डिफ़ॉल्ट मानों पर रीसेट हो जाएंगे। पढ़ें/लिखें [ShapeType](../../com.aspose.slides/shapetype)।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |

### getAdjustments() {#getAdjustments--}
```
public final IAdjustValueCollection getAdjustments()
```

आकृति के समायोजन मानों का संग्रह लौटाता है। केवल-पढ़ने-योग्य [IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)।

**Returns:**  
[IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)

### createShapeElements() {#createShapeElements--}
```
public final IShapeElement[] createShapeElements()
```

आकृति के तत्वों का array बनाता और लौटाता है।

**Returns:**  
com.aspose.slides.IShapeElement[] - Array of [ShapeElement](../../com.aspose.slides/shapeelement)