---
title: DataLabel
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αναπαριστά ετικέτες σειράς.
type: docs
weight: 1560
url: /el/aspose.slides.charts/datalabel/
---
## DataLabel κλάση

Αναπαριστά ετικέτες σειράς.

```csharp
public class DataLabel : IDataLabel
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [DataLabel](datalabel)(IChartDataPoint) | Δημιουργεί μια νέα εμφάνιση της κλάσης DataLabel. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/datalabel/actualheight) { get; } | Καθορίζει το πραγματικό ύψος του στοιχείου διαγράμματος. Καλέστε τη μέθοδο IChart.ValidateChartLayout() πριν για να λάβετε τις πραγματικές τιμές. Μόνο για ανάγνωση Single. |
| [ActualWidth](../../aspose.slides.charts/datalabel/actualwidth) { get; } | Καθορίζει το πραγματικό πλάτος του στοιχείου διαγράμματος. Καλέστε τη μέθοδο IChart.ValidateChartLayout() πριν για να λάβετε τις πραγματικές τιμές. Μόνο για ανάγνωση Single. |
| [ActualX](../../aspose.slides.charts/datalabel/actualx) { get; } | Καθορίζει την πραγματική θέση x (αριστερά) του στοιχείου διαγράμματος σε σχέση με την επάνω αριστερή γωνία του διαγράμματος. Καλέστε τη μέθοδο IChart.ValidateChartLayout() πριν για να λάβετε τις πραγματικές τιμές. Μόνο για ανάγνωση Single. |
| [ActualY](../../aspose.slides.charts/datalabel/actualy) { get; } | Καθορίζει την πραγματική άνω θέση του στοιχείου διαγράμματος σε σχέση με την επάνω αριστερή γωνία του διαγράμματος. Καλέστε τη μέθοδο IChart.ValidateChartLayout() πριν για να λάβετε τις πραγματικές τιμές. Μόνο για ανάγνωση Single. |
| [Bottom](../../aspose.slides.charts/datalabel/bottom) { get; } | Κάτω. Μόνο για ανάγνωση Single. |
| [Chart](../../aspose.slides.charts/datalabel/chart) { get; } | Επιστρέφει το γονικό διάγραμμα. Μόνο για ανάγνωση [`IChart`](../ichart). |
| [DataLabelFormat](../../aspose.slides.charts/datalabel/datalabelformat) { get; } | Επιστρέφει τη μορφή ετικέτας δεδομένων. Μόνο για ανάγνωση [`IDataLabelFormat`](../idatalabelformat). |
| [Height](../../aspose.slides.charts/datalabel/height) { get; set; } | Επιστρέφει ή ορίζει το ύψος ενός τίτλου ως κλάσμα του ύψους του διαγράμματος. Ανάγνωση/εγγραφή Single. |
| [IsVisible](../../aspose.slides.charts/datalabel/isvisible) { get; } | Το False σημαίνει ότι η ετικέτα δεδομένων δεν είναι ορατή (και έτσι όλες οι σημαίες Show*- (ShowValue, ...) είναι False). Μόνο για ανάγνωση Boolean. |
| [LabelShapeType](../../aspose.slides.charts/datalabel/labelshapetype) { get; set; } | Λαμβάνει ή ορίζει τον τύπο σχήματος της ετικέτας δεδομένων. Επιστρέφει NotDefined εάν δεν έχει οριστεί σχήμα. |
| [Right](../../aspose.slides.charts/datalabel/right) { get; } | Δεξιά. Μόνο για ανάγνωση Single. |
| [TextFormat](../../aspose.slides.charts/datalabel/textformat) { get; } | Επιστρέφει τη μορφή κειμένου. Μόνο για ανάγνωση [`IChartTextFormat`](../icharttextformat). |
| [TextFrameForOverriding](../../aspose.slides.charts/datalabel/textframeforoverriding) { get; } | Μπορεί να περιέχει πλούσιο μορφοποιημένο κείμενο. Εάν αυτή η ιδιότητα δεν είναι null, τότε αυτή η μορφοποιημένη τιμή κειμένου αντικαθιστά το αυτόματα παραγόμενο κείμενο της ετικέτας δεδομένων. Το αυτόματα παραγόμενο κείμενο της ετικέτας δεδομένων σημαίνει κείμενο που διαχειρίζεται από τις ιδιότητες ShowSeriesName, ShowValue, ... και μορφοποιείται με την ιδιότητα TextFormatManager.TextFormat. Μόνο για ανάγνωση [`ITextFrame`](../../aspose.slides/itextframe). |
| [ValueFromCell](../../aspose.slides.charts/datalabel/valuefromcell) { get; set; } | Λαμβάνει ή ορίζει το κελί δεδομένων του βιβλίου εργασίας. Εφαρμόζεται εάν η ιδιότητα IDataLabelFormat.ShowLabelValueFromCell ισούται με true. |
| [Width](../../aspose.slides.charts/datalabel/width) { get; set; } | Επιστρέφει ή ορίζει το πλάτος ενός τίτλου ως κλάσμα του πλάτους του διαγράμματος. Ανάγνωση/εγγραφή Single. |
| [X](../../aspose.slides.charts/datalabel/x) { get; set; } | Επιστρέφει ή ορίζει τη συντεταγμένη x ενός τίτλου ως κλάσμα του πλάτους του διαγράμματος. Ανάγνωση/εγγραφή Single. |
| [Y](../../aspose.slides.charts/datalabel/y) { get; set; } | Επιστρέφει ή ορίζει τη συντεταγμένη y ενός τίτλου ως κλάσμα του ύψους του διαγράμματος. Ανάγνωση/εγγραφή Single. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddTextFrameForOverriding](../../aspose.slides.charts/datalabel/addtextframeforoverriding)(string) | Αρχικοποιεί το TextFrameForOverriding με το κείμενο στην παράμετρο "text". Εάν το TextFrameForOverriding είναι ήδη αρχικοποιημένο, τότε απλώς αλλάζει το κείμενό του. |
| [GetActualLabelText](../../aspose.slides.charts/datalabel/getactuallabeltext)() | Επιστρέφει το πραγματικό κείμενο ετικέτας βάσει των ρυθμίσεων DataLabelFormat ή της τιμής TextFrameForOverriding.Text. |
| [Hide](../../aspose.slides.charts/datalabel/hide)() | Κάνει την ετικέτα δεδομένων κρυφή ορίζοντας όλες τις σημαίες Show*- (ShowValue, ...) σε κατάσταση false. Το IsVisible θα είναι false μετά από αυτό. |

### Δείτε επίσης

* διεπαφή [IDataLabel](../idatalabel)
* χώρος ονομάτων [Aspose.Slides.Charts](../../aspose.slides.charts)
* συγκρότηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->