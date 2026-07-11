---
title: ILegend
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Αναπαριστά τις ιδιότητες της λεζάντας των γραφημάτων.
type: docs
url: /el/com.aspose.slides/ilegend/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface ILegend extends ILayoutable, IFormattedTextContainer, IActualLayout
```

Αναπαριστά τις ιδιότητες της λεζάντας του γραφήματος.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getOverlay()](#getOverlay--) | Καθορίζει εάν άλλα στοιχεία γραφήματος επιτρέπεται να επικαλύπτουν τη λεζάντα. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Καθορίζει εάν άλλα στοιχεία γραφήματος επιτρέπεται να επικαλύπτουν τη λεζάντα. |
| [getPosition()](#getPosition--) | Καθορίζει τη θέση της λεζάντας σε ένα γράφημα. |
| [setPosition(int value)](#setPosition-int-) | Καθορίζει τη θέση της λεζάντας σε ένα γράφημα. |
| [getFormat()](#getFormat--) | Επιστρέφει τη μορφή μιας λεζάντας. |
| [getEntries()](#getEntries--) | Λαμβάνει τις καταχωρήσεις της λεζάντας. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```

Καθορίζει εάν άλλα στοιχεία γραφήματος επιτρέπεται να επικαλύπτουν τη λεζάντα. Ανάγνωση/Εγγραφή boolean.

**Επιστρέφει:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```

Καθορίζει εάν άλλα στοιχεία γραφήματος επιτρέπεται να επικαλύπτουν τη λεζάντα. Ανάγνωση/Εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Καθορίζει τη θέση της λεζάντας σε ένα γράφημα. Οι τιμές Non-NaN των ιδιοτήτων X, Y, Width, Heigt παρακάμπτουν το αποτέλεσμα αυτής της ιδιότητας. Ανάγνωση/Εγγραφή [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Επιστρέφει:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Καθορίζει τη θέση της λεζάντας σε ένα γράφημα. Οι τιμές Non-NaN των ιδιοτήτων X, Y, Width, Heigt παρακάμπτουν το αποτέλεσμα αυτής της ιδιότητας. Ανάγνωση/Εγγραφή [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Επιστρέφει τη μορφή μιας λεζάντας. Μόνο για ανάγνωση [IFormat](../../com.aspose.slides/iformat).

**Επιστρέφει:**
[IFormat](../../com.aspose.slides/iformat)
### getEntries() {#getEntries--}
```
public abstract ILegendEntryCollection getEntries()
```

Λαμβάνει τις καταχωρήσεις της λεζάντας. Μόνο για ανάγνωση [ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection).

**Επιστρέφει:**
[ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)