---
title: TypeInfo
second_title: Αναφορά API του Aspose.Slides για C++
description: Αναπαριστά έναν συγκεκριμένο τύπο και παρέχει πληροφορίες γι' αυτόν.
type: docs
weight: 1353
url: /el/system/typeinfo/
---
## TypeInfo κλάση


Represents a particular type and provides information about it.

```cpp
class TypeInfo
```

## Μέθοδοι

| Method | Description |
| --- | --- |
| void [AddAttribute](./addattribute/)(const [ObjectPtr](../smartptr/)\&) | Προσθέτει το καθορισμένο χαρακτηριστικό στη λίστα των χαρακτηριστικών του τύπου. |
| void [AddDefaultConstructor](./adddefaultconstructor/)() | Ορίζει κατασκευαστή προεπιλογής για τον τύπο T. |
| void [AddDefaultConstructor](./adddefaultconstructor/)([DefaultConstructor](./defaultconstructor/)) | Ορίζει κατασκευαστή προεπιλογής με το functor που δημιουργεί ένα στιγμιότυπο της κλάσης. |
| void [AddMember](./addmember/)(const [SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\&) | Προσθέτει το καθορισμένο μέλος στη λίστα των μελών του τύπου. |
| static const [TypeInfo](./)\& [BoxedValueType](./boxedvaluetype/)() | Παρέχει μοναδική δομή [TypeInfo](./) για τον τύπο **BoxedValue** ώστε να μοιράζεται από πολλαπλές κλάσεις Boxed*. |
| **bool** [Equals](./equals/)(const [TypeInfo](./)\&) const |  |
| [System::SharedPtr](../sharedptr/)\<[System::Reflection::Assembly](../../system.reflection/assembly/)\> [get_Assembly](./get_assembly/)() const | ΔΕΝ ΥΛΟΠΟΙΕΤΑΙ. Επιστρέφει έναν δείκτη στην μονάδα στην οποία έχει δηλωθεί ο τύπος που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| [String](../string/) [get_AssemblyQualifiedName](./get_assemblyqualifiedname/)() const | ΔΕΝ ΥΛΟΠΟΙΕΤΑΙ. Επιστρέφει το πλήρες όνομα, συμπεριλαμβανομένου του ονόματος της μονάδας, του τύπου που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| [TypeInfo](./) [get_BaseType](./get_basetype/)() const | Επιστρέφει τον περιγραφέα του βασικού τύπου. |
| **bool** [get_ContainsGenericParameters](./get_containsgenericparameters/)() const | Λαμβάνει μια τιμή που υποδεικνύει εάν το τρέχον αντικείμενο Type έχει παραμέτρους τύπου που δεν έχουν αντικατασταθεί από συγκεκριμένους τύπους. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [get_DeclaredMember](./get_declaredmember/)(const [String](../string/)\&) const | Λαμβάνει λίστα των μελών με το καθορισμένο όνομα. |
| [String](../string/) [get_FullName](./get_fullname/)() const | Επιστρέφει το πλήρες όνομα (χωρίς το όνομα της μονάδας) του τύπου που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [get_GenericTypeArguments](./get_generictypearguments/)() const | Λαμβάνει έναν πίνακα των γενικών ορισμάτων τύπου για αυτόν τον τύπο. |
| **bool** [get_IsAbstract](./get_isabstract/)() const | Λαμβάνει μια τιμή που υποδεικνύει εάν ο Type είναι αφηρημένος και πρέπει να αντικατασταθεί. |
| **bool** [get_IsArray](./get_isarray/)() const | Λαμβάνει μια τιμή που υποδεικνύει εάν ο τύπος είναι πίνακας. |
| **bool** [get_IsClass](./get_isclass/)() const | Λαμβάνει μια τιμή που υποδεικνύει εάν ο Type είναι κλάση ή delegate· δηλαδή, δεν είναι τύπος τιμής ή διεπαφή. |
| **bool** [get_IsEnum](./get_isenum/)() const | Λαμβάνει μια τιμή που υποδεικνύει εάν ο τρέχον Type αντιπροσωπεύει μια απαρίθμηση. |
| **bool** [get_IsGenericType](./get_isgenerictype/)() const |  |
| **bool** [get_IsGenericTypeDefinition](./get_isgenerictypedefinition/)() const | Λαμβάνει μια τιμή που υποδεικνύει εάν ο τρέχον Type αντιπροσωπεύει έναν ορισμό γενικού τύπου, από τον οποίο μπορούν να κατασκευαστούν άλλοι γενικοί τύποι. |
| **bool** [get_IsInterface](./get_isinterface/)() const | Λαμβάνει μια τιμή που υποδεικνύει εάν ο Type είναι διεπαφή· δηλαδή, δεν είναι κλάση ή τύπος τιμής. |
| **bool** [get_IsSealed](./get_issealed/)() const | Λαμβάνει μια τιμή που υποδεικνύει εάν ο Type δηλώνεται sealed. |
| **bool** [get_IsValueType](./get_isvaluetype/)() const | Λαμβάνει μια τιμή που υποδεικνύει εάν ο Type είναι τύπος τιμής. |
| **bool** [get_IsVisible](./get_isvisible/)() const | Λαμβάνει μια τιμή που υποδεικνύει εάν ο Type μπορεί να προσπελαστεί από κώδικα εκτός της μονάδας. |
| [String](../string/) [get_Name](./get_name/)() const | Επιστρέφει το όνομα του τύπου που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| [String](../string/) [get_Namespace](./get_namespace/)() const | Λαμβάνει το χώρο ονομάτων του Type. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\> [GetConstructor](./getconstructor/)(const [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\>\&) const | Αναζητά δημόσιο κατασκευαστή στιγμής του οποίου οι παράμετροι ταιριάζουν με τους τύπους στον καθορισμένο πίνακα. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Αναζητά τους κατασκευαστές που έχουν οριστεί για τον τρέχον Type, χρησιμοποιώντας τα καθορισμένα BindingFlags. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)() const | Επιστρέφει όλους τους δημόσιους κατασκευαστές που έχουν οριστεί για τον τρέχον Type. |
| [ObjectPtr](../smartptr/) [GetCustomAttribute](./getcustomattribute/)(const [TypeInfo](./)\&) const | Αναζητά το προσαρμοσμένο χαρακτηριστικό που έχει εφαρμοστεί με τον καθορισμένο τύπο και έχει εφαρμοστεί στον τύπο που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)() const | Επιστρέφει έναν πίνακα που περιέχει αντικείμενα που αντιπροσωπεύουν όλα τα προσαρμοσμένα χαρακτηριστικά που έχουν εφαρμοστεί στον τύπο. |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)(const [TypeInfo](./)\&, **bool**) const | Επιστρέφει έναν πίνακα που περιέχει αντικείμενα που αντιπροσωπεύουν συγκεκριμένα χαρακτηριστικά που έχουν εφαρμοστεί στον τύπο. |
| [TypeInfo](./) [GetElementType](./getelementtype/)() const | ΔΕΝ ΥΛΟΠΟΙΕΤΑΙ. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\> [GetField](./getfield/)(const [System::String](../string/)\&, [System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Αναζητά το καθορισμένο πεδίο, χρησιμοποιώντας τα καθορισμένα περιορισμούς σύνδεσης. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\>\> [GetFields](./getfields/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Αναζητά τα πεδία που έχουν οριστεί για τον τρέχον Type, χρησιμοποιώντας τα καθορισμένα περιορισμούς σύνδεσης. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetGenericArguments](./getgenericarguments/)() const | Λαμβάνει έναν πίνακα των γενικών ορισμάτων τύπου για αυτόν τον τύπο. |
| int [GetHashCode](./gethashcode/)() const | Επιστρέφει έναν κωδικό κατακερματισμού που σχετίζεται με αυτήν την εμφάνιση. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetInterfaces](./getinterfaces/)() const | Λαμβάνει όλες τις διεπαφές που υλοποιήθηκαν ή κληρονόμησαν από τον τρέχον Type. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [GetMember](./getmember/)(const [String](../string/)\&) const | Λαμβάνει λίστα των μελών με το καθορισμένο όνομα. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::MethodInfo](../../system.reflection/methodinfo/)\> [GetMethod](./getmethod/)(const [String](../string/)\&) const | Λαμβάνει μέθοδο με το καθορισμένο όνομα. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)() const | Επιστρέφει όλες τις δημόσιες ιδιότητες του τρέχοντος Type. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Αναζητά τις ιδιότητες του τρέχον Type, χρησιμοποιώντας τα καθορισμένα περιορισμούς σύνδεσης. |
| [TypeInfo](./) [GetTemplParamType](./gettemplparamtype/)() const | Λαμβάνει τον περιγραφέα του παραμέτρου τύπου του προτύπου. |
| **uint32_t** [Hash](./hash/)() const | Επιστρέφει μια τιμή κατακερματισμού που σχετίζεται με τον τύπο που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| **bool** [IsAssignableFrom](./isassignablefrom/)(const [TypeInfo](./)\&) const | Καθορίζει εάν ένα αντικείμενο ενός καθορισμένου τύπου μπορεί να εκχωρηθεί σε μια μεταβλητή του τρέχοντος τύπου. |
| **bool** [IsDefined](./isdefined/)(const [TypeInfo](./)\&, **bool**) const | ΔΕΝ ΥΛΟΠΟΙΕΤΑΙ. Δείχνει εάν ένα ή περισσότερα χαρακτηριστικά του καθορισμένου τύπου ή των παράγωγων τύπων του έχουν εφαρμοστεί σε αυτό το μέλος. |
| **bool** [IsInstanceOfType](./isinstanceoftype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Καθορίζει εάν το καθορισμένο αντικείμενο είναι μια εμφάνιση του τρέχοντος τύπου. |
| **bool** [IsSubclassOf](./issubclassof/)(const [TypeInfo](./)\&) const | Καθορίζει εάν ο τύπος που αντιπροσωπεύεται από το τρέχον αντικείμενο είναι υποκατηγορία της καθορισμένης κλάσης. |
| **bool** [operator!=](./operator_not_equal/)(const [TypeInfo](./)\&) const | Καθορίζει εάν το τρέχον και το καθορισμένο αντικείμενα [TypeInfo](./) δεν είναι ίσα. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Καθορίζει εάν το τρέχον αντικείμενο [TypeInfo](./) δεν είναι αντικείμενο-μηδέν, δηλαδή αντιπροσωπεύει κάποιο τύπο. |
| **bool** [operator==](./operator_equal_equal/)(const [TypeInfo](./)\&) const | Καθορίζει εάν το τρέχον και το καθορισμένο αντικείμενα [TypeInfo](./) είναι ίσα. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Καθορίζει εάν το τρέχον αντικείμενο [TypeInfo](./) είναι αντικείμενο-μηδέν, δηλαδή δεν αντιπροσωπεύει κανέναν τύπο. |
| void [reset](./reset/)() | Ορίζει το [TypeInfo](./) σε null. |
| void [set_IsValueType](./set_isvaluetype/)(**bool**) | Ορίζει μια τιμή που υποδεικνύει εάν ο Type είναι τύπος τιμής. |
| void [SetBaseType](./setbasetype/)(GetTypeInfoFunPtr) | Ορίζει τον περιγραφέα του βασικού τύπου. |
| void [SetTemplParamType](./settemplparamtype/)(const [TypeInfo](./)\&) | Ορίζει τον περιγραφέα του παραμέτρου τύπου του προτύπου. |
| static **uint32_t** [StringHash](./stringhash/)(const char_t *) | Υπολογίζει τον κατακερματισμό για τη συγκεκριμένη συμβολοσειρά. |
| [String](../string/) [ToString](./tostring/)() const | Επιστρέφει μια συμβολοσειρά που περιέχει το όνομα του τύπου που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| static const [TypeInfo](./)\& [Type](./type/)() | Επιστρέφει ένα αντικείμενο [TypeInfo](./) που αντιπροσωπεύει την κλάση [TypeInfo](./). |
|  [TypeInfo](./typeinfo/)() | Προεπιλεγμένος κατασκευαστής (δεν έχει οριστεί τύπος). |
|  [TypeInfo](./typeinfo/)(std::nullptr_t) | Κατασκευαστής αντικειμένου-μηδέν (δεν έχει οριστεί τύπος). |
|  [TypeInfo](./typeinfo/)(const char_t *) | Κατασκευαστής. |
|  [TypeInfo](./typeinfo/)(const char_t *, **uint32_t**) | Κατασκευαστής. |
|  [TypeInfo](./typeinfo/)(const std::type_info\&) | Κατασκευαστής. |

## Πεδία

| Field | Description |
| --- | --- |
| static [EmptyType](./emptytype/) | Σταθερά που αντιπροσωπεύει κενή λίστα των [TypeInfo](./). |
| static [EmptyTypes](./emptytypes/) | Σταθερά που αντιπροσωπεύει κενή λίστα των [TypeInfo](./). |

## Ορισμοί τύπων

| Typedef | Description |
| --- | --- |
| [DefaultConstructor](./defaultconstructor/) | Δείκτης συνάρτησης για δημιουργία τύπου. |

## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)