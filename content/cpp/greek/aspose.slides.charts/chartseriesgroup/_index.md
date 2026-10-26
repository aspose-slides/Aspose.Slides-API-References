---
title: ChartSeriesGroup
second_title: Αναφορά API του Aspose.Slides για C++
description: Αντιπροσωπεύει την ομάδα σειρών.
type: docs
weight: 300
url: /el/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup κλάση

Αντιπροσωπεύει ομάδα σειρών.

```cpp
class ChartSeriesGroup : public Aspose::Slides::Charts::IChartSeriesGroup,
                         public Aspose::Slides::IDOMObject
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη [Object.Equals](../../system/object/equals/) σημασιολογία της C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής τύπου C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με το IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής τύπου C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με το IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() override | Καθορίζει πώς τα μεγέθη φυσαλίδων εμφανίζονται στο γράφημα φυσαλίδων. Διαβάστε [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() override | Καθορίζει τον συντελεστή κλίμακας για το γράφημα φυσαλίδων (μπορεί να είναι μεταξύ 0 και 300 τοις εκατό του προεπιλεγμένου μεγέθους). Διαβάστε **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Επιστρέφει το γονικό γράφημα. Μόνο για ανάγνωση [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) override | Επιστρέφει τη σειρά γραφήματος στην ομάδα στο συγκεκριμένο δείκτη. |
| **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() override | Καθορίζει το μέγεθος της τρύπας σε γράφημα δαχτυλίου (μπορεί να είναι μεταξύ 0 και 90 τοις εκατό του μεγέθους της περιοχής σχεδίασης). Διαβάστε **uint8_t**. |
| **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() override | Λαμβάνει τη γωνία του πρώτου κομματιού πίτας ή δαχτυλίου, σε μοίρες (δεξιόστροφα από το πάνω, από 0 έως 360 μοίρες). Διαβάστε **uint16_t**. |
| **uint16_t** [get_GapDepth](./get_gapdepth/)() override | Επιστρέφει την απόσταση, ως ποσοστό του πλάτους του δείκτη, μεταξύ των σειρών δεδομένων σε γράφημα 3D. Διαβάστε **uint16_t**. |
| **uint16_t** [get_GapWidth](./get_gapwidth/)() override | Καθορίζει το κενό μεταξύ ομάδων ράβδων ή στηλών, ως ποσοστό του πλάτους της ράβδου ή της στήλης. Διαβάστε **uint16_t**. |
| **bool** [get_HasSeriesLines](./get_hasserieslines/)() override | Αληθές εάν το γράφημα έχει γραμμές σειρών. Εφαρμόζεται σε στοίβαξη ράβδων και γραφήματα OfPie. Διαβάστε **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_HiLowLinesFormat](./get_hilowlinesformat/)() override | Καθορίζει τη μορφή HiLowLines. Τα HiLowLines εφαρμόζονται με τους τύπους γραφημάτων HiLowClose, OpenHiLowClose, VolumeHiLowClose και VolumeOpenHiLowClose. |
| **bool** [get_IsColorVaried](./get_iscolorvaried/)() override | Καθορίζει ότι κάθε δείκτης δεδομένων στη σειρά έχει διαφορετικό χρώμα. Διαβάστε **bool**. |
| **int8_t** [get_Overlap](./get_overlap/)() override | Καθορίζει το πόσο οι ράβδοι και οι στήλες πρέπει να επικαλύπτονται σε 2Δ γραφήματα, ως ποσοστό (από -100% έως 100%). |
| [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() override | Καθορίζει πώς να προσδιοριστεί ποια σημεία δεδομένων βρίσκονται στη δεύτερη πίτα ή ράβδο σε γράφημα pie-of-pie ή bar-of-pie. Διαβάστε [PieSplitType](../piesplittype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) override | Οι προσαρμοσμένες πληροφορίες διαίρεσης για γράφημα pie-of-pie ή bar-of-pie με προσαρμοσμένη διαίρεση. Επιστρέφει το σημείο δεδομένων που θα σχεδιαστεί στη δεύτερη πίτα ή ράβδο σε γράφημα pie-of-pie ή bar-of-pie με βάση το δείκτη. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() override | Οι προσαρμοσμένες πληροφορίες διαίρεσης για γράφημα pie-of-pie ή bar-of-pie με προσαρμοσμένη διαίρεση. Περιέχει σημεία δεδομένων που θα σχεδιαστούν στη δεύτερη πίτα ή ράβδο σε γράφημα pie-of-pie ή bar-of-pie. Μόνο για ανάγνωση [PieSplitCustomPointCollection](../piesplitcustompointcollection/). |
| **double** [get_PieSplitPosition](./get_piesplitposition/)() override | Καθορίζει μια τιμή που θα χρησιμοποιηθεί για τον προσδιορισμό ποια σημεία δεδομένων βρίσκονται στη δεύτερη πίτα ή ράβδο σε γράφημα pie-of-pie ή bar-of-pie. Χρησιμοποιείται μαζί με την ιδιότητα PieSplitBy. Διαβάστε **double**. |
| **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() override | Δείχνει εάν οι σειρές αυτής της ομάδας σχεδιάζονται σε δευτερεύοντα άξονα. Μόνο για ανάγνωση **bool**. |
| **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() override | Καθορίζει το μέγεθος της δεύτερης πίτας ή ράβδου σε γράφημα pie-of-pie ή bar-of-pie, ως ποσοστό του μεγέθους της πρώτης πίτας (μπορεί να είναι μεταξύ 5 και 200 τοις εκατό). Διαβάστε **uint16_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)\> [get_Series](./get_series/)() override | Επιστρέφει μια συλλογή σειρών. Μόνο για ανάγνωση [IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/). |
| [CombinableSeriesTypesGroup](../combinableseriestypesgroup/) [get_Type](./get_type/)() override | Επιστρέφει έναν τύπο αυτής της ομάδας σειρών. Μόνο για ανάγνωση [CombinableSeriesTypesGroup](../combinableseriestypesgroup/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IUpDownBarsManager](../iupdownbarsmanager/)\> [get_UpDownBars](./get_updownbars/)() override | Παρέχει πρόσβαση στις γραμμές πάνω/κάτω σε γράφημα γραμμής ή μετοχών. Μόνο για ανάγνωση [IUpDownBarsManager](../iupdownbarsmanager/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφοράς που συνδέεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το hash προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Ανάλογη του κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [idx_get](./idx_get/)(**int32_t**) override | Λαμβάνει το στοιχείο στον καθορισμένο δείκτη. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια περίπτωση του τύπου που περιγράφεται από targetType. Ανάλογο του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο φύλακα [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή υποκατηγοριών μέσω αντιγραφής. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστικός τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή υποκατηγοριών μέσω αντιγραφής. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική εκδοχή του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική εκδοχή του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφορών κατά την καθορισμένη τιμή. |
| void [set_BubbleSizeRepresentation](./set_bubblesizerepresentation/)([BubbleSizeRepresentationType](../bubblesizerepresentationtype/)) override | Καθορίζει πώς τα μεγέθη φυσαλίδων εμφανίζονται στο γράφημα φυσαλίδων. Γράψτε [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| void [set_BubbleSizeScale](./set_bubblesizescale/)(**int32_t**) override | Καθορίζει τον συντελεστή κλίμακας για το γράφημα φυσαλίδων (μπορεί να είναι μεταξύ 0 και 300 τοις εκατό του προεπιλεγμένου μεγέθους). Γράψτε **int32_t**. |
| void [set_DoughnutHoleSize](./set_doughnutholesize/)(**uint8_t**) override | Καθορίζει το μέγεθος της τρύπας σε γράφημα δαχτυλίου (μπορεί να είναι μεταξύ 0 και 90 τοις εκατό του μεγέθους της περιοχής σχεδίασης). Γράψτε **uint8_t**. |
| void [set_FirstSliceAngle](./set_firstsliceangle/)(**uint16_t**) override | Ορίζει τη γωνία του πρώτου κομματιού πίτας ή δαχτυλίου, σε μοίρες (δεξιόστροφα από το πάνω, από 0 έως 360 μοίρες). Γράψτε **uint16_t**. |
| void [set_GapDepth](./set_gapdepth/)(**uint16_t**) override | Ορίζει την απόσταση, ως ποσοστό του πλάτους του δείκτη, μεταξύ των σειρών δεδομένων σε γράφημα 3D. Γράψτε **uint16_t**. |
| void [set_GapWidth](./set_gapwidth/)(**uint16_t**) override | Καθορίζει το κενό μεταξύ ομάδων ράβδων ή στηλών, ως ποσοστό του πλάτους της ράβδου ή της στήλης. Γράψτε **uint16_t**. |
| void [set_HasSeriesLines](./set_hasserieslines/)(**bool**) override | Αληθές εάν το γράφημα έχει γραμμές σειρών. Εφαρμόζεται σε στοίβαξη ράβδων και γραφήματα OfPie. Γράψτε **bool**. |
| void [set_IsColorVaried](./set_iscolorvaried/)(**bool**) override | Καθορίζει ότι κάθε δείκτης δεδομένων στη σειρά έχει διαφορετικό χρώμα. Γράψτε **bool**. |
| void [set_Overlap](./set_overlap/)(**int8_t**) override | Καθορίζει το πόσο οι ράβδοι και οι στήλες πρέπει να επικαλύπτονται σε 2Δ γραφήματα, ως ποσοστό (από -100% έως 100%). |
| void [set_PieSplitBy](./set_piesplitby/)([PieSplitType](../piesplittype/)) override | Καθορίζει πώς να προσδιοριστεί ποια σημεία δεδομένων βρίσκονται στη δεύτερη πίτα ή ράβδο σε γράφημα pie-of-pie ή bar-of-pie. Γράψτε [PieSplitType](../piesplittype/). |
| void [set_PieSplitPosition](./set_piesplitposition/)(**double**) override | Καθορίζει μια τιμή που θα χρησιμοποιηθεί για τον προσδιορισμό ποια σημεία δεδομένων βρίσκονται στη δεύτερη πίτα ή ράβδο σε γράφημα pie-of-pie ή bar-of-pie. Χρησιμοποιείται μαζί με την ιδιότητα PieSplitBy. Γράψτε **double**. |
| void [set_SecondPieSize](./set_secondpiesize/)(**uint16_t**) override | Καθορίζει το μέγεθος της δεύτερης πίτας ή ράβδου σε γράφημα pie-of-pie ή bar-of-pie, ως ποσοστό του μεγέθους της πρώτης πίτας (μπορεί να είναι μεταξύ 5 και 200 τοις εκατό). Γράψτε **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το ν-οστό όρισμα προτύπου σε αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε δομές σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο φύλακα [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Παρατηρήσεις

1) Δείτε την περίληψη και τις παρατηρήσεις για την κλάση ChartSeriesGroupCollection και την enum CombinableSeriesTypesGroup. 2) Η ομάδα σειρών περιέχει ορισμένες ιδιότητες σειρών που είναι κοινές για κάθε σειρά στην ομάδα («ιδιότητες ομάδας σειρών»). Οι «ιδιότητες ομάδας σειρών» στην κλάση [ChartSeriesGroup](./) είναι ανάγνωση/εγγραφή. Κάθε μία από τις «ιδιότητες ομάδας σειρών» μπορεί να έχει μια προβολή μόνο για ανάγνωση στην κλάση [ChartSeries](../chartseries/).

## Δείτε επίσης

* Κλάση [IChartSeriesGroup](../ichartseriesgroup/)
* Κλάση [IDOMObject](../../aspose.slides/idomobject/)
* Χώρος ονομάτων [Aspose::Slides::Charts](../)
* Βιβλιοθήκη [Aspose.Slides](../../)