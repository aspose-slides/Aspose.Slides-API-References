---
title: DataLabel class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.charts/datalabel/
---
## DataLabel κλάση

Αναπαριστά τις ετικέτες σειράς.

Ο τύπος DataLabel αποκαλύπτει τα ακόλουθα μέλη:

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [`__init__(self, parent_immediate)`](/slides/python-net/el/aspose.slides.charts/datalabel/__init__/#ichartdatapoint) | Δημιουργεί μια νέα παρουσία της κλάσης DataLabel. |

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`chart`](/slides/python-net/el/aspose.slides.charts/datalabel/chart/) | Επιστρέφει το γονικό διάγραμμα.<br/>            Μόνο ανάγνωση [`IChart`](/slides/python-net/el/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/el/aspose.slides.charts/datalabel/is_visible/) | False σημαίνει ότι η ετικέτα δεδομένων δεν είναι ορατή (και έτσι όλες οι σημαίες Show*- (ShowValue, ...) είναι false).<br/>            Μόνο ανάγνωση **bool**. |
| [`text_frame_for_overriding`](/slides/python-net/el/aspose.slides.charts/datalabel/text_frame_for_overriding/) | Μπορεί να περιέχει πλούσιο μορφοποιημένο κείμενο. Εάν αυτή η ιδιότητα δεν είναι None, τότε αυτή η <br/>            μορφοποιημένη τιμή κειμένου αντικαθιστά το αυτόματα δημιουργημένο κείμενο της ετικέτας δεδομένων.<br/>            Το αυτόματα δημιουργημένο κείμενο της ετικέτας δεδομένων σημαίνει κείμενο που διαχειρίζεται από τις ιδιότητες ShowSeriesName, <br/>            ShowValue, ... και μορφοποιείται με την ιδιότητα TextFormatManager.TextFormat.<br/>            Μόνο ανάγνωση [`ITextFrame`](/slides/python-net/el/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/el/aspose.slides.charts/datalabel/text_format/) | Επιστρέφει τη μορφή κειμένου.<br/>            Μόνο ανάγνωση [`IChartTextFormat`](/slides/python-net/el/aspose.slides.charts/icharttextformat). |
| [`x`](/slides/python-net/el/aspose.slides.charts/datalabel/x/) | Επιστρέφει ή ορίζει τη συντεταγμένη x ενός τίτλου ως κλάσμα του πλάτους του διαγράμματος.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`y`](/slides/python-net/el/aspose.slides.charts/datalabel/y/) | Επιστρέφει ή ορίζει τη συντεταγμένη y ενός τίτλου ως κλάσμα του ύψους του διαγράμματος.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`width`](/slides/python-net/el/aspose.slides.charts/datalabel/width/) | Επιστρέφει ή ορίζει το πλάτος ενός τίτλου ως κλάσμα του πλάτους του διαγράμματος.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`height`](/slides/python-net/el/aspose.slides.charts/datalabel/height/) | Επιστρέφει ή ορίζει το ύψος ενός τίτλου ως κλάσμα του ύψους του διαγράμματος.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`right`](/slides/python-net/el/aspose.slides.charts/datalabel/right/) | Δεξιά.<br/>            Μόνο ανάγνωση **float**. |
| [`bottom`](/slides/python-net/el/aspose.slides.charts/datalabel/bottom/) | Κάτω.<br/>            Μόνο ανάγνωση **float**. |
| [`data_label_format`](/slides/python-net/el/aspose.slides.charts/datalabel/data_label_format/) | Επιστρέφει τη μορφή ετικέτας δεδομένων.<br/>            Μόνο ανάγνωση [`IDataLabelFormat`](/slides/python-net/el/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/el/aspose.slides.charts/datalabel/value_from_cell/) | Αποκτά ή ορίζει το κελί δεδομένων του βιβλίου εργασίας. Εφαρμόζεται αν η ιδιότητα IDataLabelFormat.ShowLabelValueFromCell ισούται με true. |
| [`actual_x`](/slides/python-net/el/aspose.slides.charts/datalabel/actual_x/) | Καθορίζει την πραγματική θέση x (αριστερά) του στοιχείου του διαγράμματος σε σχέση με την αριστερή πάνω γωνία του διαγράμματος.<br/>            Καλέστε τη μέθοδο IChart.ValidateChartLayout() πριν για να λάβετε τις πραγματικές τιμές. <br/>            Ανάγνωση **float**. |
| [`actual_y`](/slides/python-net/el/aspose.slides.charts/datalabel/actual_y/) | Καθορίζει την πραγματική κορυφή του στοιχείου του διαγράμματος σε σχέση με την αριστερή πάνω γωνία του διαγράμματος.<br/>            Καλέστε τη μέθοδο IChart.ValidateChartLayout() πριν για να λάβετε τις πραγματικές τιμές. <br/>            Ανάγνωση **float**. |
| [`actual_width`](/slides/python-net/el/aspose.slides.charts/datalabel/actual_width/) | Καθορίζει το πραγματικό πλάτος του στοιχείου του διαγράμματος. Καλέστε τη μέθοδο IChart.ValidateChartLayout() πριν για να λάβετε τις πραγματικές τιμές. <br/>            Ανάγνωση **float**. |
| [`actual_height`](/slides/python-net/el/aspose.slides.charts/datalabel/actual_height/) | Καθορίζει το πραγματικό ύψος του στοιχείου του διαγράμματος. Καλέστε τη μέθοδο IChart.ValidateChartLayout() πριν για να λάβετε τις πραγματικές τιμές. <br/>            Ανάγνωση **float**. |
| [`slide`](/slides/python-net/el/aspose.slides.charts/datalabel/slide/) |  |
| [`presentation`](/slides/python-net/el/aspose.slides.charts/datalabel/presentation/) |  |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`hide(self)`](/slides/python-net/el/aspose.slides.charts/datalabel/hide/#) | Κάνει την ετικέτα δεδομένων κρυφή ορίζοντας όλες τις σημαίες Show*- (ShowValue, ...) σε κατάσταση false.<br/>            Το IsVisible θα είναι false μετά από αυτό. |
| [`get_actual_label_text(self)`](/slides/python-net/el/aspose.slides.charts/datalabel/get_actual_label_text/#) | Επιστρέφει το πραγματικό κείμενο ετικέτας βάσει των ρυθμίσεων DataLabelFormat ή της τιμής TextFrameForOverriding.Text. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/el/aspose.slides.charts/datalabel/add_text_frame_for_overriding/#str) | Αρχικοποιεί το TextFrameForOverriding με το κείμενο στην παράμετρο "text".<br/>            Εάν το TextFrameForOverriding είναι ήδη αρχικοποιημένο, τότε απλώς αλλάζει το κείμενό του. |

### Δείτε επίσης
* μονάδα [`aspose.slides.charts`](/slides/python-net/el/aspose.slides.charts)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)