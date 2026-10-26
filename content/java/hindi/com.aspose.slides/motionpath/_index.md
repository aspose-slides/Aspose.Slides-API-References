---
title: MotionPath
second_title: Aspose.Slides के लिए Java API संदर्भ
description: मोशन पाथ का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/motionpath/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IMotionPath](../../com.aspose.slides/imotionpath)
```
public class MotionPath implements IMotionPath
```

मोशन पाथ का प्रतिनिधित्व करता है।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [MotionPath()](#MotionPath--) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#add-int-java.awt.geom.Point2D.Float---int-boolean-) | पथ में नया कमांड जोड़ता है |
| [getCount()](#getCount--) | संग्रह में पाथ की संख्या लौटाता है |
| [insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-) | पथ में नया कमांड डालता है |
| [clear()](#clear--) | संग्रह से सभी कमांड हटाता है |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | संग्रह से निर्दिष्ट कमांड हटाता है |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट इंडेक्स पर कमांड हटाता है |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट इंडेक्स पर कमांड लौटाता है |
| [iterator()](#iterator--) | संग्रह के माध्यम से इटरेटर लौटाता है |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए जावा इटरैटर लौटाता है |
### MotionPath() {#MotionPath--}
```
public MotionPath()
```

### add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#add-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public final IMotionCmdPath add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```

पथ में नया कमांड जोड़ता है

**परामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | बिंदुओं की सरणी |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | सापेक्ष निर्देशांक boolean |

**रिटर्न:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public final int getCount()
```

संग्रह में पाथ की संख्या लौटाता है। केवल-पढ़ने योग्य int.

**रिटर्न:**
int
### insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public final void insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```

पथ में नया कमांड डालता है

**परामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | इंडेक्स जहाँ आइटम डालना है, शून्य-आधारित है। |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | बिंदुओं की सरणी |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | सापेक्ष निर्देशांक boolean |

### clear() {#clear--}
```
public final void clear()
```

संग्रह से सभी कमांड हटाता है।

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public final void remove(IMotionCmdPath item)
```

संग्रह से निर्दिष्ट कमांड हटाता है।

**परामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | हटाने के लिए मोशन पाथ। |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

निर्दिष्ट इंडेक्स पर कमांड हटाता है।

**परामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | डिलीट किए जाने वाले कमांड का इंडेक्स। |

### get_Item(int index) {#get-Item-int-}
```
public final IMotionCmdPath get_Item(int index)
```

निर्दिष्ट इंडेक्स पर कमांड लौटाता है।

**परामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | तत्व का इंडेक्स। |

**रिटर्न:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - यह [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) ऑब्जेक्ट।

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iterator()
```

संग्रह के माध्यम से इटरेटर लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - एक IGenericEnumerator जो संग्रह के माध्यम से इटरेट करने के लिए उपयोग किया जा सकता है।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iteratorJava()
```

पूरे संग्रह के लिए जावा इटरैटर लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - पूरा संग्रह के लिए java.util.Iterator।