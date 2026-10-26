---
title: TimeZoneInfo
second_title: Αναφορά API Aspose.Slides για C++
description: "Αναπαριστά πληροφορία που περιγράφει μια συγκεκριμένη ζώνη ώρας. Αντικείμενα αυτής της κλάσης θα πρέπει να καταλαμβάνονται μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject() function. Ποτέ μην δημιουργείτε ένα στιγμιότυπο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προξενήσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα περιβάλλετε αυτή την κλάση σε System::SmartPtr pointer και χρησιμοποιήστε αυτόν τον δείκτη για να το περάσετε στις συναρτήσεις ως όρισμα."
type: docs
weight: 1314
url: /el/system/timezoneinfo/
---
## TimeZoneInfo κλάση

Αναπαριστά πληροφορία που περιγράφει μια συγκεκριμένη ζώνη ώρας. Αντικείμενα αυτής της κλάσης θα πρέπει να καταλαμβάνονται μόνο χρησιμοποιώντας τη συνάρτηση [System::MakeObject()](../makeobject/). Ποτέ μην δημιουργείτε ένα στιγμιότυπο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προξενήσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα περιβάλλετε αυτή την κλάση σε δείκτη [System::SmartPtr](../smartptr/) και χρησιμοποιήστε αυτό το δείκτη για να το περάσετε σε συναρτήσεις ως όρισμα.

```cpp
class TimeZoneInfo : public System::IEquatable<TimeZoneInfoPtr>
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| static void [ClearCachedData](./clearcacheddata/)() | Καθαρίζει τα δεδομένα της προσωρινής μνήμης ζώνης ώρας. |
| static [DateTime](../datetime/) [ConvertTime](./converttime/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&, const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | [Convert](../convert/) χρόνο από μία ζώνη ώρας σε άλλη. |
| static [DateTimeOffset](../datetimeoffset/) [ConvertTime](./converttime/)(const [DateTimeOffset](../datetimeoffset/)\&, const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | [Convert](../convert/) χρόνο στην ώρα σε καθορισμένη ζώνη ώρας. |
| static [DateTime](../datetime/) [ConvertTime](./converttime/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | [Convert](../convert/) χρόνο στην ώρα σε καθορισμένη ζώνη ώρας. |
| static [DateTime](../datetime/) [ConvertTimeBySystemTimeZoneId](./converttimebysystemtimezoneid/)([DateTime](../datetime/), const [String](../string/)\&) | [Convert](../convert/) χρόνο στην ώρα σε καθορισμένη ζώνη ώρας. |
| static [DateTimeOffset](../datetimeoffset/) [ConvertTimeBySystemTimeZoneId](./converttimebysystemtimezoneid/)(const [DateTimeOffset](../datetimeoffset/)\&, const [String](../string/)\&) | [Convert](../convert/) χρόνο στην ώρα σε καθορισμένη ζώνη ώρας. |
| static [DateTime](../datetime/) [ConvertTimeBySystemTimeZoneId](./converttimebysystemtimezoneid/)([DateTime](../datetime/), const [String](../string/)\&, const [String](../string/)\&) | [Convert](../convert/) χρόνο στην ώρα σε καθορισμένη ζώνη ώρας. |
| static [DateTime](../datetime/) [ConvertTimeFromUtc](./converttimefromutc/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | Μετατρέπει το UTC-time στην ώρα μιας καθορισμένης ζώνης ώρας. |
| static [DateTime](../datetime/) [ConvertTimeToUtc](./converttimetoutc/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | Μετατρέπει το χρόνο σε UTC-time. |
| static [DateTime](../datetime/) [ConvertTimeToUtc](./converttimetoutc/)([DateTime](../datetime/)) | Μετατρέπει το χρόνο σε UTC-time. |
| static [DateTime](../datetime/) [ConvertTimeToUtcNoThrow](./converttimetoutcnothrow/)([DateTime](../datetime/)) | Μετατρέπει το χρόνο σε UTC-time. ΓΙΑ ΕΣΩΤΡΙΚΗ ΧΡΗΣΗ. |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [CreateCustomTimeZone](./createcustomtimezone/)(const [String](../string/)\&, [TimeSpan](../timespan/), const [String](../string/)\&, const [String](../string/)\&, const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[AdjustmentRulePtr](./adjustmentruleptr/)\>\&, **bool**) | Δημιουργεί μια προσαρμοσμένη ζώνη ώρας. |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [CreateCustomTimeZone](./createcustomtimezone/)(const [String](../string/)\&, [TimeSpan](../timespan/), const [String](../string/)\&, const [String](../string/)\&, const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[AdjustmentRulePtr](./adjustmentruleptr/)\>\&) | Δημιουργεί μια προσαρμοσμένη ζώνη ώρας. |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [CreateCustomTimeZone](./createcustomtimezone/)(const [String](../string/)\&, [TimeSpan](../timespan/), const [String](../string/)\&, const [String](../string/)\&) | Δημιουργεί μια προσαρμοσμένη ζώνη ώρας. |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) override |  |
| **bool** [Equals](./equals/)([TimeZoneInfoPtr](../timezoneinfoptr/)) override | Καθορίζει αν τα τρέχοντα και τα καθορισμένα αντικείμενα είναι ίσα. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [FindSystemTimeZoneById](./findsystemtimezonebyid/)(const [String](../string/)\&) | Λαμβάνει τη ζώνη ώρας με το καθορισμένο αναγνωριστικό. |
| [TimeSpan](../timespan/) [get_BaseUtcOffset](./get_baseutcoffset/)() const | Επιστρέφει ένα στιγμιότυπο του [TimeSpan](../timespan/) που αντιπροσωπεύει ένα χρονικό διάστημα μεταξύ της τυπικής ώρας της τρέχουσας ζώνης ώρας και της ώρας UTC. |
| [String](../string/) [get_DaylightName](./get_daylightname/)() const | Λαμβάνει το όνομα για την θερινή ώρα της τρέχουσας ζώνης ώρας. |
| [String](../string/) [get_DisplayName](./get_displayname/)() const | Λαμβάνει το όνομα για την τρέχουσα ζώνη ώρας. |
| [String](../string/) [get_Id](./get_id/)() const | Επιστρέφει το αναγνωριστικό της ζώνης ώρας που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [get_Local](./get_local/)() | Επιστρέφει ένα στιγμιότυπο του [TimeZoneInfo](./) που αντιπροσωπεύει μια τοπική ζώνη ώρας. |
| [String](../string/) [get_StandardName](./get_standardname/)() const | Λαμβάνει το όνομα για την τυπική ώρα της τρέχουσας ζώνης ώρας. |
| **bool** [get_SupportsDaylightSavingTime](./get_supportsdaylightsavingtime/)() const | Λαμβάνει σημαία που υποδείχνει αν η ζώνη ώρας έχει κανόνες θερινής ώρας. |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [get_Utc](./get_utc/)() | Επιστρέφει ένα στιγμιότυπο του [TimeZoneInfo](./) που αντιπροσωπεύει μια ζώνη ώρας UTC. |
| [ArrayPtr](../arrayptr/)\<[AdjustmentRulePtr](./adjustmentruleptr/)\> [GetAdjustmentRules](./getadjustmentrules/)() const | Επιστρέφει έναν πίνακα που αποτελείται από αντικείμενα **AdjustmentRule** που αντιπροσωπεύουν τους κανόνες προσαρμογής που εφαρμόζονται στο τρέχον αντικείμενο [TimeZoneInfo](./). |
| [ArrayPtr](../arrayptr/)\<[TimeSpan](../timespan/)\> [GetAmbiguousTimeOffsets](./getambiguoustimeoffsets/)([DateTime](../datetime/)) const | Λαμβάνει τις ημερομηνίες και ώρες UTC στις οποίες μπορεί να αντιστοιχιστεί μια καθορισμένη ημερομηνία και ώρα. |
| [ArrayPtr](../arrayptr/)\<[TimeSpan](../timespan/)\> [GetAmbiguousTimeOffsets](./getambiguoustimeoffsets/)(const [DateTimeOffset](../datetimeoffset/)\&) const | Λαμβάνει τις ημερομηνίες και ώρες UTC στις οποίες μπορεί να αντιστοιχιστεί μια καθορισμένη ημερομηνία και ώρα. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφορών που συνδέεται με το αντικείμενο. |
| int [GetHashCode](./gethashcode/)() const override | Αναλογία της μεθόδου C# [Object.GetHashCode()](../object/gethashcode/). Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| static [SharedPtr](../sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<[TimeZoneInfoPtr](../timezoneinfoptr/)\>\> [GetSystemTimeZones](./getsystemtimezones/)() | Λαμβάνει ταξινομημένη συλλογή όλων των ζωνών ώρας που είναι διαθέσιμες στο τοπικό σύστημα. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../object/gettype/). |
| [TimeSpan](../timespan/) [GetUtcOffset](./getutcoffset/)([DateTime](../datetime/)) const | Υπολογίζει τη διαφορά μεταξύ της ώρας σε αυτή τη ζώνη ώρας και της ζώνης ώρας UTC για μια καθορισμένη ημερομηνία και ώρα. |
| [TimeSpan](../timespan/) [GetUtcOffset](./getutcoffset/)(const [DateTimeOffset](../datetimeoffset/)\&) const | Υπολογίζει τη διαφορά μεταξύ της ώρας σε αυτή τη ζώνη ώρας και της ζώνης ώρας UTC για μια καθορισμένη ημερομηνία και ώρα. |
| static [TimeSpan](../timespan/) [GetUtcOffsetFromUtc](./getutcoffsetfromutc/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | Εσωτερική βοηθητική συνάρτηση που επιστρέφει τη μετατόπιση UTC για ένα UTC-datetime σε καθορισμένη ζώνη ώρας. ΓΙΑ ΕΣΩΤΡΙΚΗ ΧΡΗΣΗ. |
| static [TimeSpan](../timespan/) [GetUtcOffsetFromUtc](./getutcoffsetfromutc/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&, **bool**\&, **bool**\&) | Εσωτερική βοηθητική συνάρτηση που επιστρέφει τη μετατόπιση UTC για ένα UTC-datetime σε καθορισμένη ζώνη ώρας. ΓΙΑ ΕΣΩΤΡΙΚΗ ΧΡΗΣΗ. |
| [TimeSpan](../timespan/) [GetUtcOffsetNoThrow](./getutcoffsetnothrow/)([DateTime](../datetime/)) const | Υπολογίζει τη διαφορά μεταξύ της ώρας σε αυτή τη ζώνη ώρας και της ζώνης ώρας UTC για μια καθορισμένη ημερομηνία και ώρα. ΓΙΑ ΕΣΩΤΡΙΚΗ ΧΡΗΣΗ. |
| **bool** [HasSameRules](./hassamerules/)(const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) const | Ελέγχει αν η τρέχουσα και άλλη ζώνη ώρας έχουν τους ίδιους κανόνες προσαρμογής. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια περίπτωση τύπου που περιγράφεται από το targetType. Αναλογία του τελεστή C# 'is'. |
| **bool** [IsAmbiguousTime](./isambiguoustime/)([DateTime](../datetime/)) const | Ελέγχει αν η καθορισμένη ημερομηνία και ώρα είναι ασαφής και μπορεί να αντιστοιχιστεί σε πολλές χρονικές στιγμές UTC. |
| **bool** [IsAmbiguousTime](./isambiguoustime/)(const [DateTimeOffset](../datetimeoffset/)\&) const | Ελέγχει αν η καθορισμένη ημερομηνία και ώρα είναι ασαφής και μπορεί να αντιστοιχιστεί σε πολλές χρονικές στιγμές UTC. |
| **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)([DateTime](../datetime/)) const | Ελέγχει αν η καθορισμένη ημερομηνία και ώρα εμπίπτει στη διάρκεια της θερινής ώρας. |
| **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)(const [DateTimeOffset](../datetimeoffset/)\&) const | Ελέγχει αν η καθορισμένη ημερομηνία και ώρα εμπίπτει στη διάρκεια της θερινής ώρας. |
| **bool** [IsDaylightSavingTimeNoThrow](./isdaylightsavingtimenothrow/)([DateTime](../datetime/)) const | Ελέγχει αν η καθορισμένη ημερομηνία και ώρα εμπίπτει στη διάρκεια της θερινής ώρας. |
| **bool** [IsInvalidTime](./isinvalidtime/)([DateTime](../datetime/)) const | Ελέγχει αν η καθορισμένη ημερομηνία και ώρα είναι άκυρη. |
| void [Lock](../object/lock/)() | Υλοποιεί το statement lock() της C#. Καλείται απευθείας ή χρησιμοποιεί το αντικείμενο φρουρού [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../object/memberwiseclone/). Επιτρέπει την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../object/object/)([Object](../object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει κάτι, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκατηγοριών. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει κάτι, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκατηγοριών. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../object/referenceequals/) για την περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../object/referenceequals/) για την περίπτωση strings. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Μειώνει τον διαμερίσσιμο μετρητή αναφορών κατά την καθορισμένη τιμή. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμο δείκτη (αντί για διαμερίσιμο). Επιτρέπει την αλλαγή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του διαμερίσσιμου μετρητή αναφορών. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Αυξάνει τον διαμερίσσιμο μετρητή αναφορών. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε smart pointers ή ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον διαμερίσσιμο μετρητή αναφορών. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε smart pointers ή ThisProtector. |
| [String](../string/) [ToString](./tostring/)() const override | Αναλογία της μεθόδου C# [Object.ToString()](../object/tostring/). Επιτρέπει τη μετατροπή προσαρμοσμένων αντικειμένων σε string. |
| static [DateTime](../datetime/) [TransitionTimeToDateTime](./transitiontimetodatetime/)(**int32_t**, const **TransitionTime**\&) | Βοηθητική συνάρτηση που μετατρέπει ένα έτος και **TransitionTime** σε ένα [DateTime](../datetime/). |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Υλοποιεί το construct typeof([System.Object](../object/)) της C#. |
| void [Unlock](../object/unlock/)() | Υλοποιεί το statement lock() της C# για ξεκλείδωμα. Καλείται απευθείας ή χρησιμοποιεί το αντικείμενο φρουρού [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Αυξάνει το αδύναμο μετρητή αναφορών. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε smart pointers ή ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Μειώνει το αδύναμο μετρητή αναφορών. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε smart pointers ή ThisProtector. |
| virtual  [~Object](../object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Typedefs

| Typedef | Περιγραφή |
| --- | --- |
| [AdjustmentRulePtr](./adjustmentruleptr/) | Ένα ψευδώνυμο για έναν διαμερίσσιμο δείκτη σε ένα στιγμιότυπο της κλάσης **AdjustmentRule**. |

## Δείτε επίσης

* Κλάση [IEquatable](../iequatable/)
* Χώρος ονομάτων [System](../)
* Library [Aspose.Slides](../../)