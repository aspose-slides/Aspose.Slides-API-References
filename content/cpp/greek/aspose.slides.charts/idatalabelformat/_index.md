---
title: IDataLabelFormat
second_title: Aspose.Slides για C++ Αναφορά API
description: Αντιπροσωπεύει τις επιλογές μορφοποίησης για DataLabel.
type: docs
weight: 963
url: /el/aspose.slides.charts/idatalabelformat/
---
## IDataLabelFormat κλάση

Αντιπροσωπεύει τις επιλογές μορφοποίησης για [DataLabel](../datalabel/).

```cpp
class IDataLabelFormat : public Aspose::Slides::Charts::IFormattedTextContainer
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη λογική [Object.Equals](../../system/object/equals/) της C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C#, όπου δύο NaN θεωρούνται ίσα παρ' όλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C#, όπου δύο NaN θεωρούνται ίσα παρ' όλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Επιστρέφει το γράφημα. Μόνο για ανάγνωση [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Αντιπροσωπεύει τη μορφή της ετικέτας δεδομένων. Μόνο για ανάγνωση [IFormat](../iformat/). |
| virtual **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() | Ανάγνωση **bool**. |
| virtual [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() | Αντιπροσωπεύει τη συμβολοσειρά μορφής για το αντικείμενο DataLabels. Ανάγνωση [System::String](../../system/string/). |
| virtual [LegendDataLabelPosition](../legenddatalabelposition/) [get_Position](./get_position/)() | Αντιπροσωπεύει τη θέση της ετικέτας δεδομένων. Ανάγνωση [LegendDataLabelPosition](../legenddatalabelposition/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Επιστρέφει την παρουσίαση. Μόνο για ανάγνωση [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::String](../../system/string/) [get_Separator](./get_separator/)() | Ορίζει ή επιστρέφει ένα Variant που αντιπροσωπεύει το διαχωριστικό που χρησιμοποιείται για τις ετικέτες δεδομένων σε ένα γράφημα. Ανάγνωση [System::String](../../system/string/). |
| virtual **bool** [get_ShowBubbleSize](./get_showbubblesize/)() | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της τιμής μεγέθους φυσαλίδας της ετικέτας δεδομένων ενός συγκεκριμένου γραφήματος. True εμφανίζει την τιμή μεγέθους φυσαλίδας. False την κρύβει. Ανάγνωση **bool**. |
| virtual **bool** [get_ShowCategoryName](./get_showcategoryname/)() | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης του ονόματος κατηγορίας της ετικέτας δεδομένων ενός συγκεκριμένου γραφήματος. True για εμφάνιση του ονόματος κατηγορίας στις ετικέτες δεδομένων ενός γραφήματος. False για απόκρυψη. Ανάγνωση **bool**. |
| virtual **bool** [get_ShowLabelAsDataCallout](./get_showlabelasdatacallout/)() | Καθορίζει εάν η ετικέτα δεδομένων του συγκεκριμένου γραφήματος θα εμφανίζεται ως κλήση δεδομένων ή ως ετικέτα δεδομένων. |
| virtual **bool** [get_ShowLabelValueFromCell](./get_showlabelvaluefromcell/)() | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της τιμής κελιού της ετικέτας δεδομένων ενός συγκεκριμένου γραφήματος. True εμφανίζει την τιμή κελιού. False την κρύβει. Ανάγνωση **bool**. |
| virtual **bool** [get_ShowLeaderLines](./get_showleaderlines/)() | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης των γραμμών οδηγού της ετικέτας δεδομένων ενός συγκεκριμένου γραφήματος. True εμφανίζει τις γραμμές οδηγού. False τις κρύβει. Ανάγνωση **bool**. |
| virtual **bool** [get_ShowLegendKey](./get_showlegendkey/)() | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης του κλειδιού λεζάντας της ετικέτας δεδομένων ενός συγκεκριμένου γραφήματος. True εάν το κλειδί λεζάντας ετικέτας δεδομένων είναι ορατό. Ανάγνωση **bool**. |
| virtual **bool** [get_ShowPercentage](./get_showpercentage/)() | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της τιμής ποσοστού της ετικέτας δεδομένων ενός συγκεκριμένου γραφήματος. True εμφανίζει την τιμή ποσοστού. False την κρύβει. Ανάγνωση **bool**. |
| virtual **bool** [get_ShowSeriesName](./get_showseriesname/)() | Επιστρέφει μια Boolean που υποδεικνύει τη συμπεριφορά εμφάνισης του ονόματος σειράς για τις ετικέτες δεδομένων σε ένα γράφημα. True για εμφάνιση του ονόματος σειράς. False για απόκρυψη. Ανάγνωση **bool**. |
| virtual **bool** [get_ShowValue](./get_showvalue/)() | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της τιμής ποσοστού της ετικέτας δεδομένων ενός συγκεκριμένου γραφήματος. True εμφανίζει την τιμή ποσοστού. False την κρύβει. Ανάγνωση **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Επιστρέφει τη βασική διαφάνεια. Μόνο για ανάγνωση [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Επιστρέφει τη μορφή κειμένου του γραφήματος. Μόνο για ανάγνωση [IChartTextFormat](../icharttextformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογικό της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Επιτρέπει τη δημιουργία hash για προσαρμοσμένα αντικείμενα. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει ένα στιγμιότυπο του τύπου που περιγράφεται από το targetType. Αναλογικό του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το statement lock() της C# για κλείδωμα. Κλήση άμεσα ή χρήση του αντικειμένου [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Επιτρέπει την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατά την κατασκευή υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατά την κατασκευή υποκλάσεων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφοράς κατά την καθορισμένη τιμή. |
| virtual void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) | Εγγραφή **bool**. |
| virtual void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) | Αντιπροσωπεύει τη συμβολοσειρά μορφής για το αντικείμενο DataLabels. Εγγραφή [System::String](../../system/string/). |
| virtual void [set_Position](./set_position/)([LegendDataLabelPosition](../legenddatalabelposition/)) | Αντιπροσωπεύει τη θέση της ετικέτας δεδομένων. Εγγραφή [LegendDataLabelPosition](../legenddatalabelposition/). |
| virtual void [set_Separator](./set_separator/)([System::String](../../system/string/)) | Ορίζει ή επιστρέφει ένα Variant που αντιπροσωπεύει το διαχωριστικό που χρησιμοποιείται για τις ετικέτες δεδομένων σε ένα γράφημα. Εγγραφή [System::String](../../system/string/). |
| virtual void [set_ShowBubbleSize](./set_showbubblesize/)(**bool**) | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της τιμής μεγέθους φυσαλίδας της ετικέτας δεδομένων ενός συγκεκριμένου γραφήματος. True εμφανίζει την τιμή μεγέθους φυσαλίδας. False την κρύβει. Εγγραφή **bool**. |
| virtual void [set_ShowCategoryName](./set_showcategoryname/)(**bool**) | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης του ονόματος κατηγορίας της ετικέτας δεδομένων ενός συγκεκριμένου γραφήματος. True για εμφάνιση του ονόματος κατηγορίας στις ετικέτες δεδομένων ενός γραφήματος. False για απόκρυψη. Εγγραφή **bool**. |
| virtual void [set_ShowLabelAsDataCallout](./set_showlabelasdatacallout/)(**bool**) | Καθορίζει εάν η ετικέτα δεδομένων του συγκεκριμένου γραφήματος θα εμφανίζεται ως κλήση δεδομένων ή ως ετικέτα δεδομένων. |
| virtual void [set_ShowLabelValueFromCell](./set_showlabelvaluefromcell/)(**bool**) | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της τιμής κελιού της ετικέτας δεδομένων ενός συγκεκριμένου γραφήματος. True εμφανίζει την τιμή κελιού. False την κρύβει. Εγγραφή **bool**. |
| virtual void [set_ShowLeaderLines](./set_showleaderlines/)(**bool**) | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης των γραμμών οδηγού της ετικέτας δεδομένων ενός συγκεκριμένου γραφήματος. True εμφανίζει τις γραμμές οδηγού. False τις κρύβει. Εγγραφή **bool**. |
| virtual void [set_ShowLegendKey](./set_showlegendkey/)(**bool**) | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης του κλειδιού λεζάντας της ετικέτας δεδομένων ενός συγκεκριμένου γραφήματος. True εάν το κλειδί λεζάντας ετικέτας δεδομένων είναι ορατό. Εγγραφή **bool**. |
| virtual void [set_ShowPercentage](./set_showpercentage/)(**bool**) | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της τιμής ποσοστού της ετικέτας δεδομένων ενός συγκεκριμένου γραφήματος. True εμφανίζει την τιμή ποσοστού. False την κρύβει. Εγγραφή **bool**. |
| virtual void [set_ShowSeriesName](./set_showseriesname/)(**bool**) | Ορίζει ένα Boolean που υποδεικνύει τη συμπεριφορά εμφάνισης του ονόματος σειράς για τις ετικέτες δεδομένων σε ένα γράφημα. True για εμφάνιση του ονόματος σειράς. False για απόκρυψη. Εγγραφή **bool**. |
| virtual void [set_ShowValue](./set_showvalue/)(**bool**) | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της τιμής ποσοστού της ετικέτας δεδομένων ενός συγκεκριμένου γραφήματος. True εμφανίζει την τιμή ποσοστού. False την κρύβει. Εγγραφή **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα προτύπου ως αδρά δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή των δεικτών σε συλλογές σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφοράς. Δεν θα πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφοράς. Δεν θα πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογικό της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Επιτρέπει τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί τη δομή typeof([System.Object](../../system/object/)) της C#. |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το statement lock() της C# για ξεκλείδωμα. Κλήση άμεσα ή χρήση του αντικειμένου [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδρό μετρητή αναφοράς. Δεν θα πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδρό μετρητή αναφοράς. Δεν θα πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [IFormattedTextContainer](../iformattedtextcontainer/)
* Χώρος ονομάτων [Aspose::Slides::Charts](../)
* Βιβλιοθήκη [Aspose.Slides](../../)