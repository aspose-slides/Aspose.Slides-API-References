---
title: disconnect()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αφαιρεί τον καθορισμένο delegate από τη συλλογή delegate.
type: docs
weight: 170
url: /el/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/disconnect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(Callback) μέθοδος

Αφαιρεί τον καθορισμένο delegate από τη συλλογή delegate.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(Callback callback)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| callback | [Callback](../callback/) | Ο delegate που θα αφαιρεθεί από τη συλλογή |

### Τιμή επιστροφής

Μια αναφορά στον εαυτό

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, ClassType *) μέθοδος

Αφαιρεί τη συγκεκριμένη μη-στατική μέθοδο του καθορισμένου αντικειμένου από τη συλλογή delegate.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, ClassType *obj)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| MemberType | Ο τύπος της μη-στατικής μεθόδου που θα αφαιρεθεί από τη συλλογή delegate |
| ClassType | Ο τύπος του αντικειμένου του οποίου η μέθοδος θα αφαιρεθεί από τη συλλογή delegate |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| member | MemberType ClassType::* | Ένας δείκτης στη μη-στατική μέθοδο του καθορισμένου αντικειμένου |
| obj | ClassType * | Ένας δείκτης σε αντικείμενο του οποίου η μέθοδος θα αφαιρεθεί από τη συλλογή delegate |

### Τιμή επιστροφής

Μια αναφορά στον εαυτό

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) μέθοδος

Αφαιρεί τη συγκεκριμένη μη-στατική μέθοδο του καθορισμένου αντικειμένου από τη συλλογή delegate.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| MemberType | Ο τύπος της μη-στατικής μεθόδου που θα αφαιρεθεί από τη συλλογή delegate |
| ClassType | Ο τύπος του αντικειμένου του οποίου η μέθοδος θα αφαιρεθεί από τη συλλογή delegate |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| member | MemberType ClassType::* | Ένας δείκτης στη μη-στατική μέθοδο του καθορισμένου αντικειμένου |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | Ένας κοινόχρηστος δείκτης σε αντικείμενο του οποίου η μέθοδος θα αφαιρεθεί από τη συλλογή delegate |

### Τιμή επιστροφής

Μια αναφορά στον εαυτό

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate\&) μέθοδος

Αφαιρεί το καθορισμένο αντικείμενο MulticastDelegate από τη συλλογή delegate.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate &other)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | Μία παρουσία της κλάσης MulticastDelegate που θα αφαιρεθεί από τη συλλογή delegate |

### Τιμή επιστροφής

Μια αναφορά στον εαυτό

## Δείτε επίσης

* Typedef [Callback](../callback/)
* Typedef [SharedPtr](../../sharedptr/)
* Μέθοδος [MulticastDelegate](../multicastdelegate/)
* Κλάση [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)