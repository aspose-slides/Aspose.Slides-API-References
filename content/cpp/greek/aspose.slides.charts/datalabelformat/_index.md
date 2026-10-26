---
title: DataLabelFormat
second_title: Aspose.Slides για C++ API Αναφορά
description: Αντιπροσωπεύει επιλογές μορφοποίησης για DataLabel.
type: docs
weight: 391
url: /el/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat κλάση


Αντιπροσωπεύει επιλογές μορφοποίησης για [DataLabel](../datalabel/).

```cpp
class DataLabelFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::Charts::IDataLabelFormat
```

## Μέθοδοι

| Μεθοδος | Περιγραφή |
| --- | --- |
| **bool** [Equals](../../aspose.slides/pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Συγκρίνει με το συγκεκριμένο αντικείμενο. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας την [Object.Equals](../../system/object/equals/) σημασιολογία της C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς στο στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Επιστρέφει το γράφημα. Μόνο-ανάγνωση [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Αντιπροσωπεύει τη μορφοποίηση της ετικέτας δεδομένων. Μόνο-ανάγνωση [IFormat](../iformat/). |
| **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() override | Ανάγνωση **bool**. |
| [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() override | Αντιπροσωπεύει τη συμβολοσειρά μορφοποίησης για το αντικείμενο DataLabels. Ανάγνωση [System::String](../../system/string/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../../aspose.slides/idomobject/)\> [get_Parent_Immediate](../../aspose.slides/idomobject/get_parent_immediate/)() | Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο-ανάγνωση [IDOMObject](../../aspose.slides/idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | Επιστρέφει το γονικό [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). Μόνο-ανάγνωση [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [LegendDataLabelPosition](../legenddatalabelposition/) [get_Position](./get_position/)() override | Αντιπροσωπεύει τη θέση της ετικέτας δεδομένων. Ανάγνωση [LegendDataLabelPosition](../legenddatalabelposition/). |
| [System::String](../../system/string/) [get_Separator](./get_separator/)() override | Ορίζει ή επιστρέφει ένα Variant που αντιπροσωπεύει το διαχωριστικό που χρησιμοποιείται για τις ετικέτες δεδομένων σε ένα γράφημα. Ανάγνωση [System::String](../../system/string/). |
| **bool** [get_ShowBubbleSize](./get_showbubblesize/)() override | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της τιμής μεγέθους φυσαλίδας της ετικέτας δεδομένων σε ένα συγκεκριμένο γράφημα. True εμφανίζει την τιμή μεγέθους φυσαλίδας. False κρύβει. Ανάγνωση **bool**. |
| **bool** [get_ShowCategoryName](./get_showcategoryname/)() override | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης του ονόματος κατηγορίας της ετικέτας δεδομένων σε ένα συγκεκριμένο γράφημα. True εμφανίζει το όνομα κατηγορίας. False κρύβει. Ανάγνωση **bool**. |
| **bool** [get_ShowLabelAsDataCallout](./get_showlabelasdatacallout/)() override | Καθορίζει αν η ετικέτα δεδομένων του συγκεκριμένου γραφήματος θα εμφανίζεται ως κλήση δεδομένων ή ως ετικέτα δεδομένων. |
| **bool** [get_ShowLabelValueFromCell](./get_showlabelvaluefromcell/)() override | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της τιμής κελιού της ετικέτας δεδομένων σε ένα συγκεκριμένο γράφημα. True εμφανίζει την τιμή κελιού. False κρύβει. Ανάγνωση **bool**. |
| **bool** [get_ShowLeaderLines](./get_showleaderlines/)() override | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης των γραμμών οδηγού της ετικέτας δεδομένων σε ένα συγκεκριμένο γράφημα. True εμφανίζει τις γραμμές οδηγού. False κρύβει. Ανάγνωση **bool**. |
| **bool** [get_ShowLegendKey](./get_showlegendkey/)() override | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης του κλειδιού λεζάντας της ετικέτας δεδομένων σε ένα συγκεκριμένο γράφημα. True αν το κλειδί λεζάντας είναι ορατό. Ανάγνωση **bool**. |
| **bool** [get_ShowPercentage](./get_showpercentage/)() override | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της τιμής ποσοστού της ετικέτας δεδομένων σε ένα συγκεκριμένο γράφημα. True εμφανίζει την τιμή ποσοστού. False κρύβει. Ανάγνωση **bool**. |
| **bool** [get_ShowSeriesName](./get_showseriesname/)() override | Επιστρέφει Boolean που υποδεικνύει τη συμπεριφορά εμφάνισης του ονόματος σειράς για τις ετικέτες δεδομένων σε ένα γράφημα. True για εμφάνιση του ονόματος σειράς. False κρύβει. Ανάγνωση **bool**. |
| **bool** [get_ShowValue](./get_showvalue/)() override | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της τιμής ποσοστού της ετικέτας δεδομένων σε ένα συγκεκριμένο γράφημα. True εμφανίζει την τιμή ποσοστού. False κρύβει. Ανάγνωση **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Επιστρέφει τη μορφή κειμένου του γραφήματος. Μόνο-ανάγνωση [IChartTextFormat](../icharttextformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| **int32_t** [GetHashCode](../../aspose.slides/pviobject/gethashcode/)() const override | Επιστρέφει τον κωδικό hash. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αντίστοιχο κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια περίπτωση του τύπου που περιγράφεται από targetType. Αντίστοιχο του τελεστή 'is' της C#. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αντίστοιχο της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί τον κλώνο προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή υποκλάσεων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αντικείμενο τύπου αξίας με αναφορά σε nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδικευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδικευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινόχρηστων αναφορών κατά την καθορισμένη τιμή. |
| void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) override | Γράφει **bool**. |
| void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) override | Αντιπροσωπεύει τη συμβολοσειρά μορφοποίησης για το αντικείμενο DataLabels. Γράφει [System::String](../../system/string/). |
| void [set_Position](./set_position/)([LegendDataLabelPosition](../legenddatalabelposition/)) override | Αντιπροσωπεύει τη θέση της ετικέτας δεδομένων. Γράφει [LegendDataLabelPosition](../legenddatalabelposition/). |
| void [set_Separator](./set_separator/)([System::String](../../system/string/)) override | Ορίζει ή επιστρέφει ένα Variant που αντιπροσωπεύει το διαχωριστικό που χρησιμοποιείται για τις ετικέτες δεδομένων σε ένα γράφημα. Γράφει [System::String](../../system/string/). |
| void [set_ShowBubbleSize](./set_showbubblesize/)(**bool**) override | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της τιμής μεγέθους φυσαλίδας της ετικέτας δεδομένων σε ένα συγκεκριμένο γράφημα. True εμφανίζει την τιμή μεγέθους φυσαλίδας. False κρύβει. Γράφει **bool**. |
| void [set_ShowCategoryName](./set_showcategoryname/)(**bool**) override | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης του ονόματος κατηγορίας της ετικέτας δεδομένων σε ένα συγκεκριμένο γράφημα. True εμφανίζει το όνομα κατηγορίας. False κρύβει. Γράφει **bool**. |
| void [set_ShowLabelAsDataCallout](./set_showlabelasdatacallout/)(**bool**) override | Καθορίζει αν η ετικέτα δεδομένων του συγκεκριμένου γραφήματος θα εμφανίζεται ως κλήση δεδομένων ή ως ετικέτα δεδομένων. |
| void [set_ShowLabelValueFromCell](./set_showlabelvaluefromcell/)(**bool**) override | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της τιμής κελιού της ετικέτας δεδομένων σε ένα συγκεκριμένο γράφημα. True εμφανίζει την τιμή κελιού. False κρύβει. Γράφει **bool**. |
| void [set_ShowLeaderLines](./set_showleaderlines/)(**bool**) override | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης των γραμμών οδηγού της ετικέτας δεδομένων σε ένα συγκεκριμένο γράφημα. True εμφανίζει τις γραμμές οδηγού. False κρύβει. Γράφει **bool**. |
| void [set_ShowLegendKey](./set_showlegendkey/)(**bool**) override | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης του κλειδιού λεζάντας της ετικέτας δεδομένων σε ένα συγκεκριμένο γράφημα. True αν το κλειδί λεζάντας είναι ορατό. Γράφει **bool**. |
| void [set_ShowPercentage](./set_showpercentage/)(**bool**) override | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της τιμής ποσοστού της ετικέτας δεδομένων σε ένα συγκεκριμένο γράφημα. True εμφανίζει την τιμή ποσοστού. False κρύβει. Γράφει **bool**. |
| void [set_ShowSeriesName](./set_showseriesname/)(**bool**) override | Ορίζει Boolean που υποδεικνύει τη συμπεριφορά εμφάνισης του ονόματος σειράς για τις ετικέτες δεδομένων σε ένα γράφημα. True για εμφάνιση του ονόματος σειράς. False κρύβει. Γράφει **bool**. |
| void [set_ShowValue](./set_showvalue/)(**bool**) override | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της τιμής ποσοστού της ετικέτας δεδομένων σε ένα συγκεκριμένο γράφημα. True εμφανίζει την τιμή ποσοστού. False κρύβει. Γράφει **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα πρότυπου ως αδρό δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε δοχεία σε αδρή λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινόχρηστων αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να καλείται άμεσα· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να καλείται άμεσα· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αντίστοιχο της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκοκκίνισμα της δήλωσης C# lock(). Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδρό μετρητή αναφορών. Δεν πρέπει να καλείται άμεσα· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδρό μετρητή αναφορών. Δεν πρέπει να καλείται άμεσα· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../../aspose.slides/pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Ελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [PVIObject](../../aspose.slides/pviobject/)
* Κλάση [IDataLabelFormat](../idatalabelformat/)
* Χώρος ονομάτων [Aspose::Slides::Charts](../)
* Βιβλιοθήκη [Aspose.Slides](../../)