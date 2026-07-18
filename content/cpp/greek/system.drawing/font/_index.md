---
title: Font
second_title: Αναφορά API Aspose.Slides για C++
description: "Αναπαριστά μια συγκεκριμένη μορφή κειμένου, συμπεριλαμβανομένης της γραμματοσειράς, του μεγέθους και του στυλ. Τα αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη λειτουργία System::MakeObject() . Ποτέ μην δημιουργείτε αντίτυπο αυτού του τύπου στο στοίβα ή χρησιμοποιώντας operator new, καθώς θα επιφέρει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα να τυλίγετε αυτή την κλάση σε δείκτη System::SmartPtr και να χρησιμοποιείτε αυτόν τον δείκτη για να το περάσετε σε συναρτήσεις ως όρισμα."
type: docs
weight: 79
url: /el/system.drawing/font/
---
## Font κλάση

Αναπαριστά μια συγκεκριμένη μορφή κειμένου, συμπεριλαμβανομένης της γραμματοσειράς, του μεγέθους και του στιλ. Τα αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη λειτουργία [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε αντίτυπο αυτού του τύπου στο στοίβα ή χρησιμοποιώντας operator new, καθώς θα επιφέρει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα να τυλίγετε αυτή την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και να χρησιμοποιείτε αυτόν τον δείκτη για να το περάσετε σε συναρτήσεις ως όρισμα.

```cpp
class Font : public System::Object
```

## Μέθοδοι

| Method | Περιγραφή |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Font](./)\> [Clone](./clone/)() | Επιστρέφει αντίγραφο της τρέχουσας γραμματοσειράς. |
| void [Dispose](./dispose/)() | Απελευθερώνει όλους τους πόρους του λειτουργικού συστήματος που αποκτήθηκαν από το τρέχον αντικείμενο. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Καθορίζει εάν το τρέχον και τα καθορισμένα αντικείμενα είναι πανομοιότυπα. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σύνταξη C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
|  [Font](./font/)(const [SharedPtr](../../system/sharedptr/)\<[Font](./)\>\&, [FontStyle](../fontstyle/)) | Δημιουργεί μια νέα παρουσία της κλάσης [Font](./) που αντιπροσωπεύει τη συγκεκριμένη υπάρχουσα γραμματοσειρά με το συγκεκριμένο στυλ γραμματοσειράς. |
|  [Font](./font/)(const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../fontfamily/)\>\&, **float**, [FontStyle](../fontstyle/), [GraphicsUnit](../graphicsunit/), **uint8_t**, **bool**) | Δημιουργεί μια νέα παρουσία της κλάσης [Font](./). |
|  [Font](./font/)(const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../fontfamily/)\>\&, **float**, [GraphicsUnit](../graphicsunit/)) | Δημιουργεί μια νέα παρουσία της κλάσης [Font](./). |
|  [Font](./font/)(const [String](../../system/string/)\&, **float**, [FontStyle](../fontstyle/), [GraphicsUnit](../graphicsunit/), **uint8_t**, **bool**) | Δημιουργεί μια νέα παρουσία της κλάσης [Font](./). |
|  [Font](./font/)(const [String](../../system/string/)\&, **float**, [GraphicsUnit](../graphicsunit/)) | Δημιουργεί μια νέα παρουσία της κλάσης [Font](./). |
| static [SharedPtr](../../system/sharedptr/)\<[Font](./)\> [FromLogFont](./fromlogfont/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | ΔΕΝ ΥΛΟΠΟΙΗΤΕΙ. |
| **bool** [get_Bold](./get_bold/)() | Καθορίζει εάν η γραμματοσειρά που αντιπροσωπεύεται από το τρέχον αντικείμενο έχει εφαρμόστυ το έντονο στυλ. |
| [SharedPtr](../../system/sharedptr/)\<[FontFamily](../fontfamily/)\> [get_FontFamily](./get_fontfamily/)() | Επιστρέφει την οικογένεια γραμματοσειράς της γραμματοσειράς που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| [FontStyle](../fontstyle/) [get_FontStyle](./get_fontstyle/)() | Επιστρέφει το στυλ γραμματοσειράς της γραμματοσειράς που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| **uint8_t** [get_GdiCharSet](./get_gdicharset/)() | Επιστρέφει μια τιμή που υποδεικνύει το σύνολο χαρακτήρων GDI που χρησιμοποιείται από τη γραμματοσειρά που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| int [get_Height](./get_height/)() | Επιστρέφει το διάστημα γραμμής της γραμματοσειράς που αντιπροσωπεύεται από το τρέχον αντικείμενο σε εικονοστοιχεία. |
| **bool** [get_Italic](./get_italic/)() | Καθορίζει εάν η γραμματοσειρά που αντιπροσωπεύεται από το τρέχον αντικείμενο έχει εφαρμόστυ το πλάγιο στυλ. |
| [String](../../system/string/) [get_Name](./get_name/)() | Επιστρέφει το όνομα προσώπου της γραμματοσειράς που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| [String](../../system/string/) [get_OriginalFontName](./get_originalfontname/)() | Επιστρέφει το αρχικά καθορισμένο όνομα της γραμματοσειράς. |
| **float** [get_Size](./get_size/)() | Επιστρέφει το μέγεθος em της γραμματοσειράς που αντιπροσωπεύεται από το τρέχον αντικείμενο, μετρημένο στις μονάδες που καθορίζονται από την ιδιότητα Unit. |
| **float** [get_SizeInPoints](./get_sizeinpoints/)() | Επιστρέφει το μέγεθος em της γραμματοσειράς που αντιπροσωπεύεται από το τρέχον αντικείμενο σε μονάδες σημείου. |
| **bool** [get_Strikeout](./get_strikeout/)() | Καθορίζει εάν η γραμματοσειρά που αντιπροσωπεύεται από το τρέχον αντικείμενο έχει εφαρμόστυ το στυλ διακριτής γραμμής. |
| [FontStyle](../fontstyle/) [get_Style](./get_style/)() | Επιστρέφει το στυλ γραμματοσειράς της γραμματοσειράς που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| **bool** [get_Underline](./get_underline/)() | Καθορίζει εάν η γραμματοσειρά που αντιπροσωπεύεται από το τρέχον αντικείμενο έχει εφαρμόστυ το υπογράμμιση στυλ. |
| [GraphicsUnit](../graphicsunit/) [get_Unit](./get_unit/)() | Επιστρέφει τη μονάδα μέτρησης για τη γραμματοσειρά που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογική της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία κατακερματισμού για προσαρμοσμένα αντικείμενα. |
| **float** [GetHeight](./getheight/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Επιστρέφει το διάστημα γραμμής της γραμματοσειράς που αντιπροσωπεύεται από το τρέχον αντικείμενο, στη τρέχουσα μονάδα ενός καθορισμένου αντικειμένου [Graphics](../graphics/). |
| **float** [GetHeight](./getheight/)(**float**) | Επιστρέφει το ύψος της γραμματοσειράς που αντιπροσωπεύεται από το τρέχον αντικείμενο όταν εμφανίζεται σε συσκευή εμφάνισης με την καθορισμένη κάθετη ανάλυση. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογική της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από targetType. Αναλογική του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί την κλειδαριά της δήλωσης C# lock(). Καλείται απευθείας ή χρησιμοποιεί το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογική της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την αντιγραφή κατασκευής των υποκατηγοριών. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την αντιγραφή κατασκευής των υποκατηγοριών. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει κατά αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινόχρηστων αναφορών κατά την καθορισμένη τιμή. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμη δείκτης (αντί για κοινόχρηστο). Επιτρέπει την εναλλαγή δεικτών σε δομές σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινόχρηστων αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί γι' αυτό, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί γι' αυτό, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογική της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την αποδέσμευση της δήλωσης C# lock(). Καλείται απευθείας ή χρησιμοποιεί το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί γι' αυτό, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί γι' αυτό, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [Object](../../system/object/)
* Ονομαχώρος [System::Drawing](../)
* Βιβλιοθήκη [Aspose.Slides](../../)