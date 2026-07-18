---
title: IParagraphFormat
second_title: Aspose.Slides για C++ API Αναφορά
description: Αυτή η κλάση περιέχει τις ιδιότητες μορφοποίησης παραγράφων. Σε αντίθεση με IParagraphFormatEffectiveData, όλες οι ιδιότητες αυτής της κλάσης είναι εγγράψιμες.
type: docs
weight: 3147
url: /el/aspose.slides/iparagraphformat/
---
## IParagraphFormat κλάση


Αυτή η κλάση περιέχει τις ιδιότητες μορφοποίησης παραγράφων. Σε αντίθεση με [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/), όλες οι ιδιότητες αυτής της κλάσης είναι εγγράψιμες.

```cpp
class IParagraphFormat : public virtual System::Object
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σύνταξη C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής τύπου C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής τύπου C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() | Επιστρέφει την ευθυγράμμιση κειμένου σε παράγραφο χωρίς κληρονομικότητα. Διαβάστε [TextAlignment](../textalignment/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormat](../ibulletformat/)\> [get_Bullet](./get_bullet/)() | Επιστρέφει τη μορφή κουκκίδας της παραγράφου. Μόνο για ανάγνωση [IBulletFormat](../ibulletformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\> [get_DefaultPortionFormat](./get_defaultportionformat/)() | Επιστρέφει τη μορφή προεπιλεγμένου τμήματος μιας παραγράφου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [IPortionFormat](../iportionformat/). |
| virtual **float** [get_DefaultTabSize](./get_defaulttabsize/)() | Επιστρέφει το προεπιλεγμένο μέγεθος εσοχής με δεσοῦρα χωρίς κληρονομικότητα. Διαβάστε **float**. |
| virtual **int16_t** [get_Depth](./get_depth/)() | Επιστρέφει το βάθος της παραγράφου. Η τιμή 0 σημαίνει ακαθόριστη τιμή. Διαβάστε **int16_t**. |
| virtual [NullableBool](../nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() | Καθορίζει αν χρησιμοποιείται το ασιατικό σπασιμό γραμμής σε παράγραφο. Δεν εφαρμόζεται κληρονομικότητα. Διαβάστε [NullableBool](../nullablebool/). |
| virtual [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() | Επιστρέφει την ευθυγράμμιση γραμματοσειράς σε παράγραφο χωρίς κληρονομικότητα. Διαβάστε [Slides::FontAlignment](../fontalignment/). |
| virtual [NullableBool](../nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() | Καθορίζει αν χρησιμοποιείται η κρέμαση σημείας στίξης σε παράγραφο. Δεν εφαρμόζεται κληρονομικότητα. Διαβάστε [NullableBool](../nullablebool/). |
| virtual **float** [get_Indent](./get_indent/)() | Επιστρέφει το πρώτο κενό γραμμής/κρέμασής της παραγράφου χωρίς κληρονομικότητα. Η κρέμαση μπορεί να οριστεί με αρνητικές τιμές. Διαβάστε **float**. |
| virtual [NullableBool](../nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() | Καθορίζει αν χρησιμοποιείται το λατινικό σπασιμό γραμμής σε παράγραφο. Δεν εφαρμόζεται κληρονομικότητα. Διαβάστε [NullableBool](../nullablebool/). |
| virtual **float** [get_MarginLeft](./get_marginleft/)() | Επιστρέφει το αριστερό περιθώριο σε παράγραφο χωρίς κληρονομικότητα. Διαβάστε **float**. |
| virtual **float** [get_MarginRight](./get_marginright/)() | Επιστρέφει το δεξιό περιθώριο σε παράγραφο χωρίς κληρονομικότητα. Διαβάστε **float**. |
| virtual [NullableBool](../nullablebool/) [get_RightToLeft](./get_righttoleft/)() | Καθορίζει αν χρησιμοποιείται η γραφή από δεξιά προς αριστερά σε παράγραφο. Δεν εφαρμόζεται κληρονομικότητα. Διαβάστε [NullableBool](../nullablebool/). |
| virtual **float** [get_SpaceAfter](./get_spaceafter/)() | Επιστρέφει το ποσό του χώρου μετά την τελευταία γραμμή σε παράγραφο χωρίς κληρονομικότητα. Μία θετική τιμή καθορίζει το ποσοστό του μεγέθους της γραμματοσειράς που πρέπει να είναι το λευκό διάστημα. Μία αρνητική τιμή καθορίζει το μέγεθος του λευκού διαστήματος σε μονάδες σημείου. Διαβάστε **float**. |
| virtual **float** [get_SpaceBefore](./get_spacebefore/)() | Επιστρέφει το ποσό του χώρου πριν από την πρώτη γραμμή σε παράγραφο χωρίς κληρονομικότητα. Μία θετική τιμή καθορίζει το ποσοστό του μεγέθους της γραμματοσειράς που πρέπει να είναι το λευκό διάστημα. Μία αρνητική τιμή καθορίζει το μέγεθος του λευκού διαστήματος σε μονάδες σημείου. Διαβάστε **float**. |
| virtual **float** [get_SpaceWithin](./get_spacewithin/)() | Επιστρέφει το ποσό του χώρου μεταξύ των βασικών γραμμών σε παράγραφο. Θετική τιμή σημαίνει ποσοστό, αρνητική – μέγεθος σε σημεία. Δεν εφαρμόζεται κληρονομικότητα. Διαβάστε **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\> [get_Tab](./get_tab/)(**int32_t**) | Επιστρέφει την εσοχή μιας παραγράφου στο συγκεκριμένο δείκτη. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [Aspose::Slides::ITab](../itab/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../itabcollection/)\> [get_Tabs](./get_tabs/)() | Επιστρέφει τις εσοχές μιας παραγράφου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [ITabCollection](../itabcollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)\> [GetEffective](./geteffective/)() | Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης παραγράφου με την κληρονομικότητα εφαρμόζεται. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία κατακερματισμού προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί τη δήλωση C# lock() για κλείδωμα. Καλείται άμεσα ή χρησιμοποιεί το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγραφών σε υποκλάσεις. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγραφών σε υποκλάσεις. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αντικείμενα τύπου τιμής με αναφορά με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόμεσο μετρητή αναφοράς κατά την καθορισμένη τιμή. |
| virtual void [set_Alignment](./set_alignment/)([TextAlignment](../textalignment/)) | Ορίζει την ευθυγράμμιση κειμένου σε παράγραφο χωρίς κληρονομικότητα. Γράψτε [TextAlignment](../textalignment/). |
| virtual void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) | Ορίζει το προεπιλεγμένο μέγεθος εσοχής χωρίς κληρονομικότητα. Γράψτε **float**. |
| virtual void [set_Depth](./set_depth/)(**int16_t**) | Ορίζει το βάθος της παραγράφου. Η τιμή 0 σημαίνει ακαθόριστη τιμή. Γράψτε **int16_t**. |
| virtual void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../nullablebool/)) | Καθορίζει αν χρησιμοποιείται το ασιατικό σπασιμό γραμμής σε παράγραφο. Δεν εφαρμόζεται κληρονομικότητα. Γράψτε [NullableBool](../nullablebool/). |
| virtual void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../fontalignment/)) | Ορίζει την ευθυγράμμιση γραμματοσειράς σε παράγραφο χωρίς κληρονομικότητα. Γράψτε [Slides::FontAlignment](../fontalignment/). |
| virtual void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../nullablebool/)) | Καθορίζει αν χρησιμοποιείται η κρέμαση σημεία στίξης σε παράγραφο. Δεν εφαρμόζεται κληρονομικότητα. Γράψτε [NullableBool](../nullablebool/). |
| virtual void [set_Indent](./set_indent/)(**float**) | Ορίζει το πρώτο κενό γραμμής/κρέμασής της παραγράφου χωρίς κληρονομικότητα. Η κρέμαση μπορεί να οριστεί με αρνητικές τιμές. Γράψτε **float**. |
| virtual void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../nullablebool/)) | Καθορίζει αν χρησιμοποιείται το λατινικό σπασιμό γραμμής σε παράγραφο. Δεν εφαρμόζεται κληρονομικότητα. Γράψτε [NullableBool](../nullablebool/). |
| virtual void [set_MarginLeft](./set_marginleft/)(**float**) | Ορίζει το αριστερό περιθώριο σε παράγραφο χωρίς κληρονομικότητα. Γράψτε **float**. |
| virtual void [set_MarginRight](./set_marginright/)(**float**) | Ορίζει το δεξιό περιθώριο σε παράγραφο χωρίς κληρονομικότητα. Γράψτε **float**. |
| virtual void [set_RightToLeft](./set_righttoleft/)([NullableBool](../nullablebool/)) | Καθορίζει αν χρησιμοποιείται η γραφή από δεξιά προς αριστερά σε παράγραφο. Δεν εφαρμόζεται κληρονομικότητα. Γράψτε [NullableBool](../nullablebool/). |
| virtual void [set_SpaceAfter](./set_spaceafter/)(**float**) | Ορίζει το ποσό του χώρου μετά την τελευταία γραμμή σε παράγραφο χωρίς κληρονομικότητα. Μία θετική τιμή καθορίζει το ποσοστό του μεγέθους της γραμματοσειράς που πρέπει να είναι το λευκό διάστημα. Μία αρνητική τιμή καθορίζει το μέγεθος του λευκού διαστήματος σε μονάδες σημείου. Γράψτε **float**. |
| virtual void [set_SpaceBefore](./set_spacebefore/)(**float**) | Ορίζει το ποσό του χώρου πριν από την πρώτη γραμμή σε παράγραφο χωρίς κληρονομικότητα. Μία θετική τιμή καθορίζει το ποσοστό του μεγέθους της γραμματοσειράς που πρέπει να είναι το λευκό διάστημα. Μία αρνητική τιμή καθορίζει το μέγεθος του λευκού διαστήματος σε μονάδες σημείου. Γράψτε **float**. |
| virtual void [set_SpaceWithin](./set_spacewithin/)(**float**) | Ορίζει το ποσό του χώρου μεταξύ των βασικών γραμμών σε παράγραφο. Θετική τιμή σημαίνει ποσοστό, αρνητική – μέγεθος σε σημεία. Δεν εφαρμόζεται κληρονομικότητα. Γράψτε **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύνατο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε δοχεία σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να καλείται άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να καλείται άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί τη δημιουργία C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την απελευθέρωση του C# lock() statement. Καλείται άμεσα ή χρησιμοποιεί το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύνατο μετρητή αναφοράς. Δεν πρέπει να καλείται άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύνατο μετρητή αναφοράς. Δεν πρέπει να καλείται άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστροφή αντικειμένου. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Παρατηρήσεις


Αυτή η κλάση χρησιμοποιείται για την επιστροφή και τη διαχείριση των ιδιοτήτων μορφοποίησης παραγράφου που ορίζονται για τη συγκεκριμένη παράγραφο. Αυτό σημαίνει ότι δεν εφαρμόζεται κληρονομικότητα κατά τη λήψη τιμών, οπότε στις περισσότερες περιπτώσεις θα λάβετε τιμές που σημαίνουν «ακαθόριστη».

Για να λάβετε τις αποτελεσματικές τιμές παραμέτρων μορφοποίησης συμπεριλαμβανομένης της κληρονομικότητας, πρέπει να χρησιμοποιήσετε τη μέθοδο [IParagraphFormat::GetEffective](./geteffective/) που επιστρέφει μια παρουσία [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/).

## Δείτε επίσης

* Κλάση [Object](../../system/object/)
* Χώρος ονομάτων [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)