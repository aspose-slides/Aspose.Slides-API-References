---
title: Trendline
second_title: Aspose.Slides για την αναφορά API Java
description: Η κλάση αντιπροσωπεύει τη γραμμή τάσης της σειράς γραφήματος
type: docs
url: /el/com.aspose.slides/trendline/
---
**Κληρονομικότητα:**
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ITrendline](../../com.aspose.slides/itrendline)
```
public class Trendline extends DomObject<TrendlineCollection> implements ITrendline
```

Η κλάση αντιπροσωπεύει τη γραμμή τάσης της σειράς γραφήματος
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | Λαμβάνει ή ορίζει το όνομα της γραμμής τάσης. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | Λαμβάνει ή ορίζει το όνομα της γραμμής τάσης. |
| [getTrendlineType()](#getTrendlineType--) | Λαμβάνει ή ορίζει τον τύπο της γραμμής τάσης. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | Λαμβάνει ή ορίζει τον τύπο της γραμμής τάσης. |
| [getFormat()](#getFormat--) | Αντιπροσωπεύει τη μορφή της γραμμής τάσης. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Αντιπροσωπεύει τη μορφή της γραμμής τάσης. |
| [getBackward()](#getBackward--) | Καθορίζει τον αριθμό των κατηγοριών (ή μονάδων σε διάγραμμα διασποράς) που η γραμμή τάσης εκτείνεται πριν από τα δεδομένα για τη σειρά που τείνεται. |
| [setBackward(double value)](#setBackward-double-) | Καθορίζει τον αριθμό των κατηγοριών (ή μονάδων σε διάγραμμα διασποράς) που η γραμμή τάσης εκτείνεται πριν από τα δεδομένα για τη σειρά που τείνεται. |
| [getForward()](#getForward--) | Καθορίζει τον αριθμό των κατηγοριών (ή μονάδων σε διάγραμμα διασποράς) που η γραμμή τάσης εκτείνεται μετά τα δεδομένα για τη σειρά που τείνεται. |
| [setForward(double value)](#setForward-double-) | Καθορίζει τον αριθμό των κατηγοριών (ή μονάδων σε διάγραμμα διασποράς) που η γραμμή τάσης εκτείνεται μετά τα δεδομένα για τη σειρά που τείνεται. |
| [getIntercept()](#getIntercept--) | Καθορίζει την τιμή όπου η γραμμή τάσης θα διασχίσει τον άξονα y. |
| [setIntercept(double value)](#setIntercept-double-) | Καθορίζει την τιμή όπου η γραμμή τάσης θα διασχίσει τον άξονα y. |
| [getDisplayEquation()](#getDisplayEquation--) | Καθορίζει ότι η εξίσωση της γραμμής τάσης εμφανίζεται στο διάγραμμα (στο ίδιο ετικέτα με την τιμή Rsquaredvalue). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | Καθορίζει ότι η εξίσωση της γραμμής τάσης εμφανίζεται στο διάγραμμα (στο ίδιο ετικέτα με την τιμή Rsquaredvalue). |
| [getOrder()](#getOrder--) | Καθορίζει τη σειρά της πολυωνυμικής γραμμής τάσης. |
| [setOrder(byte value)](#setOrder-byte-) | Καθορίζει τη σειρά της πολυωνυμικής γραμμής τάσης. |
| [getPeriod()](#getPeriod--) | Καθορίζει την περίοδο της γραμμής τάσης για μια γραμμή τάσης κινητού μέσου. |
| [setPeriod(byte value)](#setPeriod-byte-) | Καθορίζει την περίοδο της γραμμής τάσης για μια γραμμή τάσης κινητού μέσου. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | Καθορίζει ότι η τιμή R-squared της γραμμής τάσης εμφανίζεται στο διάγραμμα (στο ίδιο ετικέτα με την εξίσωση). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | Καθορίζει ότι η τιμή R-squared της γραμμής τάσης εμφανίζεται στο διάγραμμα (στο ίδιο ετικέτα με την εξίσωση). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Αντιπροσωπεύει την καταχώρηση υπόμνησης που σχετίζεται με αυτή τη γραμμή τάσης Μόνο για ανάγνωση [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Αρχικοποιεί το TextFrameForOverriding με το κείμενο στην παράμετρο "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Μπορεί να περιέχει κείμενο πλούσιας μορφοποίησης. |
| [getTextFormat()](#getTextFormat--) | Επιστρέφει τη μορφή κειμένου. |
| [getChart()](#getChart--) | Επιστρέφει το γονιό διάγραμμα. |
| [getSlide()](#getSlide--) | Επιστρέφει τη γονική διαφάνεια ενός FillFormat. |
| [getPresentation()](#getPresentation--) | Επιστρέφει την γονική παρουσίαση ενός FillFormat. |
### getTrendlineName() {#getTrendlineName--}
```
public final String getTrendlineName()
```

Λαμβάνει ή ορίζει το όνομα της γραμμής τάσης. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public final void setTrendlineName(String value)
```

Λαμβάνει ή ορίζει το όνομα της γραμμής τάσης. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |
### getTrendlineType() {#getTrendlineType--}
```
public final int getTrendlineType()
```

Λαμβάνει ή ορίζει τον τύπο της γραμμής τάσης. Ανάγνωση/εγγραφή [TrendlineType](../../com.aspose.slides/trendlinetype).

**Επιστρέφει:**
int
### setTrendlineType(int value) {#setTrendlineType-int-}
```
public final void setTrendlineType(int value)
```

Λαμβάνει ή ορίζει τον τύπο της γραμμής τάσης. Ανάγνωση/εγγραφή [TrendlineType](../../com.aspose.slides/trendlinetype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Αντιπροσωπεύει τη μορφή της γραμμής τάσης. Ανάγνωση/εγγραφή [IFormat](../../com.aspose.slides/iformat).

**Επιστρέφει:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Αντιπροσωπεύει τη μορφή της γραμμής τάσης. Ανάγνωση/εγγραφή [IFormat](../../com.aspose.slides/iformat).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getBackward() {#getBackward--}
```
public final double getBackward()
```

Καθορίζει τον αριθμό των κατηγοριών (ή μονάδων σε διάγραμμα διασποράς) που η γραμμή τάσης εκτείνεται πριν από τα δεδομένα για τη σειρά που τείνεται. Σε διαγράμματα διασποράς και μη-διασποράς, η τιμή πρέπει να είναι μη-αρνητική. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setBackward(double value) {#setBackward-double-}
```
public final void setBackward(double value)
```

Καθορίζει τον αριθμό των κατηγοριών (ή μονάδων σε διάγραμμα διασποράς) που η γραμμή τάσης εκτείνεται πριν από τα δεδομένα για τη σειρά που τείνεται. Σε διαγράμματα διασποράς και μη-διασποράς, η τιμή πρέπει να είναι μη-αρνητική. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |
### getForward() {#getForward--}
```
public final double getForward()
```

Καθορίζει τον αριθμό των κατηγοριών (ή μονάδων σε διάγραμμα διασποράς) που η γραμμή τάσης εκτείνεται μετά τα δεδομένα για τη σειρά που τείνεται. Σε διαγράμματα διασποράς και μη-διασποράς, η τιμή πρέπει να είναι μη-αρνητική. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setForward(double value) {#setForward-double-}
```
public final void setForward(double value)
```

Καθορίζει τον αριθμό των κατηγοριών (ή μονάδων σε διάγραμμα διασποράς) που η γραμμή τάσης εκτείνεται μετά τα δεδομένα για τη σειρά που τείνεται. Σε διαγράμματα διασποράς και μη-διασποράς, η τιμή πρέπει να είναι μη-αρνητική. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |
### getIntercept() {#getIntercept--}
```
public final double getIntercept()
```

Καθορίζει την τιμή όπου η γραμμή τάσης θα διασχίσει τον άξονα y. Αυτή η ιδιότητα υποστηρίζεται μόνο όταν ο τύπος γραμμής τάσης είναι exp, linear ή poly. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setIntercept(double value) {#setIntercept-double-}
```
public final void setIntercept(double value)
```

Καθορίζει την τιμή όπου η γραμμή τάσης θα διασχίσει τον άξονα y. Αυτή η ιδιότητα υποστηρίζεται μόνο όταν ο τύπος γραμμής τάσης είναι exp, linear ή poly. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |
### getDisplayEquation() {#getDisplayEquation--}
```
public final boolean getDisplayEquation()
```

Καθορίζει ότι η εξίσωση της γραμμής τάσης εμφανίζεται στο διάγραμμα (στο ίδιο ετικέτα με την τιμή Rsquaredvalue). Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public final void setDisplayEquation(boolean value)
```

Καθορίζει ότι η εξίσωση της γραμμής τάσης εμφανίζεται στο διάγραμμα (στο ίδιο ετικέτα με την τιμή Rsquaredvalue). Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getOrder() {#getOrder--}
```
public final byte getOrder()
```

Καθορίζει τη σειρά της πολυωνυμικής γραμμής τάσης. Αγνοείται για άλλους τύπους γραμμής τάσης. Η τιμή πρέπει να είναι μεταξύ 2 και 6. Ανάγνωση/εγγραφή byte.

**Επιστρέφει:**
byte
### setOrder(byte value) {#setOrder-byte-}
```
public final void setOrder(byte value)
```

Καθορίζει τη σειρά της πολυωνυμικής γραμμής τάσης. Αγνοείται για άλλους τύπους γραμμής τάσης. Η τιμή πρέπει να είναι μεταξύ 2 και 6. Ανάγνωση/εγγραφή byte.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |
### getPeriod() {#getPeriod--}
```
public final byte getPeriod()
```

Καθορίζει την περίοδο της γραμμής τάσης για μια γραμμή τάσης κινητού μέσου. Αγνοείται για άλλες παραλλαγές γραμμής τάσης. Η τιμή πρέπει να είναι μεταξύ 2 και 255. Ανάγνωση/εγγραφή byte.

**Επιστρέφει:**
byte
### setPeriod(byte value) {#setPeriod-byte-}
```
public final void setPeriod(byte value)
```

Καθορίζει την περίοδο της γραμμής τάσης για μια γραμμή τάσης κινητού μέσου. Αγνοείται για άλλες παραλλαγές γραμμής τάσης. Η τιμή πρέπει να είναι μεταξύ 2 και 255. Ανάγνωση/εγγραφή byte.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |
### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public final boolean getDisplayRSquaredValue()
```

Καθορίζει ότι η τιμή R-squared της γραμμής τάσης εμφανίζεται στο διάγραμμα (στο ίδιο ετικέτα με την εξίσωση). Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public final void setDisplayRSquaredValue(boolean value)
```

Καθορίζει ότι η τιμή R-squared της γραμμής τάσης εμφανίζεται στο διάγραμμα (στο ίδιο ετικέτα με την εξίσωση). Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Αντιπροσωπεύει την καταχώρηση υπόμνησης που σχετίζεται με αυτή τη γραμμή τάσης Μόνο για ανάγνωση [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Επιστρέφει:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

Αρχικοποιεί το TextFrameForOverriding με το κείμενο στην παράμετρο "text". Εάν το TextFrameForOverriding είναι ήδη αρχικοποιημένο, τότε απλώς αλλάζει το κείμενό του.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο για ένα νέο TextFrameForOverriding. |

**Επιστρέφει:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

Μπορεί να περιέχει κείμενο πλούσιας μορφοποίησης. Εάν αυτή η ιδιότητα δεν είναι null, τότε αυτή η μορφοποιημένη τιμή κειμένου παρακάμπτει το αυτόματα παραγόμενο κείμενο της ετικέτας δεδομένων. Το αυτόματα παραγόμενο κείμενο της ετικέτας δεδομένων σημαίνει το κείμενο που διαχειρίζεται από τις ιδιότητες ShowSeriesName, ShowValue, ... και μορφοποιείται με την ιδιότητα TextFormatManager.TextFormat. Μόνο για ανάγνωση [ITextFrame](../../com.aspose.slides/itextframe).

**Επιστρέφει:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Επιστρέφει τη μορφή κειμένου. Μόνο για ανάγνωση [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Επιστρέφει:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getChart() {#getChart--}
```
public final IChart getChart()
```

Επιστρέφει το γονικό διάγραμμα. Μόνο για ανάγνωση [IChart](../../com.aspose.slides/ichart).

**Επιστρέφει:**
[IChart](../../com.aspose.slides/ichart)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Επιστρέφει τη γονική διαφάνεια ενός FillFormat. Μόνο για ανάγνωση [BaseSlide](../../com.aspose.slides/baseslide).

**Επιστρέφει:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Επιστρέφει την γονική παρουσίαση ενός FillFormat. Μόνο για ανάγνωση [IPresentation](../../com.aspose.slides/ipresentation).

**Επιστρέφει:**
[IPresentation](../../com.aspose.slides/ipresentation)