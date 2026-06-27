---
title: Chart
second_title: Aspose.Sildes για .NET Αναφορά API
description: Αντιπροσωπεύει ένα γραφικό διάγραμμα σε μια διαφάνεια.
type: docs
weight: 1240
url: /el/aspose.slides.charts/chart/
---
## Κλάση Chart

Αντιπροσωπεύει ένα γραφικό διάγραμμα σε μια διαφάνεια.

```csharp
public class Chart : GraphicalObject, IChart
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Επιστρέφει ή ορίζει το εναλλακτικό κείμενο που σχετίζεται με ένα σχήμα. Ανάγνωση/εγγραφή String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Επιστρέφει ή ορίζει τον τίτλο του εναλλακτικού κειμένου που σχετίζεται με ένα σχήμα. Ανάγνωση/εγγραφή String. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/chart/asiformattedtextcontainer) { get; } | Επιτρέπει την απόκτηση της βασικής διεπαφής IFormattedTextContainer. Μόνο για ανάγνωση [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIThemeable](../../aspose.slides.charts/chart/asithemeable) { get; } | Επιτρέπει την απόκτηση της βασικής διεπαφής IThemeable. Μόνο για ανάγνωση [`IThemeable`](../../aspose.slides.theme/ithemeable). |
| [Axes](../../aspose.slides.charts/chart/axes) { get; } | Παρέχει πρόσβαση στους άξονες του διαγράμματος. Μόνο για ανάγνωση [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/chart/backwall) { get; } | Επιστρέφει ένα αντικείμενο που επιτρέπει την αλλαγή της μορφής του πίσω τοίχου ενός τρισδιάστατου διαγράμματος. Μόνο για ανάγνωση [`IChartWall`](../ichartwall). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Η ιδιότητα καθορίζει πώς θα αποδίδεται ένα σχήμα σε λειτουργία ασπρόμαυρης εμφάνισης. Ανάγνωση/εγγραφή [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ChartData](../../aspose.slides.charts/chart/chartdata) { get; } | Επιστρέφει πληροφορίες σχετικά με τα συνδεμένα ή ενσωματωμένα δεδομένα που σχετίζονται με ένα διάγραμμα. Μόνο για ανάγνωση [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/chart/chartdatatable) { get; } | Επιστρέφει έναν πίνακα δεδομένων ενός διαγράμματος. Μόνο για ανάγνωση [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/chart/charttitle) { get; } | Επιστρέφει ή ορίζει τον τίτλο του διαγράμματος. Μόνο για ανάγνωση [`IChartTitle`](../icharttitle). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σχήμα. Μόνο για ανάγνωση Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος. Μόνο για ανάγνωση [`ICustomData`](../../aspose.slides/icustomdata). |
| [DisplayBlanksAs](../../aspose.slides.charts/chart/displayblanksas) { get; set; } | Επιστρέφει ή ορίζει τον τρόπο απεικόνισης των κενών κελιών σε ένα διάγραμμα. Ανάγνωση/εγγραφή [`DisplayBlanksAsType`](../displayblanksastype). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Επιστρέφει το αντικείμενο EffectFormat που περιέχει εφέ εικονοστοιχείων που εφαρμόζονται σε ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες εφέ. Μόνο για ανάγνωση [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Επιστρέφει το αντικείμενο FillFormat που περιέχει τις ιδιότητες διαμόρφωσης γεμίσματος για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γεμίσματος. Μόνο για ανάγνωση [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Floor](../../aspose.slides.charts/chart/floor) { get; } | Επιστρέφει ένα αντικείμενο που επιτρέπει την αλλαγή της μορφής του πατώματος ενός τρισδιάστατου διαγράμματος. Μόνο για ανάγνωση [`IChartWall`](../ichartwall). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Επιστρέφει ή ορίζει τις ιδιότητες του πλαισίου σχήματος. Ανάγνωση/εγγραφή [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Επιστρέφει τις κλειδώσεις του σχήματος. Μόνο για ανάγνωση [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [HasDataTable](../../aspose.slides.charts/chart/hasdatatable) { get; set; } | Καθορίζει αν ένα διάγραμμα έχει πίνακα δεδομένων. Ανάγνωση/εγγραφή Boolean. |
| [HasLegend](../../aspose.slides.charts/chart/haslegend) { get; set; } | Καθορίζει αν ένα διάγραμμα έχει υπόμνημα. Ανάγνωση/εγγραφή Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/chart/hasroundedcorners) { get; set; } | Καθορίζει ότι η περιοχή του διαγράμματος θα έχει στρογγυλεμένες γωνίες. Ανάγνωση/εγγραφή Boolean. |
| [HasTitle](../../aspose.slides.charts/chart/hastitle) { get; set; } | Καθορίζει αν ένα διάγραμμα έχει ορατό τίτλο. Ανάγνωση/εγγραφή Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | Επιστρέφει ή ορίζει το ύψος του σχήματος, μετρημένο σε μονάδες point. Ανάγνωση/εγγραφή Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Καθορίζει αν το σχήμα είναι κρυφό. Ανάγνωση/εγγραφή Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίστηκε για κλικ ποντικιού. Ανάγνωση/εγγραφή [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Επιστρέφει τον διαχειριστή υπερσυνδέσμων. Μόνο για ανάγνωση [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίστηκε για αιώρηση ποντικιού. Ανάγνωση/εγγραφή [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Επιστρέφει ή ορίζει την επιλογή 'Mark as decorative'. Ανάγνωση/εγγραφή Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Καθορίζει αν το σχήμα είναι ομαδοποιημένο. Μόνο για ανάγνωση Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Καθορίζει αν το σχήμα είναι TextHolder_PPT. Μόνο για ανάγνωση Boolean. |
| [Legend](../../aspose.slides.charts/chart/legend) { get; } | Επιστρέφει ή ορίζει ένα υπόμνημα για ένα διάγραμμα. Μόνο για ανάγνωση [`ILegend`](../ilegend). |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Επιστρέφει το αντικείμενο LineFormat που περιέχει τις ιδιότητες μορφοποίησης γραμμής για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γραμμής. Μόνο για ανάγνωση [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Επιστρέφει ή ορίζει το όνομα ενός σχήματος. Πρέπει να μην είναι null. Χρησιμοποιήστε κενό string αν χρειάζεται. Ανάγνωση/εγγραφή String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Επιστρέφει ένα μοναδικό αναγνωριστικό περιορισμένο στη διαφάνεια που παραμένει σταθερό για τη διάρκεια του σχήματος και επιτρέπει στο PowerPoint ή στον κώδικα διασύνδεσης να αναφερθεί αξιόπιστα στο σχήμα από οπουδήποτε στο έγγραφο. Μόνο για ανάγνωση UInt32. Δείτε επίσης [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Επιστρέφει το γονικό αντικείμενο GroupShape εάν το σχήμα είναι ομαδοποιημένο. Διαφορετικά επιστρέφει null. Μόνο για ανάγνωση [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Επιστρέφει το σύμβολο κράτησης θέσης (placeholder) για ένα σχήμα. Επιστρέφει null εάν το σχήμα δεν έχει placeholder. Μόνο για ανάγνωση [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [PlotArea](../../aspose.slides.charts/chart/plotarea) { get; } | Αντιπροσωπεύει την περιοχή σχεδίασης ενός διαγράμματος. Μόνο για ανάγνωση [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/chart/plotvisiblecellsonly) { get; set; } | Καθορίζει αν θα σχεδιαστούν μόνο τα ορατά κελιά. False για σχεδίαση τόσο ορατών όσο και κρυφών κελιά. Ανάγνωση/εγγραφή Boolean. |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Επιστρέφει τη γονική παρουσίαση μια διαφάνειας. Μόνο για ανάγνωση [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Επιστρέφει ή ορίζει τις ακατέργαστες ιδιότητες πλαισίου σχήματος. Ανάγνωση/εγγραφή [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Επιστρέφει ή ορίζει τον αριθμό των μοιρών με τους οποίους το συγκεκριμένο σχήμα περιστρέφεται γύρω από τον άξονα z. Μία θετική τιμή υποδηλώνει δεξιόστροφη περιστροφή· μία αρνητική τιμή υποδηλώνει αριστερόστροφη περιστροφή. Ανάγνωση/εγγραφή Single. |
| [Rotation3D](../../aspose.slides.charts/chart/rotation3d) { get; } | Επιστρέφει μια τρισδιάστατη περιστροφή ενός διαγράμματος. Μόνο για ανάγνωση [`IRotation3D`](../irotation3d). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Επιστρέφει τις κλειδώσεις του σχήματος. Μόνο για ανάγνωση [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 ιδιότητες) |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/chart/showdatalabelsovermaximum) { get; set; } | Καθορίζει αν θα εμφανίζονται ετικέτες δεδομένων πάνω από το μέγιστο του διαγράμματος. Ανάγνωση/εγγραφή Boolean. |
| [SideWall](../../aspose.slides.charts/chart/sidewall) { get; } | Επιστρέφει ένα αντικείμενο που επιτρέπει την αλλαγή της μορφής του πλάγιου τοίχου ενός τρισδιάστατου διαγράμματος. Μόνο για ανάγνωση [`IChartWall`](../ichartwall). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Επιστρέφει τη γονική διαφάνεια ενός σχήματος. Μόνο για ανάγνωση [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [Style](../../aspose.slides.charts/chart/style) { get; set; } | Επιστρέφει ή ορίζει το στυλ του διαγράμματος. Ανάγνωση/εγγραφή [`StyleType`](../styletype). |
| [TextFormat](../../aspose.slides.charts/chart/textformat) { get; } | Επιστρέφει τη μορφή κειμένου του διαγράμματος. Η ιδιότητα δεν ισχύει για τους παρακάτω τύπους: Treemap, Sunburst, Waterfall, Histogram, Funnel, BoxAndWhisker. Μόνο για ανάγνωση [`IChartTextFormat`](../icharttextformat). |
| [ThemeManager](../../aspose.slides.charts/chart/thememanager) { get; } | Επιστρέφει τον διαχειριστή θέματος. Μόνο για ανάγνωση [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Επιστρέφει το αντικείμενο ThreeDFormat που περιέχει τις ιδιότητες 3D εφέ για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν 3D ιδιότητες. Μόνο για ανάγνωση [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Type](../../aspose.slides.charts/chart/type) { get; set; } | Επιστρέφει ή ορίζει τον τύπο του διαγράμματος. Ανάγνωση/εγγραφή [`ChartType`](../charttype). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Επιστρέφει ένα εσωτερικό, περιορισμένο στην παρουσίαση αναγνωριστικό που προορίζεται για χρήση από πρόσθετα ή άλλον κώδικα. Δεδομένου ότι αυτή η τιμή μπορεί να επανατοποθετηθεί από το χρήστη ή προγραμματιστικά, δεν πρέπει να αντιμετωπίζεται ως μόνιμο μοναδικό κλειδί. Μόνο για ανάγνωση UInt32. Δείτε επίσης [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [UserShapes](../../aspose.slides.charts/chart/usershapes) { get; } | Καθορίζει τα σχήματα που σχεδιάζονται πάνω από το διάγραμμα. Μόνο για ανάγνωση [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Επιστρέφει ή ορίζει το πλάτος του σχήματος, μετρημένο σε μονάδες point. Ανάγνωση/εγγραφή Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Επιστρέφει ή ορίζει τη συντεταγμένη x του επάνω-αριστερού γωνιακού σημείου του σχήματος, μετρημένη σε μονάδες point. Ανάγνωση/εγγραφή Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Επιστρέφει ή ορίζει τη συντεταγμένη y του επάνω-αριστερού γωνιακού σημείου του σχήματος, μετρημένη σε μονάδες point. Ανάγνωση/εγγραφή Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Επιστρέφει τη θέση ενός σχήματος στη σειρά z. Το Shapes[0] επιστρέφει το σχήμα στο βάθος της σειράς z, και το Shapes[Shapes.Count - 1] επιστρέφει το σχήμα στο μπροστινό μέρος της σειράς z. Μόνο για ανάγνωση Int32. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Προσθέτει ένα νέο placeholder εάν δεν υπάρχει και ορίζει τις ιδιότητες του placeholder σε ένα καθορισμένο. |
| [CreateThemeEffective](../../aspose.slides.charts/chart/createthemeeffective)() | Επιστρέφει ένα αποτελεσματικό θέμα για αυτό το διάγραμμα. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Επιστρέφει ένα βασικό σχήμα placeholder (σχήμα από τη διάταξη και/ή την κύρια διαφάνεια από το οποίο κληρονομείται το τρέχον σχήμα). Επιστρέφεται null εάν το τρέχον σχήμα δεν κληρονομείται. |
| [GetImage](../../aspose.slides/shape/getimage)() | Επιστρέφει μικρογραφία σχήματος. Η προεπιλεγμένη τιμή είναι ShapeThumbnailBounds.Shape για τα όρια της μικρογραφίας. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Επιστρέφει μικρογραφία σχήματος. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Αποκτά τα οπτικά όρια του σχήματος, υπολογισμένα από το αποδοθέν περιεχόμενό του. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Ορίζει ότι αυτό το σχήμα δεν είναι placeholder. |
| [ValidateChartLayout](../../aspose.slides.charts/chart/validatechartlayout)() | Υπολογίζει τις πραγματικές τιμές των στοιχείων του διαγράμματος. Οι πραγματικές τιμές περιλαμβάνουν τη θέση των στοιχείων που υλοποιούν το interface IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) και τις πραγματικές τιμές των αξόνων (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale). |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |

### Δείτε επίσης

* κλάση [GraphicalObject](../../aspose.slides/graphicalobject)
* διασύνδεση [IChart](../ichart)
* χώρο ονομάτων [Aspose.Slides.Charts](../../aspose.slides.charts)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->