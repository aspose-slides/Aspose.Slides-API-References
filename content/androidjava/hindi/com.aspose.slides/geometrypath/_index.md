---
title: GeometryPath
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: GeometryShape का ज्यामितीय पथ दर्शाता है
type: docs
url: /hi/com.aspose.slides/geometrypath/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IGeometryPath](../../com.aspose.slides/igeometrypath)
```
public final class GeometryPath implements IGeometryPath
```

GeometryShape का ज्यामितीय पथ दर्शाता है

## कंस्ट्रक्टर

| निर्माता | विवरण |
| --- | --- |
| [GeometryPath()](#GeometryPath--) | GeometryPath का एक उदाहरण बनाता है |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getPathData()](#getPathData--) | GeometryShape का ज्यामितीय पथ पाथ सेगमेंट्स की एरे के रूप में लौटाता है। |
| [removeAt(int index)](#removeAt-int-) | ज्यामितीय पथ में निर्दिष्ट इंडेक्स पर सेगमेंट हटाता है। |
| [lineTo(PointF point)](#lineTo-android.graphics.PointF-) | पथ के अंत में रेखा जोड़ता है। |
| [lineTo(float x, float y)](#lineTo-float-float-) | पथ के अंत में रेखा जोड़ता है। |
| [lineTo(PointF point, long index)](#lineTo-android.graphics.PointF-long-) | पथ के निर्दिष्ट स्थान पर रेखा जोड़ता है। |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | पथ के निर्दिष्ट स्थान पर रेखा जोड़ता है। |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-) | पथ के अंत में क्यूबिक बीज़ियर कर्व जोड़ता है। |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | पथ के अंत में क्यूबिक बीज़ियर कर्व जोड़ता है। |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-) | पथ के निर्दिष्ट स्थान पर क्यूबिक बीज़ियर कर्व जोड़ता है। |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | पथ के निर्दिष्ट स्थान पर क्यूबिक बीज़ियर कर्व जोड़ता है। |
| [quadraticBezierTo(PointF point1, PointF point2)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-) | पथ के अंत में क्वैड्रेटिक बीज़ियर कर्व जोड़ता है। |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | पथ के अंत में क्वैड्रेटिक बीज़ियर कर्व जोड़ता है। |
| [quadraticBezierTo(PointF point1, PointF point2, long index)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-) | पथ के निर्दिष्ट स्थान पर क्वैड्रेटिक बीज़ियर कर्व जोड़ता है। |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | पथ के निर्दिष्ट स्थान पर क्वैड्रेटिक बीज़ियर कर्व जोड़ता है। |
| [closeFigure()](#closeFigure--) | इस पथ की वर्तमान आकृति को बंद करता है। |
| [moveTo(PointF point)](#moveTo-android.graphics.PointF-) | अगले बिंदु की स्थिति सेट करता है। |
| [moveTo(float x, float y)](#moveTo-float-float-) | अगले बिंदु की स्थिति सेट करता है। |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | निर्दिष्ट आर्क को पथ में जोड़ता है। |
| [getFillMode()](#getFillMode--) | fill मोड सेट करता है। |
| [setFillMode(byte value)](#setFillMode-byte-) | fill मोड सेट करता है। |
| [getStroke()](#getStroke--) | stroke appearance सेट करता है। |
| [setStroke(boolean value)](#setStroke-boolean-) | stroke appearance सेट करता है। |
### GeometryPath() {#GeometryPath--}
```
public GeometryPath()
```

GeometryPath का एक उदाहरण बनाता है

### getPathData() {#getPathData--}
```
public final IPathSegment[] getPathData()
```

GeometryShape का ज्यामितीय पथ पाथ सेगमेंट्स की एरे के रूप में लौटाता है।

**रिटर्न:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

ज्यामितीय पथ में निर्दिष्ट इंडेक्स पर सेगमेंट हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाए जाने वाले ज्यामितीय पथ का इंडेक्स। |
### lineTo(PointF point) {#lineTo-android.graphics.PointF-}
```
public final void lineTo(PointF point)
```

पथ के अंत में रेखा जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point | android.graphics.PointF | रेखा का अंत बिंदु |
### lineTo(float x, float y) {#lineTo-float-float-}
```
public final void lineTo(float x, float y)
```

पथ के अंत में रेखा जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | रेखा के अंत बिंदु का X निर्देशांक |
| y | float | रेखा के अंत बिंदु का Y निर्देशांक |
### lineTo(PointF point, long index) {#lineTo-android.graphics.PointF-long-}
```
public final void lineTo(PointF point, long index)
```

पथ के निर्दिष्ट स्थान पर रेखा जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point | android.graphics.PointF | अंत बिंदु |
| index | long | PathData में सेगमेंट का इंडेक्स |
### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public final void lineTo(float x, float y, long index)
```

पथ के निर्दिष्ट स्थान पर रेखा जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | बिंदु का X निर्देशांक |
| y | float | बिंदु का Y निर्देशांक |
| index | long | PathData में सेगमेंट का इंडेक्स |
### cubicBezierTo(PointF point1, PointF point2, PointF point3) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-}
```
public final void cubicBezierTo(PointF point1, PointF point2, PointF point3)
```

पथ के अंत में क्यूबिक बीज़ियर कर्व जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point1 | android.graphics.PointF | पहला दिशा बिंदु |
| point2 | android.graphics.PointF | दूसरा दिशा बिंदु |
| point3 | android.graphics.PointF | अंत बिंदु |
### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

पथ के अंत में क्यूबिक बीज़ियर कर्व जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x1 | float | पहले दिशा बिंदु का X निर्देशांक |
| y1 | float | पहले दिशा बिंदु का Y निर्देशांक |
| x2 | float | दूसरे दिशा बिंदु का X निर्देशांक |
| y2 | float | दूसरे दिशा बिंदु का Y निर्देशांक |
| x3 | float | अंत बिंदु का X निर्देशांक |
| y3 | float | अंत बिंदु का Y निर्देशांक |
### cubicBezierTo(PointF point1, PointF point2, PointF point3, long index) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-}
```
public final void cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)
```

पथ के निर्दिष्ट स्थान पर क्यूबिक बीज़ियर कर्व जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point1 | android.graphics.PointF | पहला दिशा बिंदु |
| point2 | android.graphics.PointF | दूसरा दिशा बिंदु |
| point3 | android.graphics.PointF | अंत बिंदु |
| index | long | PathData में सेगमेंट का इंडेक्स |
### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

पथ के निर्दिष्ट स्थान पर क्यूबिक बीज़ियर कर्व जोड़ता है।

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
### quadraticBezierTo(PointF point1, PointF point2) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-}
```
public final void quadraticBezierTo(PointF point1, PointF point2)
```

पथ के अंत में क्वैड्रेटिक बीज़ियर कर्व जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point1 | android.graphics.PointF | दिशा बिंदु |
| point2 | android.graphics.PointF | अंत बिंदु |
### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

पथ के अंत में क्वैड्रेटिक बीज़ियर कर्व जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x1 | float | दिशा बिंदु का X निर्देशांक |
| y1 | float | दिशा बिंदु का Y निर्देशांक |
| x2 | float | अंत बिंदु का X निर्देशांक |
| y2 | float | अंत बिंदु का Y निर्देशांक |
### quadraticBezierTo(PointF point1, PointF point2, long index) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-}
```
public final void quadraticBezierTo(PointF point1, PointF point2, long index)
```

पथ के निर्दिष्ट स्थान पर क्वैड्रेटिक बीज़ियर कर्व जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point1 | android.graphics.PointF | दिशा बिंदु |
| point2 | android.graphics.PointF | अंत बिंदु |
| index | long | PathData में सेगमेंट का इंडेक्स |
### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

पथ के निर्दिष्ट स्थान पर क्वैड्रेटिक बीज़ियर कर्व जोड़ता है।

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

इस पथ की वर्तमान आकृति को बंद करता है।

### moveTo(PointF point) {#moveTo-android.graphics.PointF-}
```
public final void moveTo(PointF point)
```

अगले बिंदु की स्थिति सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point | android.graphics.PointF | बिंदु की स्थिति |
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

निर्दिष्ट आर्क को पथ में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| width | float | आयत की चौड़ाई |
| heigth | float | आयत की ऊँचाई |
| startAngle | float | प्रारम्भिक कोण |
| sweepAngle | float | स्वेप कोण |
### getFillMode() {#getFillMode--}
```
public final byte getFillMode()
```

fill मोड सेट करता है

**रिटर्न:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public final void setFillMode(byte value)
```

fill मोड सेट करता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### getStroke() {#getStroke--}
```
public final boolean getStroke()
```

stroke appearance सेट करता है

**रिटर्न:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public final void setStroke(boolean value)
```

stroke appearance सेट करता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |