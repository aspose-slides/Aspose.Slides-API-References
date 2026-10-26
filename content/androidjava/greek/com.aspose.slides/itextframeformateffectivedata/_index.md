---
title: ITextFrameFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Αμετάβλητο αντικείμενο που περιέχει τις ενεργές ιδιότητες μορφοποίησης πλαισίου κειμένου.
type: docs
url: /el/com.aspose.slides/itextframeformateffectivedata/
---```
public interface ITextFrameFormatEffectiveData
```

Αμετάβλητο αντικείμενο που περιέχει τις ενεργές ιδιότητες μορφοποίησης πλαισίου κειμένου.

--------------------

Αυτή η διεπαφή χρησιμοποιείται μαζί με τη διεπαφή [ITextFrameFormat](../../com.aspose.slides/itextframeformat) για την επιστροφή ενεργών τιμών μορφοποίησης με εφαρμοσμένη κληρονομικότητα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | Επιστρέφει το ενεργό στυλ του κειμένου. |
| [getMarginLeft()](#getMarginLeft--) | Επιστρέφει το αριστερό περιθώριο (points) σε ένα TextFrame. |
| [getMarginRight()](#getMarginRight--) | Επιστρέφει το δεξί περιθώριο (points) σε ένα TextFrame. |
| [getMarginTop()](#getMarginTop--) | Επιστρέφει το άνω περιθώριο (points) σε ένα TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Επιστρέφει το κάτω περιθώριο (points) σε ένα TextFrame. |
| [getWrapText()](#getWrapText--) | Επιστρέφει εάν το κείμενο είναι τυλιγμένο στα περιθώρια του TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | Επιστρέφει το κατακόρυφο άγκυρο κείμενο σε ένα TextFrame. |
| [getCenterText()](#getCenterText--) | Επιστρέφει εάν το κείμενο πρέπει να κεντραριστεί οριζόντια στο πλαίσιο. |
| [getTextVerticalType()](#getTextVerticalType--) | Επιστρέφει τον προσανατολισμό του κειμένου. |
| [getAutofitType()](#getAutofitType--) | Επιστρέφει τη λειτουργία αυτόματης προσαρμογής κειμένου. |
| [getColumnCount()](#getColumnCount--) | Καθορίζει τον αριθμό των στηλών κειμένου στο περιοριστικό ορθογώνιο. |
| [getColumnSpacing()](#getColumnSpacing--) | Καθορίζει το διάστημα μεταξύ των στηλών κειμένου στην περιοχή κειμένου (in points). |
### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyleEffectiveData getTextStyle()
```

Επιστρέφει το ενεργό στυλ του κειμένου. Μόνο για ανάγνωση [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).

**Επιστρέφει:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Επιστρέφει το αριστερό περιθώριο (points) σε ένα TextFrame. Μόνο για ανάγνωση double.

**Επιστρέφει:**
double
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Επιστρέφει το δεξί περιθώριο (points) σε ένα TextFrame. Μόνο για ανάγνωση double.

**Επιστρέφει:**
double
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Επιστρέφει το άνω περιθώριο (points) σε ένα TextFrame. Μόνο για ανάγνωση double.

**Επιστρέφει:**
double
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Επιστρέφει το κάτω περιθώριο (points) σε ένα TextFrame. Μόνο για ανάγνωση double.

**Επιστρέφει:**
double
### getWrapText() {#getWrapText--}
```
public abstract boolean getWrapText()
```

Επιστρέφει εάν το κείμενο είναι τυλιγμένο στα περιθώρια του TextFrame. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Επιστρέφει το κατακόρυφο άγκυρο κείμενο σε ένα TextFrame. Μόνο για ανάγνωση [TextAnchorType](../../com.aspose.slides/textanchortype).

**Επιστρέφει:**
byte
### getCenterText() {#getCenterText--}
```
public abstract boolean getCenterText()
```

Επιστρέφει εάν το κείμενο πρέπει να κεντραριστεί οριζόντια στο πλαίσιο. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Επιστρέφει τον προσανατολισμό του κειμένου. Μόνο για ανάγνωση [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Επιστρέφει:**
byte
### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

Επιστρέφει τη λειτουργία αυτόματης προσαρμογής κειμένου. Μόνο για ανάγνωση [TextAutofitType](../../com.aspose.slides/textautofittype).

**Επιστρέφει:**
byte
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

Καθορίζει τον αριθμό των στηλών κειμένου στο περιοριστικό ορθογώνιο. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### getColumnSpacing() {#getColumnSpacing--}
```
public abstract float getColumnSpacing()
```

Καθορίζει το διάστημα μεταξύ των στηλών κειμένου στην περιοχή κειμένου (in points). Μόνο για ανάγνωση float.

**Επιστρέφει:**
float