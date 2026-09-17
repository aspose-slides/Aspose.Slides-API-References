---
title: Axis class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.charts/axis/
---
## Axis κλάση

Encapsulates the object that represents a chart's axis.

The Axis type exposes the following members:

## Ιδιότητες

| Property | Description |
| :- | :- |
| [`chart`](/slides/python-net/el/aspose.slides.charts/axis/chart/) | Επιστρέφει το γονικό διάγραμμα.<br/>            Μόνο-ανάγνωση [`IChart`](/slides/python-net/el/aspose.slides.charts/ichart). |
| [`axis_between_categories`](/slides/python-net/el/aspose.slides.charts/axis/axis_between_categories/) | Αντιπροσωπεύει αν ο άξονας τιμών διασχίζει τον άξονα κατηγορίας μεταξύ των κατηγοριών.<br/>             Αυτή η ιδιότητα εφαρμόζεται μόνο σε άξονες κατηγορίας και δεν εφαρμόζεται σε 3-D διαγράμματα.<br/>             Ανάγνωση/εγγραφή **bool**. |
| [`category_axis_type`](/slides/python-net/el/aspose.slides.charts/axis/category_axis_type/) | Καθορίζει τον τύπο του άξονα κατηγορίας.<br/>            Ανάγνωση/εγγραφή [`CategoryAxisType`](/slides/python-net/el/aspose.slides.charts/categoryaxistype). |
| [`cross_at`](/slides/python-net/el/aspose.slides.charts/axis/cross_at/) | Αντιπροσωπεύει το σημείο στον άξονα όπου ο κάθετος άξονας τον διασχίζει.<br/>             Ανάγνωση/εγγραφή **float**. |
| [`display_unit`](/slides/python-net/el/aspose.slides.charts/axis/display_unit/) | Καθορίζει την κλίμακα των μονάδων εμφάνισης για τον άξονα τιμών.<br/>             Ανάγνωση/εγγραφή [`DisplayUnitType`](/slides/python-net/el/aspose.slides.charts/displayunittype). |
| [`actual_max_value`](/slides/python-net/el/aspose.slides.charts/axis/actual_max_value/) | Καθορίζει την πραγματική μέγιστη τιμή στον άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή. |
| [`actual_min_value`](/slides/python-net/el/aspose.slides.charts/axis/actual_min_value/) | Καθορίζει την πραγματική ελάχιστη τιμή στον άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή. |
| [`actual_major_unit`](/slides/python-net/el/aspose.slides.charts/axis/actual_major_unit/) | Καθορίζει την πραγματική κύρια μονάδα του άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή. |
| [`actual_minor_unit`](/slides/python-net/el/aspose.slides.charts/axis/actual_minor_unit/) | Καθορίζει την πραγματική δευτερεύουσα μονάδα του άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή. |
| [`actual_major_unit_scale`](/slides/python-net/el/aspose.slides.charts/axis/actual_major_unit_scale/) | Καθορίζει την πραγματική κλίμακη κύριας μονάδας του άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή. |
| [`actual_minor_unit_scale`](/slides/python-net/el/aspose.slides.charts/axis/actual_minor_unit_scale/) | Καθορίζει την πραγματική κλίμακη δευτερεύουσας μονάδας του άξονα. Καλέστε τη μέθοδο IChart.ValidateChartLayout() προηγουμένως για να λάβετε την πραγματική τιμή. |
| [`is_automatic_max_value`](/slides/python-net/el/aspose.slides.charts/axis/is_automatic_max_value/) | Δείχνει εάν η μέγιστη τιμή εκχωρείται αυτόματα.<br/>             Ανάγνωση/εγγραφή **bool**. |
| [`max_value`](/slides/python-net/el/aspose.slides.charts/axis/max_value/) | Αντιπροσωπεύει τη μέγιστη τιμή στον άξονα τιμών.<br/>             Ανάγνωση/εγγραφή **float**. |
| [`minor_unit`](/slides/python-net/el/aspose.slides.charts/axis/minor_unit/) | Αντιπροσωπεύει τις δευτερεύουσες μονάδες για τον άξονα ημερομηνίας ή τιμών.<br/>             Ανάγνωση/εγγραφή **float**. |
| [`is_automatic_minor_unit`](/slides/python-net/el/aspose.slides.charts/axis/is_automatic_minor_unit/) | Δείχνει εάν η δευτερεύουσα μονάδα του άξονα εκχωρείται αυτόματα.<br/>             Ανάγνωση/εγγραφή **bool**. |
| [`major_unit`](/slides/python-net/el/aspose.slides.charts/axis/major_unit/) | Αντιπροσωπεύει τις κύριες μονάδες για τον άξονα ημερομηνίας ή τιμών.<br/>             Ανάγνωση/εγγραφή **float**. |
| [`is_automatic_major_unit`](/slides/python-net/el/aspose.slides.charts/axis/is_automatic_major_unit/) | Δείχνει εάν η κύρια μονάδα του άξονα εκχωρείται αυτόματα.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`is_automatic_min_value`](/slides/python-net/el/aspose.slides.charts/axis/is_automatic_min_value/) | Δείχνει εάν η ελάχιστη τιμή εκχωρείται αυτόματα.<br/>             Ανάγνωση/εγγραφή **bool**. |
| [`min_value`](/slides/python-net/el/aspose.slides.charts/axis/min_value/) | Αντιπροσωπεύει την ελάχιστη τιμή στον άξονα τιμών.<br/>             Ανάγνωση/εγγραφή **float**. |
| [`is_logarithmic`](/slides/python-net/el/aspose.slides.charts/axis/is_logarithmic/) | Αντιπροσωπεύει εάν ο τύπος κλίμακας του άξονα τιμών είναι λογαριθμικός ή όχι.<br/>             Ανάγνωση/εγγραφή **bool**. |
| [`log_base`](/slides/python-net/el/aspose.slides.charts/axis/log_base/) | Αντιπροσωπεύει τη λογάριθμη βάση. Η προεπιλογή είναι 10.<br/>             Ανάγνωση/εγγραφή **float**. |
| [`is_plot_order_reversed`](/slides/python-net/el/aspose.slides.charts/axis/is_plot_order_reversed/) | Αντιπροσωπεύει εάν το MS PowerPoint σχεδιάζει τα σημεία δεδομένων από το τελευταίο προς το πρώτο.<br/>             Ανάγνωση/εγγραφή **bool**. |
| [`is_visible`](/slides/python-net/el/aspose.slides.charts/axis/is_visible/) | Αντιπροσωπεύει εάν ο άξονας είναι ορατός.<br/>             Ανάγνωση/εγγραφή **bool**. |
| [`major_tick_mark`](/slides/python-net/el/aspose.slides.charts/axis/major_tick_mark/) | Αντιπροσωπεύει τον τύπο του κύριου σημείου σήμανσης για τον συγκεκριμένο άξονα.<br/>             Ανάγνωση/εγγραφή [`TickMarkType`](/slides/python-net/el/aspose.slides.charts/tickmarktype). |
| [`minor_tick_mark`](/slides/python-net/el/aspose.slides.charts/axis/minor_tick_mark/) | Αντιπροσωπεύει τον τύπο του δευτερεύουσας σημείου σήμανσης για τον συγκεκριμένο άξονα.<br/>             Ανάγνωση/εγγραφή [`TickMarkType`](/slides/python-net/el/aspose.slides.charts/tickmarktype). |
| [`tick_label_position`](/slides/python-net/el/aspose.slides.charts/axis/tick_label_position/) | Αντιπροσωπεύει τη θέση των ετικετών σημείων σήμανσης στον συγκεκριμένο άξονα.<br/>             Ανάγνωση/εγγραφή [`TickLabelPositionType`](/slides/python-net/el/aspose.slides.charts/ticklabelpositiontype). |
| [`major_unit_scale`](/slides/python-net/el/aspose.slides.charts/axis/major_unit_scale/) | Αντιπροσωπεύει την κλίμακη κύριας μονάδας για τον άξονα ημερομηνίας.<br/>             Ανάγνωση/εγγραφή [`TimeUnitType`](/slides/python-net/el/aspose.slides.charts/timeunittype). |
| [`minor_unit_scale`](/slides/python-net/el/aspose.slides.charts/axis/minor_unit_scale/) | Αντιπροσωπεύει την κλίμακη κύριας μονάδας για τον άξονα ημερομηνίας.<br/>             Ανάγνωση/εγγραφή [`TimeUnitType`](/slides/python-net/el/aspose.slides.charts/timeunittype). |
| [`base_unit_scale`](/slides/python-net/el/aspose.slides.charts/axis/base_unit_scale/) | Καθορίζει τη μικρότερη μονάδα χρόνου που αναπαρίσταται στον άξονα ημερομηνίας.<br/>            Ανάγνωση/εγγραφή [`TimeUnitType`](/slides/python-net/el/aspose.slides.charts/timeunittype). |
| [`minor_grid_lines_format`](/slides/python-net/el/aspose.slides.charts/axis/minor_grid_lines_format/) | Αντιπροσωπεύει τη μορφή των δευτερευουσών γραμμών πλέγματος σε άξονα διαγράμματος.<br/>             Μόνο-ανάγνωση [`IChartLinesFormat`](/slides/python-net/el/aspose.slides.charts/ichartlinesformat). |
| [`major_grid_lines_format`](/slides/python-net/el/aspose.slides.charts/axis/major_grid_lines_format/) | Αντιπροσωπεύει τη μορφή των κύριων γραμμών πλέγματος σε άξονα διαγράμματος.<br/>             Μόνο-ανάγνωση [`IChartLinesFormat`](/slides/python-net/el/aspose.slides.charts/ichartlinesformat). |
| [`show_minor_grid_lines`](/slides/python-net/el/aspose.slides.charts/axis/show_minor_grid_lines/) | Για απόκρυψη των δευτερευουσών γραμμών πλέγματος, ορίστε MinorGridLinesFormat.Line.FillFormat.FillType σε FillType.NoFill.<br/>            Μόνο-ανάγνωση **bool**. |
| [`show_major_grid_lines`](/slides/python-net/el/aspose.slides.charts/axis/show_major_grid_lines/) | Για απόκρυψη των κύριων γραμμών πλέγματος, ορίστε MajorGridLinesFormat.Line.FillFormat.FillType σε FillType.NoFill.<br/>            Μόνο-ανάγνωση **bool**. |
| [`format`](/slides/python-net/el/aspose.slides.charts/axis/format/) | Αντιπροσωπεύει τη μορφοποίηση του άξονα.<br/>             Μόνο-ανάγνωση [`IAxisFormat`](/slides/python-net/el/aspose.slides.charts/iaxisformat). |
| [`text_format`](/slides/python-net/el/aspose.slides.charts/axis/text_format/) | Αντιπροσωπεύει τη μορφοποίηση του κειμένου.<br/>             Μόνο-ανάγνωση [`IChartTextFormat`](/slides/python-net/el/aspose.slides.charts/icharttextformat). |
| [`title`](/slides/python-net/el/aspose.slides.charts/axis/title/) | Λαμβάνει τον τίτλο του άξονα.<br/>             Μόνο-ανάγνωση [`IChartTitle`](/slides/python-net/el/aspose.slides.charts/icharttitle). |
| [`cross_type`](/slides/python-net/el/aspose.slides.charts/axis/cross_type/) | Αντιπροσωπεύει τον CrossType στον συγκεκριμένο άξονα όπου διασχίζει ο άλλος άξονας.<br/>             Ανάγνωση/εγγραφή [`CrossesType`](/slides/python-net/el/aspose.slides.charts/crossestype). |
| [`position`](/slides/python-net/el/aspose.slides.charts/axis/position/) | Αντιπροσωπεύει τη θέση του άξονα.<br/>             Ανάγνωση/εγγραφή [`AxisPositionType`](/slides/python-net/el/aspose.slides.charts/axispositiontype). |
| [`has_title`](/slides/python-net/el/aspose.slides.charts/axis/has_title/) | Καθορίζει εάν ένας άξονας έχει ορατό τίτλο.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`number_format`](/slides/python-net/el/aspose.slides.charts/axis/number_format/) | Αντιπροσωπεύει τη συμβολοσειρά μορφής για τις ετικέτες άξονα.<br/>            Ανάγνωση/εγγραφή **str**. |
| [`is_number_format_linked_to_source`](/slides/python-net/el/aspose.slides.charts/axis/is_number_format_linked_to_source/) | Δείχνει εάν η μορφή είναι συνδεδεμένα δεδομένα προέλευσης.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`tick_label_rotation_angle`](/slides/python-net/el/aspose.slides.charts/axis/tick_label_rotation_angle/) | Αντιπροσωπεύει τη γωνία περιστροφής των ετικετών σημείων σήμανσης.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`tick_label_spacing`](/slides/python-net/el/aspose.slides.charts/axis/tick_label_spacing/) | Καθορίζει πόσες ετικέτες σημείων σήμανσης να παραληφθούν μεταξύ των σχεδιασμένων ετικετών. Εφαρμόζεται σε άξονα κατηγορίας ή σειράς.<br/>            Ανάγνωση/εγγραφή **int**. |
| [`is_automatic_tick_label_spacing`](/slides/python-net/el/aspose.slides.charts/axis/is_automatic_tick_label_spacing/) | Καθορίζει την αυτόματη τιμή διάστηματος ετικετών σημείων σήμανσης. Εάν false: χρησιμοποιήστε την ιδιότητα TickLabelSpacing.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`tick_marks_spacing`](/slides/python-net/el/aspose.slides.charts/axis/tick_marks_spacing/) | Καθορίζει πόσες σημαδούρες να παραλειφθούν πριν σχεδιαστεί η επόμενη.<br/>            Εφαρμόζεται σε άξονα κατηγορίας ή σειράς.<br/>            Ανάγνωση/εγγραφή **int**. |
| [`is_automatic_tick_marks_spacing`](/slides/python-net/el/aspose.slides.charts/axis/is_automatic_tick_marks_spacing/) | Καθορίζει την αυτόματη τιμή διάστηματος σημαδούρων. Εάν false: χρησιμοποιήστε την ιδιότητα TickMarksSpacing.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`label_offset`](/slides/python-net/el/aspose.slides.charts/axis/label_offset/) | Καθορίζει την απόσταση των ετικετών από τον άξονα. Εφαρμόζεται σε άξονα κατηγορίας ή ημερομηνίας. Η τιμή πρέπει να είναι μεταξύ 0% και 1000%.<br/>            Ανάγνωση/εγγραφή **int**. |
| [`aggregation_type`](/slides/python-net/el/aspose.slides.charts/axis/aggregation_type/) | Αντιπροσωπεύει τον τύπο συγκέντρωσης του άξονα κατηγορίας (binning). Εφαρμόζεται σε κατηγορία. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto. |
| [`bin_width`](/slides/python-net/el/aspose.slides.charts/axis/bin_width/) | Καθορίζει το πλάτος του bin όταν η τιμή της ιδιότητας AggregationType έχει οριστεί σε AxisAggregationType.ByBinWidth.<br/>            Εφαρμόζεται σε άξονες κατηγορίας. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto. |
| [`number_of_bins`](/slides/python-net/el/aspose.slides.charts/axis/number_of_bins/) | Καθορίζει τον αριθμό των bins όταν η τιμή της ιδιότητας AggregationType έχει οριστεί σε AxisAggregationType.ByNumberOfBins.<br/>            Εφαρμόζεται σε άξονες κατηγορίας. Χρησιμοποιείται μόνο με σειρές Histogram ή HistogramPareto. |
| [`is_overflow_bin`](/slides/python-net/el/aspose.slides.charts/axis/is_overflow_bin/) | Καθορίζει εάν εφαρμόζεται overflow bin. Χρησιμοποιήστε τις IsAutomaticOverflowBin και OverflowBin για να ρυθμίσετε την τιμή του overflow bin. |
| [`is_automatic_overflow_bin`](/slides/python-net/el/aspose.slides.charts/axis/is_automatic_overflow_bin/) | Καθορίζει την αυτόματη τιμή overflow bin. Εάν false: χρησιμοποιήστε την ιδιότητα OverflowBin. |
| [`overflow_bin`](/slides/python-net/el/aspose.slides.charts/axis/overflow_bin/) | Καθορίζει προσαρμοσμένη τιμή overflow bin. Εφαρμόζεται όταν η ιδιότητα IsAutomaticOverflowBin είναι false και η IsOverflowBin είναι true. |
| [`is_underflow_bin`](/slides/python-net/el/aspose.slides.charts/axis/is_underflow_bin/) | Καθορίζει εάν εφαρμόζεται underflow bin. Χρησιμοποιήστε τις IsAutomaticUnderflowBin και UnderflowBin για να ρυθμίσετε την τιμή του underflow bin. |
| [`is_automatic_underflow_bin`](/slides/python-net/el/aspose.slides.charts/axis/is_automatic_underflow_bin/) | Καθορίζει την αυτόματη τιμή underflow bin. Εάν false: χρησιμοποιήστε την ιδιότητα UnderflowBin. |
| [`underflow_bin`](/slides/python-net/el/aspose.slides.charts/axis/underflow_bin/) | Καθορίζει προσαρμοσμένη τιμή underflow bin. Εφαρμόζεται όταν η ιδιότητα IsAutomaticUnderflowBin είναι false και η IsUnderflowBin είναι true. |
| [`slide`](/slides/python-net/el/aspose.slides.charts/axis/slide/) |  |
| [`presentation`](/slides/python-net/el/aspose.slides.charts/axis/presentation/) |  |

## Μέθοδοι

| Method | Description |
| :- | :- |
| [`set_category_axis_type_automatically(self)`](/slides/python-net/el/aspose.slides.charts/axis/set_category_axis_type_automatically/#) | Ορίζει την ιδιότητα IAxis.CategoryAxisType με μια τιμή που καθορίζεται αυτόματα βάσει των δεδομένων του άξονα. |

### Δείτε επίσης
* module [`aspose.slides.charts`](/slides/python-net/el/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)