---
title: IChart
second_title: Aspose.Sildes για .NET Αναφορά API
description: Αντιπροσωπεύει ένα γραφικό διάγραμμα σε μια διαφάνεια.
type: docs
weight: 1720
url: /el/aspose.slides.charts/ichart/
---
## Διασύνδεση IChart

Αναπαριστά ένα γραφικό διάγραμμα σε μια διαφάνεια.

```csharp
public interface IChart : IFormattedTextContainer, IGraphicalObject, IOverrideThemeable
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/ichart/asiformattedtextcontainer) { get; } | Επιτρέπει την ανάκτηση της βασικής διεπαφής IFormattedTextContainer. Μόνο για ανάγνωση [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIGraphicalObject](../../aspose.slides.charts/ichart/asigraphicalobject) { get; } | Επιτρέπει την ανάκτηση της βασικής διεπαφής IGraphicalObject. Μόνο για ανάγνωση [`IGraphicalObject`](../../aspose.slides/igraphicalobject). |
| [AsIOverrideThemeable](../../aspose.slides.charts/ichart/asioverridethemeable) { get; } | Επιστρέφει τη διεπαφή IOverrideThemeable. Μόνο για ανάγνωση [`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable). |
| [Axes](../../aspose.slides.charts/ichart/axes) { get; } | Παρέχει πρόσβαση στους άξονες του διαγράμματος. Μόνο για ανάγνωση [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/ichart/backwall) { get; } | Επιστρέφει ένα αντικείμενο που επιτρέπει την αλλαγή μορφοποίησης του πίσω τοίχου ενός 3D διαγράμματος. Μόνο για ανάγνωση [`IChartWall`](../ichartwall). |
| [ChartData](../../aspose.slides.charts/ichart/chartdata) { get; } | Επιστρέφει πληροφορίες σχετικά με τα συνδεδεμένα ή ενσωματωμένα δεδομένα που σχετίζονται με ένα διάγραμμα. Μόνο για ανάγνωση [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/ichart/chartdatatable) { get; } | Επιστρέφει έναν πίνακα δεδομένων ενός διαγράμματος. Μόνο για ανάγνωση [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/ichart/charttitle) { get; } | Επιστρέφει ή ορίζει τον τίτλο του διαγράμματος. Μόνο για ανάγνωση [`IChartTitle`](../icharttitle). |
| [DisplayBlanksAs](../../aspose.slides.charts/ichart/displayblanksas) { get; set; } | Επιστρέφει ή ορίζει τον τρόπο σχεδίασης των κενών κελιών σε ένα διάγραμμα. Ανάγνωση/εγγραφή [`DisplayBlanksAsType`](../displayblanksastype). |
| [Floor](../../aspose.slides.charts/ichart/floor) { get; } | Επιστρέφει ένα αντικείμενο που επιτρέπει την αλλαγή μορφοποίησης του δαπέδου ενός 3D διαγράμματος. Μόνο για ανάγνωση [`IChartWall`](../ichartwall). |
| [HasDataTable](../../aspose.slides.charts/ichart/hasdatatable) { get; set; } | Καθορίζει αν ένα διάγραμμα έχει πίνακα δεδομένων. Ανάγνωση/εγγραφή Boolean. |
| [HasLegend](../../aspose.slides.charts/ichart/haslegend) { get; set; } | Καθορίζει αν ένα διάγραμμα έχει υπόμνημα. Ανάγνωση/εγγραφή Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/ichart/hasroundedcorners) { get; set; } | Καθορίζει ότι η περιοχή του διαγράμματος θα έχει στρογγυλεμένες γωνίες. Ανάγνωση/εγγραφή Boolean. |
| [HasTitle](../../aspose.slides.charts/ichart/hastitle) { get; set; } | Καθορίζει αν ένα διάγραμμα έχει ορατό τίτλο. Ανάγνωση/εγγραφή Boolean. |
| [Legend](../../aspose.slides.charts/ichart/legend) { get; } | Επιστρέφει ή ορίζει ένα υπόμνημα για ένα διάγραμμα. Μόνο για ανάγνωση [`ILegend`](../ilegend). |
| [PlotArea](../../aspose.slides.charts/ichart/plotarea) { get; } | Αναπαριστά την περιοχή σχεδίασης ενός διαγράμματος. Μόνο για ανάγνωση [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/ichart/plotvisiblecellsonly) { get; set; } | Καθορίζει αν θα σχεδιάζονται μόνο τα ορατά κελιά. Ψευδές για να σχεδιάζονται τόσο τα ορατά όσο και τα κρυφά κελιά. Ανάγνωση/εγγραφή Boolean. |
| [Rotation3D](../../aspose.slides.charts/ichart/rotation3d) { get; } | Επιστρέφει μια 3D περιστροφή ενός διαγράμματος. Μόνο για ανάγνωση [`IRotation3D`](../irotation3d). |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/ichart/showdatalabelsovermaximum) { get; set; } | Καθορίζει αν θα εμφανίζονται ετικέτες δεδομένων πάνω από το μέγιστο του διαγράμματος. Ανάγνωση/εγγραφή Boolean. |
| [SideWall](../../aspose.slides.charts/ichart/sidewall) { get; } | Επιστρέφει ένα αντικείμενο που επιτρέπει την αλλαγή μορφοποίησης του πλευρικού τοίχου ενός 3D διαγράμματος. Μόνο για ανάγνωση [`IChartWall`](../ichartwall). |
| [Style](../../aspose.slides.charts/ichart/style) { get; set; } | Επιστρέφει ή ορίζει το στυλ του διαγράμματος. Ανάγνωση/εγγραφή [`StyleType`](../styletype). |
| [Type](../../aspose.slides.charts/ichart/type) { get; set; } | Επιστρέφει ή ορίζει τον τύπο του διαγράμματος. Ανάγνωση/εγγραφή [`ChartType`](../charttype). |
| [UserShapes](../../aspose.slides.charts/ichart/usershapes) { get; } | Καθορίζει τα σχήματα που σχεδιάζονται πάνω από το διάγραμμα. Μόνο για ανάγνωση [`IGroupShape`](../../aspose.slides/igroupshape). |

## Μεθόδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [ValidateChartLayout](../../aspose.slides.charts/ichart/validatechartlayout)() | Υπολογίζει τις πραγματικές τιμές των στοιχείων του διαγράμματος. Οι πραγματικές τιμές περιλαμβάνουν τη θέση των στοιχείων που υλοποιούν τη διεπαφή IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) και τις πραγματικές τιμές των αξόνων (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |

### Δείτε επίσης

* διασύνδεση [IFormattedTextContainer](../iformattedtextcontainer)
* διασύνδεση [IGraphicalObject](../../aspose.slides/igraphicalobject)
* διασύνδεση [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* χώρο ονομάτων [Aspose.Slides.Charts](../../aspose.slides.charts)
* συγκρότημα [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->