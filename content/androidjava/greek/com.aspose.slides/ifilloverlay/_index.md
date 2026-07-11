---
title: IFillOverlay
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αντιπροσωπεύει ένα εφέ Επικάλυψης Γέμισης.
type: docs
url: /el/com.aspose.slides/ifilloverlay/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IFillOverlay extends IImageTransformOperation, IAccessiblePVIObject<IFillOverlayEffectiveData>
```

Αντιπροσωπεύει ένα εφέ Επικάλυψης Γέμισης. Μια επικάλυψη γέμισης μπορεί να χρησιμοποιηθεί για να προσδιορίσει μια πρόσθετη γέμιση για ένα αντικείμενο και να ενώσει τις δύο γεμίσεις μαζί.
## Μέθοδοι

| Method | Description |
| --- | --- |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getFillFormat()](#getFillFormat--) | Fill format. |
### getBlend() {#getBlend--}
```
public abstract int getBlend()
```


FillBlendMode. Ανάγνωση/εγγραφή [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Returns:**
int
### setBlend(int value) {#setBlend-int-}
```
public abstract void setBlend(int value)
```


FillBlendMode. Ανάγνωση/εγγραφή [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Fill format. Μόνο-ανάγνωση [IFillFormat](../../com.aspose.slides/ifillformat).

**Returns:**
[IFillFormat](../../com.aspose.slides/ifillformat)