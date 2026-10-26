---
title: ISequence
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Αναπαριστά τη συλλογή ακολουθίας εφέ.
type: docs
url: /el/com.aspose.slides/isequence/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequence extends System.Collections.Generic.IGenericEnumerable<IEffect>
```

Αναπαριστά τη σειρά (συλλογή εφέ).
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getCount()](#getCount--) | Επιστρέφει τον αριθμό των εφέ σε μια ακολουθία. |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | Αφαιρεί το καθορισμένο εφέ από μια συλλογή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί ένα εφέ από μια συλλογή. |
| [clear()](#clear--) | Αφαιρεί όλα τα εφέ από μια συλλογή. |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει ένα εφέ στο καθορισμένο δείκτη. |
| [getTriggerShape()](#getTriggerShape--) | Επιστρέφει ή ορίζει το στόχο σχήματος για την INTERACTIVE ακολουθία. |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | Επιστρέφει ή ορίζει το στόχο σχήματος για την INTERACTIVE ακολουθία. |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | Αφαιρεί το εφέ για το καθορισμένο σχήμα. |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | Επιστρέφει έναν πίνακα εφέ για το καθορισμένο σχήμα. |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | Επιστρέφει έναν πίνακα εφέ για την καθορισμένη παράγραφο. |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | Επιστρέφει τον αριθμό των εφέ για το καθορισμένο σχήμα. |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | Προσθέτει νέο εφέ στο τέλος της ακολουθίας. |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | Προσθέτει νέο εφέ κίνησης για παράγραφο στο τέλος της ακολουθίας. |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | Προσθέτει το νέο εφέ κίνησης γραφήματος για κατηγορία ή σειρά στο τέλος της ακολουθίας. |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | Προσθέτει το νέο εφέ κίνησης γραφήματος για στοιχεία σε κατηγορία ή σειρά στο τέλος της ακολουθίας. |

### getCount() {#getCount--}
```
public abstract int getCount()
```

Επιστρέφει τον αριθμό των εφέ σε μια ακολουθία. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int

### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public abstract void remove(IEffect item)
```

Αφαιρεί το καθορισμένο εφέ από μια συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | Εφέ προς αφαίρεση. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Αφαιρεί ένα εφέ από μια συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης του εφέ προς αφαίρεση int |

### clear() {#clear--}
```
public abstract void clear()
```

Αφαιρεί όλα τα εφέ από μια συλλογή.

### get_Item(int index) {#get-Item-int-}
```
public abstract IEffect get_Item(int index)
```

Επιστρέφει ένα εφέ στο καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης του στοιχείου. |

**Επιστρέφει:**
[IEffect](../../com.aspose.slides/ieffect) - Το αντικείμενο [IEffect](../../com.aspose.slides/ieffect).

### getTriggerShape() {#getTriggerShape--}
```
public abstract IShape getTriggerShape()
```

Επιστρέφει ή ορίζει το στόχο σχήματος για την INTERACTIVE ακολουθία. Αν η ακολουθία δεν είναι διαδραστική, επιστρέφει null. Ανάγνωση/εγγραφή [IShape](../../com.aspose.slides/ishape).

**Επιστρέφει:**
[IShape](../../com.aspose.slides/ishape)

### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public abstract void setTriggerShape(IShape value)
```

Επιστρέφει ή ορίζει το στόχο σχήματος για την INTERACTIVE ακολουθία. Αν η ακολουθία δεν είναι διαδραστική, επιστρέφει null. Ανάγνωση/εγγραφή [IShape](../../com.aspose.slides/ishape).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public abstract void removeByShape(IShape shape)
```

Αφαιρεί το εφέ για το καθορισμένο σχήμα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Αντικείμενο σχήματος [IShape](../../com.aspose.slides/ishape) |

### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public abstract IEffect[] getEffectsByShape(IShape shape)
```

Επιστρέφει έναν πίνακα εφέ για το καθορισμένο σχήμα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Αντικείμενο σχήματος [IShape](../../com.aspose.slides/ishape) |

**Επιστρέφει:**
com.aspose.slides.IEffect[] - Πίνακας εφέ [IEffect](../../com.aspose.slides/ieffect)

### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public abstract IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

Επιστρέφει έναν πίνακα εφέ για την καθορισμένη παράγραφο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Αντικείμενο παραγράφου [IParagraph](../../com.aspose.slides/iparagraph) |

**Επιστρέφει:**
com.aspose.slides.IEffect[] - Πίνακας εφέ [IEffect](../../com.aspose.slides/ieffect)

### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public abstract int getCount(IShape shape)
```

Επιστρέφει τον αριθμό των εφέ για το καθορισμένο σχήμα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Αντικείμενο σχήματος [IShape](../../com.aspose.slides/ishape) |

**Επιστρέφει:**
int - Αριθμός εφέ int

### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public abstract IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

Προσθέτει νέο εφέ στο τέλος της ακολουθίας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Αντικείμενο σχήματος [IShape](../../com.aspose.slides/ishape) για προσθήκη εφέ |
| effectType | int | Τύπος εφέ κίνησης [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Υποτύποι εφέ κίνησης [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Τύπος ενεργοποίησης εφέ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Επιστρέφει:**
[IEffect](../../com.aspose.slides/ieffect) - Νέο αντικείμενο εφέ [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public abstract IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

Προσθέτει νέο εφέ κίνησης για παράγραφο στο τέλος της ακολουθίας.

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>  try
>  {
>     // επιλέξτε την παράγραφο για προσθήκη εφέ
>     IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>     IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>     // προσθέστε το εφέ κίνησης Fly στην επιλεγμένη παράγραφο
>     IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>     paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>  } finally {
>     if (presentation != null) presentation.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Αντικείμενο παραγράφου [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | Τύπος εφέ κίνησης [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Υποτύποι εφέ κίνησης [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Τύπος ενεργοποίησης εφέ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Επιστρέφει:**
[IEffect](../../com.aspose.slides/ieffect) - Νέο αντικείμενο εφέ [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

Προσθέτει το νέο εφέ κίνησης γραφήματος για κατηγορία ή σειρά στο τέλος της ακολουθίας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Αντικείμενο γραφήματος [IChart](../../com.aspose.slides/ichart) |
| type | int | Τύπος εφέ κίνησης [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | Δείκτης int |
| effectType | int | Τύπος εφέ κίνησης [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Υποτύποι εφέ κίνησης [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Τύπος ενεργοποίησης εφέ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Επιστρέφει:**
[IEffect](../../com.aspose.slides/ieffect) - Νέο αντικείμενο εφέ [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```

Προσθέτει το νέο εφέ κίνησης γραφήματος για στοιχεία σε κατηγορία ή σειρά στο τέλος της ακολουθίας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Αντικείμενο γραφήματος [IChart](../../com.aspose.slides/ichart) |
| type | int | Τύπος εφέ κίνησης [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | Δείκτης ακολουθίας γραφήματος int |
| categoriesIndex | int | Δείκτης κατηγορίας int |
| effectType | int | Τύπος εφέ κίνησης [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Υποτύποι εφέ κίνησης [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Τύπος ενεργοποίησης εφέ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Επιστρέφει:**
[IEffect](../../com.aspose.slides/ieffect) - Νέο αντικείμενο εφέ [IEffect](../../com.aspose.slides/ieffect)