---
title: Sequence
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αναπαριστά τη συλλογή ακολουθίας εφέ.
type: docs
url: /el/com.aspose.slides/sequence/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ISequence](../../com.aspose.slides/isequence)
```
public final class Sequence implements ISequence
```

Αναπαριστά ακολουθία (συλλογή εφέ).
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getCount()](#getCount--) | Επιστρέφει τον αριθμό των εφέ σε μια ακολουθία. |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | Αφαιρεί το καθορισμένο εφέ από μια συλλογή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί ένα εφέ από μια συλλογή. |
| [clear()](#clear--) | Αφαιρεί όλα τα εφέ από μια συλλογή. |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει ένα εφέ στο καθορισμένο δείκτη. |
| [iterator()](#iterator--) | Επιστρέφει έναν enumerator που διατρέχει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
| [getTriggerShape()](#getTriggerShape--) | Επιστρέφει ή ορίζει το στόχο σχήματος για INTERACTIVE ακολουθία. |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | Επιστρέφει ή ορίζει το στόχο σχήματος για INTERACTIVE ακολουθία. |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | Αφαιρεί εφέ για το καθορισμένο σχήμα. |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | Επιστρέφει πίνακα εφέ για το καθορισμένο σχήμα. |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | Επιστρέφει πίνακα εφέ για την καθορισμένη παράγραφο. |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | Επιστρέφει τον αριθμό των εφέ για το καθορισμένο σχήμα. |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | Προσθέτει νέο εφέ στο τέλος της ακολουθίας. |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | Προσθέτει νέο εφέ κίνησης για παράγραφο στο τέλος της ακολουθίας. |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | Προσθέτει το νέο εφέ κίνησης διαγράμματος για την κατηγορία ή τη σειρά στο τέλος της ακολουθίας. |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | Προσθέτει το νέο εφέ κίνησης διαγράμματος για στοιχεία στην κατηγορία ή τη σειρά στο τέλος της ακολουθίας. |

### getCount() {#getCount--}
```
public final int getCount()
```

Επιστρέφει τον αριθμό των εφέ σε μια ακολουθία. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public final void remove(IEffect item)
```

Αφαιρεί το καθορισμένο εφέ από μια συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | Εφέ προς αφαίρεση. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Αφαιρεί ένα εφέ από μια συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης του εφέ που πρέπει να διαγραφεί. |

### clear() {#clear--}
```
public final void clear()
```

Αφαιρεί όλα τα εφέ από μια συλλογή.

### get_Item(int index) {#get-Item-int-}
```
public final IEffect get_Item(int index)
```

Επιστρέφει ένα εφέ στο καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης του στοιχείου. |

**Επιστρέφει:**
[IEffect](../../com.aspose.slides/ieffect) - Το [IEffect](../../com.aspose.slides/ieffect) αντικείμενο.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iterator()
```

Επιστρέφει έναν enumerator που διατρέχει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - Ένα IGenericEnumerator που μπορεί να χρησιμοποιηθεί για την διαπέραση της συλλογής.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iteratorJava()
```

Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - Ένα java.util.Iterator για ολόκληρη τη συλλογή.
### getTriggerShape() {#getTriggerShape--}
```
public final IShape getTriggerShape()
```

Επιστρέφει ή ορίζει το στόχο σχήματος για INTERACTIVE ακολουθία. Εάν η ακολουθία δεν είναι αλληλεπιδραστική, τότε επιστρέφει null. Ανάγνωση/Εγγραφή [IShape](../../com.aspose.slides/ishape).

**Επιστρέφει:**
[IShape](../../com.aspose.slides/ishape)
### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public final void setTriggerShape(IShape value)
```

Επιστρέφει ή ορίζει το στόχο σχήματος για INTERACTIVE ακολουθία. Εάν η ακολουθία δεν είναι αλληλεπιδραστική, τότε επιστρέφει null. Ανάγνωση/Εγγραφή [IShape](../../com.aspose.slides/ishape).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public final void removeByShape(IShape shape)
```

Αφαιρεί εφέ για το καθορισμένο σχήμα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public final IEffect[] getEffectsByShape(IShape shape)
```

Επιστρέφει πίνακα εφέ για το καθορισμένο σχήμα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**Επιστρέφει:**
com.aspose.slides.IEffect[]
### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public final IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

Επιστρέφει πίνακα εφέ για την καθορισμένη παράγραφο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) |  |

**Επιστρέφει:**
com.aspose.slides.IEffect[]
### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public final int getCount(IShape shape)
```

Επιστρέφει τον αριθμό των εφέ για το καθορισμένο σχήμα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**Επιστρέφει:**
int
### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public final IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

Προσθέτει νέο εφέ στο τέλος της ακολουθίας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Αντικείμενο Shape [IShape](../../com.aspose.slides/ishape) για την προσθήκη εφέ |
| effectType | int | Τύπος εφέ κίνησης [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Υποτύποι εφέ κίνησης [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Τύπος ενεργοποίησης εφέ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Επιστρέφει:**
[IEffect](../../com.aspose.slides/ieffect) - Νέο αντικείμενο εφέ [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public final IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

Προσθέτει νέο εφέ κίνησης για παράγραφο στο τέλος της ακολουθίας.

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>   try
>   {        
>      // επιλέξτε παράγραφο για προσθήκη εφέ
>      IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>      // προσθέστε το εφέ κίνησης Fly στην επιλεγμένη παράγραφο
>      IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>      paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>   }  finally {
>      if (presentation != null) presentation.dispose();
>   }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Αντικείμενο Paragraph [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | Τύπος εφέ κίνησης [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Υποτύποι εφέ κίνησης [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Τύπος ενεργοποίησης εφέ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Επιστρέφει:**
[IEffect](../../com.aspose.slides/ieffect) - Νέο αντικείμενο εφέ [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

Προσθέτει το νέο εφέ κίνησης διαγράμματος για την κατηγορία ή τη σειρά στο τέλος της ακολουθίας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Αντικείμενο Chart [IChart](../../com.aspose.slides/ichart) |
| type | int | Τύπος εφέ κίνησης [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | Δείκτης int |
| effectType | int | Τύπος εφέ κίνησης [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Υποτύποι εφέ κίνησης [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Τύπος ενεργοποίησης εφέ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Επιστρέφει:**
[IEffect](../../com.aspose.slides/ieffect) - Νέο αντικείμενο εφέ [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```

Προσθέτει το νέο εφέ κίνησης διαγράμματος για στοιχεία στην κατηγορία ή τη σειρά στο τέλος της ακολουθίας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Αντικείμενο Chart [IChart](../../com.aspose.slides/ichart) |
| type | int | Τύπος εφέ κίνησης [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | Δείκτης σειράς διαγράμματος int |
| categoriesIndex | int | Δείκτης κατηγορίας int |
| effectType | int | Τύπος εφέ κίνησης [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Υποτύποι εφέ κίνησης [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Τύπος ενεργοποίησης εφέ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Επιστρέφει:**
[IEffect](../../com.aspose.slides/ieffect) - Νέο αντικείμενο εφέ [IEffect](../../com.aspose.slides/ieffect)