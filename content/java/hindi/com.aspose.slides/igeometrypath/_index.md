---
title: IGeometryPath
second_title: Aspose.Slides for Java API Reference
description: Represents geometry path of GeometryShape
type: docs
url: /hi/com.aspose.slides/igeometrypath/
---```
public interface IGeometryPath
```

GeometryShape का जियोमेट्री पाथ दर्शाता है
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getPathData()](#getPathData--) | Returns geometry path of GeometryShape as an array of path segments. |
| [removeAt(int index)](#removeAt-int-) | Removes segment at the specified index of the geometry path. |
| [lineTo(Point2D.Float point)](#lineTo-java.awt.geom.Point2D.Float-) | Adds line to the end of the path |
| [lineTo(float x, float y)](#lineTo-float-float-) | Adds line to the end of the path |
| [lineTo(Point2D.Float point, long index)](#lineTo-java.awt.geom.Point2D.Float-long-) | Adds line to the specified place of the path |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | Adds line to the specified place of the path |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | Adds cubic Bezier curve at the end the path |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | Adds cubic Bezier curve at the end the path |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | Adds cubic Bezier curve to the specified place of the path |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | Adds cubic Bezier curve to the specified place of the path |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | Adds quadratic Bezier curve at the end the path |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | Adds quadratic Bezier curve at the end the path |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | Adds quadratic Bezier curve to the specified place of the path |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | Adds quadratic Bezier curve to the specified place of the path |
| [closeFigure()](#closeFigure--) | Closes the current figure of this path |
| [moveTo(Point2D.Float point)](#moveTo-java.awt.geom.Point2D.Float-) | Sets next point position. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Sets next point position. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Appends the specified arc to the path. |
| [getFillMode()](#getFillMode--) | Sets fill mode |
| [setFillMode(byte value)](#setFillMode-byte-) | Sets fill mode |
| [getStroke()](#getStroke--) | Sets stroke appearance |
| [setStroke(boolean value)](#setStroke-boolean-) | Sets stroke appearance |
### getPathData() {#getPathData--}
```
public abstract IPathSegment[] getPathData()
```

GeometryShape का जियोमेट्री पाथ पाथ सेगमेंट्स की एक एरे के रूप में लौटाता है।

**रिटर्न:**  
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

जियोमेट्री पाथ में निर्दिष्ट इंडेक्स पर सेगमेंट को हटाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | उस जियोमेट्री पाथ का इंडेक्स जिसे हटाया जाना चाहिए। |
### lineTo(Point2D.Float point) {#lineTo-java.awt.geom.Point2D.Float-}
```
public abstract void lineTo(Point2D.Float point)
```

पाथ के अंत में रेखा जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | रेखा का अंत बिंदु |
### lineTo(float x, float y) {#lineTo-float-float-}
```
public abstract void lineTo(float x, float y)
```

पाथ के अंत में रेखा जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | रेखा के अंत बिंदु का X निर्देशांक |
| y | float | रेखा के अंत बिंदु का Y निर्देशांक |
### lineTo(Point2D.Float point, long index) {#lineTo-java.awt.geom.Point2D.Float-long-}
```
public abstract void lineTo(Point2D.Float point, long index)
```

पाथ के निर्दिष्ट स्थान पर रेखा जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | अंत बिंदु |
| index | long | PathData में सेगमेंट का इंडेक्स |
### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public abstract void lineTo(float x, float y, long index)
```

पाथ के निर्दिष्ट स्थान पर रेखा जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | बिंदु का X निर्देशांक |
| y | float | बिंदु का Y निर्देशांक |
| index | long | PathData में सेगमेंट का इंडेक्स |
### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public abstract void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)
```

पाथ के अंत में क्यूबिक बीज़ियर कर्व जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | पहला दिशा बिंदु |
| point2 | java.awt.geom.Point2D.Float | दूसरा दिशा बिंदु |
| point3 | java.awt.geom.Point2D.Float | अंत बिंदु |
### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

पाथ के अंत में क्यूबिक बीज़ियर कर्व जोड़ता है।

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
public abstract void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)
```

पाथ के निर्दिष्ट स्थान पर क्यूबिक बीज़ियर कर्व जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | पहला दिशा बिंदु |
| point2 | java.awt.geom.Point2D.Float | दूसरा दिशा बिंदु |
| point3 | java.awt.geom.Point2D.Float | अंत बिंदु |
| index | long | PathData में सेगमेंट का इंडेक्स |
### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

पाथ के निर्दिष्ट स्थान पर क्यूबिक बीज़ियर कर्व जोड़ता है।

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
public abstract void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)
```

पाथ के अंत में क्वाड्रेटिक बीज़ियर कर्व जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | दिशा बिंदु |
| point2 | java.awt.geom.Point2D.Float | अंत बिंदु |
### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

पाथ के अंत में क्वाड्रेटिक बीज़ियर कर्व जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x1 | float | दिशा बिंदु का X निर्देशांक |
| y1 | float | दिशा बिंदु का Y निर्देशांक |
| x2 | float | अंत बिंदु का X निर्देशांक |
| y2 | float | अंत बिंदु का Y निर्देशांक |
### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public abstract void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)
```

पाथ के निर्दिष्ट स्थान पर क्वाड्रेटिक बीज़ियर कर्व जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | दिशा बिंदु |
| point2 | java.awt.geom.Point2D.Float | अंत बिंदु |
| index | long | PathData में सेगमेंट का इंडेक्स |
### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

पाथ के निर्दिष्ट स्थान पर क्वाड्रेटिक बीज़ियर कर्व जोड़ता है।

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
public abstract void closeFigure()
```

इस पाथ की वर्तमान आकृति को बंद करता है।
### moveTo(Point2D.Float point) {#moveTo-java.awt.geom.Point2D.Float-}
```
public abstract void moveTo(Point2D.Float point)
```

अगले बिंदु की स्थिति सेट करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | बिंदु की स्थिति |
### moveTo(float x, float y) {#moveTo-float-float-}
```
public abstract void moveTo(float x, float y)
```

अगले बिंदु की स्थिति सेट करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | बिंदु का X निर्देशांक |
| y | float | बिंदु का Y निर्देशांक |
### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public abstract void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```

पाथ में निर्दिष्ट आर्क जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| width | float | आयत की चौड़ाई |
| heigth | float | आयत की ऊँचाई |
| startAngle | float | प्रारंभिक कोण। |
| sweepAngle | float | स्वीप कोण। |
### getFillMode() {#getFillMode--}
```
public abstract byte getFillMode()
```

फिल मोड सेट करता है।

**रिटर्न:**  
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public abstract void setFillMode(byte value)
```

फिल मोड सेट करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### getStroke() {#getStroke--}
```
public abstract boolean getStroke()
```

स्ट्रोक का स्वरूप सेट करता है।

**रिटर्न:**  
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public abstract void setStroke(boolean value)
```

स्ट्रोक का स्वरूप सेट करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |