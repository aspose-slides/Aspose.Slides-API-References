---
title: Chart
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αντιπροσωπεύει ένα γραφικό διάγραμμα σε μια διαφάνεια.
type: docs
url: /el/com.aspose.slides/chart/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IChart](../../com.aspose.slides/ichart)
```
public class Chart extends GraphicalObject implements IChart
```

Αντιπροσωπεύει ένα γραφικό διάγραμμα σε μια διαφάνεια.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [validateChartLayout()](#validateChartLayout--) | Υπολογίζει τις πραγματικές τιμές των στοιχείων του διαγράμματος. |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | Καθορίζει εάν σχεδιάζονται μόνο τα ορατά κελιά. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | Καθορίζει εάν σχεδιάζονται μόνο τα ορατά κελιά. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | Επιστρέφει ή ορίζει τον τρόπο σχεδίασης των κενών κελιών σε ένα διάγραμμα. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | Επιστρέφει ή ορίζει τον τρόπο σχεδίασης των κενών κελιών σε ένα διάγραμμα. |
| [getChartData()](#getChartData--) | Επιστρέφει πληροφορίες σχετικά με τα συνδεδεμένα ή ενσωματωμένα δεδομένα που σχετίζονται με ένα διάγραμμα. |
| [hasTitle()](#hasTitle--) | Καθορίζει εάν ένα διάγραμμα έχει ορατό τίτλο. |
| [setTitle(boolean value)](#setTitle-boolean-) | Καθορίζει εάν ένα διάγραμμα έχει ορατό τίτλο. |
| [getChartTitle()](#getChartTitle--) | Επιστρέφει ή ορίζει τον τίτλο του διαγράμματος. |
| [hasDataTable()](#hasDataTable--) | Καθορίζει εάν ένα διάγραμμα διαθέτει πίνακα δεδομένων. |
| [setDataTable(boolean value)](#setDataTable-boolean-) | Καθορίζει εάν ένα διάγραμμα διαθέτει πίνακα δεδομένων. |
| [hasLegend()](#hasLegend--) | Καθορίζει εάν ένα διάγραμμα έχει υπόμνηση. |
| [setLegend(boolean value)](#setLegend-boolean-) | Καθορίζει εάν ένα διάγραμμα έχει υπόμνηση. |
| [getLegend()](#getLegend--) | Επιστρέφει ή ορίζει μια υπόμνηση για ένα διάγραμμα. |
| [getChartDataTable()](#getChartDataTable--) | Επιστρέφει έναν πίνακα δεδομένων ενός διαγράμματος. |
| [getStyle()](#getStyle--) | Επιστρέφει ή ορίζει το στυλ του διαγράμματος. |
| [setStyle(int value)](#setStyle-int-) | Επιστρέφει ή ορίζει το στυλ του διαγράμματος. |
| [getType()](#getType--) | Επιστρέφει ή ορίζει τον τύπο του διαγράμματος. |
| [setType(int value)](#setType-int-) | Επιστρέφει ή ορίζει τον τύπο του διαγράμματος. |
| [getPlotArea()](#getPlotArea--) | Αντιπροσωπεύει την περιοχή σχεδίασης ενός διαγράμματος. |
| [getRotation3D()](#getRotation3D--) | Επιστρέφει μια 3D περιστροφή ενός διαγράμματος. |
| [getBackWall()](#getBackWall--) | Επιστρέφει ένα αντικείμενο που επιτρέπει την αλλαγή μορφοποίησης του πίσω τοίχου ενός 3D διαγράμματος. |
| [getSideWall()](#getSideWall--) | Επιστρέφει ένα αντικείμενο που επιτρέπει την αλλαγή μορφοποίησης του πλευρικού τοίχου ενός 3D διαγράμματος. |
| [getFloor()](#getFloor--) | Επιστρέφει ένα αντικείμενο που επιτρέπει την αλλαγή μορφοποίησης του πατώματος ενός 3D διαγράμματος. |
| [getTextFormat()](#getTextFormat--) | Επιστρέφει τη μορφοποίηση κειμένου του διαγράμματος. |
| [createThemeEffective()](#createThemeEffective--) | Επιστρέφει ένα αποτελεσματικό θέμα για αυτό το διάγραμμα. |
| [getThemeManager()](#getThemeManager--) | Επιστρέφει τον διαχειριστή θεμάτων. |
| [getUserShapes()](#getUserShapes--) | Καθορίζει τα σχήματα που σχεδιάζονται πάνω από το διάγραμμα. |
| [getAxes()](#getAxes--) | Παρέχει πρόσβαση στους άξονες του διαγράμματος. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | Καθορίζει εάν θα εμφανίζονται ετικέτες δεδομένων πάνω από το μέγιστο του διαγράμματος. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | Καθορίζει εάν θα εμφανίζονται ετικέτες δεδομένων πάνω από το μέγιστο του διαγράμματος. |
| [hasRoundedCorners()](#hasRoundedCorners--) | Καθορίζει ότι η περιοχή του διαγράμματος θα έχει στρογγυλεμένες γωνίες. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | Καθορίζει ότι η περιοχή του διαγράμματος θα έχει στρογγυλεμένες γωνίες. |
| [getChart()](#getChart--) |  |

### validateChartLayout() {#validateChartLayout--}
```
public final void validateChartLayout()
```

Υπολογίζει τις πραγματικές τιμές των στοιχείων του διαγράμματος. Οι πραγματικές τιμές περιλαμβάνουν τη θέση των στοιχείων που υλοποιούν τη διεπαφή IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) και τις πραγματικές τιμές των αξόνων (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public final boolean getPlotVisibleCellsOnly()
```

Καθορίζει εάν σχεδιάζονται μόνο τα ορατά κελιά. False για να σχεδιάζονται τόσο τα ορατά όσο και τα κρυμμένα κελιά. Αναγνώσιμο/εγγράψιμο boolean.

**Επιστρέφει:**
boolean
### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public final void setPlotVisibleCellsOnly(boolean value)
```

Καθορίζει εάν σχεδιάζονται μόνο τα ορατά κελιά. False για να σχεδιάζονται τόσο τα ορατά όσο και τα κρυμμένα κελιά. Αναγνώσιμο/εγγράψιμο boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public final int getDisplayBlanksAs()
```

Επιστρέφει ή ορίζει τον τρόπο σχεδίασης των κενών κελιών σε ένα διάγραμμα. Αναγνώσιμο/εγγράψιμο [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Επιστρέφει:**
int
### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public final void setDisplayBlanksAs(int value)
```

Επιστρέφει ή ορίζει τον τρόπο σχεδίασης των κενών κελιών σε ένα διάγραμμα. Αναγνώσιμο/εγγράψιμο [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public final IChartData getChartData()
```

Επιστρέφει πληροφορίες σχετικά με τα συνδεδεμένα ή ενσωματωμένα δεδομένα που σχετίζονται με ένα διάγραμμα. Μόνο για ανάγνωση [IChartData](../../com.aspose.slides/ichartdata).

**Επιστρέφει:**
[IChartData](../../com.aspose.slides/ichartdata)
### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

Καθορίζει εάν ένα διάγραμμα έχει ορατό τίτλο. Αναγνώσιμο/εγγράψιμο boolean.

**Επιστρέφει:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

Καθορίζει εάν ένα διάγραμμα έχει ορατό τίτλο. Αναγνώσιμο/εγγράψιμο boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public final IChartTitle getChartTitle()
```

Επιστρέφει ή ορίζει τον τίτλο του διαγράμματος. Μόνο για ανάγνωση [IChartTitle](../../com.aspose.slides/icharttitle).

**Επιστρέφει:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### hasDataTable() {#hasDataTable--}
```
public final boolean hasDataTable()
```

Καθορίζει εάν ένα διάγραμμα διαθέτει πίνακα δεδομένων. Αναγνώσιμο/εγγράψιμο boolean.

**Επιστρέφει:**
boolean
### setDataTable(boolean value) {#setDataTable-boolean-}
```
public final void setDataTable(boolean value)
```

Καθορίζει εάν ένα διάγραμμα διαθέτει πίνακα δεδομένων. Αναγνώσιμο/εγγράψιμο boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public final boolean hasLegend()
```

Καθορίζει εάν ένα διάγραμμα έχει υπόμνηση. Αναγνώσιμο/εγγράψιμο boolean.

**Επιστρέφει:**
boolean
### setLegend(boolean value) {#setLegend-boolean-}
```
public final void setLegend(boolean value)
```

Καθορίζει εάν ένα διάγραμμα έχει υπόμνηση. Αναγνώσιμο/εγγράψιμο boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public final ILegend getLegend()
```

Επιστρέφει ή ορίζει μια υπόμνηση για ένα διάγραμμα. Μόνο για ανάγνωση [ILegend](../../com.aspose.slides/ilegend).

**Επιστρέφει:**
[ILegend](../../com.aspose.slides/ilegend)
### getChartDataTable() {#getChartDataTable--}
```
public final IDataTable getChartDataTable()
```

Επιστρέφει έναν πίνακα δεδομένων ενός διαγράμματος. Μόνο για ανάγνωση [IDataTable](../../com.aspose.slides/idatatable).

**Επιστρέφει:**
[IDataTable](../../com.aspose.slides/idatatable)
### getStyle() {#getStyle--}
```
public final int getStyle()
```

Επιστρέφει ή ορίζει το στυλ του διαγράμματος. Αναγνώσιμο/εγγράψιμο [StyleType](../../com.aspose.slides/styletype).

**Επιστρέφει:**
int
### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```

Επιστρέφει ή ορίζει το στυλ του διαγράμματος. Αναγνώσιμο/εγγράψιμο [StyleType](../../com.aspose.slides/styletype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```

Επιστρέφει ή ορίζει τον τύπο του διαγράμματος. Αναγνώσιμο/εγγράψιμο [ChartType](../../com.aspose.slides/charttype).

**Επιστρέφει:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Επιστρέφει ή ορίζει τον τύπο του διαγράμματος. Αναγνώσιμο/εγγράψιμο [ChartType](../../com.aspose.slides/charttype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public final IChartPlotArea getPlotArea()
```

Αντιπροσωπεύει την περιοχή σχεδίασης ενός διαγράμματος. Μόνο για ανάγνωση [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**Επιστρέφει:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)
### getRotation3D() {#getRotation3D--}
```
public final IRotation3D getRotation3D()
```

Επιστρέφει μια 3D περιστροφή ενός διαγράμματος. Μόνο για ανάγνωση [IRotation3D](../../com.aspose.slides/irotation3d).

**Επιστρέφει:**
[IRotation3D](../../com.aspose.slides/irotation3d)
### getBackWall() {#getBackWall--}
```
public final IChartWall getBackWall()
```

Επιστρέφει ένα αντικείμενο που επιτρέπει την αλλαγή μορφοποίησης του πίσω τοίχου ενός 3D διαγράμματος. Μόνο για ανάγνωση [IChartWall](../../com.aspose.slides/ichartwall).

**Επιστρέφει:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getSideWall() {#getSideWall--}
```
public final IChartWall getSideWall()
```

Επιστρέφει ένα αντικείμενο που επιτρέπει την αλλαγή μορφοποίησης του πλευρικού τοίχου ενός 3D διαγράμματος. Μόνο για ανάγνωση [IChartWall](../../com.aspose.slides/ichartwall).

**Επιστρέφει:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getFloor() {#getFloor--}
```
public final IChartWall getFloor()
```

Επιστρέφει ένα αντικείμενο που επιτρέπει την αλλαγή μορφοποίησης του πατώματος ενός 3D διαγράμματος. Μόνο για ανάγνωση [IChartWall](../../com.aspose.slides/ichartwall).

**Επιστρέφει:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Επιστρέφει τη μορφοποίηση κειμένου του διαγράμματος. Η ιδιότητα δεν ισχύει για τους παρακάτω τύπους: [ChartType.Treemap](../../com.aspose.slides/charttype\#Treemap), [ChartType.Sunburst](../../com.aspose.slides/charttype\#Sunburst), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel),[ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker). Μόνο για ανάγνωση [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Επιστρέφει:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Επιστρέφει ένα αποτελεσματικό θέμα για αυτό το διάγραμμα.

**Επιστρέφει:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Επιστρέφει τον διαχειριστή θεμάτων. Μόνο για ανάγνωση [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Επιστρέφει:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getUserShapes() {#getUserShapes--}
```
public final IGroupShape getUserShapes()
```

Καθορίζει τα σχήματα που σχεδιάζονται πάνω από το διάγραμμα. Μόνο για ανάγνωση [IGroupShape](../../com.aspose.slides/igroupshape).

**Επιστρέφει:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getAxes() {#getAxes--}
```
public final IAxesManager getAxes()
```

Παρέχει πρόσβαση στους άξονες του διαγράμματος. Μόνο για ανάγνωση [IAxesManager](../../com.aspose.slides/iaxesmanager).

**Επιστρέφει:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)
### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public final boolean getShowDataLabelsOverMaximum()
```

Καθορίζει εάν θα εμφανίζονται ετικέτες δεδομένων πάνω από το μέγιστο του διαγράμματος. Αναγνώσιμο/εγγράψιμο boolean.

**Επιστρέφει:**
boolean
### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public final void setShowDataLabelsOverMaximum(boolean value)
```

Καθορίζει εάν θα εμφανίζονται ετικέτες δεδομένων πάνω από το μέγιστο του διαγράμματος. Αναγνώσιμο/εγγράψιμο boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public final boolean hasRoundedCorners()
```

Καθορίζει ότι η περιοχή του διαγράμματος θα έχει στρογγυλεμένες γωνίες. Αναγνώσιμο/εγγράψιμο boolean.

**Επιστρέφει:**
boolean
### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public final void setRoundedCorners(boolean value)
```

Καθορίζει ότι η περιοχή του διαγράμματος θα έχει στρογγυλεμένες γωνίες. Αναγνώσιμο/εγγράψιμο boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Επιστρέφει το διάγραμμα. Μόνο για ανάγνωση [IChart](../../com.aspose.slides/ichart).

**Επιστρέφει:**
[IChart](../../com.aspose.slides/ichart)