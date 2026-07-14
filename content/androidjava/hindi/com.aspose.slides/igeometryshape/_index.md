---
title: IGeometryShape
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: सभी ज्यामितीय आकारों के लिए मूल वर्ग का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/igeometryshape/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IShape](../../com.aspose.slides/ishape)
```
public interface IGeometryShape extends IShape
```

सभी ज्यामितीय आकारों के लिए मूल वर्ग को दर्शाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getGeometryPaths()](#getGeometryPaths--) | ज्यामितीय आकार की पाथ की प्रति लौटाता है। |
| [setGeometryPath(IGeometryPath geometryPath)](#setGeometryPath-com.aspose.slides.IGeometryPath-) | [IGeometryPath](../../com.aspose.slides/igeometrypath) वस्तु से आकार की ज्यामिति को अद्यतन करता है। |
| [setGeometryPaths(IGeometryPath[] geometryPaths)](#setGeometryPaths-com.aspose.slides.IGeometryPath---) | [IGeometryPath](../../com.aspose.slides/igeometrypath) की एरे से आकार की ज्यामिति को अद्यतन करता है। |
| [getShapeStyle()](#getShapeStyle--) | आकार की शैली ऑब्जेक्ट लौटाता है। |
| [getShapeType()](#getShapeType--) | ज्यामितीय प्रीसेट प्रकार को लौटाता है या सेट करता है। |
| [setShapeType(int value)](#setShapeType-int-) | ज्यामितीय प्रीसेट प्रकार को लौटाता है या सेट करता है। |
| [getAdjustments()](#getAdjustments--) | आकार के समायोजन मानों का संग्रह लौटाता है। |
| [createShapeElements()](#createShapeElements--) | आकार के तत्वों का एरे बनाता और लौटाता है। |
### getGeometryPaths() {#getGeometryPaths--}
```
public abstract IGeometryPath[] getGeometryPaths()
```

ज्यामितीय आकार की पाथ की प्रति लौटाता है। निर्देशांक आकार के बाएँ शीर्ष कोने के सापेक्ष होते हैं।

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

**रिटर्न:**
com.aspose.slides.IGeometryPath[] - [IGeometryPath](../../com.aspose.slides/igeometrypath) का एरे
### setGeometryPath(IGeometryPath geometryPath) {#setGeometryPath-com.aspose.slides.IGeometryPath-}
```
public abstract void setGeometryPath(IGeometryPath geometryPath)
```

[IGeometryPath](../../com.aspose.slides/igeometrypath) वस्तु से आकार की ज्यामिति को अद्यतन करता है। निर्देशांक आकार के बाएँ शीर्ष कोने के सापेक्ष होने चाहिए। आकार के प्रकार को (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom) में बदलता है।

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| geometryPath | [IGeometryPath](../../com.aspose.slides/igeometrypath) | ज्यामितीय पाथ |

### setGeometryPaths(IGeometryPath[] geometryPaths) {#setGeometryPaths-com.aspose.slides.IGeometryPath---}
```
public abstract void setGeometryPaths(IGeometryPath[] geometryPaths)
```

[IGeometryPath](../../com.aspose.slides/igeometrypath) की एरे से आकार की ज्यामिति को अद्यतन करता है। निर्देशांक आकार के बाएँ शीर्ष कोने के सापेक्ष होने चाहिए। आकार के प्रकार को (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom) में बदलता है।

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| geometryPaths | [IGeometryPath\[\]](../../com.aspose.slides/igeometrypath) | ज्यामितीय पाथ की एरे |

### getShapeStyle() {#getShapeStyle--}
```
public abstract IShapeStyle getShapeStyle()
```

आकार की शैली ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [IShapeStyle](../../com.aspose.slides/ishapestyle)।

**रिटर्न:**
[IShapeStyle](../../com.aspose.slides/ishapestyle)
### getShapeType() {#getShapeType--}
```
public abstract int getShapeType()
```

ज्यामितीय प्रीसेट प्रकार को लौटाता है या सेट करता है। नोट: मान बदलने पर सभी समायोजन मान उनके डिफ़ॉल्ट मानों पर रीसेट हो जाएँगे। पढ़ें/लिखें [ShapeType](../../com.aspose.slides/shapetype)।

**रिटर्न:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public abstract void setShapeType(int value)
```

ज्यामितीय प्रीसेट प्रकार को लौटाता है या सेट करता है। नोट: मान बदलने पर सभी समायोजन मान उनके डिफ़ॉल्ट मानों पर रीसेट हो जाएँगे। पढ़ें/लिखें [ShapeType](../../com.aspose.slides/shapetype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getAdjustments() {#getAdjustments--}
```
public abstract IAdjustValueCollection getAdjustments()
```

आकार के समायोजन मानों का संग्रह लौटाता है। केवल-पढ़ने योग्य [IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)।

**रिटर्न:**
[IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
### createShapeElements() {#createShapeElements--}
```
public abstract IShapeElement[] createShapeElements()
```

आकार के तत्वों का एरे बनाता और लौटाता है।

**रिटर्न:**
com.aspose.slides.IShapeElement[] - [IShapeElement](../../com.aspose.slides/ishapeelement) का एरे