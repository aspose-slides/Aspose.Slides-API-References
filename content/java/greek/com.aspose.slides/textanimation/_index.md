---
title: TextAnimation
second_title: Αναφορά API του Aspose.Slides για Java
description: Παραστήζει κίνηση κειμένου.
type: docs
url: /el/com.aspose.slides/textanimation/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.ITextAnimation](../../com.aspose.slides/itextanimation)
```
public class TextAnimation implements ITextAnimation
```

Παραστήζει κίνηση κειμένου.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [TextAnimation()](#TextAnimation--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Προσθέτει νέο εφέ στο τέλος της τρέχουσας αλληλουχίας έως το τέλος των ομαδικών κειμενικών κινήσεων. |
| [getBuildType()](#getBuildType--) | Λίστα τύπων οικοδόμησης (π.χ. |
| [setBuildType(int value)](#setBuildType-int-) | Λίστα τύπων οικοδόμησης (π.χ. |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | Συνδεδεμένο εφέ σχήματος με ομάδα ή όχι (null). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | Συνδεδεμένο εφέ σχήματος με ομάδα ή όχι (null). |
### TextAnimation() {#TextAnimation--}
```
public TextAnimation()
```


### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public final IEffect addEffect(int effectType, int subtype, int triggerType)
```


Προσθέτει νέο εφέ στο τέλος της τρέχουσας αλληλουχίας έως το τέλος των ομαδικών κειμενικών κινήσεων. Ισχύει μόνο εάν ο αριθμός των παραγράφων κειμένου είναι ίσος ή μεγαλύτερος από τον αριθμό των εφέ αυτής της ομάδας!

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| effectType | int | Τύπος εφέ κίνησης [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Υποτύποι εφέ κίνησης [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Τύπος ενεργοποίησης εφέ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Επιστρέφει:**
[IEffect](../../com.aspose.slides/ieffect) - Νέο αντικείμενο εφέ [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public final int getBuildType()
```


Λίστα τύπων οικοδόμησης (π.χ. Παράγραφος 1,2,3, Όλες μαζί) της κίνησης κειμένου. Ανάγνωση/εγγραφή [BuildType](../../com.aspose.slides/buildtype).

**Επιστρέφει:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public final void setBuildType(int value)
```


Λίστα τύπων οικοδόμησης (π.χ. Παράγραφος 1,2,3, Όλες μαζί) της κίνησης κειμένου. Ανάγνωση/εγγραφή [BuildType](../../com.aspose.slides/buildtype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public final IEffect getEffectAnimateBackgroundShape()
```


Συνδεδεμένο εφέ σχήματος με ομάδα ή όχι (null). Ανάγνωση/εγγραφή [IEffect](../../com.aspose.slides/ieffect).

**Επιστρέφει:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public final void setEffectAnimateBackgroundShape(IEffect value)
```


Συνδεδεμένο εφέ σχήματος με ομάδα ή όχι (null). Ανάγνωση/εγγραφή [IEffect](../../com.aspose.slides/ieffect).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |