---
title: CultureInfo
second_title: Αναφορά API Aspose.Slides για C++
description: "Συλλογή τιμών και αλγορίθμων ειδικών για κάθε πολιτισμό. Οι λειτουργίες ορισμού είναι ενεργοποιημένες μόνο σε αντικείμενα που δεν είναι μόνο-ανάγνωση. Τα αντικείμενα αυτής της κλάσης πρέπει να κατασκευάζονται μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject(). Ποτέ μην δημιουργείτε στιγμιότυπο αυτού του τύπου στο στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη System::SmartPtr και χρησιμοποιήστε αυτόν τον δείκτη για να τον περάσετε σε συναρτήσεις ως όρισμα."
type: docs
weight: 53
url: /el/system.globalization/cultureinfo/
---
## CultureInfo κλάση

Συλλογή τιμών και αλγορίθμων ειδικών για κάθε πολιτισμό. Οι λειτουργίες ορισμού είναι ενεργοποιημένες μόνο σε αντικείμενα που δεν είναι μόνο-ανάγνωση. Τα αντικείμενα αυτής της κλάσης πρέπει να δομούνται μόνο χρησιμοποιώντας τη λειτουργία [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε ένα στιγμιότυπο αυτού του τύπου στο στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για να τον περάσετε σε συναρτήσεις ως όρισμα.

```cpp
class CultureInfo : public virtual System::Object,
                    public System::IFormatProvider,
                    public System::ICloneable
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| void [ClearCachedData](./clearcacheddata/)() | Ανανεώνει τις αποθηκευμένες πληροφορίες πολιτισμού. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Δημιουργεί κλώνο των πληροφοριών πολιτισμού. |
| static [CultureInfoPtr](../cultureinfoptr/) [CreateSpecificCulture](./createspecificculture/)(const [String](../../system/string/)\&) | Δημιουργεί πολιτισμό με βάση το όνομα. |
| explicit  [CultureInfo](./cultureinfo/)(int) | Πληροφορίες RTTI. |
|  [CultureInfo](./cultureinfo/)(int, **bool**) | Κατασκευαστής. |
| explicit  [CultureInfo](./cultureinfo/)(const [String](../../system/string/)\&) | Κατασκευαστής. |
|  [CultureInfo](./cultureinfo/)(const [String](../../system/string/)\&, **bool**) | Κατασκευαστής. |
|  [CultureInfo](./cultureinfo/)(std::nullptr_t) | Πάντα ρίχνει ArgumentNullException. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Συγκρίνει αντικείμενα. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με το IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με το IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual [CalendarPtr](../calendarptr/) [get_Calendar](./get_calendar/)() const | Λαμβάνει το ημερολόγιο που χρησιμοποιείται από τον πολιτισμό. |
| virtual [CompareInfoPtr](../compareinfoptr/) [get_CompareInfo](./get_compareinfo/)() const | Λαμβάνει συγκριτή συμβολοσειρών που τηρεί τους κανόνες του πολιτισμού. |
| [CultureTypes](../culturetypes/) [get_CultureTypes](./get_culturetypes/)() const | Λαμβάνει το bitwise σύμφωνο των τύπων πολιτισμού που περιγράφουν τον τρέχον πολιτισμό. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_CurrentCulture](./get_currentculture/)() | Λαμβάνει τον πολιτισμό που έχει οριστεί για το τρέχον νήμα. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_CurrentUICulture](./get_currentuiculture/)() | Λαμβάνει τον πολιτισμό διεπαφής χρήστη του τρέχοντος νήματος. |
| virtual [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [get_DateTimeFormat](./get_datetimeformat/)() const | Λαμβάνει πληροφορίες μορφής ημερομηνίας. |
| static [CultureInfoPtr](../cultureinfoptr/) [get_DefaultThreadCurrentCulture](./get_defaultthreadcurrentculture/)() | Λαμβάνει τον προεπιλεγμένο πολιτισμό στο τρέχον domain εφαρμογής. |
| static [CultureInfoPtr](../cultureinfoptr/) [get_DefaultThreadCurrentUICulture](./get_defaultthreadcurrentuiculture/)() | Λαμβάνει τον προεπιλεγμένο πολιτισμό διεπαφής χρήστη στο τρέχον domain εφαρμογής. |
| virtual [String](../../system/string/) [get_DisplayName](./get_displayname/)() const | Λαμβάνει το εμφανιζόμενο όνομα του πολιτισμού. |
| virtual [String](../../system/string/) [get_EnglishName](./get_englishname/)() const | Λαμβάνει το αγγλικό όνομα του πολιτισμού. |
| [String](../../system/string/) [get_IetfLanguageTag](./get_ietflanguagetag/)() const | Λαμβάνει το όνομα RFC 4646 για μια γλώσσα. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_InstalledUICulture](./get_installeduiculture/)() | Λαμβάνει τον πολιτισμό που είναι εγκατεστημένος με το λειτουργικό σύστημα. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_InvariantCulture](./get_invariantculture/)() | Λαμβάνει τον αμετάβλητο πολιτισμό. |
| virtual **bool** [get_IsNeutralCulture](./get_isneutralculture/)() const | Ελέγχει αν ο πολιτισμός είναι ουδέτερος. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | Ελέγχει αν το αντικείμενο πολιτισμού είναι μόνο-ανάγνωση. |
| virtual int [get_KeyboardLayoutId](./get_keyboardlayoutid/)() const | Λαμβάνει το ενεργό αναγνωριστικό τοπικής ρύθμισης εισόδου. |
| virtual int [get_LCID](./get_lcid/)() const | Λαμβάνει το αναγνωριστικό πολιτισμού. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() const | Λαμβάνει το όνομα του πολιτισμού. |
| virtual [String](../../system/string/) [get_NativeName](./get_nativename/)() const | Λαμβάνει το φυσικό όνομα του πολιτισμού. |
| virtual [NumberFormatInfoPtr](../numberformatinfoptr/) [get_NumberFormat](./get_numberformat/)() const | Λαμβάνει πληροφορίες μορφοποίησης αριθμών. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[CalendarPtr](../calendarptr/)\> [get_OptionalCalendars](./get_optionalcalendars/)() const | Λίστα ημερολογίων που μπορούν να χρησιμοποιηθούν με τον πολιτισμό. |
| virtual [CultureInfoPtr](../cultureinfoptr/) [get_Parent](./get_parent/)() const | Λαμβάνει τον γονικό πολιτισμό. |
| virtual [TextInfoPtr](../textinfoptr/) [get_TextInfo](./get_textinfo/)() const | Λαμβάνει τις παραμέτρους κειμένου που χρησιμοποιεί ο πολιτισμός. |
| virtual [String](../../system/string/) [get_ThreeLetterISOLanguageName](./get_threeletterisolanguagename/)() const | Λαμβάνει τον τριψήφιο κώδικα γλώσσας ISO 639-2. |
| virtual [String](../../system/string/) [get_ThreeLetterWindowsLanguageName](./get_threeletterwindowslanguagename/)() const | Λαμβάνει τον τριψήφιο κώδικα για τη γλώσσα όπως ορίζεται στο API [Windows](../../system.windows/). |
| virtual [String](../../system/string/) [get_TwoLetterISOLanguageName](./get_twoletterisolanguagename/)() const | Λαμβάνει το διψήφιο όνομα γλώσσας ISO που σχετίζεται με τον πολιτισμό. |
| **bool** [get_UseUserOverride](./get_useuseroverride/)() const | Λαμβάνει μια σημαία που υποδεικνύει αν το [CultureInfo](./) χρησιμοποιεί ρυθμίσεις πολιτισμού επιλεγμένες από τον χρήστη. |
| [CultureInfoPtr](../cultureinfoptr/) [GetConsoleFallbackUICulture](./getconsolefallbackuiculture/)() const | Λαμβάνει εναλλακτικό πολιτισμό κατάλληλο για εφαρμογές κονσόλας. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που συνδέεται με το αντικείμενο. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfo](./getcultureinfo/)(const [String](../../system/string/)\&) | Λαμβάνει πολιτισμό με βάση το όνομά του. Το ίδιο με το CreateSpecificCulture. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfo](./getcultureinfo/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Λαμβάνει πολιτισμό με βάση το όνομά του. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfo](./getcultureinfo/)(**int32_t**) | Λαμβάνει πολιτισμό με βάση το αναγνωριστικό. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfoByIetfLanguageTag](./getcultureinfobyietflanguagetag/)(const [String](../../system/string/)\&) | Παρωχημένο. Λαμβάνει ένα αντικείμενο [CultureInfo](./) μόνο-ανάγνωση με την καθορισμένη ετικέτα γλώσσας RFC 4646. |
| static [ArrayPtr](../../system/arrayptr/)\<[CultureInfoPtr](../cultureinfoptr/)\> [GetCultures](./getcultures/)([CultureTypes](../culturetypes/)) | Λαμβάνει πολιτισμούς που ανήκουν σε συγκεκριμένους τύπους. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | Λαμβάνει το αντικείμενο μορφής για συγκεκριμένο τύπο. |
| int [GetHashCode](./gethashcode/)() const override | Επιστρέφει τον κώδικα κατακερματισμού του αντικειμένου. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από το targetType. Αναλογικό του τελεστή C# 'is'. |
| **bool** [IsInherited](./isinherited/)() const | Λαμβάνει τη σημαία κληρονομικότητας. ΓΙΑ ΕΣΩΤΕΡΙΚΗ ΧΡΗΣΗ. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Επιτρέπει την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκλάσεων. |
| [CultureInfo](./)\& [operator=](./operator_equal/)(const [CultureInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκλάσεων. |
| **bool** [operator==](./operator_equal_equal/)(const [CultureInfo](./)\&) const | Συγκρίνει παραμέτρους πολιτισμού. |
| static [CultureInfoPtr](../cultureinfoptr/) [ReadOnly](./readonly/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | Λαμβάνει μια έκδοση μόνο-ανάγνωση του πολιτισμού. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινόχρηστων αναφορών κατά την καθορισμένη τιμή. |
| static void [set_CurrentCulture](./set_currentculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | Ορίζει τον πολιτισμό για το τρέχον νήμα. |
| static void [set_CurrentUICulture](./set_currentuiculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | Ορίζει τον πολιτισμό διεπαφής χρήστη του τρέχοντος νήματος. |
| virtual void [set_DateTimeFormat](./set_datetimeformat/)([DateTimeFormatInfoPtr](../datetimeformatinfoptr/)) | Ορίζει πληροφορίες μορφής ημερομηνίας. |
| static void [set_DefaultThreadCurrentCulture](./set_defaultthreadcurrentculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | Ορίζει τον προεπιλεγμένο πολιτισμό στο τρέχον domain εφαρμογής. |
| static void [set_DefaultThreadCurrentUICulture](./set_defaultthreadcurrentuiculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | Ορίζει τον προεπιλεγμένο πολιτισμό διεπαφής χρήστη στο τρέχον domain εφαρμογής. |
| virtual void [set_NumberFormat](./set_numberformat/)([NumberFormatInfoPtr](../numberformatinfoptr/)) | Λαμβάνει πληροφορίες μορφοποίησης αριθμών. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμη αναφορά (αντί για κοινόχρηστη). Επιτρέπει την αλλαγή των δεικτών σε δοχεία σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινόχρηστων αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να καλείται άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να καλείται άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Μεττρέπει τον πολιτισμό σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Εκτελεί το C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Εκτελεί την αποδέσμευση της δήλωσης C# lock(). Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο φρουράς [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον μετρητή αδύναμων αναφορών. Δεν πρέπει να καλείται άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον μετρητή αδύναμων αναφορών. Δεν πρέπει να καλείται άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [Object](../../system/object/)
* Κλάση [IFormatProvider](../../system/iformatprovider/)
* Κλάση [ICloneable](../../system/icloneable/)
* Ονομαχώρος [System::Globalization](../)
* Βιβλιοθήκη [Aspose.Slides](../../)