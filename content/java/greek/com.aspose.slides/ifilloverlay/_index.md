---
title: IFillOverlay
second_title: Aspose.Slides για την Αναφορά API της Java
description: Αντιπροσωπεύει ένα εφέ γεμίσματος επικάλυψης.
type: docs
url: /el/com.aspose.slides/ifilloverlay/
---
**Όλες οι Υλοποιημένες Διασυνδέσεις:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IFillOverlay extends IImageTransformOperation, IAccessiblePVIObject<IFillOverlayEffectiveData>
```

Αντιπροσωπεύει ένα εφέ γεμίσματος επικάλυψης. Μια επικάλυψη γεμίσματος μπορεί να χρησιμοποιηθεί για να καθορίσει ένα πρόσθετο γέμισμα για ένα αντικείμενο και να συνδυάσει τα δύο γέμισμα μαζί.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getFillFormat()](#getFillFormat--) | Μορφή γεμίσματος. |

### getBlend() {#getBlend--}
```
public abstract int getBlend()
```

FillBlendMode. Ανάγνωση/εγγραφή [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Επιστρέφει:**
int

### setBlend(int value) {#setBlend-int-}
```
public abstract void setBlend(int value)
```

FillBlendMode. Ανάγνωση/εγγραφή [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Μορφή γεμίσματος. Μόνο ανάγνωση [IFillFormat](../../com.aspose.slides/ifillformat).

**Επιστρέφει:**
[IFillFormat](../../com.aspose.slides/ifillformat)