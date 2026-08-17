---
title: Axis
second_title: Αναφορά API Aspose.Slides για Java
description: Περιβάλλει το αντικείμενο που αντιπροσωπεύει τον άξονα ενός γραφήματος.
type: docs
url: /el/com.aspose.slides/axis/
---
**Κληρονομικότητα:**  
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι Υλοποιημένες Διεπαφές:**  
[com.aspose.slides.IAxis](../../com.aspose.slides/iaxis)  
```
public class Axis extends DomObject<AxesManager> implements IAxis
```

Περιλαμβάνει το αντικείμενο που αντιπροσωπεύει τον άξονα ενός διαγράμματος.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getChart()](#getChart--) | Επιστρέφει το γονικό διάγραμμα. |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Αντιπροσωπεύει εάν ο άξονας τιμών διασχίζει τον άξονα κατηγοριών μεταξύ των κατηγοριών. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Αντιπροσωπεύει εάν ο άξονας τιμών διασχίζει τον άξονα κατηγοριών μεταξύ των κατηγοριών. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Καθορίζει τον τύπο του άξονα κατηγοριών. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Καθορίζει τον τύπο του άξονα κατηγοριών. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Ορίζει την ιδιότητα IAxis.CategoryAxisType με τιμή που καθορίζεται αυτόματα βάσει των δεδομένων του άξονα. |
| [getCrossAt()](#getCrossAt--) | Αντιπροσωπεύει το σημείο στον άξονα όπου ο κάθετος άξονας τον διασχίζει. |
| [setCrossAt(float value)](#setCrossAt-float-) | Αντιπροσωπεύει το σημείο στον άξονα όπου ο κάθετος άξονας τον διασχίζει. |
| [getDisplayUnit()](#getDisplayUnit--) | Καθορίζει την τιμή κλίμακας των μονάδων εμφάνισης για τον άξονα τιμών. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Καθορίζει την τιμή κλίμακας των μονάδων εμφάνισης για τον άξονα τιμών. |
| [getActualMaxValue()](#getActualMaxValue--) | Καθορίζει την πραγματική μέγιστη τιμή στον άξονα. |
| [getActualMinValue()](#getActualMinValue--) | Καθορίζει την πραγματική ελάχιστη τιμή στον άξονα. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Καθορίζει την πραγματική κύρια μονάδα του άξονα. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Καθορίζει την πραγματική δευτερεύουσα μονάδα του άξονα. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Καθορίζει την πραγματική κλίμακα της κύριας μονάδας του άξονα. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Καθορίζει την πραγματική κλίμακα της δευτερεύουσας μονάδας του άξονα. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Δείχνει εάν η μέγιστη τιμή καθορίζεται αυτόματα. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Δείχνει εάν η μέγιστη τιμή καθορίζεται αυτόματα. |
| [getMaxValue()](#getMaxValue--) | Αντιπροσωπεύει τη μέγιστη τιμή στον άξονα τιμών. |
| [setMaxValue(double value)](#setMaxValue-double-) | Αντιπροσωπεύει τη μέγιστη τιμή στον άξονα τιμών. |
| [getMinorUnit()](#getMinorUnit--) | Αντιπροσωπεύει τις δευτερεύουσες μονάδες για τον άξονα ημερομηνίας ή τιμής. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Αντιπροσωπεύει τις δευτερεύουσες μονάδες για τον άξονα ημερομηνίας ή τιμής. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Δείχνει εάν η δευτερεύουσα μονάδα του άξονα καθορίζεται αυτόματα. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Δείχνει εάν η δευτερεύουσα μονάδα του άξονα καθορίζεται αυτόματα. |
| [getMajorUnit()](#getMajorUnit--) | Αντιπροσωπεύει τις κύριες μονάδες για τον άξονα ημερομηνίας ή τιμής. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Αντιπροσωπεύει τις κύριες μονάδες για τον άξονα ημερομηνίας ή τιμής. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Δείχνει εάν η κύρια μονάδα του άξονα καθορίζεται αυτόματα. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Δείχνει εάν η κύρια μονάδα του άξονα καθορίζεται αυτόματα. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Δείχνει εάν η ελάχιστη τιμή καθορίζεται αυτόματα. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Δείχνει εάν η ελάχιστη τιμή καθορίζεται αυτόματα. |
| [getMinValue()](#getMinValue--) | Αντιπροσωπεύει την ελάχιστη τιμή στον άξονα τιμών. |
| [setMinValue(double value)](#setMinValue-double-) | Αντιπροσωπεύει την ελάχιστη τιμή στον άξονα τιμών. |
| [isLogarithmic()](#isLogarithmic--) | Αντιπροσωπεύει εάν ο τύπος κλίμακας του άξονα τιμών είναι λογαριθμικός ή όχι. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Αντιπροσωπεύει εάν ο τύπος κλίμακας του άξονα τιμών είναι λογαριθμικός ή όχι. |
| [getLogBase()](#getLogBase--) | Αντιπροσωπεύει τη λογαριθμική βάση. |
| [setLogBase(double value)](#setLogBase-double-) | Αντιπροσωπεύει τη λογαριθμική βάση. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Αντιπροσωπεύει εάν το MS PowerPoint σχεδιάζει τα σημεία δεδομένων από το τελευταίο προς το πρώτο. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Αντιπροσωπεύει εάν το MS PowerPoint σχεδιάζει τα σημεία δεδομένων από το τελευταίο προς το πρώτο. |
| [isVisible()](#isVisible--) | Αντιπροσωπεύει εάν ο άξονας είναι ορατός. |
| [setVisible(boolean value)](#setVisible-boolean-) | Αντιπροσωπεύει εάν ο άξονας είναι ορατός. |
| [getMajorTickMark()](#getMajorTickMark--) | Αντιπροσωπεύει τον τύπο της κύριας γραμμής σήμανσης για τον καθορισμένο άξονα. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Αντιπροσωπεύει τον τύπο της κύριας γραμμής σήμανσης για τον καθορισμένο άξονα. |
| [getMinorTickMark()](#getMinorTickMark--) | Αντιπροσωπεύει τον τύπο της δευτερεύουσας γραμμής σήμανσης για τον καθορισμένο άξονα. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Αντιπροσωπεύει τον τύπο της δευτερεύουσας γραμμής σήμανσης για τον καθορισμένο άξονα. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Αντιπροσωπεύει τη θέση των ετικετών των γραμμών σήμανσης στον καθορισμένο άξονα. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Αντιπροσωπεύει τη θέση των ετικετών των γραμμών σήμανσης στον καθορισμένο άξονα. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Αντιπροσωπεύει την κλίμακα της κύριας μονάδας για τον άξονα ημερομηνίας. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Αντιπροσωπεύει την κλίμακα της κύριας μονάδας για τον άξονα ημερομηνίας. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Αντιπροσωπεύει την κλίμακα της κύριας μονάδας για τον άξονα ημερομηνίας. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Αντιπροσωπεύει την κλίμακα της κύριας μονάδας για τον άξονα ημερομηνίας. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Καθορίζει τη μικρότερη μονάδα χρόνου που αναπαρίσταται στον άξονα ημερομηνίας. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Καθορίζει τη μικρότερη μονάδα χρόνου που αναπαρίσταται στον άξονα ημερομηνίας. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Αντιπροσωπεύει τη μορφή των μικρών γραμμών πλέγματος σε άξονα διαγράμματος. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Αντιπροσωπεύει τη μορφή των μεγάλων γραμμών πλέγματος σε άξονα διαγράμματος. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Για να κρύψετε τις μικρές γραμμές πλέγματος, ορίστε MinorGridLinesFormat.Line.FillFormat.FillType σε FillType.NoFill. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Για να κρύψετε τις μεγάλες γραμμές πλέγματος, ορίστε MajorGridLinesFormat.Line.FillFormat.FillType σε FillType.NoFill. |
| [getFormat()](#getFormat--) | Αντιπροσωπεύει τη μορφή του άξονα. |
| [getTextFormat()](#getTextFormat--) | Αντιπροσωπεύει τη μορφή του κειμένου. |
| [getTitle()](#getTitle--) | Ανακτά τον τίτλο του άξονα. |
| [getCrossType()](#getCrossType--) | Αντιπροσωπεύει τον τύπο διασχισμού στο καθορισμένο άξονα όπου διασχίζει ο άλλος άξονας. |
| [setCrossType(int value)](#setCrossType-int-) | Αντιπροσωπεύει τον τύπο διασχισμού στο καθορισμένο άξονα όπου διασχίζει ο άλλος άξονας. |
| [getPosition()](#getPosition--) | Αντιπροσωπεύει τη θέση του άξονα. |
| [setPosition(int value)](#setPosition-int-) | Αντιπροσωπεύει τη θέση του άξονα. |
| [hasTitle()](#hasTitle--) | Καθορίζει εάν ένας άξονας έχει ορατό τίτλο. |
| [setTitle(boolean value)](#setTitle-boolean-) | Καθορίζει εάν ένας άξονας έχει ορατό τίτλο. |
| [getNumberFormat()](#getNumberFormat--) | Αντιπροσωπεύει τη συμβολοσειρά μορφοποίησης για τις ετικέτες άξονα. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Αντιπροσωπεύει τη συμβολοσειρά μορφοποίησης για τις ετικέτες άξονα. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Δείχνει εάν η μορφή είναι συνδεδεμένα δεδομένα πηγής. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Δείχνει εάν η μορφή είναι συνδεδεμένα δεδομένα πηγής. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Αντιπροσωπεύει τη γωνία περιστροφής των ετικετών σήμανσης. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Αντιπροσωπεύει τη γωνία περιστροφής των ετικετών σήμανσης. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Καθορίζει πόσες ετικέτες σήμανσης να παραλείψετε μεταξύ των ετικετών που σχεδιάζονται. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Καθορίζει πόσες ετικέτες σήμανσης να παραλείψετε μεταξύ των ετικετών που σχεδιάζονται. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Καθορίζει την τιμή αυτόματης απόστασης ετικετών σήμανσης. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Καθορίζει την τιμή αυτόματης απόστασης ετικετών σήμανσης. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Καθορίζει πόσες γραμμές σήμανσης θα παραλειφθούν πριν σχεδιαστεί η επόμενη. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Καθορίζει πόσες γραμμές σήμανσης θα παραλειφθούν πριν σχεδιαστεί η επόμενη. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Καθορίζει την τιμή αυτόματης απόστασης των γραμμών σήμανσης. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Καθορίζει την τιμή αυτόματης απόστασης των γραμμών σήμανσης. |
| [getLabelOffset()](#getLabelOffset--) | Καθορίζει την απόσταση των ετικετών από τον άξονα. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Καθορίζει την απόσταση των ετικετών από τον άξονα. |
| [getAggregationType()](#getAggregationType--) | Αντιπροσωπεύει τον τύπο συγκέντρωσης του άξονα κατηγορίας (ομαδοποίηση). |
| [setAggregationType(int value)](#setAggregationType-int-) | Αντιπροσωπεύει τον τύπο συγκέντρωσης του άξονα κατηγορίας (ομαδοποίηση). |
| [getBinWidth()](#getBinWidth--) | Καθορίζει το πλάτος του κουβά όταν η ιδιότητα AggregationType έχει τιμή AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | Καθορίζει το πλάτος του κουβά όταν η ιδιότητα AggregationType έχει τιμή AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | Καθορίζει τον αριθμό των κουβάδων όταν η ιδιότητα AggregationType έχει τιμή AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Καθορίζει τον αριθμό των κουβάδων όταν η ιδιότητα AggregationType έχει τιμή AxisAggregationType.ByNumberOfBins. |
| [isOverflowBin()](#isOverflowBin--) | Καθορίζει εάν εφαρμόζεται υπερβολικός κουβάς. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | Καθορίζει εάν εφαρμόζεται υπερβολικός κουβάς. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | Καθορίζει την αυτόματη τιμή υπερβολικού κουβά. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | Καθορίζει την αυτόματη τιμή υπερβολικού κουβά. |
| [getOverflowBin()](#getOverflowBin--) | Καθορίζει την προσαρμοσμένη τιμή υπερβολικού κουβά. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | Καθορίζει την προσαρμοσμένη τιμή υπερβολικού κουβά. |
| [isUnderflowBin()](#isUnderflowBin--) | Καθορίζει εάν εφαρμόζεται υποβαθμιστικός κουβάς. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | Καθορίζει εάν εφαρμόζεται υποβαθμιστικός κουβάς. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | Καθορίζει την αυτόματη τιμή υποβαθμιστικού κουβά. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | Καθορίζει την αυτόματη τιμή υποβαθμιστικού κουβά. |
| [getUnderflowBin()](#getUnderflowBin--) | Καθορίζει την προσαρμοσμένη τιμή υποβαθμιστικού κουβά. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | Καθορίζει την προσαρμοσμένη τιμή υποβαθμιστικού κουβά. |
| [getSlide()](#getSlide--) | Επιστρέφει τη γονική διαφάνεια ενός FillFormat. |
| [getPresentation()](#getPresentation--) | Επιστρέφει την γονική παρουσίαση ενός FillFormat. |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Επιστρέφει το γονικό διάγραμμα. Μόνο για ανάγνωση [IChart](../../com.aspose.slides/ichart).

**Επιστρέφει:**  
[IChart](../../com.aspose.slides/ichart)

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public final boolean getAxisBetweenCategories()
```

Αντιπροσωπεύει εάν ο άξονας τιμών διασχίζει τον άξονα κατηγοριών μεταξύ των κατηγοριών. Αυτή η ιδιότητα εφαρμόζεται μόνο σε άξονες κατηγοριών και δεν ισχύει για 3-Δ διαγράμματα. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**  
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public final void setAxisBetweenCategories(boolean value)
```

Αντιπροσωπεύει εάν ο άξονας τιμών διασχίζει τον άξονα κατηγοριών μεταξύ των κατηγοριών. Αυτή η ιδιότητα εφαρμόζεται μόνο σε άξονες κατηγοριών και δεν ισχύει για 3-Δ διαγράμματα. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public final int getCategoryAxisType()
```

Καθορίζει τον τύπο του άξονα κατηγοριών. Ανάγνωση/εγγραφή [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Επιστρέφει:**  
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public final void setCategoryAxisType(int value)
```

Καθορίζει τον τύπο του άξονα κατηγοριών. Ανάγνωση/εγγραφή [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public final void setCategoryAxisTypeAutomatically()
```

Ορίζει την ιδιότητα IAxis.CategoryAxisType με τιμή που καθορίζεται αυτόματα βάσει των δεδομένων του άξονα.

### getCrossAt() {#getCrossAt--}
```
public final float getCrossAt()
```

Αντιπροσωπεύει το σημείο στον άξονα όπου ο κάθετος άξονας τον διασχίζει. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**  
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public final void setCrossAt(float value)
```

Αντιπροσωπεύει το σημείο στον άξονα όπου ο κάθετος άξονας τον διασχίζει. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public final int getDisplayUnit()
```

Καθορίζει την τιμή κλίμακας των μονάδων εμφάνισης για τον άξονα τιμών. Ανάγνωση/εγγραφή [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Επιστρέφει:**  
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public final void setDisplayUnit(int value)
```

Καθορίζει την τιμή κλίμακας των μονάδων εμφάνισης για τον άξονα τιμών. Ανάγνωση/εγγραφή [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public final double getActualMaxValue()
```

Καθορίζει την πραγματική μέγιστη τιμή στον άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να πάρετε την πραγματική τιμή.

**Επιστρέφει:**  
double

### getActualMinValue() {#getActualMinValue--}
```
public final double getActualMinValue()
```

Καθορίζει την πραγματική ελάχιστη τιμή στον άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να πάρετε την πραγματική τιμή.

**Επιστρέφει:**  
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public final double getActualMajorUnit()
```

Καθορίζει την πραγματική κύρια μονάδα του άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να πάρετε την πραγματική τιμή.

**Επιστρέφει:**  
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public final double getActualMinorUnit()
```

Καθορίζει την πραγματική δευτερεύουσα μονάδα του άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να πάρετε την πραγματική τιμή.

**Επιστρέφει:**  
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public final int getActualMajorUnitScale()
```

Καθορίζει την πραγματική κλίμακα της κύριας μονάδας του άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να πάρετε την πραγματική τιμή.

**Επιστρέφει:**  
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public final int getActualMinorUnitScale()
```

Καθορίζει την πραγματική κλίμακα της δευτερεύουσας μονάδας του άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να πάρετε την πραγματική τιμή.

**Επιστρέφει:**  
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public final boolean isAutomaticMaxValue()
```

Δείχνει εάν η μέγιστη τιμή καθορίζεται αυτόματα. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**  
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public final void setAutomaticMaxValue(boolean value)
```

Δείχνει εάν η μέγιστη τιμή καθορίζεται αυτόματα. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public final double getMaxValue()
```

Αντιπροσωπεύει τη μέγιστη τιμή στον άξονα τιμών. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**  
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public final void setMaxValue(double value)
```

Αντιπροσωπεύει τη μέγιστη τιμή στον άξονα τιμών. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public final double getMinorUnit()
```

Αντιπροσωπεύει τις δευτερεύουσες μονάδες για τον άξονα ημερομηνίας ή τιμής. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**  
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public final void setMinorUnit(double value)
```

Αντιπροσωπεύει τις δευτερεύουσες μονάδες για τον άξονα ημερομηνίας ή τιμής. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public final boolean isAutomaticMinorUnit()
```
Δείχνει αν η μικρή μονάδα του άξονα εκχωρείται αυτόματα. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public final void setAutomaticMinorUnit(boolean value)
```

Δείχνει αν η μικρή μονάδα του άξονα εκχωρείται αυτόματα. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public final double getMajorUnit()
```

Αναπαριστά τις μεγάλες μονάδες για την άξονα ημερομηνίας ή τιμής. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setMajorUnit(double value) {#setMajorUnit-double-}
```
public final void setMajorUnit(double value)
```

Αναπαριστά τις μεγάλες μονάδες για την άξονα ημερομηνίας ή τιμής. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public final boolean isAutomaticMajorUnit()
```

Δείχνει αν η μεγάλη μονάδα του άξονα εκχωρείται αυτόματα. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public final void setAutomaticMajorUnit(boolean value)
```

Δείχνει αν η μεγάλη μονάδα του άξονα εκχωρείται αυτόματα. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public final boolean isAutomaticMinValue()
```

Δείχνει αν η ελάχιστη τιμή εκχωρείται αυτόματα. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public final void setAutomaticMinValue(boolean value)
```

Δείχνει αν η ελάχιστη τιμή εκχωρείται αυτόματα. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public final double getMinValue()
```

Αναπαριστά την ελάχιστη τιμή στον άξονα τιμών. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setMinValue(double value) {#setMinValue-double-}
```
public final void setMinValue(double value)
```

Αναπαριστά την ελάχιστη τιμή στον άξονα τιμών. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public final boolean isLogarithmic()
```

Αναπαριστά αν ο τύπος κλίμακας του άξονα τιμών είναι λογαριθμικός ή όχι. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public final void setLogarithmic(boolean value)
```

Αναπαριστά αν ο τύπος κλίμακας του άξονα τιμών είναι λογαριθμικός ή όχι. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public final double getLogBase()
```

Αναπαριστά τη λογαριθμική βάση. Η προεπιλεγμένη τιμή είναι 10. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setLogBase(double value) {#setLogBase-double-}
```
public final void setLogBase(double value)
```

Αναπαριστά τη λογαριθμική βάση. Η προεπιλεγμένη τιμή είναι 10. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public final boolean isPlotOrderReversed()
```

Αναπαριστά αν το MS PowerPoint σχεδιάζει τα σημεία δεδομένων από το τελευταίο προς το πρώτο. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public final void setPlotOrderReversed(boolean value)
```

Αναπαριστά αν το MS PowerPoint σχεδιάζει τα σημεία δεδομένων από το τελευταίο προς το πρώτο. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

Αναπαριστά αν ο άξονας είναι ορατός. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

Αναπαριστά αν ο άξονας είναι ορατός. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public final int getMajorTickMark()
```

Αναπαριστά τον τύπο του κύριου δεικτοδούλιου για τον καθορισμένο άξονα. Ανάγνωση/εγγραφή [TickMarkType](../../com.aspose.slides/tickmarktype).

**Επιστρέφει:**
int
### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public final void setMajorTickMark(int value)
```

Αναπαριστά τον τύπο του κύριου δεικτοδούλιου για τον καθορισμένο άξονα. Ανάγνωση/εγγραφή [TickMarkType](../../com.aspose.slides/tickmarktype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public final int getMinorTickMark()
```

Αναπαριστά τον τύπο του δευτερεύοντος δεικτοδούλιου για τον καθορισμένο άξονα. Ανάγνωση/εγγραφή [TickMarkType](../../com.aspose.slides/tickmarktype).

**Επιστρέφει:**
int
### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public final void setMinorTickMark(int value)
```

Αναπαριστά τον τύπο του δευτερεύοντος δεικτοδούλιου για τον καθορισμένο άξονα. Ανάγνωση/εγγραφή [TickMarkType](../../com.aspose.slides/tickmarktype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public final int getTickLabelPosition()
```

Αναπαριστά τη θέση των ετικετών των δεικτοδούλιων στον καθορισμένο άξονα. Ανάγνωση/εγγραφή [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Επιστρέφει:**
int
### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public final void setTickLabelPosition(int value)
```

Αναπαριστά τη θέση των ετικετών των δεικτοδούλιων στον καθορισμένο άξονα. Ανάγνωση/εγγραφή [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public final int getMajorUnitScale()
```

Αναπαριστά την κλίμακα της μεγάλης μονάδας για την άξονα ημερομηνίας. Ανάγνωση/εγγραφή [TimeUnitType](../../com.aspose.slides/timeunittype).

**Επιστρέφει:**
int
### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public final void setMajorUnitScale(int value)
```

Αναπαριστά την κλίμακα της μεγάλης μονάδας για την άξονα ημερομηνίας. Ανάγνωση/εγγραφή [TimeUnitType](../../com.aspose.slides/timeunittype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public final int getMinorUnitScale()
```

Αναπαριστά την κλίμακα της μικρής μονάδας για την άξονα ημερομηνίας. Ανάγνωση/εγγραφή [TimeUnitType](../../com.aspose.slides/timeunittype).

**Επιστρέφει:**
int
### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public final void setMinorUnitScale(int value)
```

Αναπαριστά την κλίμακα της μικρής μονάδας για την άξονα ημερομηνίας. Ανάγνωση/εγγραφή [TimeUnitType](../../com.aspose.slides/timeunittype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public final int getBaseUnitScale()
```

Καθορίζει τη μικρότερη μονάδα χρόνου που αναπαρίσταται στην άξονα ημερομηνίας. Ανάγνωση/εγγραφή [TimeUnitType](../../com.aspose.slides/timeunittype).

**Επιστρέφει:**
int
### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public final void setBaseUnitScale(int value)
```

Καθορίζει τη μικρότερη μονάδα χρόνου που αναπαρίσταται στην άξονα ημερομηνίας. Ανάγνωση/εγγραφή [TimeUnitType](../../com.aspose.slides/timeunittype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public final IChartLinesFormat getMinorGridLinesFormat()
```

Αναπαριστά τη μορφή των μικρών γραμμών πλέγματος σε άξονα διαγράμματος. Μόνο για ανάγνωση [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Επιστρέφει:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public final IChartLinesFormat getMajorGridLinesFormat()
```

Αναπαριστά τη μορφή των μεγάλων γραμμών πλέγματος σε άξονα διαγράμματος. Μόνο για ανάγνωση [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Επιστρέφει:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public final boolean getShowMinorGridLines()
```

Για απόκρυψη μικρής γραμμής πλέγματος ορίστε MinorGridLinesFormat.Line.FillFormat.FillType σε FillType.NoFill. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean
### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public final boolean getShowMajorGridLines()
```

Για απόκρυψη μεγάλης γραμμής πλέγματος ορίστε MajorGridLinesFormat.Line.FillFormat.FillType σε FillType.NoFill. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean
### getFormat() {#getFormat--}
```
public final IAxisFormat getFormat()
```

Αναπαριστά τη μορφή του άξονα. Μόνο για ανάγνωση [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Επιστρέφει:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Αναπαριστά τη μορφή του κειμένου. Μόνο για ανάγνωση [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Επιστρέφει:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getTitle() {#getTitle--}
```
public final IChartTitle getTitle()
```

Λαμβάνει τον τίτλο του άξονα. Μόνο για ανάγνωση [IChartTitle](../../com.aspose.slides/icharttitle).

**Επιστρέφει:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### getCrossType() {#getCrossType--}
```
public final int getCrossType()
```

Αναπαριστά το CrossType στον καθορισμένο άξονα όπου ο άλλος άξονας διασχίζει. Ανάγνωση/εγγραφή [CrossesType](../../com.aspose.slides/crossestype).

**Επιστρέφει:**
int
### setCrossType(int value) {#setCrossType-int-}
```
public final void setCrossType(int value)
```

Αναπαριστά το CrossType στον καθορισμένο άξονα όπου ο άλλος άξονας διασχίζει. Ανάγνωση/εγγραφή [CrossesType](../../com.aspose.slides/crossestype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```

Αναπαριστά τη θέση του άξονα. Ανάγνωση/εγγραφή [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Επιστρέφει:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Αναπαριστά τη θέση του άξονα. Ανάγνωση/εγγραφή [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

Καθορίζει αν ένας άξονας έχει ορατό τίτλο. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

Καθορίζει αν ένας άξονας έχει ορατό τίτλο. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

Αναπαριστά τη συμβολοσειρά μορφής για τις ετικέτες του άξονα. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

Αναπαριστά τη συμβολοσειρά μορφής για τις ετικέτες του άξονα. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

Δείχνει αν η μορφή είναι συνδεδεμένη με τα δεδομένα προέλευσης. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

Δείχνει αν η μορφή είναι συνδεδεμένη με τα δεδομένα προέλευσης. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public final float getTickLabelRotationAngle()
```

Αναπαριστά τη γωνία περιστροφής των ετικετών των δεικτοδούλιων. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public final void setTickLabelRotationAngle(float value)
```

Αναπαριστά τη γωνία περιστροφής των ετικετών των δεικτοδούλιων. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public final long getTickLabelSpacing()
```

Καθορίζει πόσες ετικέτες δεικτοδούλιου παραλείπονται μεταξύ των ετικετών που σχεδιάζονται. Εφαρμόζεται σε άξονα κατηγορίας ή σειράς. Ανάγνωση/εγγραφή long.

**Επιστρέφει:**
long
### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public final void setTickLabelSpacing(long value)
```

Κατο

ρίζει πόσες ετικέτες δεικτοδούλιου παραλείπονται μεταξύ των ετικετών που σχεδιάζονται. Εφαρμόζεται σε άξονα κατηγορίας ή σειράς. Ανάγνωση/εγγραφή long.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public final boolean isAutomaticTickLabelSpacing()
```

Καθορίζει την αυτόματη τιμή απόστασης ετικετών δεικτοδούλιου. Αν false: χρησιμοποιεί την ιδιότητα TickLabelSpacing. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public final void setAutomaticTickLabelSpacing(boolean value)
```

Καθορίζει την αυτόματη τιμή απόστασης ετικετών δεικτοδούλιου. Αν false: χρησιμοποιεί την ιδιότητα TickLabelSpacing. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public final long getTickMarksSpacing()
```

Καθορίζει πόσοι δεικτοδούλιαιι θα παραλείπονται πριν σχεδιαστεί ο επόμενος. Εφαρμόζεται σε άξονα κατηγορίας ή σειράς. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
long
### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public final void setTickMarksSpacing(long value)
```

Καθορίζει πόσοι δεικτοδούλιαιι θα παραλείπονται πριν σχεδιαστεί ο επόμενος. Εφαρμόζεται σε άξονα κατηγορίας ή σειράς. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public final boolean isAutomaticTickMarksSpacing()
```

Καθορίζει την αυτόματη τιμή απόστασης δεικτοδούλιων. Αν false: χρησιμοποιεί την ιδιότητα TickMarksSpacing. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public final void setAutomaticTickMarksSpacing(boolean value)
```

Καθορίζει την αυτόματη τιμή απόστασης δεικτοδούλιων. Αν false: χρησιμοποιεί την ιδιότητα TickMarksSpacing. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public final int getLabelOffset()
```

Καθορίζει την απόσταση των ετικετών από τον άξονα. Εφαρμόζεται σε άξονα κατηγορίας ή ημερομηνίας. Η τιμή πρέπει να είναι μεταξύ 0% και 1000%. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int
### setLabelOffset(int value) {#setLabelOffset-int-}
```
public final void setLabelOffset(int value)
```

Καθορίζει την απόσταση των ετικετών από τον άξονα. Εφαρμόζεται σε άξονα κατηγορίας ή ημερομηνίας. Η τιμή πρέπει να είναι μεταξύ 0% και 1000%. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getAggregationType() {#getAggregationType--}
```
public final int getAggregationType()
```


Αναπαριστά τον τύπο συγκέντρωσης του άξονα κατηγορίας (ομαδοποίηση). Εφαρμόζεται στην κατηγορία. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto.

**Επιστρέφει:**
int
### setAggregationType(int value) {#setAggregationType-int-}
```
public final void setAggregationType(int value)
```


Αναπαριστά τον τύπο συγκέντρωσης του άξονα κατηγορίας (ομαδοποίηση). Εφαρμόζεται στην κατηγορία. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public final double getBinWidth()
```


Καθορίζει το πλάτος του κουβά όταν η ιδιότητα AggregationType είναι ορισμένη σε AxisAggregationType.ByBinWidth. Εφαρμόζεται στους άξονες κατηγορίας. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto.

**Επιστρέφει:**
double
### setBinWidth(double value) {#setBinWidth-double-}
```
public final void setBinWidth(double value)
```


Καθορίζει το πλάτος του κουβά όταν η ιδιότητα AggregationType είναι ορισμένη σε AxisAggregationType.ByBinWidth. Εφαρμόζεται στους άξονες κατηγορίας. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public final long getNumberOfBins()
```


Καθορίζει τον αριθμό των κουβάδων όταν η ιδιότητα AggregationType είναι ορισμένη σε AxisAggregationType.ByNumberOfBins. Εφαρμόζεται στους άξονες κατηγορίας. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto.

**Επιστρέφει:**
long
### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public final void setNumberOfBins(long value)
```


Καθορίζει τον αριθμό των κουβάδων όταν η ιδιότητα AggregationType είναι ορισμένη σε AxisAggregationType.ByNumberOfBins. Εφαρμόζεται στους άξονες κατηγορίας. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public final boolean isOverflowBin()
```


Καθορίζει εάν εφαρμόζεται κουβάς υπερχείλισης. Χρησιμοποιήστε τις ιδιότητες IsAutomaticOverflowBin και OverflowBin για να ρυθμίσετε την τιμή του κουβά υπερχείλισης.

**Επιστρέφει:**
boolean
### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public final void setOverflowBin(boolean value)
```


Καθορίζει εάν εφαρμόζεται κουβάς υπερχείλισης. Χρησιμοποιήστε τις ιδιότητες IsAutomaticOverflowBin και OverflowBin για να ρυθμίσετε την τιμή του κουβά υπερχείλισης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public final boolean isAutomaticOverflowBin()
```


Καθορίζει την αυτόματη τιμή του κουβά υπερχείλισης. Εάν είναι false: χρησιμοποιήστε την ιδιότητα OverflowBin.

**Επιστρέφει:**
boolean
### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public final void setAutomaticOverflowBin(boolean value)
```


Καθορίζει την αυτόματη τιμή του κουβά υπερχείλισης. Εάν είναι false: χρησιμοποιήστε την ιδιότητα OverflowBin.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public final double getOverflowBin()
```


Καθορίζει προσαρμοσμένη τιμή του κουβά υπερχείλισης. Εφαρμόζεται όταν η ιδιότητα IsAutomaticOverflowBin είναι false και η ιδιότητα IsOverflowBin είναι true.

**Επιστρέφει:**
double
### setOverflowBin(double value) {#setOverflowBin-double-}
```
public final void setOverflowBin(double value)
```


Καθορίζει προσαρμοσμένη τιμή του κουβά υπερχείλισης. Εφαρμόζεται όταν η ιδιότητα IsAutomaticOverflowBin είναι false και η ιδιότητα IsOverflowBin είναι true.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public final boolean isUnderflowBin()
```


Καθορίζει εάν εφαρμόζεται κουβάς υποροής. Χρησιμοποιήστε τις ιδιότητες IsAutomaticUnderflowBin και UnderflowBin για να ρυθμίσετε την τιμή του κουβά υποροής.

**Επιστρέφει:**
boolean
### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public final void setUnderflowBin(boolean value)
```


Καθορίζει εάν εφαρμόζεται κουβάς υποροής. Χρησιμοποιήστε τις ιδιότητες IsAutomaticUnderflowBin και UnderflowBin για να ρυθμίσετε την τιμή του κουβά υποροής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public final boolean isAutomaticUnderflowBin()
```


Καθορίζει την αυτόματη τιμή του κουβά υποροής. Εάν είναι false: χρησιμοποιήστε την ιδιότητα UnderflowBin.

**Επιστρέφει:**
boolean
### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public final void setAutomaticUnderflowBin(boolean value)
```


Καθορίζει την αυτόματη τιμή του κουβά υποροής. Εάν είναι false: χρησιμοποιήστε την ιδιότητα UnderflowBin.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public final double getUnderflowBin()
```


Καθορίζει προσαρμοσμένη τιμή του κουβά υποροής. Εφαρμόζεται όταν η ιδιότητα IsAutomaticUnderflowBin είναι false και η ιδιότητα IsUnderflowBin είναι true.

**Επιστρέφει:**
double
### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public final void setUnderflowBin(double value)
```


Καθορίζει προσαρμοσμένη τιμή του κουβά υποροής. Εφαρμόζεται όταν η ιδιότητα IsAutomaticUnderflowBin είναι false και η ιδιότητα IsUnderflowBin είναι true.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Επιστρέφει τη διαφάνεια γονέα ενός FillFormat. Μόνο για ανάγνωση [BaseSlide](../../com.aspose.slides/baseslide).

**Επιστρέφει:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Επιστρέφει την παρουσία γονέα ενός FillFormat. Μόνο για ανάγνωση [IPresentation](../../com.aspose.slides/ipresentation).

**Επιστρέφει:**
[IPresentation](../../com.aspose.slides/ipresentation)