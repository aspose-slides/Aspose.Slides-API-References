---
title: Trendline
second_title: Αναφορά API του Aspose.Slides για C++
description: Η κλάση αντιπροσωπεύει τη γραμμή τάσης της σειράς διαγράμματος
type: docs
weight: 1366
url: /el/aspose.slides.charts/trendline/
---
## Trendline κλάση

Η κλάση αντιπροσωπεύει τη γραμμή τάσης της σειράς διαγράμματος

```cpp
class Trendline : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::TrendlineCollection>>,
                  public Aspose::Slides::Charts::ITrendline
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | Αρχικοποιεί το TextFrameForOverriding με το κείμενο στην παράμετρο \"text\". Εάν το TextFrameForOverriding είναι ήδη αρχικοποιημένο, τότε απλώς αλλάζει το κείμενό του. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς με στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής με στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Προσομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρά το ότι σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Προσομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρά το ότι σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| **double** [get_Backward](./get_backward/)() override | Καθορίζει τον αριθμό των κατηγοριών (ή μονάδων σε γράφημα scatter) που η γραμμή τάσης επεκτείνεται πριν από τα δεδομένα της σειράς που υποβάλλεται σε τάση. Σε γραφήματα scatter και μη-scatter, η τιμή πρέπει να είναι οποιαδήποτε μη-αρνητική τιμή. Ανάγνωση **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Επιστρέφει το γονικό διάγραμμα. Μόνο ανάγνωση [IChart](../ichart/). |
| **bool** [get_DisplayEquation](./get_displayequation/)() override | Καθορίζει ότι η εξίσωση για τη γραμμή τάσης εμφανίζεται στο διάγραμμα (στο ίδιο ετικέτα με το Rsquaredvalue). Ανάγνωση **bool**. |
| **bool** [get_DisplayRSquaredValue](./get_displayrsquaredvalue/)() override | Καθορίζει ότι η τιμή R-squared της γραμμής τάσης εμφανίζεται στο διάγραμμα (στο ίδιο ετικέτα με την εξίσωση). Ανάγνωση **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Αναπαριστά τη μορφοποίηση της γραμμής τάσης. Ανάγνωση [IFormat](../iformat/). |
| **double** [get_Forward](./get_forward/)() override | Καθορίζει τον αριθμό των κατηγοριών (ή μονάδων σε γράφημα scatter) που η γραμμή τάσης επεκτείνεται μετά τα δεδομένα της σειράς που υποβάλλεται σε τάση. Σε γραφήματα scatter και μη-scatter, η τιμή πρέπει να είναι οποιαδήποτε μη-αρνητική τιμή. Ανάγνωση **double**. |
| **double** [get_Intercept](./get_intercept/)() override | Καθορίζει την τιμή στην οποία η γραμμή τάσης διασχίζει την άξονα y. Αυτή η ιδιότητα υποστηρίζεται μόνο όταν ο τύπος γραμμής τάσης είναι exp, linear ή poly. Ανάγνωση **double**. |
| **uint8_t** [get_Order](./get_order/)() override | Καθορίζει τη σειρά της πολυωνυμικής γραμμής τάσης. Παραβλέπτεται για άλλους τύπους γραμμής τάσης. Η τιμή πρέπει να βρίσκεται μεταξύ 2 και 6. Ανάγνωση **uint8_t**. |
| **uint8_t** [get_Period](./get_period/)() override | Καθορίζει την περίοδο της γραμμής τάσης για μια γραμμή κινητού μέσου. Παραβλέπεται για άλλες παραλλαγές γραμμής τάσης. Η τιμή πρέπει να είναι μεταξύ 2 και 255. Ανάγνωση **uint8_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() override | Αναπαριστά την καταχώρηση του υπομνήματος που σχετίζεται με αυτή τη γραμμή τάσης. Μόνο ανάγνωση [ILegendEntryProperties](../ilegendentryproperties/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Επιστρέφει τη μορφή κειμένου. Μόνο ανάγνωση [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | Μπορεί να περιέχει πλούσιο μορφοποιημένο κείμενο. Εάν αυτή η ιδιότητα δεν είναι null, τότε αυτή η μορφοποιημένη τιμή κειμένου αντικαθιστά το αυτόματα παραγόμενο κείμενο της ετικέτας δεδομένων. Το αυτόματα παραγόμενο κείμενο της ετικέτας δεδομένων σημαίνει κείμενο που διαχειρίζεται από τις ιδιότητες ShowSeriesName, ShowValue, ... και μορφοποιείται με την ιδιότητα TextFormatManager.TextFormat. Μόνο ανάγνωση [ITextFrame](../../aspose.slides/itextframe/). |
| [System::String](../../system/string/) [get_TrendlineName](./get_trendlinename/)() override | Λαμβάνει το όνομα της γραμμής τάσης. Ανάγνωση [System::String](../../system/string/). |
| [Aspose::Slides::Charts::TrendlineType](../trendlinetype/) [get_TrendlineType](./get_trendlinetype/)() override | Λαμβάνει τον τύπο της γραμμής τάσης. Ανάγνωση [Charts::TrendlineType](../trendlinetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία hash για προσαρμοσμένα αντικείμενα. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια περίπτωση του τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Εφαρμόζει το κλείδωμα της δήλωσης C# lock(). Καλείται απευθείας ή χρησιμοποιήστε το αντικείμενο [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την αντιγραφή κατασκευής υποκατηγοριών. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την αντιγραφή κατασκευής υποκατηγοριών. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφοράς κατά την καθορισμένη τιμή. |
| void [set_Backward](./set_backward/)(**double**) override | Καθορίζει τον αριθμό των κατηγοριών (ή μονάδων σε γράφημα scatter) που η γραμμή τάσης επεκτείνεται πριν από τα δεδομένα της σειράς που υποβάλλεται σε τάση. Σε γραφήματα scatter και μη-scatter, η τιμή πρέπει να είναι οποιαδήποτε μη-αρνητική τιμή. Εγγραφή **double**. |
| void [set_DisplayEquation](./set_displayequation/)(**bool**) override | Καθορίζει ότι η εξίσωση για τη γραμμή τάσης εμφανίζεται στο διάγραμμα (στο ίδιο ετικέτα με το Rsquaredvalue). Εγγραφή **bool**. |
| void [set_DisplayRSquaredValue](./set_displayrsquaredvalue/)(**bool**) override | Καθορίζει ότι η τιμή R-squared της γραμμής τάσης εμφανίζεται στο διάγραμμα (στο ίδιο ετικέτα με την εξίσωση). Εγγραφή **bool**. |
| void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) override | Αναπαριστά τη μορφή της γραμμής τάσης. Εγγραφή [IFormat](../iformat/). |
| void [set_Forward](./set_forward/)(**double**) override | Καθορίζει τον αριθμό των κατηγοριών (ή μονάδων σε γράφημα scatter) που η γραμμή τάσης επεκτείνεται μετά τα δεδομένα της σειράς που υποβάλλεται σε τάση. Σε γραφήματα scatter και μη-scatter, η τιμή πρέπει να είναι οποιαδήποτε μη-αρνητική τιμή. Εγγραφή **double**. |
| void [set_Intercept](./set_intercept/)(**double**) override | Καθορίζει την τιμή στην οποία η γραμμή τάσης διασχίζει την άξονα y. Αυτή η ιδιότητα υποστηρίζεται μόνο όταν ο τύπος γραμμής τάσης είναι exp, linear ή poly. Εγγραφή **double**. |
| void [set_Order](./set_order/)(**uint8_t**) override | Καθορίζει τη σειρά της πολυωνυμικής γραμμής τάσης. Παραβλέπτεται για άλλους τύπους γραμμής τάσης. Η τιμή πρέπει να είναι μεταξύ 2 και 6. Εγγραφή **uint8_t**. |
| void [set_Period](./set_period/)(**uint8_t**) override | Καθορίζει την περίοδο της γραμμής τάσης για μια γραμμή κινητού μέσου. Παραβλέπεται για άλλες παραλλαγές γραμμής τάσης. Η τιμή πρέπει να είναι μεταξύ 2 και 255. Εγγραφή **uint8_t**. |
| void [set_TrendlineName](./set_trendlinename/)([System::String](../../system/string/)) override | Ορίζει το όνομα της γραμμής τάσης. Εγγραφή [System::String](../../system/string/). |
| void [set_TrendlineType](./set_trendlinetype/)([Aspose::Slides::Charts::TrendlineType](../trendlinetype/)) override | Ορίζει τον τύπο της γραμμής τάσης. Εγγραφή [Charts::TrendlineType](../trendlinetype/). |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Θέτει το n'th όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την εναλλαγή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να καλείται απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να καλείται απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Εφαρμόζει την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Εφαρμόζει το ξεκλείδωμα της δήλωσης C# lock(). Καλείται απευθείας ή χρησιμοποιήστε το αντικείμενο [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να καλείται απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να καλείται απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Ελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [DomObject](../../aspose.slides/domobject/)
* Κλάση [ITrendline](../itrendline/)
* Χώρος ονομάτων [Aspose::Slides::Charts](../)
* Βιβλιοθήκη [Aspose.Slides](../../)