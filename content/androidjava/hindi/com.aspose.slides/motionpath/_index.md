---
title: MotionPath
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: motion path का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/motionpath/
---
**विरासत:**
java.lang.Object

**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.IMotionPath](../../com.aspose.slides/imotionpath)
```
public class MotionPath implements IMotionPath
```

मोशन पथ का प्रतिनिधित्व करता है।
## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [MotionPath()](#MotionPath--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#add-int-android.graphics.PointF---int-boolean-) | पाथ में नया कमांड जोड़ता है |
| [getCount()](#getCount--) | कलेक्शन में पाथ की संख्या लौटाता है। |
| [insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-android.graphics.PointF---int-boolean-) | पाथ में नया कमांड सम्मिलित करता है |
| [clear()](#clear--) | कलेक्शन से सभी कमांड हटाता है। |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | कलेक्शन से निर्दिष्ट कमांड हटाता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट इंडेक्स पर कमांड हटाता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट इंडेक्स पर कमांड लौटाता है। |
| [iterator()](#iterator--) | कलेक्शन के माध्यम से इटरेट करने वाला एन्यूमेरेटर लौटाता है। |
| [iteratorJava()](#iteratorJava--) | पूरा कलेक्शन के लिए जावा इटरिटर लौटाता है। |
### MotionPath() {#MotionPath--}
```
public MotionPath()
```

### add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#add-int-android.graphics.PointF---int-boolean-}
```
public final IMotionCmdPath add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

पाथ में नया कमांड जोड़ता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | बिंदुओं की एरे |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | रिलेटिव कोऑर्डिनेट्स बूलियन |

**रिटर्न वैल्यू:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public final int getCount()
```

कलेक्शन में पाथ की संख्या लौटाता है। केवल-पढ़ने योग्य int।

**रिटर्न वैल्यू:**
int
### insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-android.graphics.PointF---int-boolean-}
```
public final void insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

पाथ में नया कमांड सम्मिलित करता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | शून्य-आधारित इंडेक्स जहाँ आइटम सम्मिलित किया जाना चाहिए। |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | बिंदुओं की एरे |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | रिलेटिव कोऑर्डिनेट्स बूलियन |
### clear() {#clear--}
```
public final void clear()
```

कलेक्शन से सभी कमांड हटाता है।

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public final void remove(IMotionCmdPath item)
```

कलेक्शन से निर्दिष्ट कमांड हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | हटाने के लिए मोशन पाथ। |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

निर्दिष्ट इंडेक्स पर कमांड हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | डिलीट किए जाने वाले कमांड का इंडेक्स। |
### get_Item(int index) {#get-Item-int-}
```
public final IMotionCmdPath get_Item(int index)
```

निर्दिष्ट इंडेक्स पर कमांड लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | तत्व का इंडेक्स। |

**रिटर्न वैल्यू:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) ऑब्जेक्ट।
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iterator()
```

कलेक्शन के माध्यम से इटरेट करने वाला एन्यूमेरेटर लौटाता है।

**रिटर्न वैल्यू:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - एक IGenericEnumerator जिसे कलेक्शन के माध्यम से इटरेट करने के लिए इस्तेमाल किया जा सकता है।
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iteratorJava()
```

पूरा कलेक्शन के लिए जावा इटरिटर लौटाता है।

**रिटर्न वैल्यू:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - पूरा कलेक्शन के लिए एक java.util.Iterator।