---
title: IGeometryPath
second_title: Aspose.Slides Android के लिए Java API रेफ़रेंस के माध्यम से
description: GeometryShape का ज्यामितीय पथ दर्शाता है
type: docs
url: /hi/com.aspose.slides/igeometrypath/
---```
public interface IGeometryPath
```

GeometryShape का ज्यामितीय पथ दर्शाता है
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getPathData()](#getPathData--) | GeometryShape का ज्यामितीय पथ को पथ खंडों की एक सरणी के रूप में लौटाता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट अनुक्रमांक पर पथ के खंड को हटाता है। |
| [lineTo(PointF point)](#lineTo-android.graphics.PointF-) | पथ के अंत में रेखा जोड़ता है |
| [lineTo(float x, float y)](#lineTo-float-float-) | पथ के अंत में रेखा जोड़ता है |
| [lineTo(PointF point, long index)](#lineTo-android.graphics.PointF-long-) | पथ के निर्दिष्ट स्थान पर रेखा जोड़ता है |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | पथ के निर्दिष्ट स्थान पर रेखा जोड़ता है |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-) | पथ के अंत में क्यूबिक बेज़ियर वक्र जोड़ता है |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | पथ के अंत में क्यूबिक बेज़ियर वक्र जोड़ता है |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-) | पथ के निर्दिष्ट स्थान पर क्यूबिक बेज़ियर वक्र जोड़ता है |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | पथ के निर्दिष्ट स्थान पर क्यूबिक बेज़ियर वक्र जोड़ता है |
| [quadraticBezierTo(PointF point1, PointF point2)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-) | पथ के अंत में क्वाड्रेटिक बेज़ियर वक्र जोड़ता है |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | पथ के अंत में क्वाड्रेटिक बेज़ियर वक्र जोड़ता है |
| [quadraticBezierTo(PointF point1, PointF point2, long index)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-) | पथ के निर्दिष्ट स्थान पर क्वाड्रेटिक बेज़ियर वक्र जोड़ता है |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | पथ के निर्दिष्ट स्थान पर क्वाड्रेटिक बेज़ियर वक्र जोड़ता है |
| [closeFigure()](#closeFigure--) | इस पथ की वर्तमान आकृति को बंद करता है |
| [moveTo(PointF point)](#moveTo-android.graphics.PointF-) | अगले बिंदु की स्थिति सेट करता है। |
| [moveTo(float x, float y)](#moveTo-float-float-) | अगले बिंदु की स्थिति सेट करता है। |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | निर्दिष्ट आर्क को पथ में जोड़ता है। |
| [getFillMode()](#getFillMode--) | भराव मोड सेट करता है |
| [setFillMode(byte value)](#setFillMode-byte-) | भराव मोड सेट करता है |
| [getStroke()](#getStroke--) | स्ट्रोक उपस्थिति सेट करता है |
| [setStroke(boolean value)](#setStroke-boolean-) | स्ट्रोक उपस्थिति सेट करता है |
### getPathData() {#getPathData--}
```
public abstract IPathSegment[] getPathData()
```


GeometryShape का ज्यामितीय पथ को पथ खंडों की एक सरणी के रूप में लौटाता है।

**रिटर्न:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


निर्दिष्ट अनुक्रमांक पर पथ के खंड को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाए जाने वाले पथ खंड का अनुक्रमांक। |

### lineTo(PointF point) {#lineTo-android.graphics.PointF-}
```
public abstract void lineTo(PointF point)
```


पथ के अंत में रेखा जोड़ता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point | android.graphics.PointF | रेखा का अंतिम बिंदु |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public abstract void lineTo(float x, float y)
```


पथ के अंत में रेखा जोड़ता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | रेखा के अंतिम बिंदु का X निर्देशांक |
| y | float | रेखा के अंतिम बिंदु का Y निर्देशांक |

### lineTo(PointF point, long index) {#lineTo-android.graphics.PointF-long-}
```
public abstract void lineTo(PointF point, long index)
```


पथ के निर्दिष्ट स्थान पर रेखा जोड़ता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point | android.graphics.PointF | अंतिम बिंदु |
| index | long | PathData में खंड का अनुक्रमांक |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public abstract void lineTo(float x, float y, long index)
```


पथ के निर्दिष्ट स्थान पर रेखा जोड़ता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | बिंदु का X निर्देशांक |
| y | float | बिंदु का Y निर्देशांक |
| index | long | PathData में खंड का अनुक्रमांक |

### cubicBezierTo(PointF point1, PointF point2, PointF point3) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-}
```
public abstract void cubicBezierTo(PointF point1, PointF point2, PointF point3)
```


पथ के अंत में क्यूबिक बेज़ियर वक्र जोड़ता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point1 | android.graphics.PointF | पहला दिशा बिंदु |
| point2 | android.graphics.PointF | दूसरा दिशा बिंदु |
| point3 | android.graphics.PointF | अंतिम बिंदु |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```


पथ के अंत में क्यूबिक बेज़ियर वक्र जोड़ता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x1 | float | पहले दिशा बिंदु का X निर्देशांक |
| y1 | float | पहले दिशा बिंदु का Y निर्देशांक |
| x2 | float | दूसरे दिशा बिंदु का X निर्देशांक |
| y2 | float | दूसरे दिशा बिंदु का Y निर्देशांक |
| x3 | float | अंतिम बिंदु का X निर्देशांक |
| y3 | float | अंतिम बिंदु का Y निर्देशांक |

### cubicBezierTo(PointF point1, PointF point2, PointF point3, long index) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-}
```
public abstract void cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)
```


पथ के निर्दिष्ट स्थान पर क्यूबिक बेज़ियर वक्र जोड़ता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point1 | android.graphics.PointF | पहला दिशा बिंदु |
| point2 | android.graphics.PointF | दूसरा दिशा बिंदु |
| point3 | android.graphics.PointF | अंतिम बिंदु |
| index | long | PathData में खंड का अनुक्रमांक |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```


पथ के निर्दिष्ट स्थान पर क्यूबिक बेज़ियर वक्र जोड़ता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x1 | float | पहले दिशा बिंदु का X निर्देशांक |
| y1 | float | पहले दिशा बिंदु का Y निर्देशांक |
| x2 | float | दूसरे दिशा बिंदु का X निर्देशांक |
| y2 | float | दूसरे दिशा बिंदु का Y निर्देशांक |
| x3 | float | अंतिम बिंदु का X निर्देशांक |
| y3 | float | अंतिम बिंदु का Y निर्देशांक |
| index | long | PathData में खंड का अनुक्रमांक |

### quadraticBezierTo(PointF point1, PointF point2) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-}
```
public abstract void quadraticBezierTo(PointF point1, PointF point2)
```


पथ के अंत में क्वाड्रेटिक बेज़ियर वक्र जोड़ता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point1 | android.graphics.PointF | दिशा बिंदु |
| point2 | android.graphics.PointF | अंतिम बिंदु |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2)
```


पथ के अंत में क्वाड्रेटिक बेज़ियर वक्र जोड़ता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x1 | float | दिशा बिंदु का X निर्देशांक |
| y1 | float | दिशा बिंदु का Y निर्देशांक |
| x2 | float | अंतिम बिंदु का X निर्देशांक |
| y2 | float | अंतिम बिंदु का Y निर्देशांक |

### quadraticBezierTo(PointF point1, PointF point2, long index) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-}
```
public abstract void quadraticBezierTo(PointF point1, PointF point2, long index)
```


पथ के निर्दिष्ट स्थान पर क्वाड्रेटिक बेज़ियर वक्र जोड़ता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point1 | android.graphics.PointF | दिशा बिंदु |
| point2 | android.graphics.PointF | अंतिम बिंदु |
| index | long | PathData में खंड का अनुक्रमांक |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```


पथ के निर्दिष्ट स्थान पर क्वाड्रेटिक बेज़ियर वक्र जोड़ता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x1 | float | दिशा बिंदु का X निर्देशांक |
| y1 | float | दिशा बिंदु का Y निर्देशांक |
| x2 | float | अंतिम बिंदु का X निर्देशांक |
| y2 | float | अंतिम बिंदु का Y निर्देशांक |
| index | long | PathData में खंड का अनुक्रमांक |

### closeFigure() {#closeFigure--}
```
public abstract void closeFigure()
```


इस पथ के वर्तमान आकृति को बंद करता है

### moveTo(PointF point) {#moveTo-android.graphics.PointF-}
```
public abstract void moveTo(PointF point)
```


अगले बिंदु की स्थिति सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point | android.graphics.PointF | बिंदु की स्थिति |

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


निर्दिष्ट आर्क को पथ में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| width | float | आयत की चौड़ाई |
| heigth | float | आयत की ऊँचाई |
| startAngle | float | प्रारंभिक कोण |
| sweepAngle | float | स्विप कोण/ |

### getFillMode() {#getFillMode--}
```
public abstract byte getFillMode()
```


भरण मोड सेट करता है

**रिटर्न:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public abstract void setFillMode(byte value)
```


भरण मोड सेट करता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public abstract boolean getStroke()
```


स्ट्रोक उपस्थिति सेट करता है

**रिटर्न:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public abstract void setStroke(boolean value)
```


स्ट्रोक उपस्थिति सेट करता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |