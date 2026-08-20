---
title: IFillOverlay
second_title: Aspose.Slides for Java API संदर्भ
description: एक Fill Overlay प्रभाव को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/ifilloverlay/
---
**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject  
```
public interface IFillOverlay extends IImageTransformOperation, IAccessiblePVIObject<IFillOverlayEffectiveData>
```

एक Fill Overlay प्रभाव को दर्शाता है। एक fill overlay का उपयोग एक वस्तु के लिए अतिरिक्त fill निर्दिष्ट करने और दो fills को मिलाने के लिए किया जा सकता है।

## विधियां

| विधि | विवरण |
| --- | --- |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getFillFormat()](#getFillFormat--) | Fill format. |

### getBlend() {#getBlend--}
```
public abstract int getBlend()
```

FillBlendMode. पढ़ें/लिखें [FillBlendMode](../../com.aspose.slides/fillblendmode).

**रिटर्न:**  
int

### setBlend(int value) {#setBlend-int-}
```
public abstract void setBlend(int value)
```

FillBlendMode. पढ़ें/लिखें [FillBlendMode](../../com.aspose.slides/fillblendmode).

**पैरामीटर:**  

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Fill format. केवल पढ़ने योग्य [IFillFormat](../../com.aspose.slides/ifillformat).

**रिटर्न:**  
[IFillFormat](../../com.aspose.slides/ifillformat)