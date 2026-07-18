---
title: ITrendline
second_title: Αναφορά API του Aspose.Slides για C++
description: Η κλάση αντιπροσωπεύει τη γραμμή τάσης της σειράς γραφήματος
type: docs
weight: 1223
url: /el/aspose.slides.charts/itrendline/
---
## ITrendline κλάση

Η κλάση αντιπροσωπεύει τη γραμμή τάσης της σειράς γραφήματος

```cpp
class ITrendline : public Aspose::Slides::Charts::IOverridableText
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | Αρχικοποιεί το TextFrameForOverriding με το κείμενο στην παράμετρο \"text\". Εάν το TextFrameForOverriding είναι ήδη αρχικοποιημένο, τότε απλώς αλλάζει το κείμενό του. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία του C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual **double** [get_Backward](./get_backward/)() | Καθορίζει τον αριθμό των κατηγοριών (ή μονάδων σε διάγραμμα scatter) που η γραμμή τάσης επεκτείνεται πριν τα δεδομένα της σειράς που υποβάλλεται σε τάση. Σε διαγράμματα scatter και μη-scatter, η τιμή πρέπει να είναι οποιαδήποτε μη-αρνητική τιμή. Ανάγνωση **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Επιστρέφει το διάγραμμα. Μόνο για ανάγνωση [IChart](../ichart/). |
| virtual **bool** [get_DisplayEquation](./get_displayequation/)() | Καθορίζει ότι η εξίσωση της γραμμής τάσης εμφανίζεται στο διάγραμμα (στο ίδιο ετικέτα με το Rsquaredvalue). Ανάγνωση **bool**. |
| virtual **bool** [get_DisplayRSquaredValue](./get_displayrsquaredvalue/)() | Καθορίζει ότι η τιμή R-squared της γραμμής τάσης εμφανίζεται στο διάγραμμα (στο ίδιο ετικέτα με την εξίσωση). Ανάγνωση **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Αντιπροσωπεύει τη μορφή της γραμμής τάσης. Ανάγνωση [IFormat](../iformat/). |
| virtual **double** [get_Forward](./get_forward/)() | Καθορίζει τον αριθμό των κατηγοριών (ή μονάδων σε διάγραμμα scatter) που η γραμμή τάσης επεκτείνεται μετά τα δεδομένα της σειράς που υποβάλλεται σε τάση. Σε διαγράμματα scatter και μη-scatter, η τιμή πρέπει να είναι οποιαδήποτε μη-αρνητική τιμή. Ανάγνωση **double**. |
| virtual **double** [get_Intercept](./get_intercept/)() | Καθορίζει την τιμή όπου η γραμμή τάσης θα διασχίσει τον άξονα y. Αυτή η ιδιότητα υποστηρίζεται μόνο όταν ο τύπος της γραμμής τάσης είναι exp, linear ή poly. Ανάγνωση **double**. |
| virtual **uint8_t** [get_Order](./get_order/)() | Καθορίζει την τάξη της πολυωνυμικής γραμμής τάσης. Αγνοείται για άλλους τύπους γραμμής τάσης. Η τιμή πρέπει να είναι μεταξύ 2 και 6. Ανάγνωση **uint8_t**. |
| virtual **uint8_t** [get_Period](./get_period/)() | Καθορίζει την περίοδο της γραμμής τάσης για μια γραμμή τάσης κινητού μέσου. Αγνοείται για άλλες παραλλαγές γραμμής τάσης. Η τιμή πρέπει να είναι μεταξύ 2 και 255. Ανάγνωση **uint8_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Επιστρέφει την παρουσίαση. Μόνο για ανάγνωση [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() | Αντιπροσωπεύει την καταχώριση υπομνήματος σχετική με αυτή τη γραμμή τάσης. Μόνο για ανάγνωση [ILegendEntryProperties](../ilegendentryproperties/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Επιστρέφει τη βασική διαφάνεια. Μόνο για ανάγνωση [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Επιστρέφει τη μορφή κειμένου διαγράμματος. Μόνο για ανάγνωση [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | Μπορεί να περιέχει πλούσιο μορφοποιημένο κείμενο. Εάν αυτή η ιδιότητα δεν είναι null, τότε αυτή η μορφοποιημένη τιμή κειμένου αντικαθιστά το αυτό-γεννημένο κείμενο. Το αυτό-γεννημένο κείμενο είναι μια έμμεση ιδιότητα της ετικέτας δεδομένων, της ετικέτας μονάδας εμφάνισης του άξονα τιμών, του τίτλου άξονα, του τίτλου διαγράμματος, της ετικέτας της γραμμής τάσης. Το αυτό-γεννημένο κείμενο μορφοποιείται με την ιδιότητα [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/). Μόνο για ανάγνωση [ITextFrame](../../aspose.slides/itextframe/). |
| virtual [System::String](../../system/string/) [get_TrendlineName](./get_trendlinename/)() | Παίρνει το όνομα της γραμμής τάσης. Ανάγνωση [System::String](../../system/string/). |
| virtual [Aspose::Slides::Charts::TrendlineType](../trendlinetype/) [get_TrendlineType](./get_trendlinetype/)() | Παίρνει τον τύπο της γραμμής τάσης. Ανάγνωση [TrendlineType](../trendlinetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Παίρνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογικό της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία κατακερματισμού προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Παίρνει τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια περίπτωση του τύπου που περιγράφεται από targetType. Αναλογικό του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί την κλειδώση της εντολής C# lock(). Καλείται απευθείας ή χρησιμοποιεί το αντικείμενο φύλαξης [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκατηγοριών. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τ operator ανάθεσης. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκατηγοριών. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφορών κατά την καθορισμένη τιμή. |
| virtual void [set_Backward](./set_backward/)(**double**) | Καθορίζει τον αριθμό των κατηγοριών (ή μονάδων σε διάγραμμα scatter) που η γραμμή τάσης επεκτείνεται πριν τα δεδομένα της σειράς που υποβάλλεται σε τάση. Σε διαγράμματα scatter και μη-scatter, η τιμή πρέπει να είναι οποιαδήποτε μη-αρνητική τιμή. Εγγραφή **double**. |
| virtual void [set_DisplayEquation](./set_displayequation/)(**bool**) | Καθορίζει ότι η εξίσωση της γραμμής τάσης εμφανίζεται στο διάγραμμα (στο ίδιο ετικέτα με το Rsquaredvalue). Εγγραφή **bool**. |
| virtual void [set_DisplayRSquaredValue](./set_displayrsquaredvalue/)(**bool**) | Καθορίζει ότι η τιμή R-squared της γραμμής τάσης εμφανίζεται στο διάγραμμα (στο ίδιο ετικέτα με την εξίσωση). Εγγραφή **bool**. |
| virtual void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) | Αντιπροσωπεύει τη μορφή της γραμμής τάσης. Εγγραφή [IFormat](../iformat/). |
| virtual void [set_Forward](./set_forward/)(**double**) | Καθορίζει τον αριθμό των κατηγοριών (ή μονάδων σε διάγραμμα scatter) που η γραμμή τάσης επεκτείνεται μετά τα δεδομένα της σειράς που υποβάλλεται σε τάση. Σε διαγράμματα scatter και μη-scatter, η τιμή πρέπει να είναι οποιαδήποτε μη-αρνητική τιμή. Εγγραφή **double**. |
| virtual void [set_Intercept](./set_intercept/)(**double**) | Καθορίζει την τιμή όπου η γραμμή τάσης θα διασχίσει τον άξονα y. Αυτή η ιδιότητα υποστηρίζεται μόνο όταν ο τύπος της γραμμής τάσης είναι exp, linear ή poly. Εγγραφή **double**. |
| virtual void [set_Order](./set_order/)(**uint8_t**) | Καθορίζει την τάξη της πολυωνυμικής γραμμής τάσης. Αγνοείται για άλλους τύπους γραμμής τάσης. Η τιμή πρέπει να είναι μεταξύ 2 και 6. Εγγραφή **uint8_t**. |
| virtual void [set_Period](./set_period/)(**uint8_t**) | Καθορίζει την περίοδο της γραμμής τάσης για μια γραμμή τάσης κινητού μέσου. Αγνοείται για άλλες παραλλαγές γραμμής τάσης. Η τιμή πρέπει να είναι μεταξύ 2 και 255. Εγγραφή **uint8_t**. |
| virtual void [set_TrendlineName](./set_trendlinename/)([System::String](../../system/string/)) | Ορίζει το όνομα της γραμμής τάσης. Εγγραφή [System::String](../../system/string/). |
| virtual void [set_TrendlineType](./set_trendlinetype/)([Aspose::Slides::Charts::TrendlineType](../trendlinetype/)) | Ορίζει τον τύπο της γραμμής τάσης. Εγγραφή [TrendlineType](../trendlinetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινό). Επιτρέπει την αλλαγή δεικτών σε δοχεία σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Παίρνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογικό της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της εντολής C# lock(). Καλείται απευθείας ή χρησιμοποιεί το αντικείμενο φύλαξης [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [IOverridableText](../ioverridabletext/)
* Χώρος ονομάτων [Aspose::Slides::Charts](../)
* Βιβλιοθήκη [Aspose.Slides](../../)