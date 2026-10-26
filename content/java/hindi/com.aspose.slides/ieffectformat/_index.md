---
title: IEffectFormat
second_title: Aspose.Slides के लिए Java API संदर्भ
description: आकृति के प्रभाव गुणों का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ieffectformat/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IEffectParamSource](../../com.aspose.slides/ieffectparamsource)
```
public interface IEffectFormat extends IEffectParamSource
```

आकृति के प्रभाव गुणों का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [isNoEffects()](#isNoEffects--) | सभी प्रभाव निष्क्रिय हैं तो true लौटाता है (जैसे अभी अभी बनाया गया, डिफ़ॉल्ट EffectFormat ऑब्जेक्ट)। |
| [getBlurEffect()](#getBlurEffect--) | ब्लर प्रभाव। |
| [setBlurEffect(IBlur value)](#setBlurEffect-com.aspose.slides.IBlur-) | ब्लर प्रभाव। |
| [getFillOverlayEffect()](#getFillOverlayEffect--) | भर ओवरले प्रभाव। |
| [setFillOverlayEffect(IFillOverlay value)](#setFillOverlayEffect-com.aspose.slides.IFillOverlay-) | भर ओवरले प्रभाव। |
| [getGlowEffect()](#getGlowEffect--) | ग्लो प्रभाव। |
| [setGlowEffect(IGlow value)](#setGlowEffect-com.aspose.slides.IGlow-) | ग्लो प्रभाव। |
| [getInnerShadowEffect()](#getInnerShadowEffect--) | आंतरिक छाया। |
| [setInnerShadowEffect(IInnerShadow value)](#setInnerShadowEffect-com.aspose.slides.IInnerShadow-) | आंतरिक छाया। |
| [getOuterShadowEffect()](#getOuterShadowEffect--) | बाहरी छाया। |
| [setOuterShadowEffect(IOuterShadow value)](#setOuterShadowEffect-com.aspose.slides.IOuterShadow-) | बाहरी छाया। |
| [getPresetShadowEffect()](#getPresetShadowEffect--) | पूर्वनिर्धारित छाया। |
| [setPresetShadowEffect(IPresetShadow value)](#setPresetShadowEffect-com.aspose.slides.IPresetShadow-) | पूर्वनिर्धारित छाया। |
| [getReflectionEffect()](#getReflectionEffect--) | परावर्तन। |
| [setReflectionEffect(IReflection value)](#setReflectionEffect-com.aspose.slides.IReflection-) | परावर्तन। |
| [getSoftEdgeEffect()](#getSoftEdgeEffect--) | नरम किनारा। |
| [setSoftEdgeEffect(ISoftEdge value)](#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-) | नरम किनारा। |
| [setBlurEffect(double radius, boolean grow)](#setBlurEffect-double-boolean-) | ब्लर प्रभाव सेट करता है। |
| [enableFillOverlayEffect()](#enableFillOverlayEffect--) | भर ओवरले प्रभाव को सक्षम करता है। |
| [enableGlowEffect()](#enableGlowEffect--) | ग्लो प्रभाव को सक्षम करता है। |
| [enableInnerShadowEffect()](#enableInnerShadowEffect--) | आंतरिक छाया प्रभाव को सक्षम करता है। |
| [enableOuterShadowEffect()](#enableOuterShadowEffect--) | बाहरी छाया प्रभाव को सक्षम करता है। |
| [enablePresetShadowEffect()](#enablePresetShadowEffect--) | पूर्वनिर्धारित छाया प्रभाव को सक्षम करता है। |
| [enableReflectionEffect()](#enableReflectionEffect--) | परावर्तन प्रभाव को सक्षम करता है। |
| [enableSoftEdgeEffect()](#enableSoftEdgeEffect--) | नरम किनारा प्रभाव को सक्षम करता है। |
| [disableBlurEffect()](#disableBlurEffect--) | ब्लर प्रभाव को अक्षम करता है। |
| [disableFillOverlayEffect()](#disableFillOverlayEffect--) | भर ओवरले प्रभाव को अक्षम करता है। |
| [disableGlowEffect()](#disableGlowEffect--) | ग्लो प्रभाव को अक्षम करता है। |
| [disableInnerShadowEffect()](#disableInnerShadowEffect--) | आंतरिक छाया प्रभाव को अक्षम करता है। |
| [disableOuterShadowEffect()](#disableOuterShadowEffect--) | बाहरी छाया प्रभाव को अक्षम करता है। |
| [disablePresetShadowEffect()](#disablePresetShadowEffect--) | पूर्वनिर्धारित छाया प्रभाव को अक्षम करता है। |
| [disableReflectionEffect()](#disableReflectionEffect--) | परावर्तन प्रभाव को अक्षम करता है। |
| [disableSoftEdgeEffect()](#disableSoftEdgeEffect--) | नरम किनारा प्रभाव को अक्षम करता है। |
| [getEffective()](#getEffective--) | विरासत लागू करके प्रभावी फ़ॉर्मेटिंग डेटा प्राप्त करता है। |
### isNoEffects() {#isNoEffects--}
```
public abstract boolean isNoEffects()
```

सभी प्रभाव निष्क्रिय हैं तो true लौटाता है (जैसे अभी अभी बनाया गया, डिफ़ॉल्ट EffectFormat ऑब्जेक्ट)। केवल-पढ़ने योग्य बूलियन।

**वापसी:**
boolean
### getBlurEffect() {#getBlurEffect--}
```
public abstract IBlur getBlurEffect()
```

ब्लर प्रभाव। पढ़ने/लिखने [IBlur](../../com.aspose.slides/iblur)।

**वापसी:**
[IBlur](../../com.aspose.slides/iblur)
### setBlurEffect(IBlur value) {#setBlurEffect-com.aspose.slides.IBlur-}
```
public abstract void setBlurEffect(IBlur value)
```

ब्लर प्रभाव। पढ़ने/लिखने [IBlur](../../com.aspose.slides/iblur)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IBlur](../../com.aspose.slides/iblur) |  |

### getFillOverlayEffect() {#getFillOverlayEffect--}
```
public abstract IFillOverlay getFillOverlayEffect()
```

भरण ओवरले प्रभाव। पढ़ने/लिखने [IFillOverlay](../../com.aspose.slides/ifilloverlay)।

**वापसी:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay)
### setFillOverlayEffect(IFillOverlay value) {#setFillOverlayEffect-com.aspose.slides.IFillOverlay-}
```
public abstract void setFillOverlayEffect(IFillOverlay value)
```

भरण ओवरले प्रभाव। पढ़ने/लिखने [IFillOverlay](../../com.aspose.slides/ifilloverlay)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IFillOverlay](../../com.aspose.slides/ifilloverlay) |  |

### getGlowEffect() {#getGlowEffect--}
```
public abstract IGlow getGlowEffect()
```

ग्लो प्रभाव। पढ़ने/लिखने [IGlow](../../com.aspose.slides/iglow)।

**वापसी:**
[IGlow](../../com.aspose.slides/iglow)
### setGlowEffect(IGlow value) {#setGlowEffect-com.aspose.slides.IGlow-}
```
public abstract void setGlowEffect(IGlow value)
```

ग्लो प्रभाव। पढ़ने/लिखने [IGlow](../../com.aspose.slides/iglow)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IGlow](../../com.aspose.slides/iglow) |  |

### getInnerShadowEffect() {#getInnerShadowEffect--}
```
public abstract IInnerShadow getInnerShadowEffect()
```

आंतरिक छाया। पढ़ने/लिखने [IInnerShadow](../../com.aspose.slides/iinnershadow)।

**वापसी:**
[IInnerShadow](../../com.aspose.slides/iinnershadow)
### setInnerShadowEffect(IInnerShadow value) {#setInnerShadowEffect-com.aspose.slides.IInnerShadow-}
```
public abstract void setInnerShadowEffect(IInnerShadow value)
```

आंतरिक छाया। पढ़ने/लिखने [IInnerShadow](../../com.aspose.slides/iinnershadow)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IInnerShadow](../../com.aspose.slides/iinnershadow) |  |

### getOuterShadowEffect() {#getOuterShadowEffect--}
```
public abstract IOuterShadow getOuterShadowEffect()
```

बाहरी छाया। पढ़ने/लिखने [IOuterShadow](../../com.aspose.slides/ioutershadow)।

**वापसी:**
[IOuterShadow](../../com.aspose.slides/ioutershadow)
### setOuterShadowEffect(IOuterShadow value) {#setOuterShadowEffect-com.aspose.slides.IOuterShadow-}
```
public abstract void setOuterShadowEffect(IOuterShadow value)
```

बाहरी छाया। पढ़ने/लिखने [IOuterShadow](../../com.aspose.slides/ioutershadow)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IOuterShadow](../../com.aspose.slides/ioutershadow) |  |

### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public abstract IPresetShadow getPresetShadowEffect()
```

पूर्वनिर्धारित छाया। पढ़ने/लिखने [IPresetShadow](../../com.aspose.slides/ipresetshadow)।

**वापसी:**
[IPresetShadow](../../com.aspose.slides/ipresetshadow)
### setPresetShadowEffect(IPresetShadow value) {#setPresetShadowEffect-com.aspose.slides.IPresetShadow-}
```
public abstract void setPresetShadowEffect(IPresetShadow value)
```

पूर्वनिर्धारित छाया। पढ़ने/लिखने [IPresetShadow](../../com.aspose.slides/ipresetshadow)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IPresetShadow](../../com.aspose.slides/ipresetshadow) |  |

### getReflectionEffect() {#getReflectionEffect--}
```
public abstract IReflection getReflectionEffect()
```

परावर्तन। पढ़ने/लिखने [IReflection](../../com.aspose.slides/ireflection)।

**वापसी:**
[IReflection](../../com.aspose.slides/ireflection)
### setReflectionEffect(IReflection value) {#setReflectionEffect-com.aspose.slides.IReflection-}
```
public abstract void setReflectionEffect(IReflection value)
```

परावर्तन। पढ़ने/लिखने [IReflection](../../com.aspose.slides/ireflection)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IReflection](../../com.aspose.slides/ireflection) |  |

### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public abstract ISoftEdge getSoftEdgeEffect()
```

नरम किनारा। पढ़ने/लिखने [ISoftEdge](../../com.aspose.slides/isoftedge)।

**वापसी:**
[ISoftEdge](../../com.aspose.slides/isoftedge)
### setSoftEdgeEffect(ISoftEdge value) {#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-}
```
public abstract void setSoftEdgeEffect(ISoftEdge value)
```

नरम किनारा। पढ़ने/लिखने [ISoftEdge](../../com.aspose.slides/isoftedge)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ISoftEdge](../../com.aspose.slides/isoftedge) |  |

### setBlurEffect(double radius, boolean grow) {#setBlurEffect-double-boolean-}
```
public abstract void setBlurEffect(double radius, boolean grow)
```

ब्लर प्रभाव सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| radius | double | त्रिज्या। |
| grow | boolean | वृद्धि। |

### enableFillOverlayEffect() {#enableFillOverlayEffect--}
```
public abstract void enableFillOverlayEffect()
```

भरण ओवरले प्रभाव को सक्षम करता है।

### enableGlowEffect() {#enableGlowEffect--}
```
public abstract void enableGlowEffect()
```

ग्लो प्रभाव को सक्षम करता है।

### enableInnerShadowEffect() {#enableInnerShadowEffect--}
```
public abstract void enableInnerShadowEffect()
```

आंतरिक छाया प्रभाव को सक्षम करता है।

### enableOuterShadowEffect() {#enableOuterShadowEffect--}
```
public abstract void enableOuterShadowEffect()
```

बाहरी छाया प्रभाव को सक्षम करता है।

### enablePresetShadowEffect() {#enablePresetShadowEffect--}
```
public abstract void enablePresetShadowEffect()
```

पूर्वनिर्धारित छाया प्रभाव को सक्षम करता है।

### enableReflectionEffect() {#enableReflectionEffect--}
```
public abstract void enableReflectionEffect()
```

परावर्तन प्रभाव को सक्षम करता है।

### enableSoftEdgeEffect() {#enableSoftEdgeEffect--}
```
public abstract void enableSoftEdgeEffect()
```

नरम किनारा प्रभाव को सक्षम करता है।

### disableBlurEffect() {#disableBlurEffect--}
```
public abstract void disableBlurEffect()
```

ब्लर प्रभाव को अक्षम करता है।

### disableFillOverlayEffect() {#disableFillOverlayEffect--}
```
public abstract void disableFillOverlayEffect()
```

भरण ओवरले प्रभाव को अक्षम करता है।

### disableGlowEffect() {#disableGlowEffect--}
```
public abstract void disableGlowEffect()
```

ग्लो प्रभाव को अक्षम करता है।

### disableInnerShadowEffect() {#disableInnerShadowEffect--}
```
public abstract void disableInnerShadowEffect()
```

आंतरिक छाया प्रभाव को अक्षम करता है।

### disableOuterShadowEffect() {#disableOuterShadowEffect--}
```
public abstract void disableOuterShadowEffect()
```

बाहरी छाया प्रभाव को अक्षम करता है।

### disablePresetShadowEffect() {#disablePresetShadowEffect--}
```
public abstract void disablePresetShadowEffect()
```

पूर्वनिर्धारित छाया प्रभाव को अक्षम करता है।

### disableReflectionEffect() {#disableReflectionEffect--}
```
public abstract void disableReflectionEffect()
```

परावर्तन प्रभाव को अक्षम करता है।

### disableSoftEdgeEffect() {#disableSoftEdgeEffect--}
```
public abstract void disableSoftEdgeEffect()
```

नरम किनारा प्रभाव को अक्षम करता है।

### getEffective() {#getEffective--}
```
public abstract IEffectFormatEffectiveData getEffective()
```

विरासत लागू करके प्रभावी फ़ॉर्मेटिंग डेटा प्राप्त करता है।

**वापसी:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata) - A [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).