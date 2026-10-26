---
title: IMotionPath
second_title: Aspose.Slides के लिए Java API संदर्भ
description: गति पथ का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/imotionpath/
---
**सभी लागू इंटरफ़ेस:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMotionPath extends System.Collections.Generic.IGenericEnumerable<IMotionCmdPath)
```

गति पथ को दर्शाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#add-int-java.awt.geom.Point2D.Float---int-boolean-) | Add new command to path |
| [getCount()](#getCount--) | Returns the number of paths in the collection. |
| [insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-) | Insert new command to path |
| [clear()](#clear--) | Removes all commands from the collection. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Removes specified commans from the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes a command at the specified index. |
| [get_Item(int index)](#get-Item-int-) | Returns a command at the specified index. |
### add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#add-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public abstract IMotionCmdPath add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```

पथ में नया कमांड जोड़ें

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | int | एनिमेशन मोशन इफ़ेक्ट व्यवहार के लिए कमांड का प्रकार [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | बिंदुओं की सरणी java.awt.geom.Point2D.Float[] |
| ptsType | int | एनिमेशन मोशन पाथ में बिंदुओं का प्रकार [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | सापेक्ष निर्देशांक का उपयोग करना है या नहीं दर्शाता है boolean |

**वापसी:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Command of a path [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public abstract int getCount()
```

संग्रह में पाथ की संख्या लौटाता है। केवल-पढ़ने योग्य int.

**वापसी:**
int
### insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public abstract void insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```

पथ में नया कमांड जोड़ें

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | कमांड सम्मिलन के लिए सूचकांक int |
| type | int | एनिमेशन मोशन इफ़ेक्ट व्यवहार के लिए कमांड का प्रकार [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | बिंदुओं की सरणी java.awt.geom.Point2D.Float[] |
| ptsType | int | एनिमेशन मोशन पाथ में बिंदुओं का प्रकार [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | सापेक्ष निर्देशांक का उपयोग करना है या नहीं दर्शाता है boolean |

### clear() {#clear--}
```
public abstract void clear()
```

संग्रह से सभी कमांड हटाता है।

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public abstract void remove(IMotionCmdPath item)
```

निर्दिष्ट कमांड्स को संग्रह से हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | हटाने के लिए गति पथ [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) |

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

निर्दिष्ट सूचकांक पर कमांड लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | तत्व का सूचकांक। |

**वापसी:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Command at specified index [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)