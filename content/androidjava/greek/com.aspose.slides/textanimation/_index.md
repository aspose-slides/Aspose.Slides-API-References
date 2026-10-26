---
title: TextAnimation
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αναπαριστά κειμενική κίνηση.
type: docs
url: /el/com.aspose.slides/textanimation/
---
**Κληρονόμηση:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ITextAnimation](../../com.aspose.slides/itextanimation)
```
public class TextAnimation implements ITextAnimation
```

Αναπαριστά κειμενική κίνηση.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [TextAnimation()](#TextAnimation--) |  |
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Προσθέτει νέο εφέ στο τέλος της τρέχουσας ακολουθίας των ομαδικών κειμενικών κινούμενων γραφικών. |
| [getBuildType()](#getBuildType--) | Λίστα τύπων κατασκευής (για παράδειγμα |
| [setBuildType(int value)](#setBuildType-int-) | Λίστα τύπων κατασκευής (για παράδειγμα |
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


Προσθέτει νέο εφέ στο τέλος της τρέχουσας ακολουθίας των ομαδικών κειμενικών κινούμενων γραφικών. Ισχύει μόνο εάν ο αριθμός παραγράφων κειμένου είναι ίσος ή μεγαλύτερος από τον αριθμό εφέ αυτής της ομάδας!

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| effectType | int | Τύπος εφέ ανίμασης [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Υποτύποι εφέ ανίμασης [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Τύπος ενεργοποίησης του εφέ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Επιστρέφει:**
[IEffect](../../com.aspose.slides/ieffect) - Νέο αντικείμενο εφέ [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public final int getBuildType()
```


Λίστα τύπων κατασκευής (π.χ. Ενότητα 1,2,3, Όλα μαζί) της κειμενικής κίνηση. Ανάγνωση/εγγραφή [BuildType](../../com.aspose.slides/buildtype).

**Επιστρέφει:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public final void setBuildType(int value)
```


Λίστα τύπων κατασκευής (π.χ. Ενότητα 1,2,3, Όλα μαζί) της κειμενικής κίνηση. Ανάγνωση/εγγραφή [BuildType](../../com.aspose.slides/buildtype).

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