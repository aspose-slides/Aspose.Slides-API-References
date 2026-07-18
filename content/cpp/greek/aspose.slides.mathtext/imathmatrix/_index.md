---
title: IMathMatrix
second_title: Αναφορά API Aspose.Slides για C++
description: Καθορίζει το αντικείμενο Matrix, το οποίο αποτελείται από στοιχεία-παιδιά διατεταγμένα σε μία ή περισσότερες γραμμές και στήλες. Είναι σημαντικό να σημειωθεί ότι οι πίνακες δεν διαθέτουν ενσωματωμένα διαχωριστικά. Για να τοποθετήσετε τον πίνακα σε αγκύλες, θα πρέπει να χρησιμοποιήσετε το αντικείμενο διαχωριστικό (IMathDelimiter). Μπορούν να χρησιμοποιηθούν null επιχειρήματα για τη δημιουργία κενών στους πίνακες.
type: docs
weight: 391
url: /el/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix κλάση

Καθορίζει το αντικείμενο Matrix, το οποίο αποτελείται από στοιχεία-παιδιά διατεταγμένα σε μία ή περισσότερες γραμμές και στήλες. Σημειώνεται ότι οι πίνακες δεν έχουν ενσωματωμένα διαχωριστικά. Για να τοποθετήσετε τον πίνακα μέσα σε αγκύλες, θα πρέπει να χρησιμοποιήσετε το αντικείμενο διαχωριστικό ([IMathDelimiter](../imathdelimiter/)). Μπορούν να χρησιμοποιηθούν null παράμετροι για τη δημιουργία κενών στα matrices.

