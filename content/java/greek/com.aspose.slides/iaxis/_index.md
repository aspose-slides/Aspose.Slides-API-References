---
title: IAxis
second_title: Αναφορά API του Aspose.Slides για Java
description: Περιβάλλει το αντικείμενο που αντιπροσωπεύει τον άξονα ενός γραφήματος.
type: docs
url: /el/com.aspose.slides/iaxis/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IAxis extends IFormattedTextContainer
```

Ασφαλίζει το αντικείμενο που αντιπροσωπεύει τον άξονας ενός διαγράμματος.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Αντιπροσωπεύει εάν ο άξονας τιμής διασχίζει τον άξονα κατηγορίας μεταξύ των κατηγοριών. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Αντιπροσωπεύει εάν ο άξονας τιμής διασχίζει τον άξονα κατηγορίας μεταξύ των κατηγοριών. |
| [getCrossAt()](#getCrossAt--) | Αντιπροσωπεύει το σημείο στον άξονα όπου ο κάθετος άξονας τον διασχίζει. |
| [setCrossAt(float value)](#setCrossAt-float-) | Αντιπροσωπεύει το σημείο στον άξονα όπου ο κάθετος άξονας τον διασχίζει. |
| [getDisplayUnit()](#getDisplayUnit--) | Καθορίζει την κλιμακωτική τιμή των μονάδων εμφάνισης για τον άξονα τιμής. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Καθορίζει την κλιμακωτική τιμή των μονάδων εμφάνισης για τον άξονα τιμής. |
| [getActualMaxValue()](#getActualMaxValue--) | Καθορίζει την πραγματική μέγιστη τιμή στον άξονα. |
| [getActualMinValue()](#getActualMinValue--) | Καθορίζει την πραγματική ελάχιστη τιμή στον άξονα. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Καθορίζει την πραγματική κύρια μονάδα του άξονα. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Καθορίζει την πραγματική δευτερεύουσα μονάδα του άξονα. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Καθορίζει την πραγματική κλίμακα κύριας μονάδας του άξονα. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Καθορίζει την πραγματική κλίμακα δευτερεύουσας μονάδας του άξονα. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Υποδεικνύει εάν η μέγιστη τιμή ορίζεται αυτόματα. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Υποδεικνύει εάν η μέγιστη τιμή ορίζεται αυτόματα. |
| [getMaxValue()](#getMaxValue--) | Αντιπροσωπεύει τη μέγιστη τιμή στον άξονα τιμής. |
| [setMaxValue(double value)](#setMaxValue-double-) | Αντιπροσωπεύει τη μέγιστη τιμή στον άξονα τιμής. |
| [getMinorUnit()](#getMinorUnit--) | Αντιπροσωπεύει τις δευτερεύουσες μονάδες για τον άξονα ημερομηνίας ή τιμής. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Αντιπροσωπεύει τις δευτερεύουσες μονάδες για τον άξονα ημερομηνίας ή τιμής. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Υποδεικνύει εάν η δευτερεύουσα μονάδα του άξονα ορίζεται αυτόματα. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Υποδεικνύει εάν η δευτερεύουσα μονάδα του άξονα ορίζεται αυτόματα. |
| [getMajorUnit()](#getMajorUnit--) | Αντιπροσωπεύει τις κύριες μονάδες για τον άξονα ημερομηνίας ή τιμής. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Αντιπροσωπεύει τις κύριες μονάδες για τον άξονα ημερομηνίας ή τιμής. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Υποδεικνύει εάν η κύρια μονάδα του άξονα ορίζεται αυτόματα. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Υποδεικνύει εάν η κύρια μονάδα του άξονα ορίζεται αυτόματα. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Υποδεικνύει εάν η ελάχιστη τιμή ορίζεται αυτόματα. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Υποδεικνύει εάν η ελάχιστη τιμή ορίζεται αυτόματα. |
| [getMinValue()](#getMinValue--) | Αντιπροσωπεύει την ελάχιστη τιμή στον άξονα τιμής. |
| [setMinValue(double value)](#setMinValue-double-) | Αντιπροσωπεύει την ελάχιστη τιμή στον άξονα τιμής. |
| [isLogarithmic()](#isLogarithmic--) | Αντιπροσωπεύει εάν ο τύπος κλίμακας του άξονα τιμής είναι λογαριθμικός ή όχι. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Αντιπροσωπεύει εάν ο τύπος κλίμακας του άξονα τιμής είναι λογαριθμικός ή όχι. |
| [getLogBase()](#getLogBase--) | Αντιπροσωπεύει τη λογαριθμική βάση. |
| [setLogBase(double value)](#setLogBase-double-) | Αντιπροσωπεύει τη λογαριθμική βάση. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Αντιπροσωπεύει εάν το MS PowerPoint σχεδιάζει τα σημεία δεδομένων από το τελευταίο στο πρώτο. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Αντιπροσωπεύει εάν το MS PowerPoint σχεδιάζει τα σημεία δεδομένων από το τελευταίο στο πρώτο. |
| [isVisible()](#isVisible--) | Αντιπροσωπεύει εάν ο άξονας είναι ορατός. |
| [setVisible(boolean value)](#setVisible-boolean-) | Αντιπροσωπεύει εάν ο άξονας είναι ορατός. |
| [getMajorTickMark()](#getMajorTickMark--) | Αντιπροσωπεύει τον τύπο του κύριου δίαυλου σήμανσης για τον καθορισμένο άξονα. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Αντιπροσωπεύει τον τύπο του κύριου δίαυλου σήμανσης για τον καθορισμένο άξονα. |
| [getMinorTickMark()](#getMinorTickMark--) | Αντιπροσωπεύει τον τύπο του δευτερεύοντος δίαυλου σήμανσης για τον καθορισμένο άξονα. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Αντιπροσωπεύει τον τύπο του δευτερεύοντος δίαυλου σήμανσης για τον καθορισμένο άξονα. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Αντιπροσωπεύει τη θέση των ετικετών των σημείων σήμανσης στον καθορισμένο άξονα. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Αντιπροσωπεύει τη θέση των ετικετών των σημείων σήμανσης στον καθορισμένο άξονα. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Αντιπροσωπεύει την κλίμακα κύριας μονάδας για τον άξονα ημερομηνίας. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Αντιπροσωπεύει την κλίμακα κύριας μονάδας για τον άξονα ημερομηνίας. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Αντιπροσωπεύει την κλίμακα κύριας μονάδας για τον άξονα ημερομηνίας. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Αντιπροσωπεύει την κλίμακα κύριας μονάδας για τον άξονα ημερομηνίας. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Καθορίζει τη μικρότερη μονάδα χρόνου που εμφανίζεται στον άξονα ημερομηνίας. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Καθορίζει τη μικρότερη μονάδα χρόνου που εμφανίζεται στον άξονα ημερομηνίας. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Αντιπροσωπεύει τη μορφή των δευτερευουσών γραμμών πλέγματος σε άξονα διαγράμματος. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Αντιπροσωπεύει τη μορφή των κύριων γραμμών πλέγματος σε άξονα διαγράμματος. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Αντιπροσωπεύει εάν εμφανίζονται οι δευτερεύουσες γραμμές πλέγματος. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Αντιπροσωπεύει εάν εμφανίζονται οι κύριες γραμμές πλέγματος. |
| [getFormat()](#getFormat--) | Αντιπροσωπεύει τη μορφή του άξονα. |
| [getTitle()](#getTitle--) | Λαμβάνει τον τίτλο του άξονα. |
| [getCrossType()](#getCrossType--) | Αντιπροσωπεύει το CrossType στον καθορισμένο άξονα όπου ο άλλος άξονας διασχίζει. |
| [setCrossType(int value)](#setCrossType-int-) | Αντιπροσωπεύει το CrossType στον καθορισμένο άξονα όπου ο άλλος άξονας διασχίζει. |
| [getPosition()](#getPosition--) | Αντιπροσωπεύει τη θέση του άξονα. |
| [setPosition(int value)](#setPosition-int-) | Αντιπροσωπεύει τη θέση του άξονα. |
| [hasTitle()](#hasTitle--) | Καθορίζει εάν ένας άξονας έχει ορατό τίτλο. |
| [setTitle(boolean value)](#setTitle-boolean-) | Καθορίζει εάν ένας άξονας έχει ορατό τίτλο. |
| [getNumberFormat()](#getNumberFormat--) | Αντιπροσωπεύει τη συμβολοσειρά μορφής για τις ετικέτες του άξονα. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Αντιπροσωπεύει τη συμβολοσειρά μορφής για τις ετικέτες του άξονα. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Υποδεικνύει εάν η μορφή είναι συνδεδεμένα δεδομένα προέλευσης. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Υποδεικνύει εάν η μορφή είναι συνδεδεμένα δεδομένα προέλευσης. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Αντιπροσωπεύει τη γωνία περιστροφής των ετικετών των σημείων σήμανσης. Ανάγνωση/εγγραφή float. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Αντιπροσωπεύει τη γωνία περιστροφής των ετικετών των σημείων σήμανσης. Ανάγνωση/εγγραφή float. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Καθορίζει πόσες ετικέτες σημείων σήμανσης θα παραλειφθούν μεταξύ των ετικετών που σχεδιάζονται. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Καθορίζει πόσες ετικέτες σημείων σήμανσης θα παραλειφθούν μεταξύ των ετικετών που σχεδιάζονται. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Καθορίζει την αυτόματη τιμή απόστασης ετικετών σημείων σήμανσης. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Καθορίζει την αυτόματη τιμή απόστασης ετικετών σημείων σήμανσης. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Καθορίζει πόσες σημαδοδοτήσεις θα παραλειφθούν πριν σχεδιαστεί η επόμενη. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Καθορίζει πόσες σημαδοδοτήσεις θα παραλειφθούν πριν σχεδιαστεί η επόμενη. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Καθορίζει την αυτόματη τιμή απόστασης σημεία σήμανσης. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Καθορίζει την αυτόματη τιμή απόστασης σημεία σήμανσης. |
| [getLabelOffset()](#getLabelOffset--) | Καθορίζει την απόσταση των ετικετών από τον άξονα. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Καθορίζει την απόσταση των ετικετών από τον άξονα. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Καθορίζει τον τύπο του άξονα κατηγορίας. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Καθορίζει τον τύπο του άξονα κατηγορίας. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Ορίζει την ιδιότητα IAxis.CategoryAxisType με μια τιμή που καθορίζεται αυτόματα βάσει των δεδομένων του άξονα. |
| [getAggregationType()](#getAggregationType--) | Αντιπροσωπεύει τον τύπο συγκέντρωσης του άξονα κατηγορίας (ομαδοποίηση). |
| [setAggregationType(int value)](#setAggregationType-int-) | Αντιπροσωπεύει τον τύπο συγκέντρωσης του άξονα κατηγορίας (ομαδοποίηση). |
| [getBinWidth()](#getBinWidth--) | Καθορίζει το πλάτος του κουβά όταν η ιδιότητα AggregationType ορίζεται σε AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | Καθορίζει το πλάτος του κουβά όταν η ιδιότητα AggregationType ορίζεται σε AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | Καθορίζει τον αριθμό των κουβάδων όταν η ιδιότητα AggregationType ορίζεται σε AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Καθορίζει τον αριθμό των κουβάδων όταν η ιδιότητα AggregationType ορίζεται σε AxisAggregationType.ByNumberOfBins. |
| [isOverflowBin()](#isOverflowBin--) | Καθορίζει εάν εφαρμόζεται κουβάς υπερχείλισης. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | Καθορίζει εάν εφαρμόζεται κουβάς υπερχείλισης. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | Καθορίζει την αυτόματη τιμή του κουβά υπερχείλισης. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | Καθορίζει την αυτόματη τιμή του κουβά υπερχείλισης. |
| [getOverflowBin()](#getOverflowBin--) | Καθορίζει την προσαρμοσμένη τιμή του κουβά υπερχείλισης. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | Καθορίζει την προσαρμοσμένη τιμή του κουβά υπερχείλισης. |
| [isUnderflowBin()](#isUnderflowBin--) | Καθορίζει εάν εφαρμόζεται κουβάς υποκλήρωσης. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | Καθορίζει εάν εφαρμόζεται κουβάς υποκλήρωσης. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | Καθορίζει την αυτόματη τιμή του κουβά υποκλήρωσης. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | Καθορίζει την αυτόματη τιμή του κουβά υποκλήρωσης. |
| [getUnderflowBin()](#getUnderflowBin--) | Καθορίζει την προσαρμοσμένη τιμή του κουβά υποκλήρωσης. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | Καθορίζει την προσαρμοσμένη τιμή του κουβά υποκλήρωσης. |

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public abstract boolean getAxisBetweenCategories()
```

