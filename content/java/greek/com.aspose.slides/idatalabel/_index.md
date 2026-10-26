---
title: IDataLabel
second_title: Αναφορά API του Aspose.Slides για Java
description: Αναπαριστά ετικέτες σειράς.
type: docs
url: /el/com.aspose.slides/idatalabel/
---
**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridingText, IActualLayout
```

Αναπαριστά ετικέτες σειράς.
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [isVisible()](#isVisible--) | False σημαίνει ότι η ετικέτα δεδομένων δεν είναι ορατή (και επομένως όλα τα Show\*-flags (ShowValue, ...) είναι false). |
| [hide()](#hide--) | Κάντε την ετικέτα δεδομένων κρυφή ορίζοντας όλα τα Show\*-flags (ShowValue, ...) στην κατάσταση false. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Επιστρέφει τη μορφή της ετικέτας δεδομένων. |
| [getValueFromCell()](#getValueFromCell--) | Λαμβάνει ή ορίζει το κελί δεδομένων του βιβλίου εργασίας. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Λαμβάνει ή ορίζει το κελί δεδομένων του βιβλίου εργασίας. |
| [getActualLabelText()](#getActualLabelText--) | Επιστρέφει το πραγματικό κείμενο ετικέτας βάσει των ρυθμίσεων DataLabelFormat ή της τιμής TextFrameForOverriding.Text. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


False σημαίνει ότι η ετικέτα δεδομένων δεν είναι ορατή (και επομένως όλα τα Show\*-flags (ShowValue, ...) είναι false). Boolean μόνο για ανάγνωση.

--------------------

Αν η ετικέτα δεδομένων είναι ορατή, μπορείτε να την κρύψετε με τη μέθοδο Hide(). Αλλά αν η ετικέτα δεδομένων δεν είναι ορατή (IsVisible είναι false), μπορείτε να την κάνετε ορατή ορίζοντας τα Show\*-flags (ShowValue, ...) στην κατάσταση true.

**Επιστρέφει:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```


Κάντε την ετικέτα δεδομένων κρυφή ορίζοντας όλα τα Show\*-flags (ShowValue, ...) στην κατάσταση false. Το IsVisible θα είναι false μετά από αυτό.

--------------------

Αν η ετικέτα δεδομένων δεν είναι ορατή (IsVisible είναι false), μπορείτε να την κάνετε ορατή ορίζοντας τα Show\*-flags (ShowValue, ...) στην κατάσταση true.

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
java.lang.String - String του πραγματικού κειμένου ετικέτας