---
title: Chart
second_title: Aspose.Sildes για .NET Αναφορά API
description: Αναπαριστά ένα γραφικό διάγραμμα σε μια διαφάνεια.
type: docs
weight: 1260
url: /el/aspose.slides.charts/chart/
---
## Chart κλάση

Αναπαριστά ένα γραφικό γράφημα σε μια διαφάνεια.

```csharp
public class Chart : GraphicalObject, IChart
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Επιστρέφει ή ορίζει το εναλλακτικό κείμενο που σχετίζεται με ένα σχήμα. Ανάγνωση/εγγραφή String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Επιστρέφει ή ορίζει τον τίτλο του εναλλακτικού κειμένου που σχετίζεται με ένα σχήμα. Ανάγνωση/εγγραφή String. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/chart/asiformattedtextcontainer) { get; } | Επιτρέπει την απόκτηση της βασικής διεπαφής IFormattedTextContainer. Μόνο ανάγνωση [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIThemeable](../../aspose.slides.charts/chart/asithemeable) { get; } | Επιτρέπει την απόκτηση της βασικής διεπαφής IThemeable. Μόνο ανάγνωση [`IThemeable`](../../aspose.slides.theme/ithemeable). |
| [Axes](../../aspose.slides.charts/chart/axes) { get; } | Παρέχει πρόσβαση στους άξονες του διαγράμματος. Μόνο ανάγνωση [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/chart/backwall) { get; } | Επιστρέφει ένα αντικείμενο που επιτρέπει την αλλαγή μορφής του οπισθίου τοίχου ενός 3D διαγράμματος. Μόνο ανάγνωση [`IChartWall`](../ichartwall). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Η ιδιότητα καθορίζει πώς θα αποδίδεται ένα σχήμα σε λειτουργία ασπρόμαυρης εμφάνισης. Ανάγνωση/εγγραφή [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ChartData](../../aspose.slides.charts/chart/chartdata) { get; } | Επιστρέφει πληροφορίες σχετικά με τα συνδεδεμένα ή ενσωματωμένα δεδομένα που σχετίζονται με ένα διάγραμμα. Μόνο ανάγνωση [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/chart/chartdatatable) { get; } | Επιστρέφει έναν πίνακα δεδομένων ενός διαγράμματος. Μόνο ανάγνωση [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/chart/charttitle) { get; } | Επιστρέφει ή ορίζει τον τίτλο του διαγράμματος. Μόνο ανάγνωση [`IChartTitle`](../icharttitle). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σχήμα. Μόνο ανάγνωση Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος. Μόνο ανάγνωση [`ICustomData`](../../aspose.slides/icustomdata). |
| [DisplayBlanksAs](../../aspose.slides.charts/chart/displayblanksas) { get; set; } | Επιστρέφει ή ορίζει τον τρόπο σχεδίασης των κενών κελιών σε ένα διάγραμμα. Ανάγνωση/εγγραφή [`DisplayBlanksAsType`](../displayblanksastype). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Επιστρέφει το αντικείμενο EffectFormat που περιέχει εφέ pixel που εφαρμόζονται σε ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες εφέ. Μόνο ανάγνωση [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Επιστρέφει το αντικείμενο FillFormat που περιέχει ιδιότητες μορφοποίησης γεμίσματος για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γεμίσματος. Μόνο ανάγνωση [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Floor](../../aspose.slides.charts/chart/floor) { get; } | Επιστρέφει ένα αντικείμενο που επιτρέπει την αλλαγή μορφής του δαπέδου ενός 3D διαγράμματος. Μόνο ανάγνωση [`IChartWall`](../ichartwall). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Επιστρέφει ή ορίζει τις ιδιότητες του πλαισίου του σχήματος. Ανάγνωση/εγγραφή [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Επιστρέφει τις κλειδώσεις του σχήματος. Μόνο ανάγνωση [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [HasDataTable](../../aspose.slides.charts/chart/hasdatatable) { get; set; } | Καθορίζει αν ένα διάγραμμα έχει πίνακα δεδομένων. Ανάγνωση/εγγραφή Boolean. |
| [HasLegend](../../aspose.slides.charts/chart/haslegend) { get; set; } | Καθορίζει αν ένα διάγραμμα έχει υπόμνημα. Ανάγνωση/εγγραφή Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/chart/hasroundedcorners) { get; set; } | Καθορίζει ότι η περιοχή του διαγράμματος θα έχει στρογγυλεμένες γωνίες. Ανάγνωση/εγγραφή Boolean. |
| [HasTitle](../../aspose.slides.charts/chart/hastitle) { get; set; } | Καθορίζει αν ένα διάγραμμα έχει ορατό τίτλο. Ανάγνωση/εγγραφή Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | Αποκτά ή ορίζει το ύψος του σχήματος, μετρημένο σε points. Ανάγνωση/εγγραφή Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Καθορίζει αν το σχήμα είναι κρυφό. Ανάγνωση/εγγραφή Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για κλικ του ποντικιού. Ανάγνωση/εγγραφή [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Επιστρέφει τον διαχειριστή υπερσυνδέσμων. Μόνο ανάγνωση [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για πέρασμα του ποντικιού. Ανάγνωση/εγγραφή [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Αποκτά ή ορίζει την επιλογή 'Σήμανση ως διακοσμητικό'. Ανάγνωση/εγγραφή Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Καθορίζει αν το σχήμα είναι ομαδοποιημένο. Μόνο ανάγνωση Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Καθορίζει αν το σχήμα είναι TextHolder_PPT. Μόνο ανάγνωση Boolean. |
| [Legend](../../aspose.slides.charts/chart/legend) { get; } | Επιστρέφει ή ορίζει ένα υπόμνημα για ένα διάγραμμα. Μόνο ανάγνωση [`ILegend`](../ilegend). |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Επιστρέφει το αντικείμενο LineFormat που περιέχει ιδιότητες μορφοποίησης γραμμής για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γραμμής. Μόνο ανάγνωση [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Επιστρέφει ή ορίζει το όνομα ενός σχήματος. Πρέπει να μην είναι null. Χρησιμοποιήστε κενή συμβολοσειρά εάν χρειάζεται. Ανάγνωση/εγγραφή String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Επιστρέφει ένα μοναδικό αναγνωριστικό περιορισμένο σε διαφάνεια που παραμένει σταθερό για όλη τη διάρκεια ζωής του σχήματος και επιτρέπει στον PowerPoint ή σε κώδικα interop να αναφέρεται αξιόπιστα στο σχήμα από οπουδήποτε στο έγγραφο. Μόνο ανάγνωση UInt32. Δείτε επίσης [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Επιστρέφει το αντικείμενο GroupShape γονέα εάν το σχήμα είναι ομαδοποιημένο. Διαφορετικά επιστρέφει null. Μόνο ανάγνωση [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Επιστρέφει το placeholder για ένα σχήμα. Επιστρέφει null εάν το σχήμα δεν έχει placeholder. Μόνο ανάγνωση [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [PlotArea](../../aspose.slides.charts/chart/plotarea) { get; } | Αντιπροσωπεύει την περιοχή σχεδίασης ενός διαγράμματος. Μόνο ανάγνωση [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/chart/plotvisiblecellsonly) { get; set; } | Καθορίζει αν σχεδιάζονται μόνο τα ορατά κελιά. False για να σχεδιαστούν τόσο τα ορατά όσο και τα κρυφά κελιά. Ανάγνωση/εγγραφή Boolean. |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Επιστρέφει τη γονική παρουσίαση μιας διαφάνειας. Μόνο ανάγνωση [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Επιστρέφει ή ορίζει τις ακατέργαστες ιδιότητες του πλαισίου του σχήματος. Ανάγνωση/εγγραφή [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Επιστρέφει ή ορίζει τον αριθμό των μοιρών που το συγκεκριμένο σχήμα περιστρέφεται γύρω από τον άξονα z. Η θετική τιμή υποδεικνύει δεξιόστροφη περιστροφή· η αρνητική τιμή υποδεικνύει αριστερόστροφη περιστροφή. Ανάγνωση/εγγραφή Single. |
| [Rotation3D](../../aspose.slides.charts/chart/rotation3d) { get; } | Επιστρέφει μια 3D περιστροφή ενός διαγράμματος. Μόνο ανάγνωση [`IRotation3D`](../irotation3d). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Επιστρέφει τις κλειδώσεις του σχήματος. Μόνο ανάγνωση [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 ιδιότητες) |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/chart/showdatalabelsovermaximum) { get; set; } | Καθορίζει ότι θα εμφανίζονται ετικέτες δεδομένων πάνω από το μέγιστο του διαγράμματος. Ανάγνωση/εγγραφή Boolean. |
| [SideWall](../../aspose.slides.charts/chart/sidewall) { get; } | Επιστρέφει ένα αντικείμενο που επιτρέπει την αλλαγή μορφής του πλαϊνού τοίχου ενός 3D διαγράμματος. Μόνο ανάγνωση [`IChartWall`](../ichartwall). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Επιστρέφει τη γονική διαφάνεια ενός σχήματος. Μόνο ανάγνωση [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [Style](../../aspose.slides.charts/chart/style) { get; set; } | Επιστρέφει ή ορίζει το στυλ του διαγράμματος. Ανάγνωση/εγγραφή [`StyleType`](../styletype). |
| [TextFormat](../../aspose.slides.charts/chart/textformat) { get; } | Επιστρέφει τη μορφοποίηση κειμένου του διαγράμματος. Η ιδιότητα δεν εφαρμόζεται στους ακόλουθους τύπους: Treemap, Sunburst, Waterfall, Histogram, Funnel, BoxAndWhisker. Μόνο ανάγνωση [`IChartTextFormat`](../icharttextformat). |
| [ThemeManager](../../aspose.slides.charts/chart/thememanager) { get; } | Επιστρέφει τον διαχειριστή θέματος. Μόνο ανάγνωση [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Επιστρέφει το αντικείμενο ThreeDFormat που περιέχει τις ιδιότητες 3D εφέ για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες 3D. Μόνο ανάγνωση [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Type](../../aspose.slides.charts/chart/type) { get; set; } | Επιστρέφει ή ορίζει τον τύπο του διαγράμματος. Ανάγνωση/εγγραφή [`ChartType`](../charttype). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Επιστρέφει ένα εσωτερικό, περιορισμένο σε παρουσία αναγνωριστικό προορισμένο για χρήση από πρόσθετα ή άλλον κώδικα. Δεδομένου ότι αυτή η τιμή μπορεί να επαναχρησιμοποιηθεί από το χρήστη ή προγραμματιστικά, δεν πρέπει να αντιμετωπίζεται ως μόνιμο μοναδικό κλειδί. Μόνο ανάγνωση UInt32. Δείτε επίσης [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [UserShapes](../../aspose.slides.charts/chart/usershapes) { get; } | Καθορίζει τα σχήματα που σχεδιάζονται πάνω από το διάγραμμα. Μόνο ανάγνωση [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Αποκτά ή ορίζει το πλάτος του σχήματος, μετρημένο σε points. Ανάγνωση/εγγραφή Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Αποκτά ή ορίζει τη συντεταγμένη x του άνω αριστερού γωνίου του σχήματος, μετρημένη σε points. Ανάγνωση/εγγραφή Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Αποκτά ή ορίζει τη συντεταγμένη y του άνω αριστερού γωνίου του σχήματος, μετρημένη σε points. Ανάγνωση/εγγραφή Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Επιστρέφει τη θέση ενός σχήματος στην τάξη z. Shapes[0] επιστρέφει το σχήμα στο πίσω μέρος της τάξης z, και Shapes[Shapes.Count - 1] επιστρέφει το σχήμα στο μπροστινό μέρος της τάξης z. Μόνο ανάγνωση Int32. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Προσθέτει ένα νέο placeholder εάν δεν υπάρχει και ορίζει τις ιδιότητες του placeholder σε ένα καθορισμένο. |
| [CreateThemeEffective](../../aspose.slides.charts/chart/createthemeeffective)() | Επιστρέφει ένα αποτελεσματικό θέμα για αυτό το διάγραμμα. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Επιστρέφει ένα βασικό σχήμα placeholder (σχήμα από τη διάταξη και/ή τη διαφάνεια προτύπου από το οποίο κληρονομείται το τρέχον σχήμα). Επιστρέφεται null εάν το τρέχον σχήμα δεν είναι κληρονομικό. |
| [GetImage](../../aspose.slides/shape/getimage)() | Επιστρέφει τη μικρογραφία του σχήματος. Ο τύπος ShapeThumbnailBounds.Shape χρησιμοποιείται ως προεπιλογή για τα όρια της μικρογραφίας. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Επιστρέφει τη μικρογραφία του σχήματος. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Αποκτά τα οπτικά όρια του σχήματος, υπολογισμένα από το εμφανιζόμενο περιεχόμενό του. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Ορίζει ότι αυτό το σχήμα δεν είναι placeholder. |
| [ValidateChartLayout](../../aspose.slides.charts/chart/validatechartlayout)() | Υπολογίζει τις πραγματικές τιμές των στοιχείων του διαγράμματος. Οι πραγματικές τιμές περιλαμβάνουν τη θέση των στοιχείων που υλοποιούν τη διεπαφή IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) και τις πραγματικές τιμές των αξόνων (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale). |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |

### Δείτε επίσης

* κλάση [GraphicalObject](../../aspose.slides/graphicalobject)
* διεπαφή [IChart](../ichart)
* χώρος ονομάτων [Aspose.Slides.Charts](../../aspose.slides.charts)
* συγκρότημα [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->