---
title: Array
second_title: Aspose.Slides για την Αναφορά API C++
description: "Κλάση που αντιπροσωπεύει μια δομή δεδομένων πίνακα. Τα αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τις συναρτήσεις System::MakeArray() και System::MakeObject(). Ποτέ μην δημιουργείτε στιγμιότυπο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας operator new, καθώς θα προκύψουν σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη System::SmartPtr και χρησιμοποιήστε αυτόν τον δείκτη για να τη περάσετε σε συναρτήσεις ως όρισμα."
type: docs
weight: 14
url: /el/system/array/
---
## Array κλάση

Κλάση που αντιπροσωπεύει μια δομή δεδομένων πίνακα. Αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τις συναρτήσεις [System::MakeArray()](../makearray/) και [System::MakeObject()](../makeobject/). Ποτέ μην δημιουργείτε στιγμιότυπο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκύψουν σφάλματα κατά την εκτέλεση και/ή σφάλματα ελέγχου. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη [System::SmartPtr](../smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για να τη περάσετε σε συναρτήσεις ως όρισμα.

```cpp
template<typename T>class Array : public System::ArrayBase,
                                  public System::Collections::Generic::IList<T>
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος των στοιχείων ενός πίνακα |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| void [Add](./add/)(const T\&) override | Δεν υποστηρίζεται επειδή ο πίνακας που αντιπροσωπεύεται από το τρέχον αντικείμενο είναι μόνο για ανάγνωση. |
|  [Array](./array/)() | Δημιουργεί έναν κενό πίνακα. |
|  [Array](./array/)(int, const T\&) | Κατασκευαστής πλήρωσης. |
|  [Array](./array/)(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<[ValueType](./valuetype/)\>::value\&&std::is_convertible\<[ValueType](./valuetype/), T\>::value, int\>::type, [ValueType](./valuetype/)) | Κατασκευαστής πλήρωσης. |
|  [Array](./array/)(int, const T) | Κατασκευαστής πλήρωσης. |
|  [Array](./array/)(**vector_t**\&&) | Κατασκευαστής μεταφοράς. |
|  [Array](./array/)(const **vector_t**\&) | Κατασκευαστής αντιγραφής. |
|  [Array](./array/)(const std::vector\<Q\>\&) | Δημιουργεί ένα αντικείμενο [Array](./) και το γεμίζει με τιμές που αντιγράφονται από ένα αντικείμενο std::vector του οποίου ο τύπος των τιμών είναι ο ίδιος με **T** αλλά διαφορετικός από **UnderlyingType**. |
|  [Array](./array/)(std::vector\<Q\>\&&) | Δημιουργεί ένα αντικείμενο [Array](./) και το γεμίζει με τιμές που μετακινούνται από ένα αντικείμενο std::vector του οποίου ο τύπος των τιμών είναι ο ίδιος με **T** αλλά διαφορετικός από **UnderlyingType**. |
|  [Array](./array/)(std::initializer_list\<[UnderlyingType](./underlyingtype/)\>) | Δημιουργεί ένα αντικείμενο [Array](./) και το γεμίζει με τιμές από τη συγκεκριμένη λίστα αρχικοποίησης που περιέχει στοιχεία τύπου **UnderlyingType**. |
|  [Array](./array/)(const std::array\<[UnderlyingType](./underlyingtype/), InitArraySize\>\&) | Δημιουργεί ένα αντικείμενο [Array](./) και το γεμίζει με τιμές από το συγκεκριμένο πίνακα που περιέχει στοιχεία τύπου **UnderlyingType**. |
|  [Array](./array/)(std::initializer_list\<**bool**\>, int) | Δημιουργεί ένα αντικείμενο [Array](./) και το γεμίζει με τιμές από τη συγκεκριμένη λίστα αρχικοποίησης που περιέχει στοιχεία τύπου bool. |
| static [SharedPtr](../sharedptr/)\<[Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](./asreadonly/)(const [SharedPtr](../sharedptr/)\<[Array](./)\<T\>\>\&) | Μετατρέπει τον πίνακα σε συλλογή μόνο για ανάγνωση. |
| [iterator](./iterator/) [begin](./begin/)() | Επιστρέφει έναν επαναληπτή προς το πρώτο στοιχείο του container. Εάν το container είναι κενό, ο επιστρεφόμενος επαναληπτής θα είναι ίσος με [end()](./end/). |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | Επιστρέφει έναν επαναληπτή προς το πρώτο στοιχείο του container με const. Εάν το container είναι κενό, ο επιστρεφόμενος επαναληπτής θα είναι ίσος με [end()](./end/). |
| static int [BinarySearch](./binarysearch/)([System::ArrayPtr](../arrayptr/)\<T\>, const T\&) | Πραγματοποιεί δυαδική αναζήτηση στον ταξινομημένο πίνακα. |
| static int [BinarySearch](./binarysearch/)([System::ArrayPtr](../arrayptr/)\<T\>, const Y\&, const [SharedPtr](../sharedptr/)\<[Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<Z\>\>\&) | ΔΕΝ ΥΛΟΠΟΙΕΙΤΑΙ. |
| [const_iterator](./const_iterator/) [cbegin](./cbegin/)() const | Επιστρέφει έναν επαναληπτή προς το πρώτο στοιχείο του container με const. Εάν το container είναι κενό, ο επιστρεφόμενος επαναληπτής θα είναι ίσος με [cend()](./cend/). |
| [const_iterator](./const_iterator/) [cend](./cend/)() const | Επιστρέφει έναν επαναληπτή προς το στοιχείο που ακολουθεί το τελευταίο στοιχείο του container. Αυτό το στοιχείο λειτουργεί ως θέση κράτησης· η προσπάθεια πρόσβασης σε αυτό οδηγεί σε απροσδιόριστη συμπεριφορά. |
| void [Clear](./clear/)() override | Δεν υποστηρίζεται επειδή ο πίνακας που αντιπροσωπεύεται από το τρέχον αντικείμενο είναι μόνο για ανάγνωση. |
| static void [Clear](./clear/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | Αντικαθιστά **count** τιμές που ξεκινούν από το ευρετήριο **startIndex** στον καθορισμένο πίνακα με προεπιλεγμένες τιμές. |
| [ArrayPtr](../arrayptr/)\<T\> [Clone](./clone/)() | Κλωνοποιεί τον πίνακα. |
| static void [ConstrainedCopy](./constrainedcopy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Αντιγράφει μια περιοχή στοιχείων από ένα [System.Array](./) ξεκινώντας από την καθορισμένη πηγή. |
| **bool** [Contains](./contains/)(const T\&) const override | Καθορίζει εάν το καθορισμένο στοιχείο βρίσκεται στον πίνακα. |
| static [ArrayPtr](../arrayptr/)\<OutputType\> [ConvertAll](./convertall/)([ArrayPtr](../arrayptr/)\<InputType\>, [Converter](../converter/)\<InputType, OutputType\>) | Δημιουργεί ένα νέο αντικείμενο [Array](./) και το γεμίζει με στοιχεία του καθορισμένου πίνακα που μετατρέπονται σε τύπο **OutputType** χρησιμοποιώντας τον καθορισμένο μετατροπέα delegate. |
| static [ArrayPtr](../arrayptr/)\<OutputType\> [ConvertAll](./convertall/)([ArrayPtr](../arrayptr/)\<InputType\>, std::function\<OutputType(InputType)>) | Δημιουργεί ένα νέο αντικείμενο [Array](./) και το γεμίζει με στοιχεία του καθορισμένου πίνακα που μετατρέπονται σε τύπο **OutputType** χρησιμοποιώντας τον καθορισμένο μετατροπέα function object. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | Αντιγράφει τον καθορισμένο αριθμό στοιχείων από τον πηγαίο πίνακα στον προορισμό. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | Αντιγράφει τον καθορισμένο αριθμό στοιχείων από την προβολή πηγαίου πίνακα στον προορισμό. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, System::Details::ArrayView\<DstType\>, **int64_t**) | Αντιγράφει τον καθορισμένο αριθμό στοιχείων από τον πηγαίο πίνακα στην προβολή προορισμού. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, **int64_t**) | Αντιγράφει τον καθορισμένο αριθμό στοιχείων από την προβολή πηγαίου πίνακα στην προβολή προορισμού. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | Αντιγράφει τον καθορισμένο αριθμό στοιχείων από τον πηγαίο πίνακα στη στοίβα στον προορισμό. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, **int64_t**) | Αντιγράφει τον καθορισμένο αριθμό στοιχείων από τον πηγαίο πίνακα στον προορισμό στη στοίβα. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, **int64_t**) | Αντιγράφει τον καθορισμένο αριθμό στοιχείων από τον πηγαίο πίνακα στη στοίβα στον προορισμό στη στοίβα. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Αντιγράφει έναν καθορισμένο αριθμό στοιχείων από τον πηγαίο πίνακα που αρχίζει από το καθορισμένο ευρετήριο στη θέση που καθορίζεται στον προορισμό. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Αντιγράφει έναν καθορισμένο αριθμό στοιχείων από την προβολή πηγαίου πίνακα που αρχίζει από το καθορισμένο ευρετήριο στη θέση που καθορίζεται στον προορισμό. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, System::Details::ArrayView\<DstType\>, **int64_t**, **int64_t**) | Αντιγράφει έναν καθορισμένο αριθμό στοιχείων από τον πηγαίο πίνακα που αρχίζει από το καθορισμένο ευρετήριο στη θέση που καθορίζεται στην προβολή προορισμού. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, **int64_t**, System::Details::ArrayView\<DstType\>, **int64_t**, **int64_t**) | Αντιγράφει έναν καθορισμένο αριθμό στοιχείων από την προβολή πηγαίου πίνακα που αρχίζει από το καθορισμένο ευρετήριο στη θέση που καθορίζεται στην προβολή προορισμού. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Αντιγράφει έναν καθορισμένο αριθμό στοιχείων από τον πηγαίο πίνακα στη στοίβα που αρχίζει από το καθορισμένο ευρετήριο στη θέση που καθορίζεται στον προορισμό. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, System::Details::StackArray\<DstType, N\>\&, **int64_t**, **int64_t**) | Αντιγράφει έναν καθορισμένο αριθμό στοιχείων από τον πηγαίο πίνακα που αρχίζει από το καθορισμένο ευρετήριο στη θέση που καθορίζεται στον προορισμό στη στοίβα. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, **int64_t**, System::Details::StackArray\<DstType, ND\>\&, **int64_t**, **int64_t**) | Αντιγράφει έναν καθορισμένο αριθμό στοιχείων από τον πηγαίο πίνακα στη στοίβα που αρχίζει από το καθορισμένο ευρετήριο στη θέση που καθορίζεται στον προορισμό στη στοίβα. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>\&, **int64_t**, System::Details::StackArray\<DstType, ND\>\&, **int64_t**, **int64_t**) | Αντιγράφει έναν καθορισμένο αριθμό στοιχείων από την προβολή πηγαίου πίνακα που αρχίζει από το καθορισμένο ευρετήριο στη θέση που καθορίζεται στον προορισμό στη στοίβα. |
| void [CopyTo](./copyto/)([ArrayPtr](../arrayptr/)\<T\>, int) override | Αντιγράφει όλα τα στοιχεία του τρέχοντος πίνακα στον καθορισμένο πίνακα προορισμού. Τα στοιχεία εισάγονται στον προορισμό αρχίζοντας από το ευρετήριο που υποδεικνύεται από το όρισμα arrayIndex. |
| void [CopyTo](./copyto/)(const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) const | Αντιγράφει όλα τα στοιχεία του τρέχοντος πίνακα στον καθορισμένο πίνακα προορισμού. Τα στοιχεία εισάγονται στον προορισμό αρχίζοντας από το ευρετήριο που υποδεικνύεται από το όρισμα dstIndex. |
| void [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, **int64_t**) const | Αντιγράφει όλα τα στοιχεία του τρέχοντος πίνακα στην καθορισμένη προβολή προορισμού. Τα στοιχεία εισάγονται στην προβολή προορισμού αρχίζοντας από το ευρετήριο που υποδεικνύεται από το όρισμα dstIndex. |
| void [CopyTo](./copyto/)(const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**, **int64_t**) const | Αντιγράφει έναν καθορισμένο αριθμό στοιχείων από τον τρέχοντα πίνακα που αρχίζει από τη συγκεκριμένη θέση στον καθορισμένο πίνακα προορισμού. Τα στοιχεία εισάγονται στον προορισμό αρχίζοντας από το ευρετήριο που υποδεικνύεται από το όρισμα dstIndex. |
| void [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, **int64_t**, **int64_t**, **int64_t**) const | Αντιγράφει έναν καθορισμένο αριθμό στοιχείων από τον τρέχοντα πίνακα που αρχίζει από τη συγκεκριμένη θέση στην προβολή προορισμού. Τα στοιχεία εισάγονται στην προβολή προορισμού αρχίζοντας από το ευρετήριο που υποδεικνύεται από το όρισμα dstIndex. |
| int [Count](./count/)() const | Επιστρέφει έναν αριθμό που αντιπροσωπεύει το σύνολο των στοιχείων σε όλες τις διαστάσεις του πίνακα. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | Επιστρέφει έναν αντίστροφο επαναληπτή προς το πρώτο στοιχείο του αντιστροφού container. Αντιστοιχεί στο τελευταίο στοιχείο του μη αντιστροφικού container. Εάν το container είναι κενό, ο επαναληπτής είναι ίσος με [crend()](./crend/). |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | Επιστρέφει έναν αντίστροφο επαναληπτή προς το στοιχείο που ακολουθεί το τελευταίο στοιχείο του αντιστροφού container. Αντιστοιχεί στο στοιχείο που προηγείται του πρώτου στοιχείου του μη αντιστροφικού container. Αυτό το στοιχείο λειτουργεί ως θέση κράτησης· η προσπάθεια πρόσβασης σε αυτό οδηγεί σε απροσδιόριστη συμπεριφορά. |
| **vector_t**\& [data](./data/)() | Επιστρέφει μια αναφορά στη εσωτερική δομή δεδομένων που χρησιμοποιείται για την αποθήκευση των στοιχείων του πίνακα. |
| const **vector_t**\& [data](./data/)() const | Επιστρέφει μια σταθερή αναφορά στη εσωτερική δομή δεδομένων που χρησιμοποιείται για την αποθήκευση των στοιχείων του πίνακα. |
| vector_t::pointer [data_ptr](./data_ptr/)() | Επιστρέφει έναν ακατέργαστο δείκτη στην αρχή του buffer μνήμης όπου αποθηκεύονται τα στοιχεία του πίνακα. |
| const [UnderlyingType](./underlyingtype/) * [data_ptr](./data_ptr/)() const | Επιστρέφει έναν σταθερό ακατέργαστο δείκτη στην αρχή του buffer μνήμης όπου αποθηκεύονται τα στοιχεία του πίνακα. |
| [iterator](./iterator/) [end](./end/)() | Επιστρέφει έναν επαναληπτή προς το στοιχείο που ακολουθεί το τελευταίο στοιχείο του container. Αυτό το στοιχείο λειτουργεί ως θέση κράτησης· η προσπάθεια πρόσβασης σε αυτό οδηγεί σε απροσδιόριστη συμπεριφορά. |
| [const_iterator](./const_iterator/) [end](./end/)() const | Επιστρέφει έναν επαναληπτή προς το στοιχείο που ακολουθεί το τελευταίο στοιχείο του const-qualified container. Αυτό το στοιχείο λειτουργεί ως θέση κράτησης· η προσπάθεια πρόσβασης σε αυτό οδηγεί σε απροσδιόριστη συμπεριφορά. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία [Object.Equals](../object/equals/) της C#. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Εξακολουθεί τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, ούτε και με NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Εξακολουθεί τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, ούτε και με NaN. |
| static **bool** [Exists](./exists/)([ArrayPtr](../arrayptr/)\<T\>, std::function\<**bool**(T)>) | Καθορίζει εάν το καθορισμένο αντικείμενο [Array](./) περιέχει στοιχείο που ικανοποιεί τις απαιτήσεις του καθορισμένου προγνωστικού. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| static T [Find](./find/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Αναζητά το πρώτο στοιχείο στον καθορισμένο πίνακα που ικανοποιεί τις συνθήκες του καθορισμένου προγνωστικού. |
| static [System::ArrayPtr](../arrayptr/)\<T\> [FindAll](./findall/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Επιστρέφει όλα τα στοιχεία που ταιριάζουν με τις συνθήκες που ορίζονται από το καθορισμένο προγνωστικό. |
| static int [FindIndex](./findindex/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Αναζητά το πρώτο στοιχείο στον καθορισμένο πίνακα που ικανοποιεί τις συνθήκες του καθορισμένου προγνωστικού. |
| static void [ForEach](./foreach/)(const [ArrayPtr](../arrayptr/)\<T\>\&, [System::Action](../action/)\<T\>) | Εκτελεί την καθορισμένη ενέργεια σε κάθε στοιχείο του καθορισμένου πίνακα. |
| int [get_Count](./get_count/)() const override | Επιστρέφει το μέγεθος του πίνακα. |
| **bool** [get_IsFixedSize](../../system.collections.generic/ilist/get_isfixedsize/)() | Ελέγχει εάν η συλλογή έχει σταθερό μέγεθος. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const override | Δείχνει εάν ο πίνακας είναι μόνο για ανάγνωση. |
| **int32_t** [get_Length](./get_length/)() const override | Επιστρέφει έναν 32-bit ακέραιο που αντιπροσωπεύει το σύνολο των στοιχείων σε όλες τις διαστάσεις του πίνακα. |
| **int64_t** [get_LongLength](./get_longlength/)() const | Επιστρέφει έναν 64-bit ακέραιο που αντιπροσωπεύει το σύνολο των στοιχείων σε όλες τις διαστάσεις του πίνακα. |
| **int32_t** [get_Rank](./get_rank/)() const | ΔΕΝ ΥΛΟΠΟΙΕΙΤΑΙ. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | Παίρνει το αντικείμενο μέσω του οποίου συγχρονίζεται η συλλογή. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Παίρνει τη δομή δεδομένων του μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| [EnumeratorPtr](./enumeratorptr/) [GetEnumerator](./getenumerator/)() override | Επιστρέφει δείκτη σε αντικείμενο **Enumerator** που παρέχει διεπαφή IEnumerator στα στοιχεία του πίνακα που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Αντίστοιχο της μεθόδου [Object.GetHashCode()](../object/gethashcode/) της C#. Ενεργοποιεί τη δημιουργία κατακερματισμού προσαρμοσμένων αντικειμένων. |
| int [GetLength](./getlength/)(int) | Επιστρέφει τον αριθμό των στοιχείων στην καθορισμένη διάσταση. |
| **int64_t** [GetLongLength](./getlonglength/)(int) | Επιστρέφει τον αριθμό των στοιχείων στην καθορισμένη διάσταση ως 64-bit ακέραιο. |
| int [GetLowerBound](./getlowerbound/)(int) const | Επιστρέφει το κάτω όριο της καθορισμένης διάστασης. |
| size_t [GetSizeTLength](./getsizetlength/)() const | Επιστρέφει μια μεταβλητή std::size_t που αντιπροσωπεύει το σύνολο των στοιχείων σε όλες τις διαστάσεις του πίνακα. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Παίρνει τον πραγματικό τύπο του αντικειμένου. Αντίστοιχο του κλήσης [System.Object.GetType()](../object/gettype/) της C#. |
| int [GetUpperBound](./getupperbound/)(int) | Επιστρέφει το άνω όριο της καθορισμένης διάστασης. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)() | Κατασκευαστής προεπιλογής. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Κατασκευαστής αντιγραφής. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | Κατασκευαστής μεταφοράς. |
| T [idx_get](./idx_get/)(int) const override | Επιστρέφει το στοιχείο στο καθορισμένο ευρετήριο. |
| void [idx_set](./idx_set/)(int, T) override | Ορίζει την καθορισμένη τιμή ως στοιχείο του πίνακα στο καθορισμένο ευρετήριο. |
| int [IndexOf](./indexof/)(const T\&) const override | Καθορίζει το ευρετήριο της πρώτης εμφάνισης του καθορισμένου στοιχείου στον πίνακα. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&) | Καθορίζει το ευρετήριο της πρώτης εμφάνισης του καθορισμένου στοιχείου στον πίνακα. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int) | Καθορίζει το ευρετήριο της πρώτης εμφάνισης του καθορισμένου στοιχείου στον πίνακα ξεκινώντας από το καθορισμένο ευρετήριο. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int, int) | Καθορίζει το ευρετήριο της πρώτης εμφάνισης του καθορισμένου στοιχείου σε ένα εύρος στοιχείων του πίνακα που ορίζεται από το αρχικό ευρετήριο και τον αριθμό των στοιχείων στο εύρος. |
| [ArrayPtr](../arrayptr/)\<T\> [Init](./init/)(const T) | Γεμίζει τον πίνακα που αντιπροσωπεύεται από το τρέχον αντικείμενο με τις τιμές από τον καθορισμένο πίνακα. |
| void [Initialize](./initialize/)() | Γεμίζει τον πίνακα με αντικείμενα τύπου **T** που έχουν κατασκευαστεί με την προεπιλογή. |
| void [Insert](./insert/)(int, const T\&) override | Δεν υποστηρίζεται επειδή ο πίνακας που αντιπροσωπεύεται από το τρέχον αντικείμενο είναι μόνο για ανάγνωση. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αποτελεί παράδειγμα του τύπου που περιγράφεται από targetType. Αντίστοιχο του τελεστή C# `is`. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int, int) | Καθορίζει το ευρετήριο της τελευταίας εμφάνισης του καθορισμένου στοιχείου σε ένα εύρος στοιχείων του πίνακα που ορίζεται από το αρχικό ευρετήριο και τον αριθμό των στοιχείων στο εύρος. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int) | Καθορίζει το ευρετήριο της τελευταίας εμφάνισης του καθορισμένου στοιχείου στον πίνακα ξεκινώντας από το καθορισμένο ευρετήριο. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&) | Καθορίζει το ευρετήριο της τελευταίας εμφάνισης του καθορισμένου στοιχείου στον πίνακα. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../func/)\<T, T, T\>\&) | Εφαρμόζει συνάρτηση συγκροτήματος σε μια ακολουθία. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Καθορίζει εάν όλα τα στοιχεία μιας ακολουθίας ικανοποιούν μια συνθήκη. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Καθορίζει εάν μια ακολουθία περιέχει στοιχεία. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Καθορίζει εάν υπάρχει οποιοδήποτε στοιχείο στην ακολουθία ή εάν ικανοποιείται μια συνθήκη. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Μετατρέπει τα στοιχεία στον καθορισμένο τύπο. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | Συγκεντρώνει δύο ακολουθίες. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Καθορίζει εάν μια ακολουθία περιέχει την καθορισμένη τιμή. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Επιστρέφει τον αριθμό των στοιχείων στην ακολουθία (υπολογιζόμενο μέσω άμεσης μέτρησης). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../func/)\<T, **bool**\>\&) | Επιστρέφει τον αριθμό των στοιχείων στην ακολουθία που ικανοποιούν την καθορισμένη συνθήκη. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Επιστρέφει το στοιχείο σε καθορισμένο ευρετήριο σε μια ακολουθία. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Επιστρέφει το στοιχείο σε καθορισμένο ευρετήριο σε μια ακολουθία. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Επιστρέφει το πρώτο στοιχείο μιας ακολουθίας. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../func/)\<T, **bool**\>\&) | Επιστρέφει το πρώτο στοιχείο μιας ακολουθίας που ικανοποιεί την καθορισμένη συνθήκη. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Επιστρέφει το πρώτο στοιχείο μιας ακολουθίας ή μια προεπιλεγμένη τιμή αν η ακολουθία είναι κενή. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Επιστρέφει το πρώτο στοιχείο της ακολουθίας που ικανοποιεί μια συνθήκη ή μια προεπιλεγμένη τιμή αν δεν βρεθεί τέτοιο στοιχείο. |
| [System::SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<T, Key\>) | Ομαδοποιεί τα στοιχεία μιας ακολουθίας. |
| [System::SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<T, Key\>, [System::Func](../func/)\<T, Element\>) | Ομαδοποιεί τα στοιχεία μιας ακολουθίας. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<Source, Key\>) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<Source, Key\>, [System::Func](../func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Επιστρέφει το τελευταίο στοιχείο μιας ακολουθίας. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Επιστρέφει το τελευταίο στοιχείο μιας ακολουθίας ή μια προεπιλεγμένη τιμή αν η ακολουθία είναι κενή. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../func/)\<T, ResultType\>\&) | Κατασκευά εκτελεί μια λειτουργία μετασχηματισμού σε κάθε στοιχείο μιας γενικής ακολουθίας και επιστρέφει τη μέγιστη προκύπτουσα τιμή. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../func/)\<T, ResultType\>\&) | Κατασκευά εκτελεί μια λειτουργία μετασχηματισμού σε κάθε στοιχείο μιας γενικής ακολουθίας και επιστρέφει τη ελάχιστη προκύπτουσα τιμή. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | Φιλτράρει τα στοιχεία της ακολουθίας βάσει του καθορισμένου τύπου. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../func/)\<T, Key\>\&) | Ταξινομεί τα στοιχεία μιας ακολουθίας σε αύξουσα σειρά σύμφωνα με τις τιμές κλειδιού που επιλέγονται από το keySelector. |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../func/)\<Source, Key\>\&) |  |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../func/)\<T, Key\>\&) | Ταξινομεί τα στοιχεία μιας ακολουθίας σε φθίνουσα σειρά σύμφωνα με τις τιμές κλειδιού που επιλέγονται από το keySelector. |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../func/)\<Source, Key\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Αντιστρέφει τη σειρά των στοιχείων σε μια ακολουθία. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<T, ResultType\>\&) | Μετασχηματίζει τα στοιχεία μιας ακολουθίας. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<T, **int32_t**, ResultType\>\&) | Μετασχηματίζει κάθε στοιχείο μιας ακολουθίας σε νέα μορφή ενσωματώνοντας το ευρετήριο του στοιχείου. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<Source, Result\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../func/)\<T, [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | Προβάλλει κάθε στοιχείο μιας ακολουθίας και συνδυάζει τις προκύπτουσες ακολουθίες σε μία ακολουθία. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../func/)\<Source, [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Επιστρέφει έναν καθορισμένο αριθμό διαδοχικών στοιχείων από την αρχή μιας ακολουθίας. |
| [System::ArrayPtr](../arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Δημιουργεί έναν πίνακα από μια ακολουθία. |
| [SharedPtr](../sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Δημιουργεί μια List<T> από μια ακολουθία. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Φιλτράρει μια ακολουθία βάσει του καθορισμένου προγνωστικού. |
| void [Lock](../object/lock/)() | Υλοποιεί τη δήλωση C# lock() κλειδώνοντας. Κάλεσε απευθείας ή χρησιμοποίησε το αντικείμενο sentry [LockContext](../lockcontext/). |
| [UnderlyingType](./underlyingtype/) [Max](./max/)() const | Βρίσκει το μεγαλύτερο στοιχείο στον πίνακα χρησιμοποιώντας [operator<()](../operator_less/) για τη σύγκριση στοιχείων. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Αντίστοιχο της μεθόδου [Object.MemberwiseClone()](../object/memberwiseclone/) της C#. Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
| [UnderlyingType](./underlyingtype/) [Min](./min/)() const | Βρίσκει το μικρότερο στοιχείο στον πίνακα χρησιμοποιώντας [operator<()](../operator_less/) για τη σύγκριση στοιχείων. |
|  [Object](../object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../object/object/)([Object](../object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή σε υποκατηγορίες. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή σε υποκατηγορίες. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | Τελεστής ανάθεσης μετακίνησης. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Τελεστής ανάθεσης μετακίνησης. |
| [UnderlyingType](./underlyingtype/)\& [operator[]](./operator[]/)(int) | Επιστρέφει ένα στοιχείο στο καθορισμένο ευρετήριο. |
| [UnderlyingType](./underlyingtype/) const\& [operator[]](./operator[]/)(int) const | Επιστρέφει ένα στοιχείο στο καθορισμένο ευρετήριο. |
| void * [raw_data_ptr](./raw_data_ptr/)() override | Επιστρέφει δείκτη στο πρώτο στοιχείο ενός μονοδιάστατου πίνακα. Για πολυδιάστατους πίνακες το αποτέλεσμα είναι ακαθόριστο. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | Επιστρέφει έναν αντίστροφο επαναληπτή προς το πρώτο στοιχείο του αντιστροφού container. Αντιστοιχεί στο τελευταίο στοιχείο του μη αντιστροφικού container. Εάν το container είναι κενό, ο επαναληπτής είναι ίσος με [rend()](./rend/). |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | Επιστρέφει έναν αντίστροφο επαναληπτή προς το πρώτο στοιχείο του αντιστροφού container. Αντιστοιχεί στο τελευταίο στοιχείο του μη αντιστροφικού container. Εάν το container είναι κενό, ο επαναληπτής είναι ίσος με [rend()](./rend/). |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αντικείμενο τύπου τιμής με nullptr με αναφορά. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../object/referenceequals/) για περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../object/referenceequals/) για περίπτωση strings. |
| **bool** [Remove](./remove/)(const T\&) override | Δεν υποστηρίζεται επειδή ο πίνακας που αντιπροσωπεύεται από το τρέχον αντικείμενο είναι μόνο για ανάγνωση. |
| void [RemoveAt](./removeat/)(int) override | Δεν υποστηρίζεται επειδή ο πίνακας που αντιπροσωπεύεται από το τρέχον αντικείμενο είναι μόνο για ανάγνωση. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινών αναφορών κατά την καθορισμένη τιμή. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | Επιστρέφει έναν αντίστροφο επαναληπτή προς το στοιχείο που ακολουθεί το τελευταίο στοιχείο του αντιστροφού container. Αυτό το στοιχείο λειτουργεί ως θέση κράτησης· η προσπάθεια πρόσβασης σε αυτό οδηγεί σε απροσδιόριστη συμπεριφορά. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | Επιστρέφει έναν αντίστροφο επαναληπτή προς το στοιχείο που ακολουθεί το τελευταίο στοιχείο του αντιστροφού container. Αυτό το στοιχείο λειτουργεί ως θέση κράτησης· η προσπάθεια πρόσβασης σε αυτό οδηγεί σε απροσδιόριστη συμπεριφορά. |
| static void [Resize](./resize/)([ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int) | Αλλάζει το μέγεθος του καθορισμένου πίνακα στην καθορισμένη τιμή ή δημιουργεί νέο πίνακα με το καθορισμένο μέγεθος. |
| static void [Reverse](./reverse/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&) | Αντιστρέφει τα στοιχεία του καθορισμένου πίνακα. |
| static void [Reverse](./reverse/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | Αντιστρέφει ένα εύρος στοιχείων στον καθορισμένο πίνακα. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Καθορίζει ώστε ο πίνακας να αντιμετωπίζει αποθηκευμένους δείκτες ως αδύναμους (αν είναι εφαρμόσιμο). |
| void [SetValue](./setvalue/)(const T\&, int) | Ορίζει την τιμή του στοιχείου στο καθορισμένο ευρετήριο. |
| int [SharedCount](../object/sharedcount/)() const | Παίρνει την τρέχουσα τιμή του μετρητή κοινών αναφορών. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινών αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινών αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&) | Ταξινομεί τα στοιχεία του καθορισμένου πίνακα χρησιμοποιώντας την προεπιλεγμένη σύγκριση. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | Ταξινομεί ένα εύρος στοιχείων στο καθορισμένο πίνακα χρησιμοποιώντας την προεπιλεγμένη σύγκριση. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) | Ταξινομεί τα στοιχεία του καθορισμένου πίνακα χρησιμοποιώντας την καθορισμένη σύγκριση. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<Y\>\>\&) | ΔΕΝ ΥΛΟΠΟΙΕΙΤΑΙ. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [System::Comparison](../comparison/)\<T\>\&) | Ταξινομεί τα στοιχεία του καθορισμένου πίνακα χρησιμοποιώντας την καθορισμένη σύγκριση. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<TKey\>\&, const [ArrayPtr](../arrayptr/)\<TValue\>\&) | Ταξινομεί δύο πίνακες· ένας με κλειδιά και ο άλλος με τα αντίστοιχα στοιχεία, βάσει των τιμών του πίνακα κλειδιών, τα στοιχεία του οποίου συγκρίνονται με τον τελεστή <. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<TKey\>\&, const [ArrayPtr](../arrayptr/)\<TValue\>\&, int, int) | Ταξινομεί δύο πίνακες· ένας με κλειδιά και ο άλλος με τα αντίστοιχα στοιχεία, βάσει των τιμών του πίνακα κλειδιών, τα στοιχεία του οποίου συγκρίνονται με την προεπιλεγμένη σύγκριση. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Αντίστοιχο της μεθόδου [Object.ToString()](../object/tostring/) της C#. Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static **bool** [TrueForAll](./trueforall/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Καθορίζει εάν όλα τα στοιχεία στον καθορισμένο πίνακα ικανοποιούν τις συνθήκες του καθορισμένου προγνωστικού. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Υλοποιεί τη δήλωση C# lock() ξεκλειδίζοντας. Κάλεσε απευθείας ή χρησιμοποίησε το αντικείμενο sentry [LockContext](../lockcontext/). |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Παίρνει την υλοποίηση του begin const επαναληπτή για το τρέχον container. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Παίρνει την υλοποίηση του begin επαναληπτή για το τρέχον container. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Παίρνει την υλοποίηση του end const επαναληπτή για το τρέχον container. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | Παίρνει την υλοποίηση του end επαναληπτή για το τρέχον container. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | Καταστροφέας. |
| virtual  [~Object](../object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Typedefs

| Typedef | Περιγραφή |
| --- | --- |
| [ValueType](./valuetype/) | Alias για τον τύπο των στοιχείων του πίνακα. |
| [UnderlyingType](./underlyingtype/) | Alias για τον τύπο που χρησιμοποιείται για την αναπαράσταση κάθε στοιχείου του πίνακα. |
| [EnumerablePtr](./enumerableptr/) | Alias για τύπο shared pointer που δείχνει σε αντικείμενο IEnumerable που περιέχει στοιχεία τύπου **T**. |
| [EnumeratorPtr](./enumeratorptr/) | Alias για τύπο shared pointer που δείχνει σε αντικείμενο IEnumerator που περιέχει στοιχεία τύπου **T**. |
| [iterator](./iterator/) | Τύπος επαναληπτή. |
| [const_iterator](./const_iterator/) | Τύπος const επαναληπτή. |
| [reverse_iterator](./reverse_iterator/) | Τύπος αντίστροφου επαναληπτή. |
| [const_reverse_iterator](./const_reverse_iterator/) | Τύπος const αντίστροφου επαναληπτή. |

## Παρατηρήσεις

```cpp
#include <system/array.h>
#include <system/smart_ptr.h>

using namespace System;

void Print(const SmartPtr<Array<int32_t>> &arrayPtr)
{
  for (auto item: arrayPtr)
  {
    std::cout << item << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // Δημιουργία και γέμισμα του πίνακα.
  auto arrayPtr = MakeObject<Array<int32_t>>(5, 0);
  for (auto i = 0; i < arrayPtr->get_Length(); ++i)
  {
    arrayPtr[i] = 5 - i;
  }

  // Εκτύπωση στοιχείων του πίνακα.
  Print(arrayPtr);

  // Ταξινόμηση στοιχείων του πίνακα σε αύξουσα σειρά.
  Array<int32_t>::Sort(arrayPtr);

  // Εκτύπωση στοιχείων του πίνακα.
  Print(arrayPtr);

  // Εκτύπωση του αριθμού των στοιχείων του πίνακα.
  std::cout << arrayPtr->get_Length() << std::endl;

  // Εκτύπωση του δείκτη του στοιχείου που ισούται με 4.
  std::cout << arrayPtr->IndexOf(4) << std::endl;

  // Αλλαγή μεγέθους του πίνακα.
  Array<int32_t>::Resize(arrayPtr, 3);

  // Εκτύπωση στοιχείων του πίνακα.
  Print(arrayPtr);

  return 0;
}
/*
Αυτό το παράδειγμα κώδικα παράγει το ακόλουθο αποτέλεσμα:
5 4 3 2 1
1 2 3 4 5
5
3
1 2 3
*/
```

## Δείτε επίσης

* Class [ArrayBase](../arraybase/)
* Class [IList](../../system.collections.generic/ilist/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)