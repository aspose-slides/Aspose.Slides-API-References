---
title: DataLabel
second_title: Αναφορά API του Java για Aspose.Slides
description: Αναπαριστά ετικέτες σειράς.
type: docs
url: /el/com.aspose.slides/datalabel/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IDataLabel](../../com.aspose.slides/idatalabel), com.aspose.slides.IDOMObject
```
public class DataLabel implements IDataLabel, IDOMObject
```

Αναπαριστά ετικέτες σειράς.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | Δημιουργεί μια νέα παρουσία της κλάσης DataLabel. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Επιστρέφει το γονικό chart. |
| [isVisible()](#isVisible--) | False σημαίνει ότι η ετικέτα δεδομένων δεν είναι ορατή (και έτσι όλες οι σημαίες Show*-flags (ShowValue, ...) είναι ψευδείς). |
| [hide()](#hide--) | Κάνει την ετικέτα δεδομένων κρυφή ορίζοντας όλες τις σημαίες Show*-flags (ShowValue, ...) σε κατάσταση ψευδής. |
| [getActualLabelText()](#getActualLabelText--) | Επιστρέφει το πραγματικό κείμενο ετικέτας βάσει των ρυθμίσεων DataLabelFormat ή της τιμής TextFrameForOverriding.Text. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Αρχικοποιεί το TextFrameForOverriding με το κείμενο στην παράμετρο "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Μπορεί να περιέχει μορφοποιημένο πλούσιο κείμενο. |
| [getTextFormat()](#getTextFormat--) | Επιστρέφει τη διαμόρφωση κειμένου. |
| [getX()](#getX--) | Επιστρέφει ή ορίζει το x συντεταγμένο ενός τίτλου ως κλάσμα του πλάτους του chart. |
| [setX(float value)](#setX-float-) | Επιστρέφει ή ορίζει το x συντεταγμένο ενός τίτλου ως κλάσμα του πλάτους του chart. |
| [getY()](#getY--) | Επιστρέφει ή ορίζει το y συντεταγμένο ενός τίτλου ως κλάσμα του ύψους του chart. |
| [setY(float value)](#setY-float-) | Επιστρέφει ή ορίζει το y συντεταγμένο ενός τίτλου ως κλάσμα του ύψους του chart. |
| [getWidth()](#getWidth--) | Επιστρέφει ή ορίζει το πλάτος ενός τίτλου ως κλάσμα του πλάτους του chart. |
| [setWidth(float value)](#setWidth-float-) | Επιστρέφει ή ορίζει το πλάτος ενός τίτλου ως κλάσμα του πλάτους του chart. |
| [getHeight()](#getHeight--) | Επιστρέφει ή ορίζει το ύψος ενός τίτλου ως κλάσμα του ύψους του chart. |
| [setHeight(float value)](#setHeight-float-) | Επιστρέφει ή ορίζει το ύψος ενός τίτλου ως κλάσμα του ύψους του chart. |
| [getRight()](#getRight--) | Δεξιά. |
| [getBottom()](#getBottom--) | Κάτω. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Επιστρέφει τη διαμόρφωση ετικέτας δεδομένων. |
| [getValueFromCell()](#getValueFromCell--) | Λαμβάνει ή ορίζει το κελί δεδομένων του βιβλίου εργασίας. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Λαμβάνει ή ορίζει το κελί δεδομένων του βιβλίου εργασίας. |
| [getLabelShapeType()](#getLabelShapeType--) | Λαμβάνει ή ορίζει τον τύπο σχήματος της ετικέτας δεδομένων. |
| [setLabelShapeType(int value)](#setLabelShapeType-int-) | Λαμβάνει ή ορίζει τον τύπο σχήματος της ετικέτας δεδομένων. |
| [getActualX()](#getActualX--) | Καθορίζει την πραγματική θέση x (αριστερά) του στοιχείου του chart σε σχέση με την αριστερή πάνω γωνία του chart. |
| [getActualY()](#getActualY--) | Καθορίζει το πραγματικό ανώτερο σημείο του στοιχείου του chart σε σχέση με την αριστερή πάνω γωνία του chart. |
| [getActualWidth()](#getActualWidth--) | Καθορίζει το πραγματικό πλάτος του στοιχείου του chart. |
| [getActualHeight()](#getActualHeight--) | Καθορίζει το πραγματικό ύψος του στοιχείου του chart. |
| [getSlide()](#getSlide--) | Επιστρέφει τη γονική διαφάνεια ενός FillFormat. |
| [getPresentation()](#getPresentation--) | Επιστρέφει την γονική παρουσίαση ενός FillFormat. |
### DataLabel(IChartDataPoint parentImmediate) {#DataLabel-com.aspose.slides.IChartDataPoint-}
```
public DataLabel(IChartDataPoint parentImmediate)
```

Δημιουργεί μια νέα παρουσία της κλάσης DataLabel.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| parentImmediate | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Γονικό ChartDataPoint. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο για ανάγνωση IDOMObject.

**Επιστρέφει:**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```

Επιστρέφει το γονικό chart. Μόνο για ανάγνωση [IChart](../../com.aspose.slides/ichart).

**Επιστρέφει:**
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False σημαίνει ότι η ετικέτα δεδομένων δεν είναι ορατή (και έτσι όλες οι σημαίες Show*-flags (ShowValue, ...) είναι ψευδείς). Μόνο για ανάγνωση  boolean .

--------------------

Αν η ετικέτα δεδομένων είναι ορατή μπορείτε να την κρύψετε με τη μέθοδο Hide(). Αλλά αν η ετικέτα δεδομένων δεν είναι ορατή (IsVisible είναι false) μπορείτε να την κάνετε ορατή ορίζοντας τις σημαίες Show*-flags (ShowValue, ...) σε κατάσταση true.

**Επιστρέφει:**
boolean
### hide() {#hide--}
```
public final void hide()
```

Κάνει την ετικέτα δεδομένων κρυφή ορίζοντας όλες τις σημαίες Show*-flags (ShowValue, ...) σε κατάσταση ψευδής. Το IsVisible θα είναι false μετά από αυτό.

--------------------

Αν η ετικέτα δεδομένων δεν είναι ορατή (IsVisible είναι false) μπορείτε να την κάνετε ορατή ορίζοντας τις σημαίες Show*-flags (ShowValue, ...) σε κατάσταση true.

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

Επιστρέφει το πραγματικό κείμενο ετικέτας βάσει των ρυθμίσεων DataLabelFormat ή της τιμής TextFrameForOverriding.Text.

**Επιστρέφει:**
java.lang.String - Το αντικείμενο java.lang.String.
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

Μπορεί να περιέχει πλούσιο μορφοποιημένο κείμενο. Εάν αυτή η ιδιότητα δεν είναι null, τότε αυτή η μορφοποιημένη τιμή κειμένου αντικαθιστά το αυτόματα δημιουργημένο κείμενο της ετικέτας δεδομένων. Το αυτόματα δημιουργημένο κείμενο της ετικέτας δεδομένων σημαίνει κείμενο που διαχειρίζεται από τις ιδιότητες ShowSeriesName, ShowValue, ... και μορφοποιείται με την ιδιότητα TextFormatManager.TextFormat. Μόνο για ανάγνωση [ITextFrame](../../com.aspose.slides/itextframe).

**Επιστρέφει:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Επιστρέφει τη διαμόρφωση κειμένου. Μόνο για ανάγνωση [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Επιστρέφει:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getX() {#getX--}
```
public final float getX()
```

Επιστρέφει ή ορίζει το x συντεταγμένο ενός τίτλου ως κλάσμα του πλάτους του chart. Ανάγνωση/εγγραφή  float .

**Επιστρέφει:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Επιστρέφει ή ορίζει το x συντεταγμένο ενός τίτλου ως κλάσμα του πλάτους του chart. Ανάγνωση/εγγραφή  float .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |
### getY() {#getY--}
```
public final float getY()
```

Επιστρέφει ή ορίζει το y συντεταγμένο ενός τίτλου ως κλάσμα του ύψους του chart. Ανάγνωση/εγγραφή  float .

**Επιστρέφει:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Επιστρέφει ή ορίζει το y συντεταγμένο ενός τίτλου ως κλάσμα του ύψους του chart. Ανάγνωση/εγγραφή  float .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |
### getWidth() {#getWidth--}
```
public final float getWidth()
```

Επιστρέφει ή ορίζει το πλάτος ενός τίτλου ως κλάσμα του πλάτους του chart. Ανάγνωση/εγγραφή  float .

**Επιστρέφει:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Επιστρέφει ή ορίζει το πλάτος ενός τίτλου ως κλάσμα του πλάτους του chart. Ανάγνωση/εγγραφή  float .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |
### getHeight() {#getHeight--}
```
public final float getHeight()
```

Επιστρέφει ή ορίζει το ύψος ενός τίτλου ως κλάσμα του ύψους του chart. Ανάγνωση/εγγραφή  float .

**Επιστρέφει:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Επιστρέφει ή ορίζει το ύψος ενός τίτλου ως κλάσμα του ύψους του chart. Ανάγνωση/εγγραφή  float .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |
### getRight() {#getRight--}
```
public final float getRight()
```

Δεξιά. Μόνο για ανάγνωση  float .

**Επιστρέφει:**
float
### getBottom() {#getBottom--}
```
public final float getBottom()
```

Κάτω. Μόνο για ανάγνωση  float .

**Επιστρέφει:**
float
### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```

Επιστρέφει τη διαμόρφωση ετικέτας δεδομένων. Μόνο για ανάγνωση [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Επιστρέφει:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```

Λαμβάνει ή ορίζει το κελί δεδομένων του βιβλίου εργασίας. Εφαρμόζεται εάν η ιδιότητα IDataLabelFormat.ShowLabelValueFromCell είναι true.

**Επιστρέφει:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```

Λαμβάνει ή ορίζει το κελί δεδομένων του βιβλίου εργασίας. Εφαρμόζεται εάν η ιδιότητα IDataLabelFormat.ShowLabelValueFromCell είναι true.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getLabelShapeType() {#getLabelShapeType--}
```
public final int getLabelShapeType()
```

Λαμβάνει ή ορίζει τον τύπο σχήματος της ετικέτας δεδομένων. Επιστρέφει [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) εάν δεν έχει οριστεί σχήμα.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Ορίστε τον τύπο σχήματος της πρώτης ετικέτας δεδομένων σε Ellipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
int
### setLabelShapeType(int value) {#setLabelShapeType-int-}
```
public final void setLabelShapeType(int value)
```

Λαμβάνει ή ορίζει τον τύπο σχήματος της ετικέτας δεδομένων. Επιστρέφει [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) εάν δεν έχει οριστεί σχήμα.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Ορίστε τον τύπο σχήματος της πρώτης ετικέτας δεδομένων σε Ellipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getActualX() {#getActualX--}
```
public final float getActualX()
```

Καθορίζει την πραγματική θέση x (αριστερά) του στοιχείου του chart σε σχέση με την αριστερή πάνω γωνία του chart. Κάλεσε τη μέθοδο IChart.ValidateChartLayout() πριν για να λάβεις τις πραγματικές τιμές. Μόνο ανάγνωση float.

**Επιστρέφει:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

Καθορίζει το πραγματικό ανώτερο σημείο του στοιχείου του chart σε σχέση με την αριστερή πάνω γωνία του chart. Κάλεσε τη μέθοδο IChart.ValidateChartLayout() πριν για να λάβεις τις πραγματικές τιμές. Μόνο ανάγνωση float.

**Επιστρέφει:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Καθορίζει το πραγματικό πλάτος του στοιχείου του chart. Κάλεσε τη μέθοδο IChart.ValidateChartLayout() πριν για να λάβεις τις πραγματικές τιμές. Μόνο ανάγνωση float.

**Επιστρέφει:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Καθορίζει το πραγματικό ύψος του στοιχείου του chart. Κάλεσε τη μέθοδο IChart.ValidateChartLayout() πριν για να λάβεις τις πραγματικές τιμές. Μόνο ανάγνωση float.

**Επιστρέφει:**
float
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