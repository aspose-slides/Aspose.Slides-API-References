---
title: IChart
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αναπαριστά ένα γραφικό διάγραμμα σε μια διαφάνεια.
type: docs
url: /el/com.aspose.slides/ichart/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface IChart extends IGraphicalObject, IFormattedTextContainer, IOverrideThemeable
```

Αναπαριστά ένα γραφικό διάγραμμα σε μια διαφάνεια.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | Καθορίζει αν τα μόνο ορατά κελιά σχεδιαζονται. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | Καθορίζει αν τα μόνο ορατά κελιά σχεδιαζονται. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | Επιστρέφει ή ορίζει τον τρόπο σχεδίασης των κενών κελιών σε ένα διάγραμμα. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | Επιστρέφει ή ορίζει τον τρόπο σχεδίασης των κενών κελιών σε ένα διάγραμμα. |
| [getChartData()](#getChartData--) | Επιστρέφει πληροφορίες σχετικά με τα συνδεδεμένα ή ενσωματωμένα δεδομένα που σχετίζονται με ένα διάγραμμα. |
| [hasTitle()](#hasTitle--) | Καθορίζει αν ένα διάγραμμα έχει ορατό τίτλο. |
| [setTitle(boolean value)](#setTitle-boolean-) | Καθορίζει αν ένα διάγραμμα έχει ορατό τίτλο. |
| [getChartTitle()](#getChartTitle--) | Επιστρέφει ή ορίζει τίτλο διαγράμματος Μόνο ανάγνωση [IChartTitle](../../com.aspose.slides/icharttitle). |
| [hasDataTable()](#hasDataTable--) | Καθορίζει αν ένα διάγραμμα έχει πίνακα δεδομένων. |
| [setDataTable(boolean value)](#setDataTable-boolean-) | Καθορίζει αν ένα διάγραμμα έχει πίνακα δεδομένων. |
| [hasLegend()](#hasLegend--) | Καθορίζει αν ένα διάγραμμα έχει υπόμνημα. |
| [setLegend(boolean value)](#setLegend-boolean-) | Καθορίζει αν ένα διάγραμμα έχει υπόμνημα. |
| [getLegend()](#getLegend--) | Επιστρέφει ή ορίζει υπόμνημα για ένα διάγραμμα. |
| [getChartDataTable()](#getChartDataTable--) | Επιστρέφει πίνακα δεδομένων ενός διαγράμματος. |
| [getStyle()](#getStyle--) | Επιστρέφει ή ορίζει το στυλ του διαγράμματος. |
| [setStyle(int value)](#setStyle-int-) | Επιστρέφει ή ορίζει το στυλ του διαγράμματος. |
| [getType()](#getType--) | Επιστρέφει ή ορίζει τον τύπο του διαγράμματος. |
| [setType(int value)](#setType-int-) | Επιστρέφει ή ορίζει τον τύπο του διαγράμματος. |
| [getPlotArea()](#getPlotArea--) | Αναπαριστά την περιοχή σχεδίασης ενός διαγράμματος. |
| [getRotation3D()](#getRotation3D--) | Επιστρέφει μια 3Δ περιστροφή ενός διαγράμματος. |
| [getBackWall()](#getBackWall--) | Επιστρέφει ένα αντικείμενο που επιτρέπει την αλλαγή μορφής του πίσω τοίχου ενός 3Δ διαγράμματος. |
| [getSideWall()](#getSideWall--) | Επιστρέφει ένα αντικείμενο που επιτρέπει την αλλαγή μορφής του πλευρικού τοίχου ενός 3Δ διαγράμματος. |
| [getFloor()](#getFloor--) | Επιστρέφει ένα αντικείμενο που επιτρέπει την αλλαγή μορφής του δαπέδου ενός 3Δ διαγράμματος. |
| [getUserShapes()](#getUserShapes--) | Καθορίζει τα σχήματα που σχεδιάζονται πάνω στο διάγραμμα. |
| [getAxes()](#getAxes--) | Παρέχει πρόσβαση στους άξονες του διαγράμματος. |
| [validateChartLayout()](#validateChartLayout--) | Υπολογίζει τις πραγματικές τιμές των στοιχείων του διαγράμματος. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | Καθορίζει ότι οι ετικέτες δεδομένων πάνω από το μέγιστο του διαγράμματος θα εμφανίζονται. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | Καθορίζει ότι οι ετικέτες δεδομένων πάνω από το μέγιστο του διαγράμματος θα εμφανίζονται. |
| [hasRoundedCorners()](#hasRoundedCorners--) | Καθορίζει ότι η περιοχή του διαγράμματος θα έχει στρογγυλεμένες γωνίες. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | Καθορίζει ότι η περιοχή του διαγράμματος θα έχει στρογγυλεμένες γωνίες. |
### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public abstract boolean getPlotVisibleCellsOnly()
```

