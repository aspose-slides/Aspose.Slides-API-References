---
title: IEffectFormat
second_title: Αναφορά API Aspose.Slides για Java
description: Αντιπροσωπεύει τις ιδιότητες εφέ του σχήματος.
type: docs
url: /el/com.aspose.slides/ieffectformat/
---
**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IEffectParamSource](../../com.aspose.slides/ieffectparamsource)
```
public interface IEffectFormat extends IEffectParamSource
```

Αντιπροσωπεύει τις ιδιότητες εφέ του σχήματος.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [isNoEffects()](#isNoEffects--) | Επιστρέφει true αν όλα τα εφέ είναι απενεργοποιημένα (όπως μόλις δημιουργήθηκε, προεπιλεγμένο αντικείμενο EffectFormat). |
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
| [getPresetShadowEffect()](#getPresetShadowEffect--) | Προεπιλεγμένη σκιά. |
| [setPresetShadowEffect(IPresetShadow value)](#setPresetShadowEffect-com.aspose.slides.IPresetShadow-) | Προεπιλεγμένη σκιά. |
| [getReflectionEffect()](#getReflectionEffect--) | Αντανάκλαση. |
| [setReflectionEffect(IReflection value)](#setReflectionEffect-com.aspose.slides.IReflection-) | Αντανάκλαση. |
| [getSoftEdgeEffect()](#getSoftEdgeEffect--) | Μαλακό άκρο. |
| [setSoftEdgeEffect(ISoftEdge value)](#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-) | Μαλακό άκρο. |
| [setBlurEffect(double radius, boolean grow)](#setBlurEffect-double-boolean-) | Ορίζει εφέ θολώματος. |
| [enableFillOverlayEffect()](#enableFillOverlayEffect--) | Ενεργοποιεί το εφέ επικάλυψης γεμίσματος. |
| [enableGlowEffect()](#enableGlowEffect--) | Ενεργοποιεί το εφέ λάμψης. |
| [enableInnerShadowEffect()](#enableInnerShadowEffect--) | Ενεργοποιεί το εφέ εσωτερικής σκιάς. |
| [enableOuterShadowEffect()](#enableOuterShadowEffect--) | Ενεργοποιεί το εφέ εξωτερικής σκιάς. |
| [enablePresetShadowEffect()](#enablePresetShadowEffect--) | Ενεργοποιεί το εφέ προεπιλεγμένων σκιών. |
| [enableReflectionEffect()](#enableReflectionEffect--) | Ενεργοποιεί το εφέ αντανάκλασης. |
| [enableSoftEdgeEffect()](#enableSoftEdgeEffect--) | Ενεργοποιεί το εφέ μαλακού άκρου. |
| [disableBlurEffect()](#disableBlurEffect--) | Απενεργοποιεί το εφέ θολώματος. |
| [disableFillOverlayEffect()](#disableFillOverlayEffect--) | Απενεργοποιεί το εφέ επικάλυψης γεμίσματος. |
| [disableGlowEffect()](#disableGlowEffect--) | Απενεργοποιεί το εφέ λάμψης. |
| [disableInnerShadowEffect()](#disableInnerShadowEffect--) | Απενεργοποιεί το εφέ εσωτερικής σκιάς. |
| [disableOuterShadowEffect()](#disableOuterShadowEffect--) | Απενεργοποιεί το εφέ εξωτερικής σκιάς. |
| [disablePresetShadowEffect()](#disablePresetShadowEffect--) | Απενεργοποιεί το εφέ προεπιλεγμένης σκιάς. |
| [disableReflectionEffect()](#disableReflectionEffect--) | Απενεργοποιεί το εφέ αντανάκλασης. |
| [disableSoftEdgeEffect()](#disableSoftEdgeEffect--) | Απενεργοποιεί το εφέ μαλακού άκρου. |
| [getEffective()](#getEffective--) | Λαμβάνει τα δεδομένα μορφοποίησης του εφέ με την κληρονομικότητα που εφαρμόζεται. |

### isNoEffects() {#isNoEffects--}
```
public abstract boolean isNoEffects()
```


Επιστρέφει true αν όλα τα εφέ είναι απενεργοποιημένα (όπως μόλις δημιουργήθηκε, προεπιλεγμένο αντικείμενο EffectFormat). Μόνο για ανάγνωση boolean.

### getBlurEffect() {#getBlurEffect--}
```
public abstract IBlur getBlurEffect()
```


Εφέ θολώματος. Αναγνώσιμη/εγγράψιμη [IBlur](../../com.aspose.slides/iblur).

**Επιστρέφει:**
[IBlur](../../com.aspose.slides/iblur)
### setBlurEffect(IBlur value) {#setBlurEffect-com.aspose.slides.IBlur-}
```
public abstract void setBlurEffect(IBlur value)
```


Εφέ θολώματος. Αναγνώσιμη/εγγράψιμη [IBlur](../../com.aspose.slides/iblur).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IBlur](../../com.aspose.slides/iblur) |  |

### getFillOverlayEffect() {#getFillOverlayEffect--}
```
public abstract IFillOverlay getFillOverlayEffect()
```


Εφέ επικάλυψης γεμίσματος. Αναγνώσιμη/εγγράψιμη [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**Επιστρέφει:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay)
### setFillOverlayEffect(IFillOverlay value) {#setFillOverlayEffect-com.aspose.slides.IFillOverlay-}
```
public abstract void setFillOverlayEffect(IFillOverlay value)
```


Εφέ επικάλυψης γεμίσματος. Αναγνώσιμη/εγγράψιμη [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IFillOverlay](../../com.aspose.slides/ifilloverlay) |  |

### getGlowEffect() {#getGlowEffect--}
```
public abstract IGlow getGlowEffect()
```


Εφέ λάμψης. Αναγνώσιμη/εγγράψιμη [IGlow](../../com.aspose.slides/iglow).

**Επιστρέφει:**
[IGlow](../../com.aspose.slides/iglow)
### setGlowEffect(IGlow value) {#setGlowEffect-com.aspose.slides.IGlow-}
```
public abstract void setGlowEffect(IGlow value)
```


Εφέ λάμψης. Αναγνώσιμη/εγγράψιμη [IGlow](../../com.aspose.slides/iglow).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IGlow](../../com.aspose.slides/iglow) |  |

### getInnerShadowEffect() {#getInnerShadowEffect--}
```
public abstract IInnerShadow getInnerShadowEffect()
```


Εσωτερική σκιά. Αναγνώσιμη/εγγράψιμη [IInnerShadow](../../com.aspose.slides/iinnershadow).

**Επιστρέφει:**
[IInnerShadow](../../com.aspose.slides/iinnershadow)
### setInnerShadowEffect(IInnerShadow value) {#setInnerShadowEffect-com.aspose.slides.IInnerShadow-}
```
public abstract void setInnerShadowEffect(IInnerShadow value)
```


Εσωτερική σκιά. Αναγνώσιμη/εγγράψιμη [IInnerShadow](../../com.aspose.slides/iinnershadow).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IInnerShadow](../../com.aspose.slides/iinnershadow) |  |

### getOuterShadowEffect() {#getOuterShadowEffect--}
```
public abstract IOuterShadow getOuterShadowEffect()
```


Εξωτερική σκιά. Αναγνώσιμη/εγγράψιμη [IOuterShadow](../../com.aspose.slides/ioutershadow).

**Επιστρέφει:**
[IOuterShadow](../../com.aspose.slides/ioutershadow)
### setOuterShadowEffect(IOuterShadow value) {#setOuterShadowEffect-com.aspose.slides.IOuterShadow-}
```
public abstract void setOuterShadowEffect(IOuterShadow value)
```


Εξωτερική σκιά. Αναγνώσιμη/εγγράψιμη [IOuterShadow](../../com.aspose.slides/ioutershadow).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IOuterShadow](../../com.aspose.slides/ioutershadow) |  |

### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public abstract IPresetShadow getPresetShadowEffect()
```


Προεπιλεγμένη σκιά. Αναγνώσιμη/εγγράψιμη [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**Επιστρέφει:**
[IPresetShadow](../../com.aspose.slides/ipresetshadow)
### setPresetShadowEffect(IPresetShadow value) {#setPresetShadowEffect-com.aspose.slides.IPresetShadow-}
```
public abstract void setPresetShadowEffect(IPresetShadow value)
```


Προεπιλεγμένη σκιά. Αναγνώσιμη/εγγράψιμη [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IPresetShadow](../../com.aspose.slides/ipresetshadow) |  |

### getReflectionEffect() {#getReflectionEffect--}
```
public abstract IReflection getReflectionEffect()
```


Αντανάκλαση. Αναγνώσιμη/εγγράψιμη [IReflection](../../com.aspose.slides/ireflection).

**Επιστρέφει:**
[IReflection](../../com.aspose.slides/ireflection)
### setReflectionEffect(IReflection value) {#setReflectionEffect-com.aspose.slides.IReflection-}
```
public abstract void setReflectionEffect(IReflection value)
```


Αντανάκλαση. Αναγνώσιμη/εγγράψιμη [IReflection](../../com.aspose.slides/ireflection).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IReflection](../../com.aspose.slides/ireflection) |  |

### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public abstract ISoftEdge getSoftEdgeEffect()
```


Μαλακό άκρο. Αναγνώσιμη/εγγράψιμη [ISoftEdge](../../com.aspose.slides/isoftedge).

**Επιστρέφει:**
[ISoftEdge](../../com.aspose.slides/isoftedge)
### setSoftEdgeEffect(ISoftEdge value) {#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-}
```
public abstract void setSoftEdgeEffect(ISoftEdge value)
```


Μαλακό άκρο. Αναγνώσιμη/εγγράψιμη [ISoftEdge](../../com.aspose.slides/isoftedge).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ISoftEdge](../../com.aspose.slides/isoftedge) |  |

### setBlurEffect(double radius, boolean grow) {#setBlurEffect-double-boolean-}
```
public abstract void setBlurEffect(double radius, boolean grow)
```


Ορίζει εφέ θολώματος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| radius | double | Ακτίνα. |
| grow | boolean | Αύξηση. |

### enableFillOverlayEffect() {#enableFillOverlayEffect--}
```
public abstract void enableFillOverlayEffect()
```


Ενεργοποιεί το εφέ επικάλυψης γεμίσματος.

### enableGlowEffect() {#enableGlowEffect--}
```
public abstract void enableGlowEffect()
```


Ενεργοποιεί το εφέ λάμψης.

### enableInnerShadowEffect() {#enableInnerShadowEffect--}
```
public abstract void enableInnerShadowEffect()
```


Ενεργοποιεί το εφέ εσωτερικής σκιάς.

### enableOuterShadowEffect() {#enableOuterShadowEffect--}
```
public abstract void enableOuterShadowEffect()
```


Ενεργοποιεί το εφέ εξωτερικής σκιάς.

### enablePresetShadowEffect() {#enablePresetShadowEffect--}
```
public abstract void enablePresetShadowEffect()
```


Ενεργοποιεί το εφέ προεπιλεγμένων σκιών.

### enableReflectionEffect() {#enableReflectionEffect--}
```
public abstract void enableReflectionEffect()
```


Ενεργοποιεί το εφέ αντανάκλασης.

### enableSoftEdgeEffect() {#enableSoftEdgeEffect--}
```
public abstract void enableSoftEdgeEffect()
```


Ενεργοποιεί το εφέ μαλακού άκρου.

### disableBlurEffect() {#disableBlurEffect--}
```
public abstract void disableBlurEffect()
```


Απενεργοποιεί το εφέ θολώματος.

### disableFillOverlayEffect() {#disableFillOverlayEffect--}
```
public abstract void disableFillOverlayEffect()
```


Απενεργοποιεί το εφέ επικάλυψης γεμίσματος.

### disableGlowEffect() {#disableGlowEffect--}
```
public abstract void disableGlowEffect()
```


Απενεργοποιεί το εφέ λάμψης.

### disableInnerShadowEffect() {#disableInnerShadowEffect--}
```
public abstract void disableInnerShadowEffect()
```


Απενεργοποιεί το εφέ εσωτερικής σκιάς.

### disableOuterShadowEffect() {#disableOuterShadowEffect--}
```
public abstract void disableOuterShadowEffect()
```


Απενεργοποιεί το εφέ εξωτερικής σκιάς.

### disablePresetShadowEffect() {#disablePresetShadowEffect--}
```
public abstract void disablePresetShadowEffect()
```


Απενεργοποιεί το εφέ προεπιλεγμένης σκιάς.

### disableReflectionEffect() {#disableReflectionEffect--}
```
public abstract void disableReflectionEffect()
```


Απενεργοποιεί το εφέ αντανάκλασης.

### disableSoftEdgeEffect() {#disableSoftEdgeEffect--}
```
public abstract void disableSoftEdgeEffect()
```


Απενεργοποιεί το εφέ μαλακού άκρου.

### getEffective() {#getEffective--}
```
public abstract IEffectFormatEffectiveData getEffective()
```


Λαμβάνει τα δεδομένα μορφοποίησης του εφέ με την κληρονομικότητα που εφαρμόζεται.

**Επιστρέφει:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata) - Ένα [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).