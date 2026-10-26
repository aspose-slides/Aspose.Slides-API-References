---
title: IAutoShapeLock
second_title: Aspose.Slides for Android जावा API रेफ़रेंस
description: निर्धारित करता है कि पैरेंट AutoshapeEx पर कौन सी ऑपरेशन्स निष्क्रिय हैं।
type: docs
url: /hi/com.aspose.slides/iautoshapelock/
---
**All Implemented Interfaces:**  
[com.aspose.slides.IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
```
public interface IAutoShapeLock extends IBaseShapeLock
```

निर्�धारित करता है कि पैरेंट AutoshapeEx पर कौन सी ऑपरेशन्स निष्क्रिय हैं।  
## Methods

| मेथड | विवरण |
| --- | --- |
| [getGroupingLocked()](#getGroupingLocked--) | Determines whether an adding this shape to a group is forbidden. |
| [setGroupingLocked(boolean value)](#setGroupingLocked-boolean-) | Determines whether an adding this shape to a group is forbidden. |
| [getSelectLocked()](#getSelectLocked--) | Determines whether a selecting this shape is forbidden. |
| [setSelectLocked(boolean value)](#setSelectLocked-boolean-) | Determines whether a selecting this shape is forbidden. |
| [getRotateLocked()](#getRotateLocked--) | Determines whether a changing rotation angle of this shape is forbidden. |
| [setRotateLocked(boolean value)](#setRotateLocked-boolean-) | Determines whether a changing rotation angle of this shape is forbidden. |
| [getAspectRatioLocked()](#getAspectRatioLocked--) | Determines whether a shape have to preserve aspect ratio on resizing. |
| [setAspectRatioLocked(boolean value)](#setAspectRatioLocked-boolean-) | Determines whether a shape have to preserve aspect ratio on resizing. |
| [getPositionLocked()](#getPositionLocked--) | Determines whether a moving this shape is forbidden. |
| [setPositionLocked(boolean value)](#setPositionLocked-boolean-) | Determines whether a moving this shape is forbidden. |
| [getSizeLocked()](#getSizeLocked--) | Determines whether a resizing this shape is forbidden. |
| [setSizeLocked(boolean value)](#setSizeLocked-boolean-) | Determines whether a resizing this shape is forbidden. |
| [getEditPointsLocked()](#getEditPointsLocked--) | Determines whether a direct changing of contour of this shape is forbidden. |
| [setEditPointsLocked(boolean value)](#setEditPointsLocked-boolean-) | Determines whether a direct changing of contour of this shape is forbidden. |
| [getAdjustHandlesLocked()](#getAdjustHandlesLocked--) | Determines whether a changing adjust values is forbidden. |
| [setAdjustHandlesLocked(boolean value)](#setAdjustHandlesLocked-boolean-) | Determines whether a changing adjust values is forbidden. |
| [getArrowheadsLocked()](#getArrowheadsLocked--) | Determines whether a changing arrowheads is forbidden. |
| [setArrowheadsLocked(boolean value)](#setArrowheadsLocked-boolean-) | Determines whether a changing arrowheads is forbidden. |
| [getShapeTypeLocked()](#getShapeTypeLocked--) | Determines whether a changing of a shape type is forbidden. |
| [setShapeTypeLocked(boolean value)](#setShapeTypeLocked-boolean-) | Determines whether a changing of a shape type is forbidden. |
| [getTextLocked()](#getTextLocked--) | Determines whether an editing of text is forbidden. |
| [setTextLocked(boolean value)](#setTextLocked-boolean-) | Determines whether an editing of text is forbidden. |
### getGroupingLocked() {#getGroupingLocked--}
```
public abstract boolean getGroupingLocked()
```

निर्धारित करता है कि इस आकार को समूह में जोड़ना प्रतिबंधित है या नहीं। पढ़ने-लिखने योग्य बूलियन।

**रिटर्न:**  
boolean
### setGroupingLocked(boolean value) {#setGroupingLocked-boolean-}
```
public abstract void setGroupingLocked(boolean value)
```

निर्धारित करता है कि इस आकार को समूह में जोड़ना प्रतिबंधित है या नहीं। पढ़ने-लिखने योग्य बूलियन।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getSelectLocked() {#getSelectLocked--}
```
public abstract boolean getSelectLocked()
```

निर्धारित करता है कि इस आकार का चयन प्रतिबंधित है या नहीं। पढ़ने-लिखने योग्य बूलियन।

**रिटर्न:**  
boolean
### setSelectLocked(boolean value) {#setSelectLocked-boolean-}
```
public abstract void setSelectLocked(boolean value)
```

निर्धारित करता है कि इस आकार का चयन प्रतिबंधित है या नहीं। पढ़ने-लिखने योग्य बूलियन।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getRotateLocked() {#getRotateLocked--}
```
public abstract boolean getRotateLocked()
```

निर्धारित करता है कि इस आकार का घूर्णन कोण बदलना प्रतिबंधित है या नहीं। पढ़ने-लिखने योग्य बूलियन।

**रिटर्न:**  
boolean
### setRotateLocked(boolean value) {#setRotateLocked-boolean-}
```
public abstract void setRotateLocked(boolean value)
```

निर्धारित करता है कि इस आकार का घूर्णन कोण बदलना प्रतिबंधित है या नहीं। पढ़ने-लिखने योग्य बूलियन।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getAspectRatioLocked() {#getAspectRatioLocked--}
```
public abstract boolean getAspectRatioLocked()
```

निर्धारित करता है कि आकार को रिसाइज़ करते समय आस्पेक्ट रेशियो बरकरार रखना है या नहीं। पढ़ने-लिखने योग्य बूलियन।

**रिटर्न:**  
boolean
### setAspectRatioLocked(boolean value) {#setAspectRatioLocked-boolean-}
```
public abstract void setAspectRatioLocked(boolean value)
```

निर्धारित करता है कि आकार को रिसाइज़ करते समय आस्पेक्ट रेशियो बरकरार रखना है या नहीं। पढ़ने-लिखने योग्य बूलियन।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getPositionLocked() {#getPositionLocked--}
```
public abstract boolean getPositionLocked()
```

निर्धारित करता है कि इस आकार को मूव करना प्रतिबंधित है या नहीं। पढ़ने-लिखने योग्य बूलियन।

**रिटर्न:**  
boolean
### setPositionLocked(boolean value) {#setPositionLocked-boolean-}
```
public abstract void setPositionLocked(boolean value)
```

निर्धारित करता है कि इस आकार को मूव करना प्रतिबंधित है या नहीं। पढ़ने-लिखने योग्य बूलियन।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getSizeLocked() {#getSizeLocked--}
```
public abstract boolean getSizeLocked()
```

निर्धारित करता है कि इस आकार को रिसाइज़ करना प्रतिबंधित है या नहीं। पढ़ने-लिखने योग्य बूलियन।

**रिटर्न:**  
boolean
### setSizeLocked(boolean value) {#setSizeLocked-boolean-}
```
public abstract void setSizeLocked(boolean value)
```

निर्धारित करता है कि इस आकार को रिसाइज़ करना प्रतिबंधित है या नहीं। पढ़ने-लिखने योग्य बूलियन।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getEditPointsLocked() {#getEditPointsLocked--}
```
public abstract boolean getEditPointsLocked()
```

निर्धारित करता है कि इस आकार की कंटूर को सीधे बदलना प्रतिबंधित है या नहीं। पढ़ने-लिखने योग्य बूलियन।

**रिटर्न:**  
boolean
### setEditPointsLocked(boolean value) {#setEditPointsLocked-boolean-}
```
public abstract void setEditPointsLocked(boolean value)
```

निर्धारित करता है कि इस आकार की कंटूर को सीधे बदलना प्रतिबंधित है या नहीं। पढ़ने-लिखने योग्य बूलियन।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getAdjustHandlesLocked() {#getAdjustHandlesLocked--}
```
public abstract boolean getAdjustHandlesLocked()
```

निर्धारित करता है कि एडजस्ट वैल्यूज़ बदलना प्रतिबंधित है या नहीं। पढ़ने-लिखने योग्य बूलियन।

**रिटर्न:**  
boolean
### setAdjustHandlesLocked(boolean value) {#setAdjustHandlesLocked-boolean-}
```
public abstract void setAdjustHandlesLocked(boolean value)
```

निर्धारित करता है कि एडजस्ट वैल्यूज़ बदलना प्रतिबंधित है या नहीं। पढ़ने-लिखने योग्य बूलियन।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getArrowheadsLocked() {#getArrowheadsLocked--}
```
public abstract boolean getArrowheadsLocked()
```

निर्धारित करता है कि ऐरोहेड्स बदलना प्रतिबंधित है या नहीं। पढ़ने-लिखने योग्य बूलियन।

**रिटर्न:**  
boolean
### setArrowheadsLocked(boolean value) {#setArrowheadsLocked-boolean-}
```
public abstract void setArrowheadsLocked(boolean value)
```

निर्धारित करता है कि ऐरोहेड्स बदलना प्रतिबंधित है या नहीं। पढ़ने-लिखने योग्य बूलियन।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShapeTypeLocked() {#getShapeTypeLocked--}
```
public abstract boolean getShapeTypeLocked()
```

निर्धारित करता है कि आकार प्रकार बदलना प्रतिबंधित है या नहीं। पढ़ने-लिखने योग्य बूलियन।

**रिटर्न:**  
boolean
### setShapeTypeLocked(boolean value) {#setShapeTypeLocked-boolean-}
```
public abstract void setShapeTypeLocked(boolean value)
```

निर्धारित करता है कि आकार प्रकार बदलना प्रतिबंधित है या नहीं। पढ़ने-लिखने योग्य बूलियन।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getTextLocked() {#getTextLocked--}
```
public abstract boolean getTextLocked()
```

निर्धारित करता है कि टेक्स्ट को एडिट करना प्रतिबंधित है या नहीं। पढ़ने-लिखने योग्य बूलियन।

**रिटर्न:**  
boolean
### setTextLocked(boolean value) {#setTextLocked-boolean-}
```
public abstract void setTextLocked(boolean value)
```

निर्धारित करता है कि टेक्स्ट को एडिट करना प्रतिबंधित है या नहीं। पढ़ने-लिखने योग्य बूलियन।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |