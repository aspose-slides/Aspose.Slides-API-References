---
title: Trendline class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.charts/trendline/
---
## Trendline κλάση

Class represents trend line of chart series

The Trendline type exposes the following members:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`trendline_name`](/slides/python-net/el/aspose.slides.charts/trendline/trendline_name/) | Λαμβάνει ή ορίζει το όνομα της γραμμής τάσης.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`trendline_type`](/slides/python-net/el/aspose.slides.charts/trendline/trendline_type/) | Λαμβάνει ή ορίζει τον τύπο της γραμμής τάσης.<br/>            Ανάγνωση/εγγραφή [`TrendlineType`](/slides/python-net/el/aspose.slides.charts/trendlinetype). |
| [`format`](/slides/python-net/el/aspose.slides.charts/trendline/format/) | Αντιπροσωπεύει τη μορφή της γραμμής τάσης.<br/>            Ανάγνωση/εγγραφή [`IFormat`](/slides/python-net/el/aspose.slides.charts/iformat). |
| [`backward`](/slides/python-net/el/aspose.slides.charts/trendline/backward/) | Καθορίζει τον αριθμό των κατηγοριών (ή μονάδων σε διάγραμμα διασποράς) που η γραμμή τάσης εκτείνεται πριν<br/>            τα δεδομένα για τη σειρά που καταγράφεται. Σε διαγράμματα διασποράς και μη-διασποράς, η τιμή πρέπει να είναι μη-αρνητική<br/>            τιμή.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`forward`](/slides/python-net/el/aspose.slides.charts/trendline/forward/) | Καθορίζει τον αριθμό των κατηγοριών (ή μονάδων σε διάγραμμα διασποράς) που η γραμμή τάσης εκτείνεται μετά τα δεδομένα<br/>            για τη σειρά που καταγράφεται. Σε διαγράμματα διασποράς και μη-διασποράς, η τιμή πρέπει να είναι μη-αρνητική<br/>            τιμή.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`intercept`](/slides/python-net/el/aspose.slides.charts/trendline/intercept/) | Καθορίζει την τιμή όπου η γραμμή τάσης διασχίζει τον άξονα y. Αυτή η ιδιότητα υποστηρίζεται μόνο<br/>            όταν ο τύπος γραμμής τάσης είναι exp, linear ή poly.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`display_equation`](/slides/python-net/el/aspose.slides.charts/trendline/display_equation/) | Καθορίζει ότι η εξίσωση για τη γραμμή τάσης εμφανίζεται στο διάγραμμα (στην ίδια ετικέτα με την τιμή Rsquared).<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`order`](/slides/python-net/el/aspose.slides.charts/trendline/order/) | Καθορίζει τη σειρά της πολυωνυμικής γραμμής τάσης. Παράβλεπται για άλλους τύπους γραμμής τάσης. Η τιμή πρέπει να είναι μεταξύ 2 και 6.<br/>            Ανάγνωση/εγγραφή **int**. |
| [`period`](/slides/python-net/el/aspose.slides.charts/trendline/period/) | Καθορίζει την περίοδο της γραμμής τάσης για μια γραμμή τάσης κινητού μέσου. Παράβλεπται για άλλες<br/>            παραλλαγές γραμμής τάσης. Η τιμή πρέπει να είναι μεταξύ 2 και 255.<br/>            Ανάγνωση/εγγραφή **int**. |
| [`display_r_squared_value`](/slides/python-net/el/aspose.slides.charts/trendline/display_r_squared_value/) | Καθορίζει ότι η τιμή R-squared της γραμμής τάσης εμφανίζεται στο διάγραμμα (στην ίδια ετικέτα με την εξίσωση).<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`related_legend_entry`](/slides/python-net/el/aspose.slides.charts/trendline/related_legend_entry/) | Αντιπροσωπεύει την καταχώριση υπόμνου που σχετίζεται με αυτή τη γραμμή τάσης<br/>            Μόνο για ανάγνωση [`ILegendEntryProperties`](/slides/python-net/el/aspose.slides.charts/ilegendentryproperties). |
| [`text_frame_for_overriding`](/slides/python-net/el/aspose.slides.charts/trendline/text_frame_for_overriding/) | Μπορεί να περιέχει πλούσιο μορφοποιημένο κείμενο. Εάν αυτή η ιδιότητα δεν είναι None, τότε αυτή η <br/>            μορφοποιημένη τιμή κειμένου αντικαθιστά το αυτόματα παραγόμενο κείμενο της ετικέτας δεδομένων.<br/>            Το αυτόματα παραγόμενο κείμενο της ετικέτας δεδομένων σημαίνει το κείμενο που διαχειρίζεται από τις ιδιότητες ShowSeriesName, <br/>            ShowValue, ... και μορφοποιείται με την ιδιότητα TextFormatManager.TextFormat.<br/>            Μόνο για ανάγνωση [`ITextFrame`](/slides/python-net/el/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/el/aspose.slides.charts/trendline/text_format/) | Επιστρέφει τη μορφή κειμένου.<br/>            Μόνο για ανάγνωση [`IChartTextFormat`](/slides/python-net/el/aspose.slides.charts/icharttextformat). |
| [`chart`](/slides/python-net/el/aspose.slides.charts/trendline/chart/) | Επιστρέφει το γονικό διάγραμμα.<br/>            Μόνο για ανάγνωση [`IChart`](/slides/python-net/el/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/el/aspose.slides.charts/trendline/slide/) |  |
| [`presentation`](/slides/python-net/el/aspose.slides.charts/trendline/presentation/) |  |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/el/aspose.slides.charts/trendline/add_text_frame_for_overriding/#str) | Αρχικοποιεί το TextFrameForOverriding με το κείμενο στην παράμετρο "text".<br/>            Εάν το TextFrameForOverriding είναι ήδη αρχικοποιημένο, τότε απλώς αλλάζει το κείμενό του. |

### Δείτε επίσης
* μονάδα [`aspose.slides.charts`](/slides/python-net/el/aspose.slides.charts)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)