---
title: Chart
second_title: Αναφορά API του Aspose.Slides για Java
description: Αντιπροσωπεύει ένα γραφικό διάγραμμα σε μια διαφάνεια.
type: docs
url: /el/com.aspose.slides/chart/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**All Implemented Interfaces:**
[com.aspose.slides.IChart](../../com.aspose.slides/ichart)
```
public class Chart extends GraphicalObject implements IChart
```

Αντιπροσωπεύει ένα γραφικό διάγραμμα σε μια διαφάνεια.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [validateChartLayout()](#validateChartLayout--) | Υπολογίζει τις πραγματικές τιμές των στοιχείων του διαγράμματος. |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | Καθορίζει εάν τα μόνο ορατά κελιά σχεδιάζονται. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | Καθορίζει εάν τα μόνο ορατά κελιά σχεδιάζονται. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | Επιστρέφει ή ορίζει τον τρόπο σχεδίασης των κενών κελιών σε ένα διάγραμμα. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | Επιστρέφει ή ορίζει τον τρόπο σχεδίασης των κενών κελιών σε ένα διάγραμμα. |
| [getChartData()](#getChartData--) | Επιστρέφει πληροφορίες σχετικά με τα συνδεδεμένα ή ενσωματωμένα δεδομένα που σχετίζονται με ένα διάγραμμα. |
| [hasTitle()](#hasTitle--) | Καθορίζει εάν ένα διάγραμμα έχει ορατό τίτλο. |
| [setTitle(boolean value)](#setTitle-boolean-) | Καθορίζει εάν ένα διάγραμμα έχει ορατό τίτλο. |
| [getChartTitle()](#getChartTitle--) | Επιστρέφει ή ορίζει τον τίτλο ενός διαγράμματος. |
| [hasDataTable()](#hasDataTable--) | Καθορίζει εάν ένα διάγραμμα έχει πίνακα δεδομένων. |
| [setDataTable(boolean value)](#setDataTable-boolean-) | Καθορίζει εάν ένα διάγραμμα έχει πίνακα δεδομένων. |
| [hasLegend()](#hasLegend--) | Καθορίζει εάν ένα διάγραμμα έχει υπόμνημα. |
| [setLegend(boolean value)](#setLegend-boolean-) | Καθορίζει εάν ένα διάγραμμα έχει υπόμνημα. |
| [getLegend()](#getLegend--) | Επιστρέφει ή ορίζει ένα υπόμνημα για ένα διάγραμμα. |
| [getChartDataTable()](#getChartDataTable--) | Επιστρέφει έναν πίνακα δεδομένων ενός διαγράμματος. |
| [getStyle()](#getStyle--) | Επιστρέφει ή ορίζει το στυλ του διαγράμματος. |
| [setStyle(int value)](#setStyle-int-) | Επιστρέφει ή ορίζει το στυλ του διαγράμματος. |
| [getType()](#getType--) | Επιστρέφει ή ορίζει τον τύπο του διαγράμματος. |
| [setType(int value)](#setType-int-) | Επιστρέφει ή ορίζει τον τύπο του διαγράμματος. |
| [getPlotArea()](#getPlotArea--) | Αντιπροσωπεύει την περιοχή σχεδίασης ενός διαγράμματος. |
| [getRotation3D()](#getRotation3D--) | Επιστρέφει μια 3Δ περιστροφή ενός διαγράμματος. |
| [getBackWall()](#getBackWall--) | Επιστρέφει ένα αντικείμενο που επιτρέπει την αλλαγή μορφής του πίσω τοίχου ενός 3Δ διαγράμματος. |
| [getSideWall()](#getSideWall--) | Επιστρέφει ένα αντικείμενο που επιτρέπει την αλλαγή μορφής του πλευρικού τοίχου ενός 3Δ διαγράμματος. |
| [getFloor()](#getFloor--) | Επιστρέφει ένα αντικείμενο που επιτρέπει την αλλαγή μορφής του δαπέδου ενός 3Δ διαγράμματος. |
| [getTextFormat()](#getTextFormat--) | Επιστρέφει τη μορφή κειμένου του διαγράμματος. |
| [createThemeEffective()](#createThemeEffective--) | Επιστρέφει ένα ενεργό θέμα για αυτό το διάγραμμα. |
| [getThemeManager()](#getThemeManager--) | Επιστρέφει το διαχειριστή θεμάτων. |
| [getUserShapes()](#getUserShapes--) | Καθορίστε τα σχήματα που σχεδιάζονται πάνω από το διάγραμμα. |
| [getAxes()](#getAxes--) | Παρέχει πρόσβαση στους άξονες του διαγράμματος. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | Καθορίζει ότι ετικέτες δεδομένων πάνω από το μέγιστο του διαγράμματος θα εμφανίζονται. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | Καθορίζει ότι ετικέτες δεδομένων πάνω από το μέγιστο του διαγράμματος θα εμφανίζονται. |
| [hasRoundedCorners()](#hasRoundedCorners--) | Καθορίζει ότι η περιοχή του διαγράμματος θα έχει στρογγυλεμένες γωνίες. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | Καθορίζει ότι η περιοχή του διαγράμματος θα έχει στρογγυλεμένες γωνίες. |
| [getChart()](#getChart--) |  |

### validateChartLayout() {#validateChartLayout--}
```
public final void validateChartLayout()
```

Υπολογίζει τις πραγματικές τιμές των στοιχείων του διαγράμματος. Οι πραγματικές τιμές περιλαμβάνουν τη θέση των στοιχείων που υλοποιούν τη διεπαφή IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) και τις πραγματικές τιμές των αξόνων (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale).

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public final boolean getPlotVisibleCellsOnly()
```

Καθορίζει εάν τα μόνο ορατά κελιά σχεδιάζονται. False για τη σχεδίαση και ορατών και κρυφών κελιών. Ανάγνωση/εγγραφή boolean.

**Returns:**
boolean
### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public final void setPlotVisibleCellsOnly(boolean value)
```

Καθορίζει εάν τα μόνο ορατά κελιά σχεδιάζονται. False για τη σχεδίαση και ορατών και κρυφών κελιών. Ανάγνωση/εγγραφή boolean.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public final int getDisplayBlanksAs()
```

Επιστρέφει ή ορίζει τον τρόπο σχεδίασης των κενών κελιών σε ένα διάγραμμα. Ανάγνωση/εγγραφή [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Returns:**
int
### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public final void setDisplayBlanksAs(int value)
```

Επιστρέφει ή ορίζει τον τρόπο σχεδίασης των κενών κελιών σε ένα διάγραμμα. Ανάγνωση/εγγραφή [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public final IChartData getChartData()
```

Επιστρέφει πληροφορίες σχετικά με τα συνδεδεμένα ή ενσωματωμένα δεδομένα που σχετίζονται με ένα διάγραμμα. Ανάγνωση μόνο [IChartData](../../com.aspose.slides/ichartdata).

**Returns:**
[IChartData](../../com.aspose.slides/ichartdata)
### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

Καθορίζει εάν ένα διάγραμμα έχει ορατό τίτλο. Ανάγνωση/εγγραφή boolean.

**Returns:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

Καθορίζει εάν ένα διάγραμμα έχει ορατό τίτλο. Ανάγνωση/εγγραφή boolean.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public final IChartTitle getChartTitle()
```

Επιστρέφει ή ορίζει τον τίτλο ενός διαγράμματος. Ανάγνωση μόνο [IChartTitle](../../com.aspose.slides/icharttitle).

**Returns:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### hasDataTable() {#hasDataTable--}
```
public final boolean hasDataTable()
```

Καθορίζει εάν ένα διάγραμμα έχει πίνακα δεδομένων. Ανάγνωση/εγγραφή boolean.

**Returns:**
boolean
### setDataTable(boolean value) {#setDataTable-boolean-}
```
public final void setDataTable(boolean value)
```

Καθορίζει εάν ένα διάγραμμα έχει πίνακα δεδομένων. Ανάγνωση/εγγραφή boolean.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public final boolean hasLegend()
```

Καθορίζει εάν ένα διάγραμμα έχει υπόμνημα. Ανάγνωση/εγγραφή boolean.

**Returns:**
boolean
### setLegend(boolean value) {#setLegend-boolean-}
```
public final void setLegend(boolean value)
```

Καθορίζει εάν ένα διάγραμμα έχει υπόμνημα. Ανάγνωση/εγγραφή boolean.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public final ILegend getLegend()
```

Επιστρέφει ή ορίζει ένα υπόμνημα για ένα διάγραμμα. Ανάγνωση μόνο [ILegend](../../com.aspose.slides/ilegend).

**Returns:**
[ILegend](../../com.aspose.slides/ilegend)
### getChartDataTable() {#getChartDataTable--}
```
public final IDataTable getChartDataTable()
```

Επιστρέφει έναν πίνακα δεδομένων ενός διαγράμματος. Ανάγνωση μόνο [IDataTable](../../com.aspose.slides/idatatable).

**Returns:**
[IDataTable](../../com.aspose.slides/idatatable)
### getStyle() {#getStyle--}
```
public final int getStyle()
```

Επιστρέφει ή ορίζει το στυλ του διαγράμματος. Ανάγνωση/εγγραφή [StyleType](../../com.aspose.slides/styletype).

**Returns:**
int
### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```

Επιστρέφει ή ορίζει το στυλ του διαγράμματος. Ανάγνωση/εγγραφή [StyleType](../../com.aspose.slides/styletype).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```

Επιστρέφει ή ορίζει τον τύπο του διαγράμματος. Ανάγνωση/εγγραφή [ChartType](../../com.aspose.slides/charttype).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Επιστρέφει ή ορίζει τον τύπο του διαγράμματος. Ανάγνωση/εγγραφή [ChartType](../../com.aspose.slides/charttype).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public final IChartPlotArea getPlotArea()
```

Αντιπροσωπεύει την περιοχή σχεδίασης ενός διαγράμματος. Ανάγνωση μόνο [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**Returns:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)
### getRotation3D() {#getRotation3D--}
```
public final IRotation3D getRotation3D()
```

Επιστρέφει μια 3Δ περιστροφή ενός διαγράμματος. Ανάγνωση μόνο [IRotation3D](../../com.aspose.slides/irotation3d).

**Returns:**
[IRotation3D](../../com.aspose.slides/irotation3d)
### getBackWall() {#getBackWall--}
```
public final IChartWall getBackWall()
```

Επιστρέφει ένα αντικείμενο που επιτρέπει την αλλαγή μορφής του πίσω τοίχου ενός 3Δ διαγράμματος. Ανάγνωση μόνο [IChartWall](../../com.aspose.slides/ichartwall).

**Returns:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getSideWall() {#getSideWall--}
```
public final IChartWall getSideWall()
```

Επιστρέφει ένα αντικείμενο που επιτρέπει την αλλαγή μορφής του πλευρικού τοίχου ενός 3Δ διαγράμματος. Ανάγνωση μόνο [IChartWall](../../com.aspose.slides/ichartwall).

**Returns:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getFloor() {#getFloor--}
```
public final IChartWall getFloor()
```

Επιστρέφει ένα αντικείμενο που επιτρέπει την αλλαγή μορφής του δαπέδου ενός 3Δ διαγράμματος. Ανάγνωση μόνο [IChartWall](../../com.aspose.slides/ichartwall).

**Returns:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Επιστρέφει τη μορφή κειμένου του διαγράμματος. Η ιδιότητα δεν εφαρμόζεται για τους ακόλουθους τύπους: [ChartType.Treemap](../../com.aspose.slides/charttype\#Treemap), [ChartType.Sunburst](../../com.aspose.slides/charttype\#Sunburst), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel),[ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker). Ανάγνωση μόνο [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Returns:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Επιστρέφει ένα ενεργό θέμα για αυτό το διάγραμμα.

**Returns:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Επιστρέφει το διαχειριστή θεμάτων. Ανάγνωση μόνο [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Returns:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getUserShapes() {#getUserShapes--}
```
public final IGroupShape getUserShapes()
```

Καθορίστε τα σχήματα που σχεδιάζονται πάνω από το διάγραμμα. Ανάγνωση μόνο [IGroupShape](../../com.aspose.slides/igroupshape).

**Returns:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getAxes() {#getAxes--}
```
public final IAxesManager getAxes()
```

Παρέχει πρόσβαση στους άξονες του διαγράμματος. Ανάγνωση μόνο [IAxesManager](../../com.aspose.slides/iaxesmanager).

**Returns:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)
### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public final boolean getShowDataLabelsOverMaximum()
```

Καθορίζει ότι ετικέτες δεδομένων πάνω από το μέγιστο του διαγράμματος θα εμφανίζονται. Ανάγνωση/εγγραφή boolean.

**Returns:**
boolean
### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public final void setShowDataLabelsOverMaximum(boolean value)
```

Καθορίζει ότι ετικέτες δεδομένων πάνω από το μέγιστο του διαγράμματος θα εμφανίζονται. Ανάγνωση/εγγραφή boolean.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public final boolean hasRoundedCorners()
```

Καθορίζει ότι η περιοχή του διαγράμματος θα έχει στρογγυλεμένες γωνίες. Ανάγνωση/εγγραφή boolean.

**Returns:**
boolean
### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public final void setRoundedCorners(boolean value)
```

Καθορίζει ότι η περιοχή του διαγράμματος θα έχει στρογγυλεμένες γωνίες. Ανάγνωση/εγγραφή boolean.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Επιστρέφει το διάγραμμα. Ανάγνωση μόνο [IChart](../../com.aspose.slides/ichart).

**Returns:**
[IChart](../../com.aspose.slides/ichart)