```cpp
class IMathMatrix : public virtual Aspose::Slides::MathText::IMathElement
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathAccent](../imathaccent/)\> [Accent](../imathelement/accent/)(char16_t) | Ορίζει ένα σημάδι τόνου (έναν χαρακτήρα στην κορυφή αυτού του στοιχείου) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Αποδέχεται τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([System::String](../../system/string/)) | Αποδέχεται τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfOneArgument](../mathfunctionsofoneargument/)) | Αποδέχεται τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Αποδέχεται τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα και επιπλέον καθορισμένο όρισμα |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::String](../../system/string/)) | Αποδέχεται τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα και επιπλέον καθορισμένο όρισμα |
| virtual void [DeleteColumn](./deletecolumn/)(**int32_t**) | Διαγράφει τη συγκεκριμένη στήλη |
| virtual void [DeleteRow](./deleterow/)(**int32_t**) | Διαγράφει τη συγκεκριμένη γραμμή |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::String](../../system/string/)) | Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathFractionTypes](../mathfractiontypes/)) | Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::String](../../system/string/), [MathFractionTypes](../mathfractiontypes/)) | Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../imathelement/enclose/)() | Τοποθετεί ένα μαθηματικό στοιχείο σε παρενθέσεις |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../imathelement/enclose/)(char16_t, char16_t) | Τοποθετεί αυτό το στοιχείο σε καθορισμένους χαρακτήρες, όπως παρενθέσεις ή άλλους χαρακτήρες ως πλαίσιο |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Προσομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Προσομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../imathelement/function/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Αποδέχεται μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτήν την παρουσία ως όνομα συνάρτησης |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../imathelement/function/)([System::String](../../system/string/)) | Αποδέχεται μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτήν την παρουσία ως όνομα συνάρτησης |
| virtual [MathVerticalAlignment](../mathverticalalignment/) [get_BaseJustification](./get_basejustification/)() | Καθορίζει την κάθετη στοίχιση σε σχέση με το περιβάλλον κείμενο. Οι δυνατές τιμές είναι πάνω, κάτω και κέντρο. Προεπιλογή: Κέντρο |
| virtual **int32_t** [get_ColumnCount](./get_columncount/)() | Αριθμός στηλών στο matrix |
| virtual **uint32_t** [get_ColumnGap](./get_columngap/)() | Η τιμή του οριζόντιου κενού μεταξύ των στηλών ενός matrix· αν το ColumnGapRule είναι 3 (\"Exactly\"), η μονάδα ερμηνεύεται ως twips (1/20 του σημείου). Αν το ColumnGapRule είναι 4 (\"Multiple\"), η μονάδα ερμηνεύεται ως αριθμός 0,5 em. Σε άλλες περιπτώσεις αγνοείται. Προεπιλογή: 0 |
| virtual [MathSpacingRules](../mathspacingrules/) [get_ColumnGapRule](./get_columngaprule/)() | Ο τύπος του οριζόντιου κενού μεταξύ των στηλών ενός matrix· οι μονάδες μπορούν να είναι em ή points (αποθηκευμένες ως twips). Προεπιλογή: SingleSpacingGap (0) |
| virtual **bool** [get_HidePlaceholders](./get_hideplaceholders/)() | Αποκρύπτει τα σύμβολα κράτησης για κενά στοιχεία του matrix. Προεπιλογή: false |
| virtual **uint32_t** [get_MinColumnWidth](./get_mincolumnwidth/)() | Ελάχιστο πλάτος στήλης σε twips (1/20 του σημείου). Το κενό (επίσης γνωστό ως „Column Gap“ ή „Gap Width“) προστίθεται στο MinColumnWidth για τον υπολογισμό του συνολικού Matrix [Column](../../aspose.slides/column/) Spacing (απόσταση μεταξύ των ίδιων άκρων διαφορετικών στηλών). Προεπιλογή: 0. |
| virtual **int32_t** [get_RowCount](./get_rowcount/)() | Αριθμός γραμμών στο matrix |
| virtual **uint32_t** [get_RowGap](./get_rowgap/)() | Η τιμή του κάθετου κενού μεταξύ των γραμμών ενός matrix· αν το RowGapRule είναι 3 (\"Exactly\"), η μονάδα ερμηνεύεται ως twips (1/20 του σημείου). Αν το RowGapRule είναι 4 (\"Multiple\"), η μονάδα ερμηνεύεται ως half-lines. Προεπιλογή: 0 |
| virtual [MathSpacingRules](../mathspacingrules/) [get_RowGapRule](./get_rowgaprule/)() | Ο τύπος του κάθετου κενού μεταξύ των γραμμών ενός matrix· οι μονάδες μπορούν να είναι lines ή points (αποθηκευμένες ως twips). Προεπιλογή: SingleSpacingGap (0) |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>\> [GetChildren](../imathelement/getchildren/)() | Λαμβάνει τα στοιχεία-παιδιά |
| virtual [MathHorizontalAlignment](../mathhorizontalalignment/) [GetColumnAlignment](./getcolumnalignment/)(**int32_t**) | Λαμβάνει την οριζόντια στοίχιση της συγκεκριμένης στήλης |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογική μέθοδος του C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία κατακερματισμού για προσαρμοσμένα αντικείμενα. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογική κλήση C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../imathelement/group/)() | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας μια αγκύλη-πλήκτρο στο κάτω μέρος |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../imathelement/group/)(char16_t, [MathTopBotPositions](../mathtopbotpositions/), [MathTopBotPositions](../mathtopbotpositions/)) | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας ένα χαρακτήρα ομαδοποίησης όπως η αγκύλη-πλήκτρο στο κάτω μέρος ή άλλος |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\> [idx_get](./idx_get/)(**int32_t**, **int32_t**) | Στοιχεία του matrix |
| virtual void [idx_set](./idx_set/)(**int32_t**, **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Στοιχεία του matrix |
| virtual void [InsertColumnAfter](./insertcolumnafter/)(**int32_t**) | Εισάγει μια νέα στήλη μετά από την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα στήλη είναι null. |
| virtual void [InsertColumnBefore](./insertcolumnbefore/)(**int32_t**) | Εισάγει μια νέα στήλη πριν από την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα στήλη είναι null. |
| virtual void [InsertRowAfter](./insertrowafter/)(**int32_t**) | Εισάγει μια νέα γραμμή μετά από την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα γραμμή είναι null. |
| virtual void [InsertRowBefore](./insertrowbefore/)(**int32_t**) | Εισάγει μια νέα γραμμή πριν από την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα γραμμή είναι null. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathLimitLocations](../mathlimitlocations/)) | Αποδέχεται το ολοκλήρωμα |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Αποδέχεται το ολοκλήρωμα |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/)) | Αποδέχεται το ολοκλήρωμα χωρίς όρια |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/), [MathLimitLocations](../mathlimitlocations/)) | Αποδέχεται το ολοκλήρωμα |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/)) | Αποδέχεται το ολοκλήρωμα |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια περίπτωση περιγραφόμενη από targetType. Αναλογική του C# ‘is’ τελεστή. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../imathelement/join/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Συνενώνει ένα μαθηματικό στοιχείο και σχηματίζει ένα μαθηματικό μπλοκ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../imathelement/join/)([System::String](../../system/string/)) | Συνενώνει ένα μαθηματικό κείμενο και σχηματίζει ένα μαθηματικό μπλοκ |
| void [Lock](../../system/object/lock/)() | Εφαρμόζει την εντολή lock() του C#. Καλείται απευθείας ή με χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογική μέθοδος του C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί το κλωνοποίηση προσαρμοσμένων τύπων. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../imathelement/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Δημιουργεί έναν N-αριακό τελεστή |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../imathelement/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::String](../../system/string/), [System::String](../../system/string/)) | Δημιουργεί έναν N-αριακό τελεστή |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία αντιγράφων υποκατηγοριών. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία αντιγράφων υποκατηγοριών. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Overbar](../imathelement/overbar/)() | Τοποθετεί μια μπάρα στην κορυφή αυτού του στοιχείου |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../imathelement/radical/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Καθορίζει τη μαθηματική ρίζα του δοσμένου βαθμού από το καθορισμένο όρισμα. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../imathelement/radical/)([System::String](../../system/string/)) | Καθορίζει τη μαθηματική ρίζα του δοσμένου βαθμού από το καθορισμένο όρισμα. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αναφορά τιμής αντικειμένου με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφορών κατά την καθορισμένη τιμή. |
| virtual void [set_BaseJustification](./set_basejustification/)([MathVerticalAlignment](../mathverticalalignment/)) | Καθορίζει την κάθετη στοίχιση σε σχέση με το περιβάλλον κείμενο. Οι δυνατές τιμές είναι πάνω, κάτω και κέντρο. Προεπιλογή: Κέντρο |
| virtual void [set_ColumnGap](./set_columngap/)(**uint32_t**) | Η τιμή του οριζόντιου κενού μεταξύ των στηλών ενός matrix· αν το ColumnGapRule είναι 3 (\"Exactly\"), η μονάδα ερμηνεύεται ως twips (1/20 του σημείου). Αν το ColumnGapRule είναι 4 (\"Multiple\"), η μονάδα ερμηνεύεται ως αριθμός 0,5 em. Σε άλλες περιπτώσεις αγνοείται. Προεπιλογή: 0 |
| virtual void [set_ColumnGapRule](./set_columngaprule/)([MathSpacingRules](../mathspacingrules/)) | Ο τύπος του οριζόντιου κενού μεταξύ των στηλών ενός matrix· οι μονάδες μπορούν να είναι em ή points (αποθηκευμένες ως twips). Προεπιλογή: SingleSpacingGap (0) |
| virtual void [set_HidePlaceholders](./set_hideplaceholders/)(**bool**) | Αποκρύπτει τα σύμβολα κράτησης για κενά στοιχεία του matrix. Προεπιλογή: false |
| virtual void [set_MinColumnWidth](./set_mincolumnwidth/)(**uint32_t**) | Ελάχιστο πλάτος στήλης σε twips (1/20 του σημείου). Το κενό (επίσης γνωστό ως „Column Gap“ ή „Gap Width“) προστίθεται στο MinColumnWidth για τον υπολογισμό του συνολικού Matrix [Column](../../aspose.slides/column/) Spacing (απόσταση μεταξύ των ίδιων άκρων διαφορετικών στηλών). Προεπιλογή: 0. |
| virtual void [set_RowGap](./set_rowgap/)(**uint32_t**) | Η τιμή του κάθετου κενού μεταξύ των γραμμών ενός matrix· αν το RowGapRule είναι 3 (\"Exactly\"), η μονάδα ερμηνεύεται ως twips (1/20 του σημείου). Αν το RowGapRule είναι 4 (\"Multiple\"), η μονάδα ερμηνεύεται ως half-lines. Προεπιλογή: 0 |
| virtual void [set_RowGapRule](./set_rowgaprule/)([MathSpacingRules](../mathspacingrules/)) | Ο τύπος του κάθετου κενού μεταξύ των γραμμών ενός matrix· οι μονάδες μπορούν να είναι lines ή points (αποθηκευμένες ως twips). Προεπιλογή: SingleSpacingGap (0) |
| virtual void [SetColumnAlignment](./setcolumnalignment/)(**int32_t**, [MathHorizontalAlignment](../mathhorizontalalignment/)) | Ορίζει την οριζόντια στοίχιση της συγκεκριμένης στήλης |
| virtual void [SetColumnsAlignment](./setcolumnsalignment/)(**int32_t**, **uint32_t**, [MathHorizontalAlignment](../mathhorizontalalignment/)) | Ορίζει την οριζόντια στοίχιση των συγκεκριμένων στηλών |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../imathelement/setlowerlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Αποδέχεται το κάτω όριο |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../imathelement/setlowerlimit/)([System::String](../../system/string/)) | Αποδέχεται το κάτω όριο |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../imathelement/setsubscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Δημιουργεί υπόστροφο |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../imathelement/setsubscript/)([System::String](../../system/string/)) | Δημιουργεί υπόστροφο |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../imathelement/setsubsuperscriptontheleft/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Δημιουργεί υπόστροφο και εκθέτη αριστερά |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../imathelement/setsubsuperscriptontheleft/)([System::String](../../system/string/), [System::String](../../system/string/)) | Δημιουργεί υπόστροφο και εκθέτη αριστερά |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../imathelement/setsubsuperscriptontheright/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Δημιουργεί υπόστροφο και εκθέτη δεξιά |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../imathelement/setsubsuperscriptontheright/)([System::String](../../system/string/), [System::String](../../system/string/)) | Δημιουργεί υπόστροφο και εκθέτη δεξιά |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../imathelement/setsuperscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Δημιουργεί εκθέτη |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../imathelement/setsuperscript/)([System::String](../../system/string/)) | Δημιουργεί εκθέτη |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα προτύπου ως αδύνατο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε δομές σε αδύναμη λειτουργία. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../imathelement/setupperlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Αποδέχεται το άνω όριο |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../imathelement/setupperlimit/)([System::String](../../system/string/)) | Αποδέχεται το άνω όριο |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../imathelement/toborderbox/)() | Τοποθετεί αυτό το στοιχείο σε border-box |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../imathelement/toborderbox/)(**bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**) | Τοποθετεί αυτό το στοιχείο σε border-box |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBox](../imathbox/)\> [ToBox](../imathelement/tobox/)() | Τοποθετεί αυτό το στοιχείο σε μη-οπτικό κουτί (λογική ομαδοποίηση) που χρησιμοποιείται για ομαδοποίηση στοιχείων μιας εξίσωσης ή άλλης παρουσίασης μαθηματικού κειμένου. Ένα κουτί μπορεί (για παράδειγμα) να λειτουργήσει ως εξομοιωτής τελεστή με ή χωρίς σημείο στοίχισης, να χρησιμεύσει ως σημείο αλλαγής γραμμής, ή να ομαδοποιηθεί ώστε να μην επιτρέπει αλλαγές γραμμής εντός. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathArray](../imatharray/)\> [ToMathArray](../imathelement/tomatharray/)() | Τοποθετεί σε κατακόρυφη σειρά |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογική μέθοδος του C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί τη δομή typeof([System.Object](../../system/object/)) του C#. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Underbar](../imathelement/underbar/)() | Τοποθετεί μια μπάρα στο κάτω μέρος αυτού του στοιχείου |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την εντολή lock() του C# για ξεκλείδωμα. Καλείται απευθείας ή με χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύνατο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύνατο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Παρατηρήσεις

Παράδειγμα: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## Δείτε επίσης

* Κλάση [IMathElement](../imathelement/)
* Χώρος ονομάτων [Aspose::Slides::MathText](../)
* Βιβλιοθήκη [Aspose.Slides](../../)