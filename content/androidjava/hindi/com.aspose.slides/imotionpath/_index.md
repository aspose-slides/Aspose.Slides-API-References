---
title: IMotionPath
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: मूवमेंट पथ को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/imotionpath/
---
**सभी लागू इंटरफ़ेस:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMotionPath extends System.Collections.Generic.IGenericEnumerable<IMotionCmdPath>
```

मूवमेंट पथ को दर्शाता है।
## विधियां

| मेथड | विवरण |
| --- | --- |
| [add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#add-int-android.graphics.PointF---int-boolean-) | पथ में नया कमांड जोड़ें |
| [getCount()](#getCount--) | संग्रह में पाथ की संख्या लौटाता है। |
| [insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-android.graphics.PointF---int-boolean-) | पथ में नया कमांड डालें |
| [clear()](#clear--) | संग्रह से सभी कमांड हटाता है। |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | संग्रह से निर्दिष्ट कमांड हटाता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट सूचकांक पर कमांड हटाता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट सूचकांक पर कमांड लौटाता है। |
### add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#add-int-android.graphics.PointF---int-boolean-}
```
public abstract IMotionCmdPath add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

पथ में नया कमांड जोड़ें

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | int | एनिमेशन मोशन इफ़ेक्ट व्यवहार के लिए कमांड का प्रकार [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | बिंदु सरणी android.graphics.PointF[] |
| ptsType | int | एनिमेशन मोशन पाथ में बिंदुओं का प्रकार [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | सापेक्ष निर्देशांक उपयोग किया जाए या न किया जाए, यह दर्शाता है boolean |

**रिटर्न:**  
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - पथ का कमांड [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public abstract int getCount()
```

संग्रह में पाथ की संख्या लौटाता है। केवल-पढ़ने योग्य int.

**रिटर्न:**  
int
### insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-android.graphics.PointF---int-boolean-}
```
public abstract void insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

पथ में नया कमांड डालें

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | कमांड डालने के लिए सूचकांक int |
| type | int | एनिमेशन मोशन इफ़ेक्ट व्यवहार के लिए कमांड का प्रकार [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | बिंदु सरणी android.graphics.PointF[] |
| ptsType | int | एनिमेशन मोशन पाथ में बिंदुओं का प्रकार [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | सापेक्ष निर्देशांक उपयोग किया जाए या न किया जाए, यह दर्शाता है boolean |
### clear() {#clear--}
```
public abstract void clear()
```

संग्रह से सभी कमांड हटाता है।

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public abstract void remove(IMotionCmdPath item)
```

संग्रह से निर्दिष्ट कमांड हटाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | हटाने के लिए मोशन पाथ [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

निर्दिष्ट सूचकांक पर कमांड हटाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | कमांड हटाने के लिए सूचकांक int |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMotionCmdPath get_Item(int index)
```

निर्दिष्ट सूचकांक पर एक कमांड लौटाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | तत्व का सूचकांक। |

**रिटर्न:**  
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - निर्दिष्ट सूचकांक पर कमांड [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)