---
title: ITextAnimation
second_title: Aspose.Slides for Java API Reference
description: Αναπαριστά την κίνηση κειμένου.
type: docs
url: /el/com.aspose.slides/itextanimation/
---```
public interface ITextAnimation
```

Αναπαριστά την κίνηση κειμένου.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Προσθέτει νέο εφέ στο τέλος της τρέχουσας ακολουθίας στο τέλος των ομαδικών κινήσεων κειμένου. |
| [getBuildType()](#getBuildType--) | Λίστα τύπου δημιουργίας (για π.χ. |
| [setBuildType(int value)](#setBuildType-int-) | Λίστα τύπου δημιουργίας (για π.χ. |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | Εφέ συνδεδεμένου σχήματος με ομάδα ή όχι (null) Ανάγνωση/εγγραφή [IEffect](../../com.aspose.slides/ieffect). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | Εφέ συνδεδεμένου σχήματος με ομάδα ή όχι (null) Ανάγνωση/εγγραφή [IEffect](../../com.aspose.slides/ieffect). |
### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public abstract IEffect addEffect(int effectType, int subtype, int triggerType)
```

Προσθέτει νέο εφέ στο τέλος της τρέχουσας ακολουθίας στο τέλος των ομαδικών κινήσεων κειμένου. Ισχύει μόνο εάν ο αριθμός των παραγράφων κειμένου είναι ίσος ή μεγαλύτερος από τον αριθμό των εφέ αυτής της ομάδας!

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| effectType | int | Τύπος εφέ κίνησης [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Υποτύπους εφέ κίνησης [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Τύπο ενεργοποίησης εφέ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Επιστρέφει:**
[IEffect](../../com.aspose.slides/ieffect) - Νέο αντικείμενο εφέ [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public abstract int getBuildType()
```

Λίστα τύπου δημιουργίας (π.χ. Παράγραφος 1,2,3, Όλα ταυτόχρονα) της κίνησης κειμένου. Ανάγνωση/εγγραφή \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**Επιστρέφει:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public abstract void setBuildType(int value)
```

Λίστα τύπου δημιουργίας (π.χ. Παράγραφος 1,2,3, Όλα ταυτόχρονα) της κίνησης κειμένου. Ανάγνωση/εγγραφή \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public abstract IEffect getEffectAnimateBackgroundShape()
```

Εφέ συνδεδεμένου σχήματος με ομάδα ή όχι (null) Ανάγνωση/εγγραφή [IEffect](../../com.aspose.slides/ieffect).

**Επιστρέφει:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public abstract void setEffectAnimateBackgroundShape(IEffect value)
```

Εφέ συνδεδεμένου σχήματος με ομάδα ή όχι (null) Ανάγνωση/εγγραφή [IEffect](../../com.aspose.slides/ieffect).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |