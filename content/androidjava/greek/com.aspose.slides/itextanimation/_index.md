---
title: ITextAnimation
second_title: Aspose.Slides for Android via Java API Reference
description: Represent text animation.
type: docs
url: /el/com.aspose.slides/itextanimation/
---```
public interface ITextAnimation
```

Αναπαριστά κίνηση κειμένου.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Προσθέτει νέο εφέ στο τέλος της τρέχουσας ακολουθίας μέχρι το τέλος των ομαδικών κινήσεων κειμένου. |
| [getBuildType()](#getBuildType--) | Λίστα τύπων κατασκευής (για π.χ. |
| [setBuildType(int value)](#setBuildType-int-) | Λίστα τύπων κατασκευής (για π.χ. |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | Συσχετισμένο εφέ σχήματος με ομάδα ή όχι (null) Ανάγνωση/Εγγραφή [IEffect](../../com.aspose.slides/ieffect). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | Συσχετισμένο εφέ σχήματος με ομάδα ή όχι (null) Ανάγνωση/Εγγραφή [IEffect](../../com.aspose.slides/ieffect). |
### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public abstract IEffect addEffect(int effectType, int subtype, int triggerType)
```


Προσθέτει νέο εφέ στο τέλος της τρέχουσας ακολουθίας μέχρι το τέλος των ομαδικών κινήσεων κειμένου. Ισχύει μόνο εάν ο αριθμός των παραγράφων κειμένου είναι ίσος ή μεγαλύτερος από τον αριθμό των εφέ αυτής της ομάδας!

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
public abstract int getBuildType()
```


Λίστα τύπων κατασκευής (π.χ. Παράγραφος 1,2,3, Όλα μαζί) της κίνησης κειμένου. Ανάγνωση/Εγγραφή \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**Επιστρέφει:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public abstract void setBuildType(int value)
```


Λίστα τύπων κατασκευής (π.χ. Παράγραφος 1,2,3, Όλα μαζί) της κίνησης κειμένου. Ανάγνωση/Εγγραφή \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public abstract IEffect getEffectAnimateBackgroundShape()
```


Συσχετισμένο εφέ σχήματος με ομάδα ή όχι (null) Ανάγνωση/Εγγραφή [IEffect](../../com.aspose.slides/ieffect).

**Επιστρέφει:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public abstract void setEffectAnimateBackgroundShape(IEffect value)
```


Συσχετισμένο εφέ σχήματος με ομάδα ή όχι (null) Ανάγνωση/Εγγραφή [IEffect](../../com.aspose.slides/ieffect).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |