---
title: IAxis
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Περιβάλλει το αντικείμενο που αντιπροσωπεύει τον άξονα ενός διαγράμματος.
type: docs
url: /el/com.aspose.slides/iaxis/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IAxis extends IFormattedTextContainer
```

Περιβάλλει το αντικείμενο που αντιπροσωπεύει τον άξονα ενός διαγράμματος.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Αναπαριστά αν ο άξονας τιμών διασχίζει τον άξονα κατηγορίας μεταξύ των κατηγοριών. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Αναπαριστά αν ο άξονας τιμών διασχίζει τον άξονας κατηγορίας μεταξύ των κατηγοριών. |
| [getCrossAt()](#getCrossAt--) | Αναπαριστά το σημείο στον άξονα όπου ο κάθετος άξονας τον διασχίζει. |
| [setCrossAt(float value)](#setCrossAt-float-) | Αναπαριστά το σημείο στον άξονα όπου ο κάθετος άξονας τον διασχίζει. |
| [getDisplayUnit()](#getDisplayUnit--) | Καθορίζει την τιμή κλιμάκωσης των μονάδων εμφάνισης για τον άξονα τιμών. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Καθορίζει την τιμή κλιμάκωσης των μονάδων εμφάνισης για τον άξονα τιμών. |
| [getActualMaxValue()](#getActualMaxValue--) | Καθορίζει την πραγματική μέγιστη τιμή στον άξονα. |
| [getActualMinValue()](#getActualMinValue--) | Καθορίζει την πραγματική ελάχιστη τιμή στον άξονα. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Καθορίζει την πραγματική κύρια μονάδα του άξονα. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Καθορίζει την πραγματική δευτερεύουσα μονάδα του άξονα. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Καθορίζει την πραγματική κλίμακα κύριας μονάδας του άξονα. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Καθορίζει την πραγματική κλίμακα δευτερεύουσας μονάδας του άξονα. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Υποδεικνύει εάν η μέγιστη τιμή ορίζεται αυτόματα. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Υποδεικνύει εάν η μέγιστη τιμή ορίζεται αυτόματα. |
| [getMaxValue()](#getMaxValue--) | Αναπαριστά τη μέγιστη τιμή στον άξονα τιμών. |
| [setMaxValue(double value)](#setMaxValue-double-) | Αναπαριστά τη μέγιστη τιμή στον άξονα τιμών. |
| [getMinorUnit()](#getMinorUnit--) | Αναπαριστά τις δευτερεύουσες μονάδες για τον άξονα ημερομηνίας ή τιμής. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Αναπαριστά τις δευτερεύουσες μονάδες για τον άξονα ημερομηνίας ή τιμής. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Υποδεικνύει εάν η δευτερεύουσα μονάδα του άξονα ορίζεται αυτόματα. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Υποδεικνύει εάν η δευτερεύουσα μονάδα του άξονα ορίζεται αυτόματα. |
| [getMajorUnit()](#getMajorUnit--) | Αναπαριστά τις κύριες μονάδες για τον άξονα ημερομηνίας ή τιμής. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Αναπαριστά τις κύριες μονάδες για τον άξονα ημερομηνίας ή τιμής. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Υποδεικνύει εάν η κύρια μονάδα του άξονα ορίζεται αυτόματα. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Υποδεικνύει εάν η κύρια μονάδα του άξονα ορίζεται αυτόματα. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Υποδεικνύει εάν η ελάχιστη τιμή ορίζεται αυτόματα. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Υποδεικνύει εάν η ελάχιστη τιμή ορίζεται αυτόματα. |
| [getMinValue()](#getMinValue--) | Αναπαριστά την ελάχιστη τιμή στον άξονα τιμών. |
| [setMinValue(double value)](#setMinValue-double-) | Αναπαριστά την ελάχιστη τιμή στον άξονα τιμών. |
| [isLogarithmic()](#isLogarithmic--) | Αναπαριστά εάν ο τύπος κλίμακας του άξονα τιμών είναι λογαριθμικός ή όχι. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Αναπαριστά εάν ο τύπος κλίμακας του άξονα τιμών είναι λογαριθμικός ή όχι. |
| [getLogBase()](#getLogBase--) | Αναπαριστά τη λογαριθμική βάση. |
| [setLogBase(double value)](#setLogBase-double-) | Αναπαριστά τη λογαριθμική βάση. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Αναπαριστά εάν το MS PowerPoint σχεδιάζει τα σημεία δεδομένων από το τέλος προς την αρχή. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Αναπαριστά εάν το MS PowerPoint σχεδιάζει τα σημεία δεδομένων από το τέλος προς την αρχή. |
| [isVisible()](#isVisible--) | Αναπαριστά εάν ο άξονας είναι ορατός. |
| [setVisible(boolean value)](#setVisible-boolean-) | Αναπαριστά εάν ο άξονας είναι ορατός. |
| [getMajorTickMark()](#getMajorTickMark--) | Αναπαριστά τον τύπο της κύριας σημαδούρας για τον συγκεκριμένο άξονα. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Αναπαριστά τον τύπο της κύριας σημαδούρας για τον συγκεκριμένο άξονα. |
| [getMinorTickMark()](#getMinorTickMark--) | Αναπαριστά τον τύπο της δευτερεύουσας σημαδούρας για τον συγκεκριμένο άξονα. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Αναπαριστά τον τύπο της δευτερεύουσας σημαδούρας για τον συγκεκριμένο άξονα. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Αναπαριστά τη θέση των ετικετών των σημαδιών στον συγκεκριμένο άξονα. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Αναπαριστά τη θέση των ετικετών των σημαδιών στον συγκεκριμένο άξονα. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Αναπαριστά την κλίμακα κύριας μονάδας για τον άξονα ημερομηνίας. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Αναπαριστά την κλίμακα κύριας μονάδας για τον άξονα ημερομηνίας. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Αναπαριστά την κλίμακα κύριας μονάδας για τον άξονα ημερομηνίας. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Αναπαριστά την κλίμακα κύριας μονάδας για τον άξονα ημερομηνίας. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Καθορίζει τη μικρότερη μονάδα χρόνου που εμφανίζεται στον άξονα ημερομηνίας. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Καθορίζει τη μικρότερη μονάδα χρόνου που εμφανίζεται στον άξονα ημερομηνίας. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Αναπαριστά τη μορφή των δευτερευουσών γραμμών πλέγματος σε άξονα διαγράμματος. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Αναπαριστά τη μορφή των κύριων γραμμών πλέγματος σε άξονα διαγράμματος. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Αναπαριστά εάν οι δευτερεύουσες γραμμές πλέγματος εμφανίζονται. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Αναπαριστά εάν οι κύριες γραμμές πλέγματος εμφανίζονται. |
| [getFormat()](#getFormat--) | Αναπαριστά τη μορφή του άξονα. |
| [getTitle()](#getTitle--) | Λαμβάνει τον τίτλο του άξονα. |
| [getCrossType()](#getCrossType--) | Αναπαριστά το CrossType στον καθορισμένο άξονα όπου διασχίζει ο άλλος άξονας. |
| [setCrossType(int value)](#setCrossType-int-) | Αναπαριστά το CrossType στον καθορισμένο άξονα όπου διασχίζει ο άλλος άξονας. |
| [getPosition()](#getPosition--) | Αναπαριστά τη θέση του άξονα. |
| [setPosition(int value)](#setPosition-int-) | Αναπαριστά τη θέση του άξονα. |
| [hasTitle()](#hasTitle--) | Καθορίζει εάν ο άξονας έχει ορατό τίτλο. |
| [setTitle(boolean value)](#setTitle-boolean-) | Καθορίζει εάν ο άξονας έχει ορατό τίτλο. |
| [getNumberFormat()](#getNumberFormat--) | Αναπαριστά το συμβολοσειρά μορφής για τις ετικέτες του άξονα. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Αναπαριστά το συμβολοσειρά μορφής για τις ετικέτες του άξονα. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Υποδεικνύει εάν η μορφή είναι συνδεδεμένη με τα δεδομένα προέλευσης. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Υποδεικνύει εάν η μορφή είναι συνδεδεμένη με τα δεδομένα προέλευσης. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Αναπαριστά τη γωνία περιστροφής των ετικετών των σημαδιών. Ανάγνωση/εγγραφή float. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Αναπαριστά τη γωνία περιστροφής των ετικετών των σημαδιών. Ανάγνωση/εγγραφή float. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Καθορίζει πόσες ετικέτες σημαδιών παραλείπονται μεταξύ των σημειώσεων που σχεδιάζονται. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Καθορίζει πόσες ετικέτες σημαδιών παραλείπονται μεταξύ των σημειώσεων που σχεδιάζονται. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Καθορίζει την αυτόματη τιμή απόστασης ετικετών σημαδιών. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Καθορίζει την αυτόματη τιμή απόστασης ετικετών σημαδιών. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Καθορίζει πόσες σημαδούρες πρέπει να παραλειφθούν πριν σχεδιαστεί η επόμενη. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Καθορίζει πόσες σημαδούρες πρέπει να παραλειφθούν πριν σχεδιαστεί η επόμενη. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Καθορίζει την τιμή αυτόματης απόστασης σημαδιών. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Καθορίζει την τιμή αυτόματης απόστασης σημαδιών. |
| [getLabelOffset()](#getLabelOffset--) | Καθορίζει την απόσταση των ετικετών από τον άξονα. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Καθορίζει την απόσταση των ετικετών από τον άξονα. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Καθορίζει τον τύπο του άξονα κατηγορίας. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Καθορίζει τον τύπο του άξονα κατηγορίας. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Ορίζει την ιδιότητα IAxis.CategoryAxisType με τιμή που καθορίζεται αυτόματα βάσει των δεδομένων του άξονα. |
| [getAggregationType()](#getAggregationType--) | Αναπαριστά τον τύπο συγκέντρωσης του άξονα κατηγορίας (ομαδοποίηση). |
| [setAggregationType(int value)](#setAggregationType-int-) | Αναπαριστά τον τύπο συγκέντρωσης του άξονα κατηγορίας (ομαδοποίηση). |
| [getBinWidth()](#getBinWidth--) | Καθορίζει το πλάτος του κάδου όταν η ιδιότητα AggregationType ορίζεται σε AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | Καθορίζει το πλάτος του κάδου όταν η ιδιότητα AggregationType ορίζεται σε AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | Καθορίζει τον αριθμό των κάδων όταν η ιδιότητα AggregationType ορίζεται σε AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Καθορίζει τον αριθμό των κάδων όταν η ιδιότητα AggregationType ορίζεται σε AxisAggregationType.ByNumberOfBins. |
| [isOverflowBin()](#isOverflowBin--) | Καθορίζει εάν εφαρμόζεται κάδος υπερχείλισης. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | Καθορίζει εάν εφαρμόζεται κάδος υπερχείλισης. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | Καθορίζει την αυτόματη τιμή του κάδου υπερχείλισης. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | Καθορίζει την αυτόματη τιμή του κάδου υπερχείλισης. |
| [getOverflowBin()](#getOverflowBin--) | Καθορίζει την προσαρμοσμένη τιμή του κάδου υπερχείλισης. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | Καθορίζει την προσαρμοσμένη τιμή του κάδου υπερχείλισης. |
| [isUnderflowBin()](#isUnderflowBin--) | Καθορίζει εάν εφαρμόζεται κάδος υποροής. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | Καθορίζει εάν εφαρμόζεται κάδος υποροής. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | Καθορίζει την αυτόματη τιμή του κάδου υποροής. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | Καθορίζει την αυτόματη τιμή του κάδου υποροής. |
| [getUnderflowBin()](#getUnderflowBin--) | Καθορίζει την προσαρμοσμένη τιμή του κάδου υποροής. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | Καθορίζει την προσαρμοσμένη τιμή του κάδου υποροής. |

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public abstract boolean getAxisBetweenCategories()
```

Αναπαριστά αν ο άξονας τιμών διασχίζει τον άξονα κατηγορίας μεταξύ των κατηγοριών. Αυτή η ιδιότητα εφαρμόζεται μόνο σε άξονες κατηγορίας και δεν εφαρμόζεται σε 3-Δ διαγράμματα. Ανάγνωση/εγγραφή boolean.

**Returns:**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public abstract void setAxisBetweenCategories(boolean value)
```

Αναπαριστά αν ο άξονας τιμών διασχίζει τον άξονα κατηγορίας μεταξύ των κατηγοριών. Αυτή η ιδιότητα εφαρμόζεται μόνο σε άξονες κατηγορίας και δεν εφαρμόζεται σε 3-Δ διαγράμματα. Ανάγνωση/εγγραφή boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getCrossAt() {#getCrossAt--}
```
public abstract float getCrossAt()
```

Αναπαριστά το σημείο στον άξονα όπου ο κάθετος άξονας τον διασχίζει. Ανάγνωση/εγγραφή float.

**Returns:**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public abstract void setCrossAt(float value)
```

Αναπαριστά το σημείο στον άξονα όπου ο κάθετος άξονας τον διασχίζει. Ανάγνωση/εγγραφή float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public abstract int getDisplayUnit()
```

Καθορίζει την τιμή κλιμάκωσης των μονάδων εμφάνισης για τον άξονα τιμών. Ανάγνωση/εγγραφή [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Returns:**
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public abstract void setDisplayUnit(int value)
```

