---
title: IFillOverlay
second_title: Aspose.Slides Android के लिए Java API रेफ़रेंस
description: एक Fill Overlay प्रभाव का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ifilloverlay/
---
**All Implemented Interfaces:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IFillOverlay extends IImageTransformOperation, IAccessiblePVIObject<IFillOverlayEffectiveData>
```

एक Fill Overlay प्रभाव का प्रतिनिधित्व करता है। Fill overlay का उपयोग किसी वस्तु के लिए अतिरिक्त fill निर्दिष्ट करने और दोनों fills को मिलाने के लिए किया जा सकता है।
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

**वापसी मान:**
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

**वापसी मान:**
[IFillFormat](../../com.aspose.slides/ifillformat)