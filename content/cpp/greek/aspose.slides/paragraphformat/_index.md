---
title: ParagraphFormat
second_title: Αναφορά API Aspose.Slides για C++
description: Αυτή η κλάση περιέχει τις ιδιότητες μορφοποίησης παραγράφου. Σε αντίθεση με IParagraphFormatEffectiveData, όλες οι ιδιότητες αυτής της κλάσης είναι εγγράψιμες.
type: docs
weight: 4668
url: /el/aspose.slides/paragraphformat/
---
## ParagraphFormat κλάση

Αυτή η κλάση περιέχει τις ιδιότητες μορφοποίησης παραγράφου. Σε αντίθεση με [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/), όλες οι ιδιότητες αυτής της κλάσης είναι εγγράψιμες.

```cpp
class ParagraphFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::IParagraphFormat,
                        public Aspose::Slides::Charts::IChartParagraphFormat
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Συγκρίνει με το καθορισμένο αντικείμενο. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς με στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Προσομοιώνει σύγκριση κινητής υποδιαστολής τύπου C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Προσομοιώνει σύγκριση κινητής υποδιαστολής τύπου C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερικές ανάγκες. |
| [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() override | Επιστρέφει τη στοίχιση κειμένου σε μια παράγραφο χωρίς κληρονόμηση. Διαβάστε [TextAlignment](../textalignment/). |
| **float** [get_DefaultTabSize](./get_defaulttabsize/)() override | Επιστρέφει το προεπιλεγμένο μέγεθος εσοχής χωρίς κληρονόμηση. Διαβάστε **float**. |
| [NullableBool](../nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() override | Προσδιορίζει εάν η ασιατική διάσπαση γραμμής χρησιμοποιείται σε μια παράγραφο. Δεν εφαρμόζεται κληρονόμηση. Διαβάστε [NullableBool](../nullablebool/). |
| [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() override | Επιστρέφει την ευθυγράμμιση γραμματοσειράς σε μια παράγραφο χωρίς κληρονόμηση. Διαβάστε [Slides::FontAlignment](../fontalignment/). |
| [NullableBool](../nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() override | Προσδιορίζει εάν η «κρεμαστή» στίξη χρησιμοποιείται σε μια παράγραφο. Δεν εφαρμόζεται κληρονόμηση. Διαβάστε [NullableBool](../nullablebool/). |
| **float** [get_Indent](./get_indent/)() override | Επιστρέφει την εσοχή πρώτης γραμμής/κρεμαστή εσοχή της παραγράφου χωρίς κληρονόμηση. Η κρεμαστή εσοχή μπορεί να οριστεί με αρνητικές τιμές. Διαβάστε **float**. |
| [NullableBool](../nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() override | Προσδιορίζει εάν η λατινική διάσπαση γραμμής χρησιμοποιείται σε μια παράγραφο. Δεν εφαρμόζεται κληρονόμηση. Διαβάστε [NullableBool](../nullablebool/). |
| **float** [get_MarginLeft](./get_marginleft/)() override | Επιστρέφει το αριστερό περιθώριο σε μια παράγραφο χωρίς κληρονόμηση. Διαβάστε **float**. |
| **float** [get_MarginRight](./get_marginright/)() override | Επιστρέφει το δεξί περιθώριο σε μια παράγραφο χωρίς κληρονόμηση. Διαβάστε **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο για ανάγνωση [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Επιστρέφει το γονικό [IPresentationComponent](../ipresentationcomponent/). Μόνο για ανάγνωση [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_RightToLeft](./get_righttoleft/)() override | Προσδιορίζει εάν η γραφή από Δεξιά προς Αριστερά χρησιμοποιείται σε μια παράγραφο. Δεν εφαρμόζεται κληρονόμηση. Διαβάστε [NullableBool](../nullablebool/). |
| **float** [get_SpaceAfter](./get_spaceafter/)() override | Επιστρέφει το ποσό του διαστήματος μετά την τελευταία γραμμή σε μια παράγραφο χωρίς κληρονόμηση. Μια θετική τιμή καθορίζει το ποσοστό του μεγέθους γραμματοσειράς που πρέπει να είναι το λευκό διάστημα. Μια αρνητική τιμή καθορίζει το μέγεθος του λευκού διαστήματος σε σημεία. Διαβάστε **float**. |
| **float** [get_SpaceBefore](./get_spacebefore/)() override | Επιστρέφει το ποσό του διαστήματος πριν την πρώτη γραμμή σε μια παράγραφο χωρίς κληρονόμηση. Μια θετική τιμή καθορίζει το ποσοστό του μεγέθους γραμματοσειράς που πρέπει να είναι το λευκό διάστημα. Μια αρνητική τιμή καθορίζει το μέγεθος του λευκού διαστήματος σε σημεία. Διαβάστε **float**. |
| **float** [get_SpaceWithin](./get_spacewithin/)() override | Επιστρέφει το ποσό του διαστήματος μεταξύ βασικών γραμμών σε μια παράγραφο. Η θετική τιμή σημαίνει ποσοστό, η αρνητική – μέγεθος σε σημεία. Δεν εφαρμόζεται κληρονόμηση. Διαβάστε **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\> [get_Tab](./get_tab/)(**int32_t**) override | Επιστρέφει την εσοχή μιας παραγράφου στο καθορισμένο δείκτη. Δεν εφαρμόζεται κληρονόμηση. Μόνο για ανάγνωση [Aspose::Slides::ITab](../itab/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../itabcollection/)\> [get_Tabs](./get_tabs/)() override | Επιστρέφει τις εσοχές μιας παραγράφου. Δεν εφαρμόζεται κληρονόμηση. Μόνο για ανάγνωση [ITabCollection](../itabcollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που είναι συνδεδεμένη με το αντικείμενο. |
| [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)\> [GetEffective](./geteffective/)() override | Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης παραγράφου με την εφαρμοσμένη κληρονόμηση. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Επιστρέφει τον κωδικό κατακερματισμού. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αντίστοιχο της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια παρουσία τύπου που περιγράφεται από targetType. Αντίστοιχο του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί τη δήλωση κλειδώματος C# lock(). Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αντίστοιχο της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την κατασκευή αντιγράφων των υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την κατασκευή αντιγράφων των υποκλάσεων. |
|  [ParagraphFormat](./paragraphformat/)() | Αρχικοποιεί μια νέα παρουσία της κλάσης [ParagraphFormat](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει τιμή τύπου αναφοράς με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινόχρηστων αναφορών κατά την καθορισμένη τιμή. |
| void [set_Alignment](./set_alignment/)([TextAlignment](../textalignment/)) override | Ορίζει τη στοίχιση κειμένου σε μια παράγραφο χωρίς κληρονόμηση. Γράψτε [TextAlignment](../textalignment/). |
| void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) override | Ορίζει το προεπιλεγμένο μέγεθος εσοχής χωρίς κληρονόμηση. Γράψτε **float**. |
| void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../nullablebool/)) override | Προσδιορίζει εάν η ασιατική διάσπαση γραμμής χρησιμοποιείται σε μια παράγραφο. Δεν εφαρμόζεται κληρονόμηση. Γράψτε [NullableBool](../nullablebool/). |
| void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../fontalignment/)) override | Ορίζει μια ευθυγράμμιση γραμματοσειράς σε μια παράγραφο χωρίς κληρονόμηση. Γράψτε [Slides::FontAlignment](../fontalignment/). |
| void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../nullablebool/)) override | Προσδιορίζει εάν η κρεμαστή στίξη χρησιμοποιείται σε μια παράγραφο. Δεν εφαρμόζεται κληρονόμηση. Γράψτε [NullableBool](../nullablebool/). |
| void [set_Indent](./set_indent/)(**float**) override | Ορίζει την εσοχή πρώτης γραμμής/κρεμαστή εσοχή της παραγράφου χωρίς κληρονόμηση. Η κρεμαστή εσοχή μπορεί να οριστεί με αρνητικές τιμές. Γράψτε **float**. |
| void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../nullablebool/)) override | Προσδιορίζει εάν η λατινική διάσπαση γραμμής χρησιμοποιείται σε μια παράγραφο. Δεν εφαρμόζεται κληρονόμηση. Γράψτε [NullableBool](../nullablebool/). |
| void [set_MarginLeft](./set_marginleft/)(**float**) override | Ορίζει το αριστερό περιθώριο σε μια παράγραφο χωρίς κληρονόμηση. Γράψτε **float**. |
| void [set_MarginRight](./set_marginright/)(**float**) override | Ορίζει το δεξί περιθώριο σε μια παράγραφο χωρίς κληρονόμηση. Γράψτε **float**. |
| void [set_RightToLeft](./set_righttoleft/)([NullableBool](../nullablebool/)) override | Προσδιορίζει εάν η γραφή από Δεξιά προς Αριστερά χρησιμοποιείται σε μια παράγραφο. Δεν εφαρμόζεται κληρονόμηση. Γράψτε [NullableBool](../nullablebool/). |
| void [set_SpaceAfter](./set_spaceafter/)(**float**) override | Ορίζει το ποσό του διαστήματος μετά την τελευταία γραμμή σε μια παράγραφο χωρίς κληρονόμηση. Μια θετική τιμή καθορίζει το ποσοστό του μεγέθους γραμματοσειράς που πρέπει να είναι το λευκό διάστημα. Μια αρνητική τιμή καθορίζει το μέγεθος του λευκού διαστήματος σε σημεία. Γράψτε **float**. |
| void [set_SpaceBefore](./set_spacebefore/)(**float**) override | Ορίζει το ποσό του διαστήματος πριν την πρώτη γραμμή σε μια παράγραφο χωρίς κληρονόμηση. Μια θετική τιμή καθορίζει το ποσοστό του μεγέθους γραμματοσειράς που πρέπει να είναι το λευκό διάστημα. Μια αρνητική τιμή καθορίζει το μέγεθος του λευκού διαστήματος σε σημεία. Γράψτε **float**. |
| void [set_SpaceWithin](./set_spacewithin/)(**float**) override | Ορίζει το ποσό του διαστήματος μεταξύ βασικών γραμμών σε μια παράγραφο. Η θετική τιμή σημαίνει ποσοστό, η αρνητική – μέγεθος σε σημεία. Δεν εφαρμόζεται κληρονόμηση. Γράψτε **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την εναλλαγή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αντίστοιχο της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την αποδεσμευτική δήλωση C# lock(). Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Παρατηρήσεις

Αυτή η κλάση χρησιμοποιείται για την επιστροφή και τη διαχείριση των ιδιοτήτων μορφοποίησης παραγράφου που ορίζονται για τη συγκεκριμένη παράγραφο. Αυτό σημαίνει ότι δεν εφαρμόζεται κληρονόμηση κατά τη λήψη τιμών, έτσι στις περισσότερες περιπτώσεις θα λάβετε τιμές που σημαίνουν «απροσδιόριστο».

Για να λάβετε τις αποτελεσματικές τιμές παραμέτρων μορφοποίησης συμπεριλαμβανομένων των κληρονομημένων, πρέπει να χρησιμοποιήσετε τη μέθοδο [ParagraphFormat::GetEffective](./geteffective/) η οποία επιστρέφει μια παρουσία [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/).

## Δείτε επίσης

* Κλάση [PVIObject](../pviobject/)
* Κλάση [IParagraphFormat](../iparagraphformat/)
* Κλάση [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat/)
* Χώρος ονομάτων [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)