---
title: ITextFrameFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Αμετάβλητο αντικείμενο που περιέχει τις ιδιότητες διαμόρφωσης του αποτελεσματικού πλαισίου κειμένου.
type: docs
url: /el/com.aspose.slides/itextframeformateffectivedata/
---```
public interface ITextFrameFormatEffectiveData
```

Αμετάβλητο αντικείμενο που περιέχει τις ιδιότητες διαμόρφωσης του αποτελεσματικού πλαισίου κειμένου.

--------------------

Αυτή η διεπαφή χρησιμοποιείται μαζί με τη διεπαφή [ITextFrameFormat](../../com.aspose.slides/itextframeformat) για την επιστροφή των αποτελεσματικών τιμών διαμόρφωσης με την κληρονομικότητα που εφαρμόζεται.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | Επιστρέφει το στυλ του αποτελεσματικού κειμένου. |
| [getMarginLeft()](#getMarginLeft--) | Επιστρέφει το αριστερό περιθώριο (σημεία) σε ένα TextFrame. |
| [getMarginRight()](#getMarginRight--) | Επιστρέφει το δεξιό περιθώριο (σημεία) σε ένα TextFrame. |
| [getMarginTop()](#getMarginTop--) | Επιστρέφει το πάνω περιθώριο (σημεία) σε ένα TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Επιστρέφει το κάτω περιθώριο (σημεία) σε ένα TextFrame. |
| [getWrapText()](#getWrapText--) | Επιστρέφει αν το κείμενο τυλίγεται στα περιθώρια του TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | Επιστρέφει το κάθετο κείμενο αγκύρωσης σε ένα TextFrame. |
| [getCenterText()](#getCenterText--) | Επιστρέφει αν το κείμενο πρέπει να κεντραστεί οριζόντια στο πλαίσιο. |
| [getTextVerticalType()](#getTextVerticalType--) | Επιστρέφει προσανατολισμό κειμένου. |
| [getAutofitType()](#getAutofitType--) | Επιστρέφει τη λειτουργία αυτόματης προσαρμογής κειμένου. |
| [getColumnCount()](#getColumnCount--) | Καθορίζει τον αριθμό των στηλών κειμένου στο περιτυλιγμένο ορθογώνιο. |
| [getColumnSpacing()](#getColumnSpacing--) | Καθορίζει το διάστημα μεταξύ των στηλών κειμένου στην περιοχή κειμένου (σε σημεία). |

### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyleEffectiveData getTextStyle()
```

Επιστρέφει το στυλ του αποτελεσματικού κειμένου. Μόνο για ανάγνωση [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).

**Returns:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Επιστρέφει το αριστερό περιθώριο (σημεία) σε ένα TextFrame. Μόνο για ανάγνωση double.

**Returns:**
double

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Επιστρέφει το δεξιό περιθώριο (σημεία) σε ένα TextFrame. Μόνο για ανάγνωση double.

**Returns:**
double

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Επιστρέφει το πάνω περιθώριο (σημεία) σε ένα TextFrame. Μόνο για ανάγνωση double.

**Returns:**
double

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Επιστρέφει το κάτω περιθώριο (σημεία) σε ένα TextFrame. Μόνο για ανάγνωση double.

**Returns:**
double

### getWrapText() {#getWrapText--}
```
public abstract boolean getWrapText()
```

Επιστρέφει αν το κείμενο τυλίγεται στα περιθώρια του TextFrame. Μόνο για ανάγνωση boolean.

**Returns:**
boolean

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Επιστρέφει το κάθετο κείμενο αγκύρωσης σε ένα TextFrame. Μόνο για ανάγνωση [TextAnchorType](../../com.aspose.slides/textanchortype).

**Returns:**
byte

### getCenterText() {#getCenterText--}
```
public abstract boolean getCenterText()
```

Επιστρέφει αν το κείμενο πρέπει να κεντραστεί οριζόντια στο πλαίσιο. Μόνο για ανάγνωση boolean.

**Returns:**
boolean

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Επιστρέφει προσανατολισμό κειμένου. Μόνο για ανάγνωση [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Returns:**
byte

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

Επιστρέφει τη λειτουργία αυτόματης προσαρμογής κειμένου. Μόνο για ανάγνωση [TextAutofitType](../../com.aspose.slides/textautofittype).

**Returns:**
byte

### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

Καθορίζει τον αριθμό των στηλών κειμένου στο περιτυλιγμένο ορθογώνιο. Μόνο για ανάγνωση int.

**Returns:**
int

### getColumnSpacing() {#getColumnSpacing--}
```
public abstract float getColumnSpacing()
```

Καθορίζει το διάστημα μεταξύ των στηλών κειμένου στην περιοχή κειμένου (σε σημεία). Μόνο για ανάγνωση float.

**Returns:**
float