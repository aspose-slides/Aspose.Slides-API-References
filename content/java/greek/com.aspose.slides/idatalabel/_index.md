---
title: IDataLabel
second_title: Aspose.Slides για την Java API Αναφορά
description: Αναπαριστά ετικέτες σειράς.
type: docs
url: /el/com.aspose.slides/idatalabel/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

Αναπαριστά ετικέτες σειράς.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [isVisible()](#isVisible--) | False σημαίνει ότι η ετικέτα δεδομένων δεν είναι ορατή (και έτσι όλες οι σημαίες Show*-flags (ShowValue, ...) είναι false). |
| [hide()](#hide--) | Κάντε την ετικέτα δεδομένων κρυφή ορίζοντας όλες τις σημαίες Show*-flags (ShowValue, ...) σε κατάσταση false. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Επιστρέφει τη μορφή της ετικέτας δεδομένων. |
| [getValueFromCell()](#getValueFromCell--) | Λαμβάνει ή ορίζει το κελί δεδομένων του βιβλίου εργασίας. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Λαμβάνει ή ορίζει το κελί δεδομένων του βιβλίου εργασίας. |
| [getActualLabelText()](#getActualLabelText--) | Επιστρέφει το πραγματικό κείμενο ετικέτας βάσει των ρυθμίσεων DataLabelFormat ή της τιμής TextFrameForOverriding.Text. |
| [getLabelShapeType()](#getLabelShapeType--) | Λαμβάνει ή ορίζει τον τύπο σχήματος της ετικέτας δεδομένων. |
| [setLabelShapeType(int value)](#setLabelShapeType-int-) | Λαμβάνει ή ορίζει τον τύπο σχήματος της ετικέτας δεδομένων. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False σημαίνει ότι η ετικέτα δεδομένων δεν είναι ορατή (και έτσι όλες οι σημαίες Show*-flags (ShowValue, ...) είναι false). Μόνο για ανάγνωση boolean.

--------------------

Αν η ετικέτα δεδομένων είναι ορατή, μπορείτε να την κρύψετε με τη μέθοδο Hide(). Αλλά αν η ετικέτα δεδομένων δεν είναι ορατή (IsVisible είναι false), μπορείτε να την κάνετε ορατή ορίζοντας τις σημαίες Show*-flags (ShowValue, ...) σε κατάσταση true.

**Επιστρέφει:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Κάντε την ετικέτα δεδομένων κρυφή ορίζοντας όλες τις σημαίες Show*-flags (ShowValue, ...) σε κατάσταση false. Το IsVisible θα είναι false μετά από αυτό.

--------------------

Αν η ετικέτα δεδομένων δεν είναι ορατή (IsVisible είναι false) μπορείτε να την κάνετε ορατή ορίζοντας τις σημαίες Show*-flags (ShowValue, ...) σε κατάσταση true.

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

Επιστρέφει τη μορφή της ετικέτας δεδομένων. Μόνο για ανάγνωση [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Επιστρέφει:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

Λαμβάνει ή ορίζει το κελί δεδομένων του βιβλίου εργασίας. Εφαρμόζεται εάν η ιδιότητα IDataLabelFormat.ShowLabelValueFromCell είναι true.

**Επιστρέφει:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

Λαμβάνει ή ορίζει το κελί δεδομένων του βιβλίου εργασίας. Εφαρμόζεται εάν η ιδιότητα IDataLabelFormat.ShowLabelValueFromCell είναι true.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

Επιστρέφει το πραγματικό κείμενο ετικέτας βάσει των ρυθμίσεων DataLabelFormat ή της τιμής TextFrameForOverriding.Text.

**Επιστρέφει:**
java.lang.String - Πραγματικό κείμενο ετικέτας String
### getLabelShapeType() {#getLabelShapeType--}
```
public abstract int getLabelShapeType()
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
public abstract void setLabelShapeType(int value)
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