---
title: ExceptionWrapper()
second_title: Αναφορά API του Aspose.Slides για C++
description: Δημιουργεί μια μηδενική (null) παρουσία της κλάσης ExceptionWrapper που δεν αντιπροσωπεύει καμία εξαίρεση.
type: docs
weight: 14
url: /el/system/exceptionwrapper/exceptionwrapper/
---
## ExceptionWrapper::ExceptionWrapper(std::nullptr_t) κατασκευαστής

Δημιουργεί μια κενή (null) παρουσία της κλάσης [ExceptionWrapper](../) που δεν αντιπροσωπεύει καμία εξαίρεση.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(std::nullptr_t)
```

## ExceptionWrapper::ExceptionWrapper(const ExceptionPtr\&) κατασκευαστής

Δημιουργεί μια παρουσία της κλάσης [ExceptionWrapper](../) που περιέχει τον δοθέντα δείκτη.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionPtr &ptr)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ptr | const [ExceptionPtr](../../exceptionptr/)\& | Έξυπνος δείκτης στην παρουσία της κλάσης Exception. |

## ExceptionWrapper::ExceptionWrapper(const ExceptionWrapper\&) κατασκευαστής

Κατασκευαστής αντιγραφής.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionWrapper &other)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| other | const [ExceptionWrapper](../)\& | Άλλη παρουσία της κλάσης περιτυλιγτή που πρέπει να αντιγραφεί. |

## ExceptionWrapper::ExceptionWrapper(ExceptionWrapper\&&) κατασκευαστής

Κατασκευαστής μετακίνησης.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(ExceptionWrapper &&other) noexcept
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| other | [ExceptionWrapper](../)\&& | Άλλη παρουσία της κλάσης περιτυλιγτή που πρέπει να μεταφερθεί. |

## ExceptionWrapper::ExceptionWrapper(Args\&&...) κατασκευαστής

Κατασκευαστής που προωθεί τις παραμέτρους στους κατασκευαστές της κλάσης Exception και δημιουργεί έναν έξυπνο δείκτη που κρατά μια νέα παρουσία της κλάσης Exception.

```cpp
template<typename ...,typename> System::ExceptionWrapper<T>::ExceptionWrapper(Args &&...args)
```

## Δείτε επίσης

* Typedef [ExceptionPtr](../../exceptionptr/)
* Κλάση [ExceptionWrapper](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)