Καθορίζει την τιμή κλιμάκωσης των μονάδων εμφάνισης για τον άξονα τιμών. Ανάγνωση/εγγραφή [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public abstract double getActualMaxValue()
```

Καθορίζει την πραγματική μέγιστη τιμή στον άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή.

**Returns:**
double

### getActualMinValue() {#getActualMinValue--}
```
public abstract double getActualMinValue()
```

Καθορίζει την πραγματική ελάχιστη τιμή στον άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή.

**Returns:**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public abstract double getActualMajorUnit()
```

Καθορίζει την πραγματική κύρια μονάδα του άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή.

**Returns:**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public abstract double getActualMinorUnit()
```

Καθορίζει την πραγματική δευτερεύουσα μονάδα του άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή.

**Returns:**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public abstract int getActualMajorUnitScale()
```

Καθορίζει την πραγματική κλίμακα κύριας μονάδας του άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή.

**Returns:**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public abstract int getActualMinorUnitScale()
```

Καθορίζει την πραγματική κλίμακα δευτερεύουσας μονάδας του άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή.

**Returns:**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public abstract boolean isAutomaticMaxValue()
```

Υποδεικνύει εάν η μέγιστη τιμή ορίζεται αυτόματα. Ανάγνωση/εγγραφή boolean.

**Returns:**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public abstract void setAutomaticMaxValue(boolean value)
```

Υποδεικνύει εάν η μέγιστη τιμή ορίζεται αυτόματα. Ανάγνωση/εγγραφή boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public abstract double getMaxValue()
```

Αναπαριστά τη μέγιστη τιμή στον άξονα τιμών. Ανάγνωση/εγγραφή double.

**Returns:**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public abstract void setMaxValue(double value)
```

Αναπαριστά τη μέγιστη τιμή στον άξονα τιμών. Ανάγνωση/εγγραφή double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public abstract double getMinorUnit()
```

Αναπαριστά τις δευτερεύουσες μονάδες για τον άξονα ημερομηνίας ή τιμής. Ανάγνωση/εγγραφή double.

**Returns:**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public abstract void setMinorUnit(double value)
```

Αναπαριστά τις δευτερεύουσες μονάδες για τον άξονα ημερομηνίας ή τιμής. Ανάγνωση/εγγραφή double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public abstract boolean isAutomaticMinorUnit()
```

Υποδεικνύει εάν η δευτερεύουσα μονάδα του άξονα ορίζεται αυτόματα. Ανάγνωση/εγγραφή boolean.

**Returns:**
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public abstract void setAutomaticMinorUnit(boolean value)
```

Υποδεικνύει εάν η δευτερεύουσα μονάδα του άξονα ορίζεται αυτόματα. Ανάγνωση/εγγραφή boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public abstract double getMajorUnit()
```

Αναπαριστά τις κύριες μονάδες για τον άξονα ημερομηνίας ή τιμής. Ανάγνωση/εγγραφή double.

**Returns:**
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public abstract void setMajorUnit(double value)
```

Αναπαριστά τις κύριες μονάδες για τον άξονα ημερομηνίας ή τιμής. Ανάγνωση/εγγραφή double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public abstract boolean isAutomaticMajorUnit()
```

Υποδεικνύει εάν η κύρια μονάδα του άξονα ορίζεται αυτόματα. Ανάγνωση/εγγραφή boolean.

**Returns:**
boolean

### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public abstract void setAutomaticMajorUnit(boolean value)
```

Υποδεικνύει εάν η κύρια μονάδα του άξονα ορίζεται αυτόματα. Ανάγνωση/εγγραφή boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public abstract boolean isAutomaticMinValue()
```

Υποδεικνύει εάν η ελάχιστη τιμή ορίζεται αυτόματα. Ανάγνωση/εγγραφή boolean.

**Returns:**
boolean

### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public abstract void setAutomaticMinValue(boolean value)
```

Υποδεικνύει εάν η ελάχιστη τιμή ορίζεται αυτόματα. Ανάγνωση/εγγραφή boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public abstract double getMinValue()
```

Αναπαριστά την ελάχιστη τιμή στον άξονα τιμών. Ανάγνωση/εγγραφή double.

**Returns:**
double

### setMinValue(double value) {#setMinValue-double-}
```
public abstract void setMinValue(double value)
```

Αναπαριστά την ελάχιστη τιμή στον άξονα τιμών. Ανάγνωση/εγγραφή double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public abstract boolean isLogarithmic()
```

Αναπαριστά εάν ο τύπος κλίμακας του άξονα τιμών είναι λογαριθμικός ή όχι. Ανάγνωση/εγγραφή boolean.

**Returns:**
boolean

### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public abstract void setLogarithmic(boolean value)
```

Αναπαριστά εάν ο τύπος κλίμακας του άξονα τιμών είναι λογαριθμικός ή όχι. Ανάγνωση/εγγραφή boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public abstract double getLogBase()
```

Αναπαριστά τη λογαριθμική βάση. Η προεπιλεγμένη τιμή είναι 10. Ανάγνωση/εγγραφή double.

**Returns:**
double

### setLogBase(double value) {#setLogBase-double-}
```
public abstract void setLogBase(double value)
```

Αναπαριστά τη λογαριθμική βάση. Η προεπιλεγμένη τιμή είναι 10. Ανάγνωση/εγγραφή double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public abstract boolean isPlotOrderReversed()
```

Αναπαριστά εάν το MS PowerPoint σχεδιάζει τα σημεία δεδομένων από το τέλος προς την αρχή. Ανάγνωση/εγγραφή boolean.

**Returns:**
boolean

### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public abstract void setPlotOrderReversed(boolean value)
```

Αναπαριστά εάν το MS PowerPoint σχεδιάζει τα σημεία δεδομένων από το τέλος προς την αρχή. Ανάγνωση/εγγραφή boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Αναπαριστά εάν ο άξονας είναι ορατός. Ανάγνωση/εγγραφή boolean.

**Returns:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public void                {          }{          } { 
```

Αναπαριστά εάν ο άξονας είναι ορατός. Ανάγνωση/εγγραφή boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public abstract int getMajorTickMark()
```

Αναπαριστά τον τύπο της κύριας σημαδούρας για τον καθορισμένο άξονα. Ανάγνωση/εγγραφή [TickMarkType](../../com.aspose.slides/tickmarktype).

**Returns:**
int

### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public abstract void setMajorTickMark(int value)
```

Αναπαριστά τον τύπο της κύριας σημαδούρας για τον καθορισμένο άξονα. Ανάγνωση/εγγραφή [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public abstract int getMinorTickMark()
```

Αναπαριστά τον τύπο της δευτερεύουσας σημαδούρας για τον καθορισμένο άξονα. Ανάγνωση/εγγραφή [TickMarkType](../../com.aspose.slides/tickmarktype).

**Returns:**
int

### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public abstract void setMinorTickMark(int value)
```

Αναπαριστά τον τύπο της δευτερεύουσας σημαδούρας για τον καθορισμένο άξονα. Ανάγνωση/εγγραφή [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public abstract int getTickLabelPosition()
```

Αναπαριστά τη θέση των ετικετών σημαδιών στον καθορισμένο άξονα. Ανάγνωση/εγγραφή [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Returns:**
int

### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public abstract void setTickLabelPosition(int value)
```

Αναπαριστά τη θέση των ετικετών σημαδιών στον καθορισμένο άξονα. Ανάγνωση/εγγραφή [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public abstract int getMajorUnitScale()
```

Αναπαριστά την κλίμακα κύριας μονάδας για τον άξονα ημερομηνίας. Ανάγνωση/εγγραφή [TimeUnitType](../../com.aspose.slides/timeunittype).

**Returns:**
int

### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public abstract void setMajorUnitScale(int value)
```

Αναπαριστά την κλίμακα κύριας μονάδας για τον άξονα ημερομηνίας. Ανάγνωση/εγγραφή [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public abstract int getMinorUnitScale()
```

Αναπαριστά την κλίμακα κύριας μονάδας για τον άξονα ημερομηνίας. Ανάγνωση/εγγραφή [TimeUnitType](../../com.aspose.slides/timeunittype).

**Returns:**
int

### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public abstract void setMinorUnitScale(int value)
```

Αναπαριστά την κλίμακα κύριας μονάδας για τον άξονα ημερομηνίας. Ανάγνωση/εγγραφή [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public abstract int getBaseUnitScale()
```

Καθορίζει τη μικρότερη μονάδα χρόνου που εμφανίζεται στον άξονα ημερομηνίας. Ανάγνωση/εγγραφή [TimeUnitType](../../com.aspose.slides/timeunittype).

**Returns:**
int

### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public           ?

```

Καθορίζει τη μικρότερη μονάδα χρόνου που εμφανίζεται στον άξονα ημερομηνίας. Ανάγνωση/εγγραφή [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

Αναπαριστά τη μορφή των δευτερευουσών γραμμών πλέγματος σε άξονα διαγράμματος. Μόνο ανάγνωση [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Returns:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public abstract IChartLinesFormat getMajorGridLinesFormat()
```

Αναπαριστά τη μορφή των κύριων γραμμών πλέγματος σε άξονα διαγράμματος. Μόνο ανάγνωση [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Returns:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public abstract boolean getShowMinorGridLines()
```

Αναπαριστά εάν οι δευτερεύουσες γραμμές πλέγματος εμφανίζονται. Μόνο ανάγνωση boolean.

**Returns:**
boolean

### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public abstract boolean getShowMajorGridLines()
```

Αναπαριστά εάν οι κύριες γραμμές πλέγματος εμφανίζονται. Μόνο ανάγνωση boolean.

**Returns:**
boolean

### getFormat() {#getFormat--}
```
public abstract IAxisFormat getFormat()
```

Αναπαριστά τη μορφή του άξονα. Μόνο ανάγνωση [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Returns:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)

### getTitle() {#getTitle--}
```
public abstract IChartTitle getTitle()
```

Λαμβάνει τον τίτλο του άξονα. Μόνο ανάγνωση [IChartTitle](../../com.aspose.slides/icharttitle).

**Returns:**
[IChartTitle](../../com.aspose.slides/icharttitle)

### getCrossType() {#getCrossType--}
```
public abstract int getCrossType()
```

Αναπαριστά το CrossType στον καθορισμένο άξονα όπου διασχίζει ο άλλος άξονας. Ανάγνωση/εγγραφή [CrossesType](../../com.aspose.slides/crossestype).

**Returns:**
int

### setCrossType(int value) {#setCrossType-int-}
```
public abstract void setCrossType(int value)
```

Αναπαριστά το CrossType στον καθορισμένο άξονα όπου διασχίζει ο άλλος άξονας. Ανάγνωση/εγγραφή [CrossesType](../../com.aspose.slides/crossestype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Αναπαριστά τη θέση του άξονα. Ανάγνωση/εγγραφή [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Returns:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Αναπαριστά τη θέση του άξονα. Ανάγνωση/εγγραφή [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

Καθορίζει εάν ο άξονας έχει ορατό τίτλο. Ανάγνωση/εγγραφή boolean.

**Returns:**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

Καθορίζει εάν ο άξονας έχει ορατό τίτλο. Ανάγνωση/εγγραφή boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

Αναπαριστά το συμβολοσειρά μορφής για τις ετικέτες του άξονα. Ανάγνωση/εγγραφή String.

**Returns:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

Αναπαριστά το συμβολοσειρά μορφής για τις ετικέτες του άξονα. Ανάγνωση/εγγραφή String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Υποδεικνύει εάν η μορφή είναι συνδεδεμένη με τα δεδομένα προέλευσης. Ανάγνωση/εγγραφή boolean.

**Returns:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Υποδεικνύει εάν η μορφή είναι συνδεδεμένη με τα δεδομένα προέλευσης. Ανάγνωση/εγγραφή boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public abstract float getTickLabelRotationAngle()
```

Αναπαριστά τη γωνία περιστροφής των ετικετών σημαδιών. Ανάγνωση/εγγραφή float.

**Returns:**
float

### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public abstract void setTickLabelRotationAngle(float value)
```

Αναπαριστά τη γωνία περιστροφής των ετικετών σημαδιών. Ανάγνωση/εγγραφή float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public abstract long getTickLabelSpacing()
```

Καθορίζει πόσες ετικέτες σημαδιών παραλείπονται μεταξύ των σημειώσεων που σχεδιάζονται. Ανάγνωση/εγγραφή long.

**Returns:**
long

### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public abstract void setTickLabelSpacing(long value)
```

Καθορίζει πόσες ετικέτες σημαδιών παραλείπονται μεταξύ των σημειώσεων που σχεδιάζονται. Ανάγνωση/εγγραφή long.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public abstract boolean isAutomaticTickLabelSpacing()
```

Καθορίζει την αυτόματη τιμή απόστασης ετικετών σημαδιών. Αν είναι false: χρησιμοποιήστε την ιδιότητα TickLabelSpacing. Ανάγνωση/εγγραφή boolean.

**Returns:**
boolean

### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public abstract void setAutomaticTickLabelSpacing(boolean value)
```

Καθορίζει την αυτόματη τιμή απόστασης ετικετών σημαδιών. Αν είναι false: χρησιμοποιήστε την ιδιότητα TickLabelSpacing. Ανάγνωση/εγγραφή boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public abstract long getTickMarksSpacing()
```

Καθορίζει πόσες σημαδούρες πρέπει να παραλειφθούν πριν σχεδιαστεί η επόμενη. Εφαρμόζεται σε άξονα κατηγορίας ή σειράς. Ανάγνωση/εγγραφή int.

**Returns:**
long

### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public abstract void setTickMarksSpacing(long value)
```

Καθορίζει πόσες σημαδούρες πρέπει να παραλειφθούν πριν σχεδιαστεί η επόμενη. Εφαρμόζεται σε άξονα κατηγορίας ή σειράς. Ανάγνωση/εγγραφή int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public abstract boolean isAutomaticTickMarksSpacing()
```

Καθορίζει την αυτόματη τιμή απόστασης σημαδιών. Αν είναι false: χρησιμοποιήστε την ιδιότητα TickMarksSpacing. Ανάγνωση/εγγραφή boolean.

**Returns:**
boolean

### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public abstract boolean isAutomaticTickMarksSpacing()
```

Καθορίζει την αυτόματη τιμή απόστασης σημαδιών. Αν είναι false: χρησιμοποιήστε την ιδιότητα TickMarksSpacing. Ανάγνωση/εγγραφή boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public abstract int getLabelOffset()
```

Καθορίζει την απόσταση των ετικετών από τον άξονα. Εφαρμόζεται σε άξονα κατηγορίας ή ημερομηνίας. Η τιμή πρέπει να είναι μεταξύ 0% και 1000%. Ανάγνωση/εγγραφή int.

**Returns:**
int

### setLabelOffset(int value) {#setLabelOffset-int-}
```
public abstract void setLabelOffset(int value)
```

Καθορίζει την απόσταση των ετικετών από τον άξονα. Εφαρμόζεται σε άξονα κατηγορίας ή ημερομηνίας. Η τιμή πρέπει να είναι μεταξύ 0% και 1000%. Ανάγνωση/εγγραφή int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public abstract int getCategoryAxisType()
```

Καθορίζει τον τύπο του άξονα κατηγορίας. Ανάγνωση/εγγραφή [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Returns:**
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public abstract void setCategoryAxisType(int value)
```

Καθορίζει τον τύπο του άξονα κατηγορίας. Ανάγνωση/εγγραφή [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public abstract void setCategoryAxisTypeAutomatically()
```

Ορίζει την ιδιότητα IAxis.CategoryAxisType με τιμή που καθορίζεται αυτόματα βάσει των δεδομένων του άξονα.

### getAggregationType() {#getAggregationType--}
```
public abstract int getAggregationType()
```

Αναπαριστά τον τύπο συγκέντρωσης του άξονα κατηγορίας (ομαδοποίηση). Εφαρμόζεται σε κατηγορία. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto.

**Returns:**
int

### setAggregationType(int value) {#setAggregationType-int-}
```
public abstract void setAggregationType(int value)
```

Αναπαριστά τον τύπο συγκέντρωσης του άξονα κατηγορίας (ομαδοποίηση). Εφαρμόζεται σε κατηγορία. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public abstract double getBinWidth()
```

Καθορίζει το πλάτος του κάδου όταν η ιδιότητα AggregationType ορίζεται σε AxisAggregationType.ByBinWidth. Εφαρμόζεται σε άξονες κατηγορίας. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto.

**Returns:**
double

### setBinWidth(double value) {#setBinWidth-double-}
```
public abstract void setBinWidth(double value)
```

Καθορίζει το πλάτος του κάδου όταν η ιδιότητα AggregationType ορίζεται σε AxisAggregationType.ByBinWidth. Εφαρμόζεται σε άξονες κατηγορίας. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public abstract long getNumberOfBins()
```

Καθορίζει τον αριθμό των κάδων όταν η ιδιότητα AggregationType ορίζεται σε AxisAggregationType.ByNumberOfBins. Εφαρμόζεται σε άξονες κατηγορίας. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto.

**Returns:**
long

### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public abstract void setNumberOfBins(long value)
```

Καθορίζει τον αριθμό των κάδων όταν η ιδιότητα AggregationType ορίζεται σε AxisAggregationType.ByNumberOfBins. Εφαρμόζεται σε άξονες κατηγορίας. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public abstract boolean isOverflowBin()
```

Καθορίζει εάν εφαρμόζεται κάδος υπερχείλισης. Χρησιμοποιήστε τις ιδιότητες IsAutomaticOverflowBin και OverflowBin για προσαρμογή της τιμής.

**Returns:**
boolean

### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public abstract void setOverflowBin(boolean value)
```

Καθορίζει εάν εφαρμόζεται κάδος υπερχείλισης. Χρησιμοποιήστε τις ιδιότητες IsAutomaticOverflowBin και OverflowBin για προσαρμογή της τιμής.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public abstract boolean isAutomaticOverflowBin()
```

Καθορίζει την αυτόματη τιμή του κάδου υπερχείλισης. Αν είναι false: χρησιμοποιήστε την ιδιότητα OverflowBin.

**Returns:**
boolean

### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public abstract void setAutomaticOverflowBin(boolean value)
```

Καθορίζει την αυτόματη τιμή του κάδου υπερχείλισης. Αν είναι false: χρησιμοποιήστε την ιδιότητα OverflowBin.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public abstract double getOverflowBin()
```

Καθορίζει την προσαρμοσμένη τιμή του κάδου υπερχείλισης. Εφαρμόζεται όταν η ιδιότητα IsAutomaticOverflowBin είναι false και η ιδιότητα IsOverflowBin είναι true.

**Returns:**
double

### setOverflowBin(double value) {#setOverflowBin-double-}
```
public abstract void setOverflowBin(double value)
```

Καθορίζει την προσαρμοσμένη τιμή του κάδου υπερχείλισης. Εφαρμόζεται όταν η ιδιότητα IsAutomaticOverflowBin είναι false και η ιδιότητα IsOverflowBin είναι true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public abstract boolean isUnderflowBin()
```

Καθορίζει εάν εφαρμόζεται κάδος υποροής. Χρησιμοποιήστε τις ιδιότητες IsAutomaticUnderflowBin και UnderflowBin για προσαρμογή της τιμής.

**Returns:**
boolean

### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public abstract void setUnderflowBin(boolean value)
```

Καθορίζει εάν εφαρμόζεται κάδος υποροής. Χρησιμοποιήστε τις ιδιότητες IsAutomaticUnderflowBin και UnderflowBin για προσαρμογή της τιμής.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public abstract boolean isAutomaticUnderflowBin()
```

Καθορίζει την αυτόματη τιμή του κάδου υποροής. Αν είναι false: χρησιμοποιήστε την ιδιότητα UnderflowBin.

**Returns:**
boolean

### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public abstract void setAutomaticUnderflowBin(boolean value)
```

Καθορίζει την αυτόματη τιμή του κάδου υποροής. Αν είναι false: χρησιμοποιήστε την ιδιότητα UnderflowBin.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public abstract double getUnderflowBin()
```

Καθορίζει την προσαρμοσμένη τιμή του κάδου υποροής. Εφαρμόζεται όταν η ιδιότητα IsAutomaticUnderflowBin είναι false και η ιδιότητα IsUnderflowBin είναι true.

**Returns:**
double

### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public abstract void setUnderflowBin(double value)
```

Καθορίζει την προσαρμοσμένη τιμή του κάδου υποροής. Εφαρμόζεται όταν η ιδιότητα IsAutomaticUnderflowBin είναι false και η ιδιότητα IsUnderflowBin είναι true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |