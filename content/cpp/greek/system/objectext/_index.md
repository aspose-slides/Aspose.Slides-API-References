---
title: ObjectExt
second_title: Αναφορά API Aspose.Slides για C++
description: Παρέχει στατικές μεθόδους που προσομοιώνουν τις μεθόδους Object της C# που καλούνται για μη-Object τύπους C++ (συμβολοσειρές, αριθμούς κ.α.). Πρόκειται για έναν στατικό τύπο χωρίς υπηρεσίες στιγμιότυπου. Δεν πρέπει ποτέ να δημιουργείτε στιγμιότυπα του με κανέναν τρόπο.
type: docs
weight: 1132
url: /el/system/objectext/
---
## ObjectExt κλάση

Παρέχει στατικές μεθόδους που προσομοιώνουν μεθόδους C# [Object](../object/) που καλούνται για μη-Object τύπους C++ (συμβολοσειρές, αριθμούς κ.λπ.). Αυτός είναι ένας στατικός τύπος χωρίς υπηρεσίες στιγμιοτύπου. Δεν πρέπει ποτέ να δημιουργήσετε στιγμιότυπα του με οποιονδήποτε τρόπο.

```cpp
class ObjectExt : public System::ObjectType
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| static std::enable_if<(std::is_fundamental\<To\>::value), std::array\<To, sizeof...(From)>\>::type [ArrayInitializerCast](./arrayinitializercast/)(From ...) | Μετατρέπει θεμελιώδεις τιμές array (που το C# κάνει αυτόματα αλλά το C++ προφανώς δεν κάνει). |
| static std::enable_if\<std::is_enum\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | Συσκευάζει τύπους τιμών για μετατροπή σε [Object](../object/). Υλοποίηση για τύπους enum. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | Συσκευάζει τύπους τιμών για μετατροπή σε [Object](../object/). Υλοποίηση για μη-enum τύπους. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | Συσκευάζει τύπους [Nullable](../nullable/) για μετατροπή σε [Object](../object/). |
| static [SmartPtr](../smartptr/)\<[Object](../object/)\> [Box](./box/)(const [String](../string/)\&) | Συσκευάζει τιμές συμβολοσειράς. |
| static [SmartPtr](../smartptr/)\<[System::BoxedValueBase](../boxedvaluebase/)\> [BoxEnum](./boxenum/)(T) | Συσκευάζει τύπους enum για να διαδοθούν ως [Object](../object/). |
| static [SmartPtr](../smartptr/)\<[System::Collections::IList](../../system.collections/ilist/)\> [CastToIList](./casttoilist/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) |  |
| static auto [Coalesce](./coalesce/)(T0, T1) | Υλοποίηση της μετάφρασης του τελεστή '??' για μη-μηδενικούς τύπους. |
| static T0 [Coalesce](./coalesce/)([System::Nullable](../nullable/)\<T0\>, T1) | Υλοποίηση της μετάφρασης του τελεστή '??' για τύπους με δυνατότητα null. |
| static auto [CoalesceAssign](./coalesceassign/)(T0\&, T1) | Υλοποίηση της μετάφρασης του τελεστή '??='. |
| static std::conditional\<std::is_convertible\<RT2, RT1\>::value, RT1, RT2\>::type [CoalesceInternal](./coalesceinternal/)(RT1, F) | Υλοποίηση της μετάφρασης του τελεστή '??' για μη-μηδενικούς τύπους. Υπερφόρτωση για την περίπτωση που το RT2 μπορεί να μετατραπεί σε RT1. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) |  |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) | Αντικατάσταση για κλήσεις C# [Object.Equals](../object/equals/) που λειτουργούν για οποιονδήποτε τύπο στο C++. Υπερφόρτωση για τύπους έξυπνων δεικτών. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value, **bool**\>::type [Equals](./equals/)(T, const T2\&) | Αντικατάσταση για κλήσεις C# [Object.Equals](../object/equals/) που λειτουργούν για οποιονδήποτε τύπο στο C++. Υπερφόρτωση για τύπους δομών. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) | Αντικατάσταση για κλήσεις C# [Object.Equals](../object/equals/) που λειτουργούν για οποιονδήποτε τύπο στο C++. Υπερφόρτωση για τύπους scalar. |
| static **bool** [Equals](./equals/)(const char_t(&), [String](../string/)) | Αντικατάσταση για κλήσεις C# [Object.Equals](../object/equals/) που λειτουργούν για οποιονδήποτε τύπο στο C++. Υπερφόρτωση για κυριολεκτικό συμβολοσειράς με σύγκριση συμβολοσειρών. |
| static **bool** [Equals](./equals/)(const **float**\&, const **float**\&) | Προσομοιώνει τη σύγκριση κινητής υποδιαστολής τύπου C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ισοδύναμο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](./equals/)(const **double**\&, const **double**\&) | Προσομοιώνει τη σύγκριση κινητής υποδιαστολής τύπου C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ισοδύναμο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value, [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>\>::type [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static std::enable_if\<[System::IsSmartPtr](../issmartptr/)\<T\>::value, [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>\>::type [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static int [GetHashCode](./gethashcode/)(const T\&) | Εκτελεί κλήσεις [GetHashCode()](./gethashcode/)· λειτουργεί τόσο σε υποκλάσεις [Object](../object/) όσο και σε μη σχετιζόμενους τύπους. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | Εκτελεί τη μετάφραση του typeof(). Υπερφόρτωση για έξυπνα δείκτες. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | Εκτελεί τη μετάφραση του typeof(). Υπερφόρτωση για δομές. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | Εκτελεί τη μετάφραση του typeof(). Υπερφόρτωση για εξαιρέσεις. |
| static std::enable_if\<std::is_fundamental\<T\>::value||std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T) | Εκτελεί τη μετάφραση του typeof(). Υπερφόρτωση για πρωτογενείς τύπους. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T) | Εκτελεί τη μετάφραση του typeof(). Υπερφόρτωση για τύπους [Nullable](../nullable/). |
| static std::enable_if\<std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Εκτελεί τη μετάφραση του typeof(). Υπερφόρτωση για πρωτογενείς τύπους. |
| static std::enable_if\<std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Εκτελεί τη μετάφραση του typeof(). Υπερφόρτωση για τύπους enum. |
| static std::enable_if<(\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsBoxable](../isboxable/)\<T\>::value)||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Εκτελεί τη μετάφραση του typeof(). Υπερφόρτωση για δομές και δείκτες. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Εκτελεί τη μετάφραση του typeof(). Υπερφόρτωση για [Nullable](../nullable/). |
| static std::enable_if\<detail::is_a\<T, MulticastDelegate\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Εκτελεί τη μετάφραση του typeof(). Υπερφόρτωση για MulticastDelegate. |
| static std::enable_if<\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&[IsBoxable](../isboxable/)\<T\>::value\&&\!detail::is_a\<T, MulticastDelegate\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Εκτελεί τη μετάφραση του typeof(). Υπερφόρτωση για δομές και δείκτες. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)(const [String](../string/)\&) | Εκτελεί τη μετάφραση του typeof(). Υπερφόρτωση για τύπο συμβολοσειράς. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Εκτελεί τη μετάφραση του typeof(). Υπερφόρτωση για **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Εκτελεί τη μετάφραση του typeof(). Υπερφόρτωση για **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Εκτελεί τη μετάφραση του typeof(). Υπερφόρτωση για **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Εκτελεί τη μετάφραση του typeof(). Υπερφόρτωση για **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Εκτελεί τη μετάφραση του typeof(). Υπερφόρτωση για **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Εκτελεί τη μετάφραση του typeof(). Υπερφόρτωση για **uint8_t**. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value, **bool**\>::type [Is](./is/)(const T\&) | Εκτελεί τη μετάφραση του τελεστή 'is'. Ειδικότερα για τύπους που μπορούν να τοποθετηθούν σε κουτί (τιμές) που είναι ακριβώς όπως είναι. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value\&&std::is_final\<T\>::value\&&\![System::IsBoxable](../isboxable/)\<T\>::value\&&[System::IsSmartPtr](../issmartptr/)\<U\>::value, **bool**\>::type [Is](./is/)(const U\&) | Εκτελεί τη μετάφραση του τελεστή 'is'. Ειδικότερα για τύπους δείκτες βελτιστοποιημένους για τελικές κλάσεις. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value\&&\!std::is_final\<T\>::value\&&\![System::IsBoxable](../isboxable/)\<T\>::value\&&[System::IsSmartPtr](../issmartptr/)\<U\>::value, **bool**\>::type [Is](./is/)(const U\&) | Εκτελεί τη μετάφραση του τελεστή 'is'. Ειδικότερα για τύπους δείκτες. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [Object](../object/)\&) | Εκτελεί τη μετάφραση του τελεστή 'is'. Ειδικότερα για τύπους τιμών. |
| static std::enable_if<\!std::is_convertible\<T, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [Object](../object/)\&) | Εκτελεί τη μετάφραση του τελεστή 'is'. Ειδικότερα για μη μετατρέψιμους τύπους. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<U\>\&) | Εκτελεί τη μετάφραση του τελεστή 'is'. Ειδικότερα για τύπους δείκτες. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, **bool**\>::type [Is](./is/)(const [ExceptionWrapper](../exceptionwrapper/)\<U\>\&) | Εκτελεί τη μετάφραση του τελεστή 'is'. Ειδικότερα για τύπους περιτύλιξης εξαιρέσεων. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Εκτελεί τη μετάφραση του τελεστή 'is'. Ειδικότερα για τύπους με δυνατότητα null. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&detail::has_operator_equal\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Εκτελεί τη μετάφραση του τελετή 'is'. Ειδικότερα για τύπους που μπορούν να τοποθετηθούν σε κουτί με ορισμένο τελεστή ==. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&\!detail::has_operator_equal\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Εκτελεί τη μετάφραση του τελετή 'is'. Ειδικότερα για τύπους που μπορούν να τοποθετηθούν σε κουτί χωρίς ορισμένο ==. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&\!std::is_same\<V, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<V\>\&) | Εκτελεί τη μετάφραση του τελεστή 'is'. Ειδικότερα για τύπους τιμών που τοποθετούνται σε κουτί προς διεπαφές. |
| static std::enable_if\<std::is_enum\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<U\>\&) | Εκτελεί τη μετάφραση του τελεστή 'is'. Ειδικότερα για τύπους enum. |
| static std::enable_if\<std::is_enum\<T\>::value, **bool**\>::type [Is](./is/)(const [WeakPtr](../weakptr/)\<U\>\&) | Εκτελεί τη μετάφραση του τελετή 'is'. Ειδικότερα για τύπους enum σε σχέση με αδύναμους δείκτες. |
| static **bool** [Is](./is/)(const [Nullable](../nullable/)\<U\>\&) | Εκτελεί τη μετάφραση του τελετή 'is'. Ειδικότερα για τύπο [Nullable](../nullable/). |
| static **bool** [Is](./is/)(const char16_t *) | Εκτελεί τη μετάφραση του τελετή 'is'. Ειδικότερα για κυριολεκτικό συμβολοσειράς. |
| static **bool** [Is](./is/)(**int32_t**) | Εκτελεί τη μετάφραση του τελετή 'is'. Ειδικότερα για κυριολεκτικό ακέραιου. |
| static **bool** [IsBoxedValue](./isboxedvalue/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Ελέγχει αν το αντικείμενο είναι μια τιμή σε κουτί. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, T\>::type [ObjectToUnknown](./objecttounknown/)([SmartPtr](../smartptr/)\<[Object](../object/)\>) | Μετατρέπει [Object](../object/) σε άγνωστο τύπο, χειριζόμενο τόσο τύπους έξυπνων δεικτών όσο και περιπτώσεις τιμών σε κουτί. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, T\>::type [ObjectToUnknown](./objecttounknown/)([SmartPtr](../smartptr/)\<[Object](../object/)\>) | Μετατρέπει [Object](../object/) σε άγνωστο τύπο, χειριζόμενο τόσο τύπους έξυπνων δεικτών όσο και κουβιέτ τιμών. |
| static [String](../string/) [ToString](./tostring/)(const char_t *) | Αντικατάσταση για τη μέθοδο C# ToString ώστε να λειτουργεί σε οποιονδήποτε τύπο C++. |
| static [String](../string/) [ToString](./tostring/)(const [Nullable](../nullable/)\<T\>\&) | Αντικατάσταση για τη μέθοδο C# ToString ώστε να λειτουργεί σε οποιονδήποτε τύπο C++. |
| static std::enable_if\<std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | Αντικατάσταση για τη μέθοδο C# ToString ώστε να λειτουργεί σε οποιονδήποτε τύπο C++. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | Αντικατάσταση για τη μέθοδο C# ToString ώστε να λειτουργεί σε οποιονδήποτε τύπο C++. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value||std::is_pointer\<T\>::value||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | Αντικατάσταση για τη μέθοδο C# ToString ώστε να λειτουργεί σε οποιονδήποτε τύπο C++. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value\&&\!std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | Αντικατάσταση για τη μέθοδο C# ToString ώστε να λειτουργεί σε οποιονδήποτε τύπο C++. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value\&&\!std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&&) | Αντικατάσταση για τη μέθοδο C# ToString ώστε να λειτουργεί σε οποιονδήποτε τύπο C++. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | Αντικατάσταση για τη μέθοδο C# ToString ώστε να λειτουργεί σε οποιονδήποτε τύπο C++. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | Αντικατάσταση για τη μέθοδο C# ToString ώστε να λειτουργεί σε οποιονδήποτε τύπο C++. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_reference\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&&) | Αντικατάσταση για τη μέθοδο C# ToString ώστε να λειτουργεί σε οποιονδήποτε τύπο C++. |
| static std::enable_if\<std::is_enum\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Αποσυσκευάζει τύπους τιμών μετά τη μετατροπή σε [Object](../object/). Υλοποίηση για τύπους enum. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&detail::has_operator_equal\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Αποσυσκευάζει τύπους τιμών μετά τη μετατροπή σε [Object](../object/). Υλοποίηση για μη-enum και μη-μηδενικούς τύπους. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&\!detail::has_operator_equal\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Αποσυσκευάζει τύπους τιμών μετά τη μετατροπή σε [Object](../object/). Υλοποίηση για μη-enum και μη-μηδενικούς τύπους. |
| static std::enable_if\<std::is_enum\<E\>::value\&&std::numeric_limits\<T\>::is_integer, T\>::type [Unbox](./unbox/)(E) | Αποσυσκευάζει τύπους enum σε ακέραιο. |
| static std::enable_if\<std::is_enum\<E\>::value\&&std::is_enum\<T\>::value, T\>::type [Unbox](./unbox/)(E) | Μετατρέπει τύπους enum. |
| static [String](../string/) [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Αποσυσκευάζει τιμές συμβολοσειράς. |
| static [String](../string/) [UnboxStringSafe](./unboxstringsafe/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Αποσυσκευάζει συμβολοσειρά από την τιμή σε κουτί. |
| static [Nullable](../nullable/)\<T\> [UnboxToNullable](./unboxtonullable/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&, **bool**) | Αποσυσκευάζει αντικείμενο σε τύπο με δυνατότητα null. |
| static std::enable_if<\!std::is_scalar\<T\>::value, **bool**\>::type [UnknownIsNull](./unknownisnull/)(T) | Ελέγχει αν αντικείμενο άγνωστου τύπου είναι nullptr. Υπερφόρτωση για μη-Scalar τύπους. |
| static std::enable_if\<std::is_scalar\<T\>::value, **bool**\>::type [UnknownIsNull](./unknownisnull/)(T) | Ελέγχει αν αντικείμενο άγνωστου τύπου είναι nullptr. Υπερφόρτωση για Scalar τύπους. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[Object](../object/)\>\>::type [UnknownToObject](./unknowntoobject/)(T) | Μετατρέπει άγνωστο τύπο σε [Object](../object/), χειριζόμενο τόσο τύπους έξυπνων δεικτών όσο και τιμές. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[Object](../object/)\>\>::type [UnknownToObject](./unknowntoobject/)(const T\&) | Μετατρέπει άγνωστο τύπο σε [Object](../object/), χειριζόμενο τόσο τύπους έξυπνων δεικτών όσο και τιμές. |

## Δείτε επίσης

* Κλάση [ObjectType](../objecttype/)
* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)