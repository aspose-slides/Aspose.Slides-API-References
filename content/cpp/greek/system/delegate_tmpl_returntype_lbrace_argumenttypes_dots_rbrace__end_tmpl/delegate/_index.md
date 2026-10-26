---
title: Delegate()
second_title: Aspose.Slides για C++ API Αναφορά
description: Προεπιλεγμένος κατασκευαστής. Δημιουργεί το αντικείμενο delegate που δεν δείχνει σε τίποτα.
type: docs
weight: 1
url: /el/system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/delegate/
---
## Delegate< ReturnType(ArgumentTypes...)>::Delegate() μέθοδος

Προεπιλεγμένος κατασκευαστής. Δημιουργεί το αντικείμενο delegate που δεν δείχνει σε τίποτα.

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate()=default
```

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(const Delegate\&) μέθοδος




```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(const Delegate &)=default
```

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(Delegate\&&) μέθοδος

Μετακινήσιμο αντίγραφο κατασκευαστή. Αναλαμβάνει την ιδιοκτησία ενός αντικειμένου στο οποίο δείχνει ο συγκεκριμένος delegate.

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(Delegate &&o) noexcept
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| o | Delegate\&& | Το αντικείμενο Delegate από το οποίο θα μετακινηθεί η αναφερόμενη οντότητα |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if<\!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) μέθοδος

Κατασκευαστής. Δημιουργεί ένα αντικείμενο delegate από τον καθορισμένο δείκτη σε ελεύθερη συνάρτηση ή στατική μέθοδο.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<!std::is_bind_expression<T>::value &&std::is_pointer<T>::value &&std::is_function<typename std::remove_pointer<T>::type>::value>::type *=0)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Ο | τύπος του δείκτη σε συνάρτηση ή στατική μέθοδο που δέχεται ο κατασκευαστής ως όρισμα |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| function | T | Δείκτης σε μια «έκφραση bind» – έναν δείκτη συνάρτησης που δημιουργείται από std::bind() – ο οποίος θα είναι ο στόχος του νεοδημιουργημένου αντικειμένου Delegate |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) μέθοδος

Κατασκευαστής. Δημιουργεί ένα delegate από τον καθορισμένο δείκτη στο αντικείμενο συνάρτησης που δημιουργείται από std::bind().

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<std::is_bind_expression<T>::value>::type *=0)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Ο | τύπος του αντικειμένου συνάρτησης που δημιουργείται από std::bind() και δέχεται ο κατασκευαστής ως όρισμα |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| function | T | Δείκτης σε μια «έκφραση bind» – έναν δείκτη συνάρτησης που δημιουργείται από std::bind() – ο οποίος θα είναι ο στόχος του νεοδημιουργημένου αντικειμένου Delegate |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(int, T\&) μέθοδος

Κατασκευαστής. Δημιουργεί ένα delegate από το καθορισμένο αντικείμενο συνάρτησης.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(int functor_tag, T &functor)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος του αντικειμένου συνάρτησης που δέχεται ο κατασκευαστής ως όρισμα |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| functor_tag | int | Μια ψεύτικη ακέραια τιμή· αυτό το όρισμα χρησιμοποιείται για την επίλυση αμφισημίας |
| functor | T\& | Ένα αντικείμενο συνάρτησης στο οποίο θα δείχνει ο νεοδημιουργημένος delegate |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(long, T\&&) μέθοδος

Μετακινήσιμο κατασκευαστής. Δημιουργεί ένα delegate από το καθορισμένο αντικείμενο συνάρτησης.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(long functor_tag, T &&functor)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος του αντικειμένου συνάρτησης που δέχεται ο κατασκευαστής ως όρισμα |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| functor_tag | long | Μια ψεύτικη ακέραια τιμή· αυτό το όρισμα χρησιμοποιείται για την επίλυση αμφισημίας |
| functor | T\&& | Ένα αντικείμενο συνάρτησης στο οποίο θα δείχνει ο νεοδημιουργημένος delegate |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*, ClassType *) μέθοδος

Κατασκευαστής. Δημιουργεί ένα delegate που δείχνει στη συγκεκριμένη μη-στατική μέθοδο του συγκεκριμένου αντικειμένου.

```cpp
template<class MemberType,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*member, ClassType *obj)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| MemberType | Ο τύπος της μη-στατικής μεθόδου που δέχεται ο κατασκευαστής ως όρισμα |
| ClassType | Ο τύπος του αντικειμένου που δέχεται ο κατασκευαστής ως όρισμα |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| member | MemberType ClassType::* | Δείκτης στη μη-στατική μέθοδο που θα δείχνει ο νεοδημιουργημένος delegate |
| obj | ClassType * | Δείκτης σε αντικειμενικό μέλος της κλάσης του οποίου η μέθοδος θα είναι ο στόχος του νεοδημιουργημένου delegate |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*, const SharedPtr\<ClassType\>\&) μέθοδος

Κατασκευαστής. Δημιουργεί ένα delegate που δείχνει στη συγκεκριμένη μη-στατική μέθοδο του συγκεκριμένου αντικειμένου.

```cpp
template<class MemberType,class MemberClass,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*member, const SharedPtr<ClassType> &obj)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| MemberType | Ο τύπος της μη-στατικής μεθόδου που δέχεται ο κατασκευαστής ως όρισμα |
| ClassType | Ο τύπος του αντικειμένου που δέχεται ο κατασκευαστής ως όρισμα |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| member | MemberType MemberClass::* | Δείκτης στη μη-στατική μέθοδο που θα δείχνει ο νεοδημιουργημένος delegate |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | Κοινό δείκτη σε αντικειμενικό μέλος της κλάσης του οποίου η μέθοδος θα είναι ο στόχος του νεοδημιουργημένου delegate |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(std::function\<R(Args...)>) μέθοδος

Δημιουργεί ένα αντικείμενο delegate που δείχνει σε ένα αντικείμενο συνάρτησης std::function.

```cpp
template<class R,class...> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(std::function<R(Args...)> f)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| R | Ο τύπος επιστροφής του αντικειμένου συνάρτησης που δέχεται ο κατασκευαστής ως όρισμα |
| Args | Η λίστα παραμέτρων του αντικειμένου συνάρτησης που δέχεται ο κατασκευαστής ως όρισμα |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| f | std::function\<R(Args...)> | Αντικείμενο συνάρτησης που θα είναι ο στόχος του νεοδημιουργημένου αντικειμένου delegate |

## Δείτε επίσης

* Typedef [SharedPtr](../../sharedptr/)
* Κλάση [Delegate< ReturnType(ArgumentTypes...)>](../)
* Χώρος ονομάτων [System](../../)
* Library [Aspose.Slides](../../../)