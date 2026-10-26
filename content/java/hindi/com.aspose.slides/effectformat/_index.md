---
title: EffectFormat
second_title: Aspose.Slides के लिए Java API संदर्भ
description: आकार के प्रभाव गुणों को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/effectformat/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IEffectFormat](../../com.aspose.slides/ieffectformat)  
```
public final class EffectFormat extends PVIObject implements IEffectFormat
```

आकार के प्रभाव गुणों को दर्शाता है।  

## विधियां

| विधि | विवरण |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [isNoEffects()](#isNoEffects--) | सभी प्रभाव अक्षम हैं तो true लौटाता है (जैसे कि अभी बनाया गया, डिफ़ॉल्ट EffectFormat ऑब्जेक्ट)। |
| [getBlurEffect()](#getBlurEffect--) | ब्लर प्रभाव। |
| [setBlurEffect(IBlur value)](#setBlurEffect-com.aspose.slides.IBlur-) | ब्लर प्रभाव। |
| [getFillOverlayEffect()](#getFillOverlayEffect--) | फ़िल ओवरले प्रभाव। |
| [setFillOverlayEffect(IFillOverlay value)](#setFillOverlayEffect-com.aspose.slides.IFillOverlay-) | फ़िल ओवरले प्रभाव। |
| [getGlowEffect()](#getGlowEffect--) | ग्लो प्रभाव। |
| [setGlowEffect(IGlow value)](#setGlowEffect-com.aspose.slides.IGlow-) | ग्लो प्रभाव। |
| [getInnerShadowEffect()](#getInnerShadowEffect--) | आंतरिक छाया। |
| [setInnerShadowEffect(IInnerShadow value)](#setInnerShadowEffect-com.aspose.slides.IInnerShadow-) | आंतरिक छाया। |
| [getOuterShadowEffect()](#getOuterShadowEffect--) | बाहरी छाया। |
| [setOuterShadowEffect(IOuterShadow value)](#setOuterShadowEffect-com.aspose.slides.IOuterShadow-) | बाहरी छाया। |
| [getPresetShadowEffect()](#getPresetShadowEffect--) | प्रीसेट छाया। |
| [setPresetShadowEffect(IPresetShadow value)](#setPresetShadowEffect-com.aspose.slides.IPresetShadow-) | प्रीसेट छाया। |
| [getReflectionEffect()](#getReflectionEffect--) | रिफ्लेक्शन। |
| [setReflectionEffect(IReflection value)](#setReflectionEffect-com.aspose.slides.IReflection-) | रिफ्लेक्शन। |
| [getSoftEdgeEffect()](#getSoftEdgeEffect--) | सॉफ्ट एज। |
| [setSoftEdgeEffect(ISoftEdge value)](#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-) | सॉफ्ट एज। |
| [setBlurEffect(double radius, boolean grow)](#setBlurEffect-double-boolean-) | ब्लर प्रभाव सेट करता है। |
| [enableFillOverlayEffect()](#enableFillOverlayEffect--) | फ़िल ओवरले प्रभाव सक्षम करता है। |
| [enableGlowEffect()](#enableGlowEffect--) | ग्लो प्रभाव सक्षम करता है। |
| [enableInnerShadowEffect()](#enableInnerShadowEffect--) | आंतरिक छाया प्रभाव सक्षम करता है। |
| [enableOuterShadowEffect()](#enableOuterShadowEffect--) | बाहरी छाया प्रभाव सक्षम करता है। |
| [enablePresetShadowEffect()](#enablePresetShadowEffect--) | प्रीसेट शैडो प्रभाव सक्षम करता है। |
| [enableReflectionEffect()](#enableReflectionEffect--) | रिफ्लेक्शन प्रभाव सक्षम करता है। |
| [enableSoftEdgeEffect()](#enableSoftEdgeEffect--) | सॉफ्ट एज प्रभाव सक्षम करता है। |
| [disableBlurEffect()](#disableBlurEffect--) | ब्लर प्रभाव अक्षम करता है। |
| [disableFillOverlayEffect()](#disableFillOverlayEffect--) | फ़िल ओवरले प्रभाव अक्षम करता है। |
| [disableGlowEffect()](#disableGlowEffect--) | ग्लो प्रभाव अक्षम करता है। |
| [disableInnerShadowEffect()](#disableInnerShadowEffect--) | आंतरिक छाया प्रभाव अक्षम करता है। |
| [disableOuterShadowEffect()](#disableOuterShadowEffect--) | बाहरी छाया प्रभाव अक्षम करता है। |
| [disablePresetShadowEffect()](#disablePresetShadowEffect--) | प्रीसेट छाया प्रभाव अक्षम करता है। |
| [disableReflectionEffect()](#disableReflectionEffect--) | रिफ्लेक्शन प्रभाव अक्षम करता है। |
| [disableSoftEdgeEffect()](#disableSoftEdgeEffect--) | सॉफ्ट एज प्रभाव अक्षम करता है। |
| [getEffective()](#getEffective--) | विरासत लागू किए गए प्रभाव फ़ॉर्मेटिंग डेटा को प्राप्त करता है। |

### getVersion() {#getVersion--}
```
public long getVersion()
```

संस्करण। केवल-पढ़ने योग्य long।

**वापसी:**
long

### isNoEffects() {#isNoEffects--}
```
public final boolean isNoEffects()
```

सभी प्रभाव अक्षम हैं तो true लौटाता है (जैसे कि अभी बनाया गया, डिफ़ॉल्ट EffectFormat ऑब्जेक्ट)। केवल-पढ़ने योग्य boolean।

**वापसी:**
boolean

### getBlurEffect() {#getBlurEffect--}
```
public final IBlur getBlurEffect()
```

ब्लर प्रभाव। पढ़े-लिखे योग्य [IBlur](../../com.aspose.slides/iblur)।

**वापसी:**
[IBlur](../../com.aspose.slides/iblur)

### setBlurEffect(IBlur value) {#setBlurEffect-com.aspose.slides.IBlur-}
```
public final void setBlurEffect(IBlur value)
```

ब्लर प्रभाव। पढ़े-लिखे योग्य [IBlur](../../com.aspose.slides/iblur)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IBlur](../../com.aspose.slides/iblur) |  |

### getFillOverlayEffect() {#getFillOverlayEffect--}
```
public final IFillOverlay getFillOverlayEffect()
```

फ़िल ओवरले प्रभाव। पढ़े-लिखे योग्य [IFillOverlay](../../com.aspose.slides/ifilloverlay)।

**वापसी:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay)

### setFillOverlayEffect(IFillOverlay value) {#setFillOverlayEffect-com.aspose.slides.IFillOverlay-}
```
public final void setFillOverlayEffect(IFillOverlay value)
```

फ़िल ओवरले प्रभाव। पढ़े-लिखे योग्य [IFillOverlay](../../com.aspose.slides/ifilloverlay)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IFillOverlay](../../com.aspose.slides/ifilloverlay) |  |

### getGlowEffect() {#getGlowEffect--}
```
public final IGlow getGlowEffect()
```

ग्लो प्रभाव। पढ़े-लिखे योग्य [IGlow](../../com.aspose.slides/iglow)।

**वापसी:**
[IGlow](../../com.aspose.slides/iglow)

### setGlowEffect(IGlow value) {#setGlowEffect-com.aspose.slides.IGlow-}
```
public final void setGlowEffect(IGlow value)
```

ग्लो प्रभाव। पढ़े-लिखे योग्य [IGlow](../../com.aspose.slides/iglow)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IGlow](../../com.aspose.slides/iglow) |  |

### getInnerShadowEffect() {#getInnerShadowEffect--}
```
public final IInnerShadow getInnerShadowEffect()
```

आंतरिक छाया। पढ़े-लिखे योग्य [IInnerShadow](../../com.aspose.slides/iinnershadow)।

**वापसी:**
[IInnerShadow](../../com.aspose.slides/iinnershadow)

### setInnerShadowEffect(IInnerShadow value) {#setInnerShadowEffect-com.aspose.slides.IInnerShadow-}
```
public final void setInnerShadowEffect(IInnerShadow value)
```

आंतरिक छाया। पढ़े-लिखे योग्य [IInnerShadow](../../com.aspose.slides/iinnershadow)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IInnerShadow](../../com.aspose.slides/iinnershadow) |  |

### getOuterShadowEffect() {#getOuterShadowEffect--}
```
public final IOuterShadow getOuterShadowEffect()
```

बाहरी छाया। पढ़े-लिखे योग्य [IOuterShadow](../../com.aspose.slides/ioutershadow)।

**वापसी:**
[IOuterShadow](../../com.aspose.slides/ioutershadow)

### setOuterShadowEffect(IOuterShadow value) {#setOuterShadowEffect-com.aspose.slides.IOuterShadow-}
```
public final void setOuterShadowEffect(IOuterShadow value)
```

बाहरी छाया। पढ़े-लिखे योग्य [IOuterShadow](../../com.aspose.slides/ioutershadow)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IOuterShadow](../../com.aspose.slides/ioutershadow) |  |

### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public final IPresetShadow getPresetShadowEffect()
```

प्रीसेट छाया। पढ़े-लिखे योग्य [IPresetShadow](../../com.aspose.slides/ipresetshadow)।

**वापसी:**
[IPresetShadow](../../com.aspose.slides/ipresetshadow)

### setPresetShadowEffect(IPresetShadow value) {#setPresetShadowEffect-com.aspose.slides.IPresetShadow-}
```
public final void setPresetShadowEffect(IPresetShadow value)
```

प्रीसेट छाया। पढ़े-लिखे योग्य [IPresetShadow](../../com.aspose.slides/ipresetshadow)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IPresetShadow](../../com.aspose.slides/ipresetshadow) |  |

### getReflectionEffect() {#getReflectionEffect--}
```
public final IReflection getReflectionEffect()
```

रिफ्लेक्शन। पढ़े-लिखे योग्य [IReflection](../../com.aspose.slides/ireflection)।

**वापसी:**
[IReflection](../../com.aspose.slides/ireflection)

### setReflectionEffect(IReflection value) {#setReflectionEffect-com.aspose.slides.IReflection-}
```
public final void setReflectionEffect(IReflection value)
```

रिफ्लेक्शन। पढ़े-लिखे योग्य [IReflection](../../com.aspose.slides/ireflection)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IReflection](../../com.aspose.slides/ireflection) |  |

### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public final ISoftEdge getSoftEdgeEffect()
```

सॉफ्ट एज। पढ़े-लिखे योग्य [ISoftEdge](../../com.aspose.slides/isoftedge)।

**वापसी:**
[ISoftEdge](../../com.aspose.slides/isoftedge)

### setSoftEdgeEffect(ISoftEdge value) {#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-}
```
public final void setSoftEdgeEffect(ISoftEdge value)
```

सॉफ्ट एज। पढ़े-लिखे योग्य [ISoftEdge](../../com.aspose.slides/isoftedge)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ISoftEdge](../../com.aspose.slides/isoftedge) |  |

### setBlurEffect(double radius, boolean grow) {#setBlurEffect-double-boolean-}
```
public final void setBlurEffect(double radius, boolean grow)
```

ब्लर प्रभाव सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| radius | double | Radius. |
| grow | boolean | Grow. |

### enableFillOverlayEffect() {#enableFillOverlayEffect--}
```
public final void enableFillOverlayEffect()
```

फ़िल ओवरले प्रभाव सक्षम करता है।

### enableGlowEffect() {#enableGlowEffect--}
```
public final void enableGlowEffect()
```

ग्लो प्रभाव सक्षम करता है।

### enableInnerShadowEffect() {#enableInnerShadowEffect--}
```
public final void enableInnerShadowEffect()
```

आंतरिक छाया प्रभाव सक्षम करता है।

### enableOuterShadowEffect() {#enableOuterShadowEffect--}
```
public final void enableOuterShadowEffect()
```

बाहरी छाया प्रभाव सक्षम करता है।

### enablePresetShadowEffect() {#enablePresetShadowEffect--}
```
public final void enablePresetShadowEffect()
```

प्रीसेट शैडो प्रभाव सक्षम करता है।

### enableReflectionEffect() {#enableReflectionEffect--}
```
public final void enableReflectionEffect()
```

रिफ्लेक्शन प्रभाव सक्षम करता है।

### enableSoftEdgeEffect() {#enableSoftEdgeEffect--}
```
public final void enableSoftEdgeEffect()
```

सॉफ्ट एज प्रभाव सक्षम करता है।

### disableBlurEffect() {#disableBlurEffect--}
```
public final void disableBlurEffect()
```

ब्लर प्रभाव अक्षम करता है।

### disableFillOverlayEffect() {#disableFillOverlayEffect--}
```
public final void disableFillOverlayEffect()
```

फ़िल ओवरले प्रभाव अक्षम करता है।

### disableGlowEffect() {#disableGlowEffect--}
```
public final void disableGlowEffect()
```

ग्लो प्रभाव अक्षम करता है।

### disableInnerShadowEffect() {#disableInnerShadowEffect--}
```
public final void disableInnerShadowEffect()
```

आंतरिक छाया प्रभाव अक्षम करता है।

### disableOuterShadowEffect() {#disableOuterShadowEffect--}
```
public final void disableOuterShadowEffect()
```

बाहरी छाया प्रभाव अक्षम करता है।

### disablePresetShadowEffect() {#disablePresetShadowEffect--}
```
public final void disablePresetShadowEffect()
```

प्रीसेट छाया प्रभाव अक्षम करता है।

### disableReflectionEffect() {#disableReflectionEffect--}
```
public final void disableReflectionEffect()
```

रिफ्लेक्शन प्रभाव अक्षम करता है।

### disableSoftEdgeEffect() {#disableSoftEdgeEffect--}
```
public final void disableSoftEdgeEffect()
```

सॉफ्ट एज प्रभाव अक्षम करता है।

### getEffective() {#getEffective--}
```
public final IEffectFormatEffectiveData getEffective()
```

विरासत लागू किए गए प्रभाव फ़ॉर्मेटिंग डेटा को प्राप्त करता है।

--------------------

> ```
> This example demonstrates getting some of shape's effective effect properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IEffectFormatEffectiveData effectiveEffectFormat = pres.getSlides().get_Item(0).Shapes().get_Item(0).getEffectFormat().getEffective();
>  	if (effectiveEffectFormat.isNoEffects())
>  	{
>  		System.out.println("The shape has not effects applied.");
>  	}
>  	else
>  	{
>  		if (effectiveEffectFormat.getBlurEffect() != null)
>  			System.out.println("Blur effect radius: " + effectiveEffectFormat.getBlurEffect().getRadius());
>  		if (effectiveEffectFormat.getFillOverlayEffect() != null)
>  			System.out.println("Fill overlay effect fill type: " + effectiveEffectFormat.getFillOverlayEffect().getFillFormat().getFillType());
>  		if (effectiveEffectFormat.getGlowEffect() != null)
>  			System.out.println("Glow effect color: " + effectiveEffectFormat.getGlowEffect().getColor());
>  		if (effectiveEffectFormat.getInnerShadowEffect() != null)
>  			System.out.println("Inner shadow effect shadow color: " + effectiveEffectFormat.getInnerShadowEffect().getShadowColor());
>  		if (effectiveEffectFormat.getOuterShadowEffect() != null)
>  			System.out.println("Outer shadow effect shadow color: " + effectiveEffectFormat.getOuterShadowEffect().getShadowColor());
>  		if (effectiveEffectFormat.getPresetShadowEffect() != null)
>  			System.out.println("Preset shadow effect shadow color: " + effectiveEffectFormat.getPresetShadowEffect().getShadowColor());
>  		if (effectiveEffectFormat.getReflectionEffect() != null)
>  			System.out.println("Reflection effect distance: " + effectiveEffectFormat.getReflectionEffect().getDistance());
>  		if (effectiveEffectFormat.getSoftEdgeEffect() != null)
>  			System.out.println("Soft edge effect radius: " + effectiveEffectFormat.getSoftEdgeEffect().getRadius());
>  	}
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**वापसी:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata) - A [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).