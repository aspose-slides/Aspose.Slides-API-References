---
title: GeometryPath
second_title: Aspose.Slides जावा के लिए API संदर्भ
description: GeometryShape का geometry पथ दर्शाता है
type: docs
url: /hi/com.aspose.slides/geometrypath/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IGeometryPath](../../com.aspose.slides/igeometrypath)
```
public final class GeometryPath implements IGeometryPath
```

GeometryShape का geometry path दर्शाता है।

## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [GeometryPath()](#GeometryPath--) | GeometryPath का एक उदाहरण बनाता है |

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getPathData()](#getPathData--) | GeometryShape के geometry path को path segments की array के रूप में लौटाता है। |
| [removeAt(int index)](#removeAt-int-) | geometry path के निर्दिष्ट इंडेक्स पर सेगमेंट को हटाता है। |
| [lineTo(Point2D.Float point)](#lineTo-java.awt.geom.Point2D.Float-) | पाथ के अंत में लाइन जोड़ता है |
| [lineTo(float x, float y)](#lineTo-float-float-) | पाथ के अंत में लाइन जोड़ता है |
| [lineTo(Point2D.Float point, long index)](#lineTo-java.awt.geom.Point2D.Float-long-) | पाथ में निर्दिष्ट स्थान पर लाइन जोड़ता है |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | पाथ में निर्दिष्ट स्थान पर लाइन जोड़ता है |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | पाथ के अंत में क्यूबिक Bezier कर्व जोड़ता है |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | पाथ के अंत में क्यूबिक Bezier कर्व जोड़ता है |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | पाथ में निर्दिष्ट स्थान पर क्यूबिक Bezier कर्व जोड़ता है |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | पाथ में निर्दिष्ट स्थान पर क्यूबिक Bezier कर्व जोड़ता है |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | पाथ के अंत में क्वाड्रैटिक Bezier कर्व जोड़ता है |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | पाथ के अंत में क्वाड्रैटिक Bezier कर्व जोड़ता है |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | पाथ में निर्दिष्ट स्थान पर क्वाड्रैटिक Bezier कर्व जोड़ता है |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | पाथ में निर्दिष्ट स्थान पर क्वाड्रैटिक Bezier कर्व जोड़ता है |
| [closeFigure()](#closeFigure--) | इस पाथ के वर्तमान फ़िगर को बंद करता है |
| [moveTo(Point2D.Float point)](#moveTo-java.awt.geom.Point2D.Float-) | अगले बिंदु की स्थिति सेट करता है। |
| [moveTo(float x, float y)](#moveTo-float-float-) | अगले बिंदु की स्थिति सेट करता है। |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | निर्दिष्ट आर्क को पाथ में जोड़ता है। |
| [getFillMode()](#getFillMode--) | भरने का मोड सेट करता है |
| [setFillMode(byte value)](#setFillMode-byte-) | भरने का मोड सेट करता है |
| [getStroke()](#getStroke--) | स्ट्रोक की उपस्थिति सेट करता है |
| [setStroke(boolean value)](#setStroke-boolean-) | स्ट्रोक की उपस्थिति सेट करता है |
### GeometryPath() {#GeometryPath--}
```
public GeometryPath()
```

GeometryPath का एक उदाहरण बनाता है

### getPathData() {#getPathData--}
```
public final IPathSegment[] getPathData()
```

GeometryShape के geometry path को path segments की array के रूप में लौटाता है।

**रिटर्न:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

geometry path के निर्दिष्ट इंडेक्स पर सेगमेंट को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाए जाने वाले geometry path का इंडेक्स। |

### lineTo(Point2D.Float point) {#lineTo-java.awt.geom.Point2D.Float-}
```
public final void lineTo(Point2D.Float point)
```

पाथ के अंत में लाइन जोड़ता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | लाइन का अंत बिंदु |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public final void lineTo(float x, float y)
```

पाथ के अंत में लाइन जोड़ता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | लाइन के अंत बिंदु का X निर्देशांक |
| y | float | लाइन के अंत बिंदु का Y निर्देशांक |

### lineTo(Point2D.Float point, long index) {#lineTo-java.awt.geom.Point2D.Float-long-}
```
public final void lineTo(Point2D.Float point, long index)
```

पाथ में निर्दिष्ट स्थान पर लाइन जोड़ता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | अंत बिंदु |
| index | long | PathData में सेगमेंट का इंडेक्स |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public final void lineTo(float x, float y, long index)
```

पाथ में निर्दिष्ट स्थान पर लाइन जोड़ता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | बिंदु का X निर्देशांक |
| y | float | बिंदु का Y निर्देशांक |
| index | long | PathData में सेगमेंट का इंडेक्स |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public final void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)
```

पाथ के अंत में क्यूबिक Bezier कर्व जोड़ता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | पहला दिशा बिंदु |
| point2 | java.awt.geom.Point2D.Float | दूसरा दिशा बिंदु |
| point3 | java.awt.geom.Point2D.Float | अंत बिंदु |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

पाथ के अंत में क्यूबिक Bezier कर्व जोड़ता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x1 | float | पहले दिशा बिंदु का X निर्देशांक |
| y1 | float | पहले दिशा बिंदु का Y निर्देशांक |
| x2 | float | दूसरे दिशा बिंदु का X निर्देशांक |
| y2 | float | दूसरे दिशा बिंदु का Y निर्देशांक |
| x3 | float | अंत बिंदु का X निर्देशांक |
| y3 | float | अंत बिंदु का Y निर्देशांक |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public final void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)
```

पाथ में निर्दिष्ट स्थान पर क्यूबिक Bezier कर्व जोड़ता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | पहला दिशा बिंदु |
| point2 | java.awt.geom.Point2D.Float | दूसरा दिशा बिंदु |
| point3 | java.awt.geom.Point2D.Float | अंत बिंदु |
| index | long | PathData में सेगमेंट का इंडेक्स |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

पाथ में निर्दिष्ट स्थान पर क्यूबिक Bezier कर्व जोड़ता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x1 | float | पहले दिशा बिंदु का X निर्देशांक |
| y1 | float | पहले दिशा बिंदु का Y निर्देशांक |
| x2 | float | दूसरे दिशा बिंदु का X निर्देशांक |
| y2 | float | दूसरे दिशा बिंदु का Y निर्देशांक |
| x3 | float | अंत बिंदु का X निर्देशांक |
| y3 | float | अंत बिंदु का Y निर्देशांक |
| index | long | PathData में सेगमेंट का इंडेक्स |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public final void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)
```

पाथ के अंत में क्वाड्रैटिक Bezier कर्व जोड़ता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | दिशा बिंदु |
| point2 | java.awt.geom.Point2D.Float | अंत बिंदु |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

पाथ के अंत में क्वाड्रैटिक Bezier कर्व जोड़ता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x1 | float | दिशा बिंदु का X निर्देशांक |
| y1 | float | दिशा बिंदु का Y निर्देशांक |
| x2 | float | अंत बिंदु का X निर्देशांक |
| y2 | float | अंत बिंदु का Y निर्देशांक |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public final void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)
```

पाथ में निर्दिष्ट स्थान पर क्वाड्रैटिक Bezier कर्व जोड़ता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | दिशा बिंदु |
| point2 | java.awt.geom.Point2D.Float | अंत बिंदु |
| index | long | PathData में सेगमेंट का इंडेक्स |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

पाथ में निर्दिष्ट स्थान पर क्वाड्रैटिक Bezier कर्व जोड़ता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x1 | float | दिशा बिंदु का X निर्देशांक |
| y1 | float | दिशा बिंदु का Y निर्देशांक |
| x2 | float | अंत बिंदु का X निर्देशांक |
| y2 | float | अंत बिंदु का Y निर्देशांक |
| index | long | PathData में सेगमेंट का इंडेक्स |

### closeFigure() {#closeFigure--}
```
public final void closeFigure()
```

इस पाथ के वर्तमान फ़िगर को बंद करता है

### moveTo(Point2D.Float point) {#moveTo-java.awt.geom.Point2D.Float-}
```
public final void moveTo(Point2D.Float point)
```

अगले बिंदु की स्थिति सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | बिंदु की स्थिति |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public final void moveTo(float x, float y)
```

अगले बिंदु की स्थिति सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | बिंदु का X निर्देशांक |
| y | float | बिंदु का Y निर्देशांक |

### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public final void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```

निर्दिष्ट आर्क को पाथ में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| width | float | आयत की चौड़ाई |
| heigth | float | आयत की ऊँचाई |
| startAngle | float | प्रारंभिक कोण। |
| sweepAngle | float | स्वेप कोण। |

### getFillMode() {#getFillMode--}
```
public final byte getFillMode()
```

भरने का मोड सेट करता है

**रिटर्न:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public final void setFillMode(byte value)
```

भरने का मोड सेट करता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public final boolean getStroke()
```

स्ट्रोक की उपस्थिति सेट करता है

**रिटर्न:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public final void setStroke(boolean value)
```

स्ट्रोक की उपस्थिति सेट करता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |