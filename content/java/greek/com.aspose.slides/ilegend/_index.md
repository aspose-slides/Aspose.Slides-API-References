---
title: ILegend
second_title: Αναφορά API Aspose.Slides για Java
description: Αναπαριστά τις ιδιότητες του υπομνήματος των διαγραμμάτων.
type: docs
url: /el/com.aspose.slides/ilegend/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface ILegend extends ILayoutable, IFormattedTextContainer, IActualLayout
```

Αντιπροσωπεύει τις ιδιότητες του υπομνήματος του διαγράμματος.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getOverlay()](#getOverlay--) | Καθορίζει εάν άλλα στοιχεία διαγράμματος επιτρέπεται να επικαλύπτονται με το υπόμνημα. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Καθορίζει εάν άλλα στοιχεία διαγράμματος επιτρέπεται να επικαλύπτονται με το υπόμνημα. |
| [getPosition()](#getPosition--) | Προσδιορίζει τη θέση του υπομνήματος σε ένα διάγραμμα. |
| [setPosition(int value)](#setPosition-int-) | Προσδιορίζει τη θέση του υπομνήματος σε ένα διάγραμμα. |
| [getFormat()](#getFormat--) | Επιστρέφει τη μορφή ενός υπομνήματος. |
| [getEntries()](#getEntries--) | Αποκτά τις καταχωρίσεις του υπομνήματος. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```

Καθορίζει εάν άλλα στοιχεία διαγράμματος επιτρέπεται να επικαλύπτονται με το υπόμνημα. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```

Καθορίζει εάν άλλα στοιχεία διαγράμματος επιτρέπεται να επικαλύπτονται με το υπόμνημα. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Προσδιορίζει τη θέση του υπομνήματος σε ένα διάγραμμα. Οι μη-NaN τιμές των ιδιοτήτων X, Y, Width, Heigt παρακάμπτουν το αποτέλεσμα αυτής της ιδιότητας. Ανάγνωση/εγγραφή [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Επιστρέφει:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Προσδιορίζει τη θέση του υπομνήματος σε ένα διάγραμμα. Οι μη-NaN τιμές των ιδιοτήτων X, Y, Width, Heigt παρακάμπτουν το αποτέλεσμα αυτής της ιδιότητας. Ανάγνωση/εγγραφή [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Επιστρέφει τη μορφή ενός υπομνήματος. Μόνο για ανάγνωση [IFormat](../../com.aspose.slides/iformat).

**Επιστρέφει:**
[IFormat](../../com.aspose.slides/iformat)
### getEntries() {#getEntries--}
```
public abstract ILegendEntryCollection getEntries()
```

Αποκτά τις καταχωρίσεις του υπομνήματος. Μόνο για ανάγνωση [ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection).

**Επιστρέφει:**
[ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)