Καθορίζει αν τα μόνο ορατά κελιά σχεδιαζονται. False για σχεδίαση τόσο των ορατών όσο και των κρυμμένων κελιών. Αναγνώσιμη/εγγράψιμη boolean.

**Επιστρέφει:**
boolean
### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public abstract void setPlotVisibleCellsOnly(boolean value)
```

Καθορίζει αν τα μόνο ορατά κελιά σχεδιαζονται. False για σχεδίαση τόσο των ορατών όσο και των κρυμμένων κελιών. Αναγνώσιμη/εγγράψιμη boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public abstract int getDisplayBlanksAs()
```

Επιστρέφει ή ορίζει τον τρόπο σχεδίασης των κενών κελιών σε ένα διάγραμμα. Αναγνώσιμη/εγγράψιμη [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Επιστρέφει:**
int
### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public abstract void setDisplayBlanksAs(int value)
```

Επιστρέφει ή ορίζει τον τρόπο σχεδίασης των κενών κελιών σε ένα διάγραμμα. Αναγνώσιμη/εγγράψιμη [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getChartData() {#getChartData--}
```
public abstract IChartData getChartData()
```

Επιστρέφει πληροφορίες σχετικά με τα συνδεδεμένα ή ενσωματωμένα δεδομένα που σχετίζονται με ένα διάγραμμα. Μόνο ανάγνωση [IChartData](../../com.aspose.slides/ichartdata).

**Επιστρέφει:**
[IChartData](../../com.aspose.slides/ichartdata)
### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

Καθορίζει αν ένα διάγραμμα έχει ορατό τίτλο. Αναγνώσιμη/εγγράψιμη boolean.

**Επιστρέφει:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

Καθορίζει αν ένα διάγραμμα έχει ορατό τίτλο. Αναγνώσιμη/εγγράψιμη boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getChartTitle() {#getChartTitle--}
```
public abstract IChartTitle getChartTitle()
```

Επιστρέφει ή ορίζει τίτλο διαγράμματος Μόνο ανάγνωση [IChartTitle](../../com.aspose.slides/icharttitle).

**Επιστρέφει:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### hasDataTable() {#hasDataTable--}
```
public abstract boolean hasDataTable()
```

Καθορίζει αν ένα διάγραμμα έχει πίνακα δεδομένων. Αναγνώσιμη/εγγράψιμη boolean.

**Επιστρέφει:**
boolean
### setDataTable(boolean value) {#setDataTable-boolean-}
```
public abstract void setDataTable(boolean value)
```

Καθορίζει αν ένα διάγραμμα έχει πίνακα δεδομένων. Αναγνώσιμη/εγγράψιμη boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### hasLegend() {#hasLegend--}
```
public abstract boolean hasLegend()
```

Καθορίζει αν ένα διάγραμμα έχει υπόμνημα. Αναγνώσιμη/εγγράψιμη boolean.

**Επιστρέφει:**
boolean
### setLegend(boolean value) {#setLegend-boolean-}
```
public abstract void setLegend(boolean value)
```

Καθορίζει αν ένα διάγραμμα έχει υπόμνημα. Αναγνώσιμη/εγγράψιμη boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getLegend() {#getLegend--}
```
public abstract ILegend getLegend()
```

Επιστρέφει ή ορίζει υπόμνημα για ένα διάγραμμα. Μόνο ανάγνωση [ILegend](../../com.aspose.slides/ilegend).

**Επιστρέφει:**
[ILegend](../../com.aspose.slides/ilegend)
### getChartDataTable() {#getChartDataTable--}
```
public abstract IDataTable getChartDataTable()
```

Επιστρέφει πίνακα δεδομένων ενός διαγράμματος. Μόνο ανάγνωση [IDataTable](../../com.aspose.slides/idatatable).

**Επιστρέφει:**
[IDataTable](../../com.aspose.slides/idatatable)
### getStyle() {#getStyle--}
```
public abstract int getStyle()
```

Επιστρέφει ή ορίζει το στυλ του διαγράμματος. Αναγνώσιμη/εγγράψιμη [StyleType](../../com.aspose.slides/styletype).

**Επιστρέφει:**
int
### setStyle(int value) {#setStyle-int-}
```
public abstract void setStyle(int value)
```

Επιστρέφει ή ορίζει το στυλ του διαγράμματος. Αναγνώσιμη/εγγράψιμη [StyleType](../../com.aspose.slides/styletype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getType() {#getType--}
```
public abstract int getType()
```

Επιστρέφει ή ορίζει τον τύπο του διαγράμματος. Αναγνώσιμη/εγγράψιμη [ChartType](../../com.aspose.slides/charttype).

**Επιστρέφει:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Επιστρέφει ή ορίζει τον τύπο του διαγράμματος. Αναγνώσιμη/εγγράψιμη [ChartType](../../com.aspose.slides/charttype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getPlotArea() {#getPlotArea--}
```
public abstract IChartPlotArea getPlotArea()
```

Αναπαριστά την περιοχή σχεδίασης ενός διαγράμματος. Μόνο ανάγνωση [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**Επιστρέφει:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)
### getRotation3D() {#getRotation3D--}
```
public abstract IRotation3D getRotation3D()
```

Επιστρέφει μια 3Δ περιστροφή ενός διαγράμματος. Μόνο ανάγνωση [IRotation3D](../../com.aspose.slides/irotation3d).

**Επιστρέφει:**
[IRotation3D](../../com.aspose.slides/irotation3d)
### getBackWall() {#getBackWall--}
```
public abstract IChartWall getBackWall()
```

Επιστρέφει ένα αντικείμενο που επιτρέπει την αλλαγή μορφής του πίσω τοίχου ενός 3Δ διαγράμματος. Μόνο ανάγνωση [IChartWall](../../com.aspose.slides/ichartwall).

**Επιστρέφει:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getSideWall() {#getSideWall--}
```
public abstract IChartWall getSideWall()
```

Επιστρέφει ένα αντικείμενο που επιτρέπει την αλλαγή μορφής του πλευρικού τοίχου ενός 3Δ διαγράμματος. Μόνο ανάγνωση [IChartWall](../../com.aspose.slides/ichartwall).

**Επιστρέφει:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getFloor() {#getFloor--}
```
public abstract IChartWall getFloor()
```

Επιστρέφει ένα αντικείμενο που επιτρέπει την αλλαγή μορφής του δαπέδου ενός 3Δ διαγράμματος. Μόνο ανάγνωση [IChartWall](../../com.aspose.slides/ichartwall).

**Επιστρέφει:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getUserShapes() {#getUserShapes--}
```
public abstract IGroupShape getUserShapes()
```

Καθορίζει τα σχήματα που σχεδιάζονται πάνω στο διάγραμμα. Μόνο ανάγνωση [IGroupShape](../../com.aspose.slides/igroupshape).

**Επιστρέφει:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getAxes() {#getAxes--}
```
public abstract IAxesManager getAxes()
```

Παρέχει πρόσβαση στους άξονες του διαγράμματος. Μόνο ανάγνωση [IAxesManager](../../com.aspose.slides/iaxesmanager).

**Επιστρέφει:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)
### validateChartLayout() {#validateChartLayout--}
```
public abstract void validateChartLayout()
```

Υπολογίζει τις πραγματικές τιμές των στοιχείων του διαγράμματος. Οι πραγματικές τιμές περιλαμβάνουν τη θέση των στοιχείων που υλοποιούν το interface IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) και τις πραγματικές τιμές των αξόνων (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)
### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public abstract boolean getShowDataLabelsOverMaximum()
```

Καθορίζει ότι οι ετικέτες δεδομένων πάνω από το μέγιστο του διαγράμματος θα εμφανίζονται. Αναγνώσιμη/εγγράψιμη boolean.

**Επιστρέφει:**
boolean
### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public abstract void setShowDataLabelsOverMaximum(boolean value)
```

Καθορίζει ότι οι ετικέτες δεδομένων πάνω από το μέγιστο του διαγράμματος θα εμφανίζονται. Αναγνώσιμη/εγγράψιμη boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### hasRoundedCorners() {#hasRoundedCorners--}
```
public abstract boolean hasRoundedCorners()
```

Καθορίζει ότι η περιοχή του διαγράμματος θα έχει στρογγυλεμένες γωνίες. Αναγνώσιμη/εγγράψιμη boolean.

**Επιστρέφει:**
boolean
### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public abstract void setRoundedCorners(boolean value)
```

Καθορίζει ότι η περιοχή του διαγράμματος θα έχει στρογγυλεμένες γωνίες. Αναγνώσιμη/εγγράψιμη boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |