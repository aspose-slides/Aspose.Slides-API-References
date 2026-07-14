---
title: IEffectFormat
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: आकृति की प्रभाव विशेषताओं को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/ieffectformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.IEffectParamSource](../../com.aspose.slides/ieffectparamsource)
```
public interface IEffectFormat extends IEffectParamSource
```

आकृति की प्रभाव गुणों का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [isNoEffects()](#isNoEffects--) | यदि सभी प्रभाव निष्क्रिय हैं तो true लौटाता है (जैसे अभी बनाया गया, डिफ़ॉल्ट EffectFormat ऑब्जेक्ट)। |
| [getBlurEffect()](#getBlurEffect--) | ब्लर प्रभाव। |
| [setBlurEffect(IBlur value)](#setBlurEffect-com.aspose.slides.IBlur-) | ब्लर प्रभाव। |
| [getFillOverlayEffect()](#getFillOverlayEffect--) | फ़िल ओवरले प्रभाव। |
| [setFillOverlayEffect(IFillOverlay value)](#setFillOverlayEffect-com.aspose.slides.IFillOverlay-) | फ़िल ओवरले प्रभाव। |
| [getGlowEffect()](#getGlowEffect--) | ग्लो प्रभाव। |
| [setGlowEffect(IGlow value)](#setGlowEffect-com.aspose.slides.IGlow-) | ग्लो प्रभाव। |
| [getInnerShadowEffect()](#getInnerShadowEffect--) | इनर शैडो। |
| [setInnerShadowEffect(IInnerShadow value)](#setInnerShadowEffect-com.aspose.slides.IInnerShadow-) | इनर शैडो। |
| [getOuterShadowEffect()](#getOuterShadowEffect--) | आउटर शैडो। |
| [setOuterShadowEffect(IOuterShadow value)](#setOuterShadowEffect-com.aspose.slides.IOuterShadow-) | आउटर शैडो। |
| [getPresetShadowEffect()](#getPresetShadowEffect--) | प्रीसेट शैडो। |
| [setPresetShadowEffect(IPresetShadow value)](#setPresetShadowEffect-com.aspose.slides.IPresetShadow-) | प्रीसेट शैडो। |
| [getReflectionEffect()](#getReflectionEffect--) | परावर्तन। |
| [setReflectionEffect(IReflection value)](#setReflectionEffect-com.aspose.slides.IReflection-) | परावर्तन। |
| [getSoftEdgeEffect()](#getSoftEdgeEffect--) | नरम किनारा। |
| [setSoftEdgeEffect(ISoftEdge value)](#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-) | नरम किनारा। |
| [setBlurEffect(double radius, boolean grow)](#setBlurEffect-double-boolean-) | ब्लर प्रभाव सेट करता है। |
| [enableFillOverlayEffect()](#enableFillOverlayEffect--) | फ़िल ओवरले प्रभाव सक्षम करता है। |
| [enableGlowEffect()](#enableGlowEffect--) | ग्लो प्रभाव सक्षम करता है। |
| [enableInnerShadowEffect()](#enableInnerShadowEffect--) | इनर शैडो प्रभाव सक्षम करता है। |
| [enableOuterShadowEffect()](#enableOuterShadowEffect--) | आउटर शैडो प्रभाव सक्षम करता है। |
| [enablePresetShadowEffect()](#enablePresetShadowEffect--) | प्रीसेट शैडो प्रभाव सक्षम करता है। |
| [enableReflectionEffect()](#enableReflectionEffect--) | परावर्तन प्रभाव सक्षम करता है। |
| [enableSoftEdgeEffect()](#enableSoftEdgeEffect--) | नरम किनारा प्रभाव सक्षम करता है। |
| [disableBlurEffect()](#disableBlurEffect--) | ब्लर प्रभाव निष्क्रिय करता है। |
| [disableFillOverlayEffect()](#disableFillOverlayEffect--) | फ़िल ओवरले प्रभाव निष्क्रिय करता है। |
| [disableGlowEffect()](#disableGlowEffect--) | ग्लो प्रभाव निष्क्रिय करता है। |
| [disableInnerShadowEffect()](#disableInnerShadowEffect--) | इनर शैडो प्रभाव निष्क्रिय करता है। |
| [disableOuterShadowEffect()](#disableOuterShadowEffect--) | आउटर शैडो प्रभाव निष्क्रिय करता है। |
| [disablePresetShadowEffect()](#disablePresetShadowEffect--) | प्रीसेट शैडो प्रभाव निष्क्रिय करता है। |
| [disableReflectionEffect()](#disableReflectionEffect--) | परावर्तन प्रभाव निष्क्रिय करता है। |
| [disableSoftEdgeEffect()](#disableSoftEdgeEffect--) | नरम किनारा प्रभाव निष्क्रिय करता है। |
| [getEffective()](#getEffective--) | विरासत लागू करके प्रभावी प्रभाव स्वरूप डेटा प्राप्त करता है। |

### isNoEffects() {#isNoEffects--}
```
public abstract boolean isNoEffects()
```

यदि सभी प्रभाव निष्क्रिय हैं तो true लौटाता है (जैसे अभी बनाया गया, डिफ़ॉल्ट EffectFormat ऑब्जेक्ट)। केवल-पठन बूलियन।

**वापसी:**
boolean

### getBlurEffect() {#getBlurEffect--}
```
public abstract IBlur getBlurEffect()
```

ब्लर प्रभाव। पढ़ें/लिखें [IBlur](../../com.aspose.slides/iblur)।

**वापसी:**
[IBlur](../../com.aspose.slides/iblur)

### setBlurEffect(IBlur value) {#setBlurEffect-com.aspose.slides.IBlur-}
```
public abstract void setBlurEffect(IBlur value)
```

ब्लर प्रभाव। पढ़ें/लिखें [IBlur](../../com.aspose.slides/iblur)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IBlur](../../com.aspose.slides/iblur) |  |

### getFillOverlayEffect() {#getFillOverlayEffect--}
```
public abstract IFillOverlay getFillOverlayEffect()
```

फ़िल ओवरले प्रभाव। पढ़ें/लिखें [IFillOverlay](../../com.aspose.slides/ifilloverlay)।

**वापसी:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay)

### setFillOverlayEffect(IFillOverlay value) {#setFillOverlayEffect-com.aspose.slides.IFillOverlay-}
```
public abstract void setFillOverlayEffect(IFillOverlay value)
```

फ़िल ओवरले प्रभाव। पढ़ें/लिखें [IFillOverlay](../../com.aspose.slides/ifilloverlay)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IFillOverlay](../../com.aspose.slides/ifilloverlay) |  |

### getGlowEffect() {#getGlowEffect--}
```
public abstract IGlow getGlowEffect()
```

ग्लो प्रभाव। पढ़ें/लिखें [IGlow](../../com.aspose.slides/iglow)।

**वापसी:**
[IGlow](../../com.aspose.slides/iglow)

### setGlowEffect(IGlow value) {#setGlowEffect-com.aspose.slides.IGlow-}
```
public abstract void setGlowEffect(IGlow value)
```

ग्लो प्रभाव। पढ़ें/लिखें [IGlow](../../com.aspose.slides/iglow)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IGlow](../../com.aspose.slides/iglow) |  |

### getInnerShadowEffect() {#getInnerShadowEffect--}
```
public abstract IInnerShadow getInnerShadowEffect()
```

इनर शैडो। पढ़ें/लिखें [IInnerShadow](../../com.aspose.slides/iinnershadow)।

**वापसी:**
[IInnerShadow](../../com.aspose.slides/iinnershadow)

### setInnerShadowEffect(IInnerShadow value) {#setInnerShadowEffect-com.aspose.slides.IInnerShadow-}
```
public abstract void setInnerShadowEffect(IInnerShadow value)
```

इनर शैडो। पढ़ें/लिखें [IInnerShadow](../../com.aspose.slides/iinnershadow)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IInnerShadow](../../com.aspose.slides/iinnershadow) |  |

### getOuterShadowEffect() {#getOuterShadowEffect--}
```
public abstract IOuterShadow getOuterShadowEffect()
```

आउटर शैडो। पढ़ें/लिखें [IOuterShadow](../../com.aspose.slides/ioutershadow)।

**वापसी:**
[IOuterShadow](../../com.aspose.slides/ioutershadow)

### setOuterShadowEffect(IOuterShadow value) {#setOuterShadowEffect-com.aspose.slides.IOuterShadow-}
```
public abstract void setOuterShadowEffect(IOuterShadow value)
```

आउटर शैडो। पढ़ें/लिखें [IOuterShadow](../../com.aspose.slides/ioutershadow)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IOuterShadow](../../com.aspose.slides/ioutershadow) |  |

### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public abstract IPresetShadow getPresetShadowEffect()
```

प्रीसेट शैडो। पढ़ें/लिखें [IPresetShadow](../../com.aspose.slides/ipresetshadow)।

**वापसी:**
[IPresetShadow](../../com.aspose.slides/ipresetshadow)

### setPresetShadowEffect(IPresetShadow value) {#setPresetShadowEffect-com.aspose.slides.IPresetShadow-}
```
public abstract void setPresetShadowEffect(IPresetShadow value)
```

प्रीसेट शैडो। पढ़ें/लिखें [IPresetShadow](../../com.aspose.slides/ipresetshadow)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IPresetShadow](../../com.aspose.slides/ipresetshadow) |  |

### getReflectionEffect() {#getReflectionEffect--}
```
public abstract IReflection getReflectionEffect()
```

परावर्तन। पढ़ें/लिखें [IReflection](../../com.aspose.slides/ireflection)।

**वापसी:**
[IReflection](../../com.aspose.slides/ireflection)

### setReflectionEffect(IReflection value) {#setReflectionEffect-com.aspose.slides.IReflection-}
```
public abstract void setReflectionEffect(IReflection value)
```

परावर्तन। पढ़ें/लिखें [IReflection](../../com.aspose.slides/ireflection)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IReflection](../../com.aspose.slides/ireflection) |  |

### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public abstract ISoftEdge getSoftEdgeEffect()
```

नरम किनारा। पढ़ें/लिखें [ISoftEdge](../../com.aspose.slides/isoftedge)।

**वापसी:**
[ISoftEdge](../../com.aspose.slides/isoftedge)

### setSoftEdgeEffect(ISoftEdge value) {#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-}
```
public abstract void setSoftEdgeEffect(ISoftEdge value)
```

नरम किनारा। पढ़ें/लिखें [ISoftEdge](../../com.aspose.slides/isoftedge)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ISoftEdge](../../com.aspose.slides/isoftedge) |  |

### setBlurEffect(double radius, boolean grow) {#setBlurEffect-double-boolean-}
```
public abstract void setBlurEffect(double radius, boolean grow)
```

ब्लर प्रभाव सेट करता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| radius | double | त्रिज्या। |
| grow | boolean | वृद्धि। |

### enableFillOverlayEffect() {#enableFillOverlayEffect--}
```
public abstract void enableFillOverlayEffect()
```

फ़िल ओवरले प्रभाव सक्षम करता है।

### enableGlowEffect() {#enableGlowEffect--}
```
public abstract void enableGlowEffect()
```

ग्लो प्रभाव सक्षम करता है।

### enableInnerShadowEffect() {#enableInnerShadowEffect--}
```
public abstract void enableInnerShadowEffect()
```

इनर शैडो प्रभाव सक्षम करता है।

### enableOuterShadowEffect() {#enableOuterShadowEffect--}
```
public abstract void enableOuterShadowEffect()
```

आउटर शैडो प्रभाव सक्षम करता है।

### enablePresetShadowEffect() {#enablePresetShadowEffect--}
```
public abstract void enablePresetShadowEffect()
```

प्रीसेट शैडो प्रभाव सक्षम करता है।

### enableReflectionEffect() {#enableReflectionEffect--}
```
public abstract void enableReflectionEffect()
```

परावर्तन प्रभाव सक्षम करता है।

### enableSoftEdgeEffect() {#enableSoftEdgeEffect--}
```
public abstract void enableSoftEdgeEffect()
```

नरम किनारा प्रभाव सक्षम करता है।

### disableBlurEffect() {#disableBlurEffect--}
```
public abstract void disableBlurEffect()
```

ब्लर प्रभाव निष्क्रिय करता है।

### disableFillOverlayEffect() {#disableFillOverlayEffect--}
```
public abstract void disableFillOverlayEffect()
```

फ़िल ओवरले प्रभाव निष्क्रिय करता है।

### disableGlowEffect() {#disableGlowEffect--}
```
public abstract void disableGlowEffect()
```

ग्लो प्रभाव निष्क्रिय करता है।

### disableInnerShadowEffect() {#disableInnerShadowEffect--}
```
public abstract void disableInnerShadowEffect()
```

इनर शैडो प्रभाव निष्क्रिय करता है।

### disableOuterShadowEffect() {#disableOuterShadowEffect--}
```
public abstract void disableOuterShadowEffect()
```

आउटर शैडो प्रभाव निष्क्रिय करता है।

### disablePresetShadowEffect() {#disablePresetShadowEffect--}
```
public abstract void disablePresetShadowEffect()
```

प्रीसेट शैडो प्रभाव निष्क्रिय करता है।

### disableReflectionEffect() {#disableReflectionEffect--}
```
public abstract void disableReflectionEffect()
```

परावर्तन प्रभाव निष्क्रिय करता है।

### disableSoftEdgeEffect() {#disableSoftEdgeEffect--}
```
public abstract void disableSoftEdgeEffect()
```

नरम किनारा प्रभाव निष्क्रिय करता है।

### getEffective() {#getEffective--}
```
public abstract IEffectFormatEffectiveData getEffective()
```

विरासत लागू करके प्रभावी प्रभाव स्वरूप डेटा प्राप्त करता है।

**वापसी:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata) - A [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).