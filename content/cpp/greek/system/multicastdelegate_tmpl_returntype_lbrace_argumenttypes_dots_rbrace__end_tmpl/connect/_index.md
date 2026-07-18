---
title: connect()
second_title: Aspose.Slides για C++ Αναφορά API
description: Προσθέτει το καθορισμένο delegate στη συλλογή.
type: docs
weight: 144
url: /el/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/connect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(Callback) μέθοδος

Προσθέτει το καθορισμένο delegate στη συλλογή.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(Callback callback)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| callback | [Callback](../callback/) | Το delegate προς προσθήκη στη συλλογή |

### Τιμή Επιστροφής

Μία αναφορά στον εαυτό

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(std::function\<R(Args...)>) μέθοδος

Προσθέτει το καθορισμένο αντικείμενο συνάρτησης στη συλλογή delegate. Το αντικείμενο συνάρτησης μετατρέπεται σε τύπο delegate Callback πριν προστεθεί στη συλλογή.

```cpp
template<class R,class...> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(std::function<R(Args...)> f)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| R | Ο τύπος επιστροφής του αντικειμένου συνάρτησης προς προσθήκη στη συλλογή |
| Args | Η λίστα ορισμάτων του αντικειμένου συνάρτησης προς προσθήκη στη συλλογή |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| f | std::function\<R(Args...)> | Το αντικείμενο συνάρτησης προς προσθήκη στη συλλογή |

### Τιμή Επιστροφής

Μία αναφορά στον εαυτό

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MulticastDelegate\&) μέθοδος

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MulticastDelegate &other)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | Μία παρουσία της κλάσης MulticastDelegate προς προσθήκη στη συλλογή delegate |

### Τιμή Επιστροφής

Μία αναφορά στον εαυτό

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, ClassType *) μέθοδος

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, ClassType *obj)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| MemberType | Ο τύπος της μη-στατικής μεθόδου που θα προστεθεί στη συλλογή delegate |
| ClassType | Ο τύπος του αντικειμένου της μεθόδου του οποίου θα προστεθεί στη συλλογή delegate |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| member | MemberType ClassType::* | Δείκτης στη μη-στατική μέθοδο του καθορισμένου αντικειμένου |
| obj | ClassType * | Δείκτης σε μέλος-μέθοδο αντικειμένου του οποίου θα προστεθεί στη συλλογή delegate |

### Τιμή Επιστροφής

Μία αναφορά στον εαυτό

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) μέθοδος

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| MemberType | Ο τύπος της μη-στατικής μεθόδου που θα προστεθεί στη συλλογή delegate |
| ClassType | Ο τύπος του αντικειμένου της μεθόδου του οποίου θα προστεθεί στη συλλογή delegate |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| member | MemberType ClassType::* | Δείκτης στη μη-στατική μέθοδο του καθορισμένου αντικειμένου |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | Κοινόχρηστος δείκτης (shared pointer) σε μέλος-μέθοδο αντικειμένου του οποίου θα προστεθεί στη συλλογή delegate |

### Τιμή Επιστροφής

Μία αναφορά στον εαυτό

## Δείτε επίσης

* Typedef [Callback](../callback/)
* Typedef [SharedPtr](../../sharedptr/)
* Method [MulticastDelegate](../multicastdelegate/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)