Αντιπροσωπεύει εάν ο άξονας τιμής διασχίζει τον άξονα κατηγορίας μεταξύ των κατηγοριών. Αυτή η ιδιότητα ισχύει μόνο για άξονες κατηγορίας και δεν ισχύει για 3-D διαγράμματα. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public abstract void setAxisBetweenCategories(boolean value)
```

Αντιπροσωπεύει εάν ο άξονας τιμής διασχίζει τον άξονα κατηγορίας μεταξύ των κατηγοριών. Αυτή η ιδιότητα ισχύει μόνο για άξονες κατηγορίας και δεν ισχύει για 3-D διαγράμματα. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getCrossAt() {#getCrossAt--}
```
public abstract float getCrossAt()
```

Αντιπροσωπεύει το σημείο στον άξονα όπου ο κάθετος άξονας τον διασχίζει. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setCrossAt(float value) {#setCrossAt-float-}
```
public abstract void setCrossAt(float value)
```

Αντιπροσωπεύει το σημείο στον άξονα όπου ο κάθετος άξονας τον διασχίζει. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public abstract int getDisplayUnit()
```

Καθορίζει την κλιμακωτική τιμή των μονάδων εμφάνισης για τον άξονα τιμής. Ανάγνωση/εγγραφή [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Επιστρέφει:**
int
### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public abstract void setDisplayUnit(int value)
```

Καθορίζει την κλιμακωτική τιμή των μονάδων εμφάνισης για τον άξονα τιμής. Ανάγνωση/εγγραφή [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public abstract double getActualMaxValue()
```

Καθορίζει την πραγματική μέγιστη τιμή στον άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή.

**Επιστρέφει:**
double
### getActualMinValue() {#getActualMinValue--}
```
public abstract double getActualMinValue()
```

Καθορίζει την πραγματική ελάχιστη τιμή στον άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή.

**Επιστρέφει:**
double
### getActualMajorUnit() {#getActualMajorUnit--}
```
public abstract double getActualMajorUnit()
```

Καθορίζει την πραγματική κύρια μονάδα του άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή.

**Επιστρέφει:**
double
### getActualMinorUnit() {#getActualMinorUnit--}
```
public abstract double getActualMinorUnit()
```

Καθορίζει την πραγματική δευτερεύουσα μονάδα του άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή.

**Επιστρέφει:**
double
### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public abstract int getActualMajorUnitScale()
```

Καθορίζει την πραγματική κλίμακα κύριας μονάδας του άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή.

**Επιστρέφει:**
int
### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public abstract int getActualMinorUnitScale()
```

Καθορίζει την πραγματική κλίμακα δευτερεύουσας μονάδας του άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή.

**Επιστρέφει:**
int
### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public abstract boolean isAutomaticMaxValue()
```

Υποδεικνύει εάν η μέγιστη τιμή ορίζεται αυτόματα. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public abstract void setAutomaticMaxValue(boolean value)
```

Υποδεικνύει εάν η μέγιστη τιμή ορίζεται αυτόματα. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public abstract double getMaxValue()
```

Αντιπροσωπεύει τη μέγιστη τιμή στον άξονα τιμής. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setMaxValue(double value) {#setMaxValue-double-}
```
public abstract void setMaxValue(double value)
```

Αντιπροσωπεύει τη μέγιστη τιμή στον άξονα τιμής. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public abstract double getMinorUnit()
```

Αντιπροσωπεύει τις δευτερεύουσες μονάδες για τον άξονα ημερομηνίας ή τιμής. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setMinorUnit(double value) {#setMinorUnit-double-}
```
public abstract void setMinorUnit(double value)
```

Αντιπροσωπεύει τις δευτερεύουσες μονάδες για τον άξονα ημερομηνίας ή τιμής. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public abstract boolean isAutomaticMinorUnit()
```

Υποδεικνύει εάν η δευτερεύουσα μονάδα του άξονα ορίζεται αυτόματα. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public abstract void setAutomaticMinorUnit(boolean value)
```

Υποδεικνύει εάν η δευτερεύουσα μονάδα του άξονα ορίζεται αυτόματα. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public abstract double getMajorUnit()
```

Αντιπροσωπεύει τις κύριες μονάδες για τον άξονα ημερομηνίας ή τιμής. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setMajorUnit(double value) {#setMajorUnit-double-}
```
public abstract void setMajorUnit(double value)
```

Αντιπροσωπεύει τις κύριες μονάδες για τον άξονα ημερομηνίας ή τιμής. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public abstract boolean isAutomaticMajorUnit()
```

Υποδεικνύει εάν η κύρια μονάδα του άξονα ορίζεται αυτόματα. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public abstract void setAutomaticMajorUnit(boolean value)
```

Δείχνει αν η κύρια μονάδα του άξονα έχει οριστεί αυτόματα. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public abstract boolean isAutomaticMinValue()
```

Δείχνει αν η ελάχιστη τιμή έχει οριστεί αυτόματα. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public abstract void setAutomaticMinValue(boolean value)
```

Δείχνει αν η ελάχιστη τιμή έχει οριστεί αυτόματα. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public abstract double getMinValue()
```

Αναπαριστά την ελάχιστη τιμή στον άξονα τιμών. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double

### setMinValue(double value) {#setMinValue-double-}
```
public abstract void setMinValue(double value)
```

Αναπαριστά την ελάχιστη τιμή στον άξονα τιμών. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public abstract boolean isLogarithmic()
```

Αναπαριστά εάν ο τύπος κλίμακας του άξονα τιμών είναι λογαριθμικός ή όχι. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public abstract void setLogarithmic(boolean value)
```

Αναπαριστά εάν ο τύπος κλίμακας του άξονα τιμών είναι λογαριθμικός ή όχι. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public abstract double getLogBase()
```

Αναπαριστά τη λογαριθμική βάση. Η προεπιλεγμένη τιμή είναι 10. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double

### setLogBase(double value) {#setLogBase-double-}
```
public abstract void setLogBase(double value)
```

Αναπαριστά τη λογαριθμική βάση. Η προεπιλεγμένη τιμή είναι 10. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public abstract boolean isPlotOrderReversed()
```

Αναπαριστά εάν το MS PowerPoint σχεδιάζει τα σημεία δεδομένων από το τελευταίο προς το πρώτο. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public abstract void setPlotOrderReversed(boolean value)
```

Αναπαριστά εάν το MS PowerPoint σχεδιάζει τα σημεία δεδομένων από το τελευταίο προς το πρώτο. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Αναπαριστά εάν ο άξονας είναι ορατός. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Αναπαριστά εάν ο άξονας είναι ορατός. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public abstract int getMajorTickMark()
```

Αναπαριστά τον τύπο του κύριου σημείαμα κλίμακας για τον καθορισμένο άξονα. Ανάγνωση/εγγραφή [TickMarkType](../../com.aspose.slides/tickmarktype).

**Επιστρέφει:**
int

### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public abstract void setMajorTickMark(int value)
```

Αναπαριστά τον τύπο του κύριου σημείαμα κλίμακας για τον καθορισμένο άξονα. Ανάγνωση/εγγραφή [TickMarkType](../../com.aspose.slides/tickmarktype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public abstract int getMinorTickMark()
```

Αναπαριστά τον τύπο του δευτερεύουσας σημείαμα κλίμακας για τον καθορισμένο άξονα. Ανάγνωση/εγγραφή [TickMarkType](../../com.aspose.slides/tickmarktype).

**Επιστρέφει:**
int

### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public abstract void setMinorTickMark(int value)
```

Αναπαριστά τον τύπο του δευτερεύουσας σημείαμα κλίμακας για τον καθορισμένο άξονα. Ανάγνωση/εγγραφή [TickMarkType](../../com.aspose.slides/tickmarktype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public abstract int getTickLabelPosition()
```

Αναπαριστά τη θέση των ετικετών των σημείωνμα κλίμακας στον καθορισμένο άξονα. Ανάγνωση/εγγραφή [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Επιστρέφει:**
int

### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public abstract void setTickLabelPosition(int value)
```

Αναπαριστά τη θέση των ετικετών των σημείωνμα κλίμακας στον καθορισμένο άξονα. Ανάγνωση/εγγραφή [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public abstract int getMajorUnitScale()
```

Αναπαριστά την κλίμακα της κύριας μονάδας για τον άξονα ημερομηνίας. Ανάγνωση/εγγραφή [TimeUnitType](../../com.aspose.slides/timeunittype).

**Επιστρέφει:**
int

### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public abstract void setMajorUnitScale(int value)
```

Αναπαριστά την κλίμακα της κύριας μονάδας για τον άξονα ημερομηνίας. Ανάγνωση/εγγραφή [TimeUnitType](../../com.aspose.slides/timeunittype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public abstract int getMinorUnitScale()
```

Αναπαριστά την κλίμακα της κύριας μονάδας για τον άξονα ημερομηνίας. Ανάγνωση/εγγραφή [TimeUnitType](../../com.aspose.slides/timeunittype).

**Επιστρέφει:**
int

### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public abstract void setMinorUnitScale(int value)
```

Αναπαριστά την κλίμακα της κύριας μονάδας για τον άξονα ημερομηνίας. Ανάγνωση/εγγραφή [TimeUnitType](../../com.aspose.slides/timeunittype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public abstract int getBaseUnitScale()
```

Καθορίζει τη μικρότερη μονάδα χρόνου που αναπαρίσταται στον άξονα ημερομηνίας. Ανάγνωση/εγγραφή [TimeUnitType](../../com.aspose.slides/timeunittype).

**Επιστρέφει:**
int

### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public abstract void setBaseUnitScale(int value)
```

Καθορίζει τη μικρότερη μονάδα χρόνου που αναπαρίσταται στον άξονα ημερομηνίας. Ανάγνωση/εγγραφή [TimeUnitType](../../com.aspose.slides/timeunittype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

Αναπαριστά τη μορφή των δευτεροβάθμιων πλεγμάτων σε άξονα γραφήματος. Μόνο για ανάγνωση [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Επιστρέφει:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

Αναπαριστά τη μορφή των κύριων πλεγμάτων σε άξονα γραφήματος. Μόνο για ανάγνωση [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Επιστρέφει:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public abstract boolean getShowMinorGridLines()
```

Αναπαριστά εάν εμφανίζονται τα δευτερεύοντα πλέγματα. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean

### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public abstract boolean getShowMajorGridLines()
```

Αναπαριστά εάν εμφανίζονται τα κύρια πλέγματα. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean

### getFormat() {#getFormat--}
```
public abstract IAxisFormat getFormat()
```

Αναπαριστά τη μορφή του άξονα. Μόνο για ανάγνωση [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Επιστρέφει:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)

### getTitle() {#getTitle--}
```
public abstract IChartTitle getTitle()
```

Ανακτά τον τίτλο του άξονα. Μόνο για ανάγνωση [IChartTitle](../../com.aspose.slides/icharttitle).

**Επιστρέφει:**
[IChartTitle](../../com.aspose.slides/icharttitle)

### getCrossType() {#getCrossType--}
```
public abstract int getCrossType()
```

Αναπαριστά τον CrossType στον καθορισμένο άξονα όπου διασχίζεται ο άλλος άξονας. Ανάγνωση/εγγραφή [CrossesType](../../com.aspose.slides/crossestype).

**Επιστρέφει:**
int

### setCrossType(int value) {#setCrossType-int-}
```
public abstract void setCrossType(int value)
```

Αναπαριστά τον CrossType στον καθορισμένο άξονα όπου διασχίζεται ο άλλος άξονας. Ανάγνωση/εγγραφή [CrossesType](../../com.aspose.slides/crossestype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Αναπαριστά τη θέση του άξονα. Ανάγνωση/εγγραφή [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Επιστρέφει:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract int getPosition()
```

Αναπαριστά τη θέση του άξονα. Ανάγνωση/εγγραφή [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

Καθορίζει εάν ένας άξονας διαθέτει ορατό τίτλο. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

Καθορίζει εάν ένας άξονας διαθέτει ορατό τίτλο. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

Αναπαριστά τη μορφή συμβολοσειράς για τις ετικέτες του άξονα. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

Αναπαριστά τη μορφή συμβολοσειράς για τις ετικέτες του άξονα. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Δείχνει εάν η μορφή είναι συνδεδεμένη με τα πηγαία δεδομένα. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Δείχνει εάν η μορφή είναι συνδεδεμένη με τα πηγαία δεδομένα. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public abstract float getTickLabelRotationAngle()
```

Αναπαριστά τη γωνία περιστροφής των ετικετών σημείωνμα. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float

### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public abstract void setTickLabelRotationAngle(float value)
```

Αναπαριστά τη γωνία περιστροφής των ετικετών σημείωνμα. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public abstract long getTickLabelSpacing()
```

Καθορίζει πόσες ετικέτες σημείωνμα παραλείπονται μεταξύ των σχεδιασμένων ετικετών. Ανάγνωση/εγγραφή long.

**Επιστρέφει:**
long

### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public abstract void setTickLabelSpacing(long value)
```

Καθορίζει πόσες ετικέτες σημείωνμα παραλείπονται μεταξύ των σχεδιασμένων ετικετών. Ανάγνωση/εγγραφή long.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public abstract boolean isAutomaticTickLabelSpacing()
```

Καθορίζει αυτόματη τιμή διαστήματος ετικετών σημείωνμα. Εάν false: χρησιμοποιεί την ιδιότητα TickLabelSpacing. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public abstract void setAutomaticTickLabelSpacing(boolean value)
```

Καθορίζει αυτόματη τιμή διαστήματος ετικετών σημείωνμα. Εάν false: χρησιμοποιεί την ιδιότητα TickLabelSpacing. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public abstract long getTickMarksSpacing()
```

Καθορίζει πόσα σημείαμα πρέπει να παραλειφθούν πριν σχεδιαστεί το επόμενο. Εφαρμόζεται σε άξονα κατηγορίας ή σειράς. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
long

### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public abstract void setTickMarksSpacing(long value)
```

Καθορίζει πόσα σημείαμα πρέπει να παραλειφθούν πριν σχεδιαστεί το επόμενο. Εφαρμόζεται σε άξονα κατηγορίας ή σειράς. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public abstract boolean isAutomaticTickMarksSpacing()
```

Καθορίζει αυτόματη τιμή διαστήματος σημείωνμα. Εάν false: χρησιμοποιεί την ιδιότητα TickMarksSpacing. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public abstract void setAutomaticTickMarksSpacing(boolean value)
```

Καθορίζει αυτόματη τιμή διαστήματος σημείωνμα. Εάν false: χρησιμοποιεί την ιδιότητα TickMarksSpacing. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public abstract int getLabelOffset()
```

Καθορίζει την απόσταση των ετικετών από τον άξονα. Εφαρμόζεται σε άξονα κατηγορίας ή ημερομηνίας. Η τιμή πρέπει να είναι μεταξύ 0% και 1000%. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int

### setLabelOffset(int value) {#setLabelOffset-int-}
```
public abstract void setLabelOffset(int value)
```

Καθορίζει την απόσταση των ετικετών από τον άξονα. Εφαρμόζεται σε άξονα κατηγορίας ή ημερομηνίας. Η τιμή πρέπει να είναι μεταξύ 0% και 1000%. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public abstract int getCategoryAxisType()
```

Καθορίζει τον τύπο του άξονα κατηγορίας. Ανάγνωση/εγγραφή [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Επιστρέφει:**
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public abstract void setCategoryAxisType(int value)
```

Καθορίζει τον τύπο του άξονα κατηγορίας. Ανάγνωση/εγγραφή [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
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

**Επιστρέφει:**
int

### setAggregationType(int value) {#setAggregationType-int-}
```
public abstract void setAggregationType(int value)
```

Αναπαριστά τον τύπο συγκέντρωσης του άξονα κατηγορίας (ομαδοποίηση). Εφαρμόζεται σε κατηγορία. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getBinWidth() {#getBinWidth--}
```
public abstract double getBinWidth()
```

Καθορίζει το πλάτος του κουβά όταν η τιμή της ιδιότητας AggregationType ορίζεται σε AxisAggregationType.ByBinWidth. Εφαρμόζεται σε άξονες κατηγορίας. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto.

**Επιστρέφει:**
double
### setBinWidth(double value) {#setBinWidth-double-}
```
public abstract void setBinWidth(double value)
```

Καθορίζει το πλάτος του κουβά όταν η τιμή της ιδιότητας AggregationType ορίζεται σε AxisAggregationType.ByBinWidth. Εφαρμόζεται σε άξονες κατηγορίας. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public abstract long getNumberOfBins()
```

Καθορίζει τον αριθμό των κουβών όταν η τιμή της ιδιότητας AggregationType ορίζεται σε AxisAggregationType.ByNumberOfBins. Εφαρμόζεται σε άξονες κατηγορίας. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto.

**Επιστρέφει:**
long
### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public abstract void setNumberOfBins(long value)
```

Καθορίζει τον αριθμό των κουβών όταν η τιμή της ιδιότητας AggregationType ορίζεται σε AxisAggregationType.ByNumberOfBins. Εφαρμόζεται σε άξονες κατηγορίας. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public abstract boolean isOverflowBin()
```

Καθορίζει αν εφαρμόζεται overflow bucket. Χρησιμοποιήστε τις IsAutomaticOverflowBin και OverflowBin για να προσαρμόσετε την τιμή του overflow bucket.

**Επιστρέφει:**
boolean
### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public abstract void setOverflowBin(boolean value)
```

Καθορίζει αν εφαρμόζεται overflow bucket. Χρησιμοποιήστε τις IsAutomaticOverflowBin και OverflowBin για να προσαρμόσετε την τιμή του overflow bucket.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public abstract boolean isAutomaticOverflowBin()
```

Καθορίζει αυτόματη τιμή overflow bucket. Αν είναι false: χρησιμοποιήστε την ιδιότητα OverflowBin.

**Επιστρέφει:**
boolean
### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public abstract void setAutomaticOverflowBin(boolean value)
```

Καθορίζει αυτόματη τιμή overflow bucket. Αν είναι false: χρησιμοποιήστε την ιδιότητα OverflowBin.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public abstract double getOverflowBin()
```

Καθορίζει την προσαρμοσμένη τιμή του overflow bucket. Εφαρμόζεται όταν η ιδιότητα IsAutomaticOverflowBin ορίζεται σε false και η ιδιότητα IsOverflowBin είναι true.

**Επιστρέφει:**
double
### setOverflowBin(double value) {#setOverflowBin-double-}
```
public abstract void setOverflowBin(double value)
```

Καθορίζει την προσαρμοσμένη τιμή του overflow bucket. Εφαρμόζεται όταν η ιδιότητα IsAutomaticOverflowBin ορίζεται σε false και η ιδιότητα IsOverflowBin είναι true.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public abstract boolean isUnderflowBin()
```

Καθορίζει αν εφαρμόζεται underflow bucket. Χρησιμοποιήστε τις IsAutomaticUnderflowBin και UnderflowBin για να προσαρμόσετε την τιμή του underflow bucket.

**Επιστρέφει:**
boolean
### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public abstract void setUnderflowBin(boolean value)
```

Καθορίζει αν εφαρμόζεται underflow bucket. Χρησιμοποιήστε τις IsAutomaticUnderflowBin και UnderflowBin για να προσαρμόσετε την τιμή του underflow bucket.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public abstract boolean isAutomaticUnderflowBin()
```

Καθορίζει αυτόματη τιμή underflow bucket. Αν είναι false: χρησιμοποιήστε την ιδιότητα UnderflowBin.

**Επιστρέφει:**
boolean
### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public abstract void setAutomaticUnderflowBin(boolean value)
```

Καθορίζει αυτόματη τιμή underflow bucket. Αν είναι false: χρησιμοποιήστε την ιδιότητα UnderflowBin.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public abstract double getUnderflowBin()
```

Καθορίζει την προσαρμοσμένη τιμή του underflow bucket. Εφαρμόζεται όταν η ιδιότητα IsAutomaticUnderflowBin ορίζεται σε false και η ιδιότητα IsUnderflowBin είναι true.

**Επιστρέφει:**
double
### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public abstract void setUnderflowBin(double value)
```

Καθορίζει την προσαρμοσμένη τιμή του underflow bucket. Εφαρμόζεται όταν η ιδιότητα IsAutomaticUnderflowBin ορίζεται σε false και η ιδιότητα IsUnderflowBin είναι true.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |