---
title: EffectFormat
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
description: Αναπαριστά τις ιδιότητες εφέ του σχήματος.
type: docs
url: /el/com.aspose.slides/effectformat/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IEffectFormat](../../com.aspose.slides/ieffectformat)
```
public final class EffectFormat extends PVIObject implements IEffectFormat
```

Αναπαριστά τις ιδιότητες εφέ του σχήματος.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [isNoEffects()](#isNoEffects--) | Επιστρέφει true εάν όλα τα εφέ είναι απενεργοποιημένα (όπως μόλις δημιουργήθηκε, προεπιλεγμένο αντικείμενο EffectFormat). |
| [getBlurEffect()](#getBlurEffect--) | Εφέ θολώματος. |
| [setBlurEffect(IBlur value)](#setBlurEffect-com.aspose.slides.IBlur-) | Εφέ θολώματος. |
| [getFillOverlayEffect()](#getFillOverlayEffect--) | Εφέ επικάλυψης γεμίσματος. |
| [setFillOverlayEffect(IFillOverlay value)](#setFillOverlayEffect-com.aspose.slides.IFillOverlay-) | Εφέ επικάλυψης γεμίσματος. |
| [getGlowEffect()](#getGlowEffect--) | Εφέ λάμψης. |
| [setGlowEffect(IGlow value)](#setGlowEffect-com.aspose.slides.IGlow-) | Εφέ λάμψης. |
| [getInnerShadowEffect()](#getInnerShadowEffect--) | Εσωτερική σκιά. |
| [setInnerShadowEffect(IInnerShadow value)](#setInnerShadowEffect-com.aspose.slides.IInnerShadow-) | Εσωτερική σκιά. |
| [getOuterShadowEffect()](#getOuterShadowEffect--) | Εξωτερική σκιά. |
| [setOuterShadowEffect(IOuterShadow value)](#setOuterShadowEffect-com.aspose.slides.IOuterShadow-) | Εξωτερική σκιά. |
| [getPresetShadowEffect()](#getPresetShadowEffect--) | Προρυθμισμένη σκιά. |
| [setPresetShadowEffect(IPresetShadow value)](#setPresetShadowEffect-com.aspose.slides.IPresetShadow-) | Προρυθμισμένη σκιά. |
| [getReflectionEffect()](#getReflectionEffect--) | Αντανάκλαση. |
| [setReflectionEffect(IReflection value)](#setReflectionEffect-com.aspose.slides.IReflection-) | Αντανάκλαση. |
| [getSoftEdgeEffect()](#getSoftEdgeEffect--) | Απαλό άκρο. |
| [setSoftEdgeEffect(ISoftEdge value)](#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-) | Απαλό άκρο. |
| [setBlurEffect(double radius, boolean grow)](#setBlurEffect-double-boolean-) | Ορίζει το εφέ θολώματος. |
| [enableFillOverlayEffect()](#enableFillOverlayEffect--) | Ενεργοποιεί το εφέ επικάλυψης γεμίσματος. |
| [enableGlowEffect()](#enableGlowEffect--) | Ενεργοποιεί το εφέ λάμψης. |
| [enableInnerShadowEffect()](#enableInnerShadowEffect--) | Ενεργοποιεί το εφέ εσωτερικής σκιάς. |
| [enableOuterShadowEffect()](#enableOuterShadowEffect--) | Ενεργοποιεί το εφέ εξωτερικής σκιάς. |
| [enablePresetShadowEffect()](#enablePresetShadowEffect--) | Ενεργοποιεί το εφέ προρυθμισμένων σκιών. |
| [enableReflectionEffect()](#enableReflectionEffect--) | Ενεργοποιεί το εφέ αντανάκλασης. |
| [enableSoftEdgeEffect()](#enableSoftEdgeEffect--) | Ενεργοποιεί το εφέ απαλού άκρου. |
| [disableBlurEffect()](#disableBlurEffect--) | Απενεργοποιεί το εφέ θολώματος. |
| [disableFillOverlayEffect()](#disableFillOverlayEffect--) | Απενεργοποιεί το εφέ επικάλυψης γεμίσματος. |
| [disableGlowEffect()](#disableGlowEffect--) | Απενεργοποιεί το εφέ λάμψης. |
| [disableInnerShadowEffect()](#disableInnerShadowEffect--) | Απενεργοποιεί το εφέ εσωτερικής σκιάς. |
| [disableOuterShadowEffect()](#disableOuterShadowEffect--) | Απενεργοποιεί το εφέ εξωτερικής σκιάς. |
| [disablePresetShadowEffect()](#disablePresetShadowEffect--) | Απενεργοποιεί το εφέ προρυθμισμένης σκιάς. |
| [disableReflectionEffect()](#disableReflectionEffect--) | Απενεργοποιεί το εφέ αντανάκλασης. |
| [disableSoftEdgeEffect()](#disableSoftEdgeEffect--) | Απενεργοποιεί το εφέ απαλού άκρου. |
| [getEffective()](#getEffective--) | Αποκτά δεδομένα μορφοποίησης εφέ με την εφαρμογή κληρονομικότητας. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Έκδοση. Μόνο για ανάγνωση long.

**Επιστρέφει:**
long

### isNoEffects() {#isNoEffects--}
```
public final boolean isNoEffects()
```

Επιστρέφει true εάν όλα τα εφέ είναι απενεργοποιημένα (όπως μόλις δημιουργήθηκε, προεπιλεγμένο αντικείμενο EffectFormat). Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean

### getBlurEffect() {#getBlurEffect--}
```
public final IBlur getBlurEffect()
```

Εφέ θολώματος. Ανάγνωση/εγγραφή [IBlur](../../com.aspose.slides/iblur).

**Επιστρέφει:**
[IBlur](../../com.aspose.slides/iblur)

### setBlurEffect(IBlur value) {#setBlurEffect-com.aspose.slides.IBlur-}
```
public final void setBlurEffect(IBlur value)
```

Εφέ θολώματος. Ανάγνωση/εγγραφή [IBlur](../../com.aspose.slides/iblur).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IBlur](../../com.aspose.slides/iblur) |  |

### getFillOverlayEffect() {#getFillOverlayEffect--}
```
public final IFillOverlay getFillOverlayEffect()
```

Εφέ επικάλυψης γεμίσματος. Ανάγνωση/εγγραφή [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**Επιστρέφει:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay)

### setFillOverlayEffect(IFillOverlay value) {#setFillOverlayEffect-com.aspose.slides.IFillOverlay-}
```
public final void setFillOverlayEffect(IFillOverlay value)
```

Εφέ επικάλυψης γεμίσματος. Ανάγνωση/εγγραφή [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IFillOverlay](../../com.aspose.slides/ifilloverlay) |  |

### getGlowEffect() {#getGlowEffect--}
```
public final IGlow getGlowEffect()
```

Εφέ λάμψης. Ανάγνωση/εγγραφή [IGlow](../../com.aspose.slides/iglow).

**Επιστρέφει:**
[IGlow](../../com.aspose.slides/iglow)

### setGlowEffect(IGlow value) {#setGlowEffect-com.aspose.slides.IGlow-}
```
public final void setGlowEffect(IGlow value)
```

Εφέ λάμψης. Ανάγνωση/εγγραφή [IGlow](../../com.aspose.slides/iglow).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IGlow](../../com.aspose.slides/iglow) |  |

### getInnerShadowEffect() {#getInnerShadowEffect--}
```
public final IInnerShadow getInnerShadowEffect()
```

Εσωτερική σκιά. Ανάγνωση/εγγραφή [IInnerShadow](../../com.aspose.slides/iinnershadow).

**Επιστρέφει:**
[IInnerShadow](../../com.aspose.slides/iinnershadow)

### setInnerShadowEffect(IInnerShadow value) {#setInnerShadowEffect-com.aspose.slides.IInnerShadow-}
```
public final void setInnerShadowEffect(IInnerShadow value)
```

Εσωτερική σκιά. Ανάγνωση/εγγραφή [IInnerShadow](../../com.aspose.slides/iinnershadow).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IInnerShadow](../../com.aspose.slides/iinnershadow) |  |

### getOuterShadowEffect() {#getOuterShadowEffect--}
```
public final IOuterShadow getOuterShadowEffect()
```

Εξωτερική σκιά. Ανάγνωση/εγγραφή [IOuterShadow](../../com.aspose.slides/ioutershadow).

**Επιστρέφει:**
[IOuterShadow](../../com.aspose.slides/ioutershadow)

### setOuterShadowEffect(IOuterShadow value) {#setOuterShadowEffect-com.aspose.slides.IOuterShadow-}
```
public final void setOuterShadowEffect(IOuterShadow value)
```

Εξωτερική σκιά. Ανάγνωση/εγγραφή [IOuterShadow](../../com.aspose.slides/ioutershadow).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IOuterShadow](../../com.aspose.slides/ioutershadow) |  |

### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public final IPresetShadow getPresetShadowEffect()
```

Προρυθμισμένη σκιά. Ανάγνωση/εγγραφή [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**Επιστρέφει:**
[IPresetShadow](../../com.aspose.slides/ipresetshadow)

### setPresetShadowEffect(IPresetShadow value) {#setPresetShadowEffect-com.aspose.slides.IPresetShadow-}
```
public final void setPresetShadowEffect(IPresetShadow value)
```

Προρυθμισμένη σκιά. Ανάγνωση/εγγραφή [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IPresetShadow](../../com.aspose.slides/ipresetshadow) |  |

### getReflectionEffect() {#getReflectionEffect--}
```
public final IReflection getReflectionEffect()
```

Αντανάκλαση. Ανάγνωση/εγγραφή [IReflection](../../com.aspose.slides/ireflection).

**Επιστρέφει:**
[IReflection](../../com.aspose.slides/ireflection)

### setReflectionEffect(IReflection value) {#setReflectionEffect-com.aspose.slides.IReflection-}
```
public final void setReflectionEffect(IReflection value)
```

Αντανάκλαση. Ανάγνωση/εγγραφή [IReflection](../../com.aspose.slides/ireflection).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IReflection](../../com.aspose.slides/ireflection) |  |

### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public final ISoftEdge getSoftEdgeEffect()
```

Απαλό άκρο. Ανάγνωση/εγγραφή [ISoftEdge](../../com.aspose.slides/isoftedge).

**Επιστρέφει:**
[ISoftEdge](../../com.aspose.slides/isoftedge)

### setSoftEdgeEffect(ISoftEdge value) {#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-}
```
public final void setSoftEdgeEffect(ISoftEdge value)
```

Απαλό άκρο. Ανάγνωση/εγγραφή [ISoftEdge](../../com.aspose.slides/isoftedge).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ISoftEdge](../../com.aspose.slides/isoftedge) |  |

### setBlurEffect(double radius, boolean grow) {#setBlurEffect-double-boolean-}
```
public final void setBlurEffect(double radius, boolean grow)
```

Ορίζει το εφέ θολώματος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| radius | double | Ακτίνα. |
| grow | boolean | Μεγέθυνση. |

### enableFillOverlayEffect() {#enableFillOverlayEffect--}
```
public final void enableFillOverlayEffect()
```

Ενεργοποιεί το εφέ επικάλυψης γεμίσματος.

### enableGlowEffect() {#enableGlowEffect--}
```
public final void enableGlowEffect()
```

Ενεργοποιεί το εφέ λάμψης.

### enableInnerShadowEffect() {#enableInnerShadowEffect--}
```
public final void enableInnerShadowEffect()
```

Ενεργοποιεί το εφέ εσωτερικής σκιάς.

### enableOuterShadowEffect() {#enableOuterShadowEffect--}
```
public final void enableOuterShadowEffect()
```

Ενεργοποιεί το εφέ εξωτερικής σκιάς.

### enablePresetShadowEffect() {#enablePresetShadowEffect--}
```
public final void enablePresetShadowEffect()
```

Ενεργοποιεί το εφέ προρυθμισμένων σκιών.

### enableReflectionEffect() {#enableReflectionEffect--}
```
public final void enableReflectionEffect()
```

Ενεργοποιεί το εφέ αντανάκλασης.

### enableSoftEdgeEffect() {#enableSoftEdgeEffect--}
```
public final void enableSoftEdgeEffect()
```

Ενεργοποιεί το εφέ απαλού άκρου.

### disableBlurEffect() {#disableBlurEffect--}
```
public final void disableBlurEffect()
```

Απενεργοποιεί το εφέ θολώματος.

### disableFillOverlayEffect() {#disableFillOverlayEffect--}
```
public final void disableFillOverlayEffect()
```

Απενεργοποιεί το εφέ επικάλυψης γεμίσματος.

### disableGlowEffect() {#disableGlowEffect--}
```
public final void disableGlowEffect()
```

Απενεργοποιεί το εφέ λάμψης.

### disableInnerShadowEffect() {#disableInnerShadowEffect--}
```
public final void disableInnerShadowEffect()
```

Απενεργοποιεί το εφέ εσωτερικής σκιάς.

### disableOuterShadowEffect() {#disableOuterShadowEffect--}
```
public final void disableOuterShadowEffect()
```

Απενεργοποιεί το εφέ εξωτερικής σκιάς.

### disablePresetShadowEffect() {#disablePresetShadowEffect--}
```
public final void disablePresetShadowEffect()
```

Απενεργοποιεί το εφέ προρυθμισμένης σκιάς.

### disableReflectionEffect() {#disableReflectionEffect--}
```
public final void disableReflectionEffect()
```

Απενεργοποιεί το εφέ αντανάκλασης.

### disableSoftEdgeEffect() {#disableSoftEdgeEffect--}
```
public final void disableSoftEdgeEffect()
```

Απενεργοποιεί το εφέ απαλού άκρου.

### getEffective() {#getEffective--}
```
public final IEffectFormatEffectiveData getEffective()
```

Αποκτά δεδομένα μορφοποίησης εφέ με την εφαρμογή κληρονομικότητας.

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

**Επιστρέφει:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata) - Ένα [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).