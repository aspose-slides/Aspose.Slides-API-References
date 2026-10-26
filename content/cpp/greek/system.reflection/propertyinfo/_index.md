---
title: PropertyInfo
second_title: Aspose.Slides για C++ API Reference
description: Αναπαριστά πληροφορίες ιδιότητας.
type: docs
weight: 144
url: /el/system.reflection/propertyinfo/
---
## Κλάση PropertyInfo

Αναπαριστά πληροφορίες ιδιότητας.

```cpp
class PropertyInfo : public System::Reflection::MemberInfo
```

## Μέθοδοι

| Method | Description |
| --- | --- |
| void [AddAttribute](../memberinfo/addattribute/)(const [ObjectPtr](../memberinfo/objectptr/)\&) | Προσθέτει χαρακτηριστικό στη συλλογή. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Αντιπαράγει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα ακόμη και αν σύμφωνα με το IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Αντιπαράγει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα ακόμη και αν σύμφωνα με το IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [TypeInfo](../../system/typeinfo/) [get_DeclaringType](../memberinfo/get_declaringtype/)() const | Λαμβάνει τον τύπο δήλωσης. |
| const [String](../../system/string/)\& [get_FullName](../memberinfo/get_fullname/)() const | Λαμβάνει το πλήρες όνομα του μέλους. Μπορεί να διαφέρει σε χειροκίνητα υλοποιημένα τμήματα. |
| [MemberTypes](../membertypes/) [get_MemberType](./get_membertype/)() const override | Λαμβάνει μια τιμή MemberTypes που υποδεικνύει ότι αυτό το μέλος είναι ιδιότητα. |
| const [String](../../system/string/)\& [get_Name](../memberinfo/get_name/)() const | Λαμβάνει το όνομα του μέλους. |
| [TypeInfo](../../system/typeinfo/) [get_PropertyType](./get_propertytype/)() | Λαμβάνει τον τύπο της ιδιότητας. |
| [TypeInfo](../../system/typeinfo/) [get_ReflectedType](../memberinfo/get_reflectedtype/)() const | Λαμβάνει τον τύπο του αντανακλούμενου τύπου. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\> [GetCustomAttributes](../memberinfo/getcustomattributes/)(const [TypeInfo](../../system/typeinfo/)\&, **bool**) const | Επιστρέφει έναν πίνακα που περιέχει αντικείμενα που αντιπροσωπεύουν όλα τα προσαρμοσμένα χαρακτηριστικά που εφαρμόζονται στον τύπο που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\> [GetCustomAttributes](../memberinfo/getcustomattributes/)(**bool**) const | Επιστρέφει έναν πίνακα που περιέχει αντικείμενα που αντιπροσωπεύουν όλα τα προσαρμοσμένα χαρακτηριστικά που εφαρμόζονται στον τύπο που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογικό της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί την κατακερματοποίηση προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [GetValue](./getvalue/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Λαμβάνει την τιμή της ιδιότητας από συγκεκριμένο αντικείμενο. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [GetValue](./getvalue/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>, [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\>) | Λαμβάνει την τιμή της ιδιότητας από συγκεκριμένο αντικείμενο. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει ένα παράδειγμα τύπου που περιγράφεται από targetType. Αναλογικό του C# 'is' τελεστή. |
| void [Lock](../../system/object/lock/)() | Εφαρμόζει το κλείδωμα της δήλωσης C# lock(). Καλείται απευθείας ή χρησιμοποιεί το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) μεθόδου. Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία αντιγράφων υποκατηγοριών. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία αντιγράφων υποκατηγοριών. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const) | Κατασκευαστής. Ιδιότητα με μόνο σταθερό getter. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<PropertyType\>(ClassType::*)()) | Κατασκευαστής. Ιδιότητα με μόνο μη-σταθερό getter. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)([System::SharedPtr](../../system/sharedptr/)\<PropertyType\>), [System::SharedPtr](../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const) | Κατασκευαστής. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)([System::Nullable](../../system/nullable/)\<NullableType\>), [System::Nullable](../../system/nullable/)\<NullableType\>(ClassType::*)()) | Κατασκευαστής. [Nullable](../../system/nullable/) ιδιότητα με setter και getter. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)([System::Nullable](../../system/nullable/)\<NullableType\>), [System::Nullable](../../system/nullable/)\<NullableType\>(ClassType::*)() const) | Κατασκευαστής. [Nullable](../../system/nullable/) ιδιότητα με μόνο σταθερό getter. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)([System::SharedPtr](../../system/sharedptr/)\<PropertyType\>), [System::SharedPtr](../../system/sharedptr/)\<PropertyType\>(ClassType::*)()) | Κατασκευαστής. [Object](../../system/object/) ιδιότητα με μόνο getter. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)([System::String](../../system/string/)), [System::String](../../system/string/)(ClassType::*)()) | Δημιουργεί πληροφορίες ιδιότητας string. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)([System::String](../../system/string/)), [System::String](../../system/string/)(ClassType::*)() const) | Δημιουργεί πληροφορίες ιδιότητας string από κλάση με σταθερό getter. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)([System::Decimal](../../system/decimal/)), [System::Decimal](../../system/decimal/)(ClassType::*)()) | Δημιουργεί πληροφορίες ιδιότητας [Decimal](../../system/decimal/). |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)([System::Decimal](../../system/decimal/)), [System::Decimal](../../system/decimal/)(ClassType::*)() const) | Δημιουργεί πληροφορίες ιδιότητας [Decimal](../../system/decimal/) από κλάση με σταθερό getter. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)(**bool**), **bool**(ClassType::*)()) | Δημιουργεί πληροφορίες boolean ιδιότητας. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)(**bool**), **bool**(ClassType::*)() const) | Δημιουργεί πληροφορίες boolean ιδιότητας από κλάση με σταθερό getter. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)(**int64_t**), **int64_t**(ClassType::*)()) | Δημιουργεί πληροφορίες ιδιότητας **int64_t**. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)(**int64_t**), **int64_t**(ClassType::*)() const) | Δημιουργεί πληροφορίες ιδιότητας **int64_t** από κλάση με σταθερό getter. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφοράς κατά την καθορισμένη τιμή. |
| void [set_PropertyType](./set_propertytype/)(const [TypeInfo](../../system/typeinfo/)\&) | Ορίζει τον τύπο αυτής της ιδιότητας. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα προτύπου ως αδυναμισμένο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε δοχεία σε αδυναμισμένη λειτουργία. |
| void [SetValue](./setvalue/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>, [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Ορίζει την τιμή της ιδιότητας σε συγκεκριμένο αντικείμενο. |
| void [SetValue](./setvalue/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>, [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>, [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\>) | Ορίζει την τιμή της ιδιότητας σε συγκεκριμένο αντικείμενο. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί για αυτό χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί για αυτό χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογικό της C# [Object.ToString()](../../system/object/tostring/) μεθόδου. Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί το κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Εφαρμόζει το ξεκλείδωμα της δήλωσης C# lock(). Καλείται απευθείας ή χρησιμοποιεί το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδυναμισμένο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί για αυτό χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδυναμισμένο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί για αυτό χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [MemberInfo](../memberinfo/)
* Χώρος ονομάτων [System::Reflection](../)
* Βιβλιοθήκη [Aspose.Slides](../../)