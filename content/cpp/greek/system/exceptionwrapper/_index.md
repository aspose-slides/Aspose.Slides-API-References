---
title: ExceptionWrapper
second_title: Aspose.Slides για C++ – Αναφορά API
description: Πρότυπο που αντιπροσωπεύει το wrapper των εξαιρέσεων που προέρχονται από την κλάση Exception.
type: docs
weight: 833
url: /el/system/exceptionwrapper/
---
## ExceptionWrapper κλάση

Template που αντιπροσωπεύει το wrapper των εξαιρέσεων που προέρχονται από την κλάση Exception.

```cpp
template<typename T>class ExceptionWrapper
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  [ExceptionWrapper](./exceptionwrapper/)(std::nullptr_t) | Κατασκευάζει μια null-instance της κλάσης [ExceptionWrapper](./) που δεν αντιπροσωπεύει καμία εξαίρεση. |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionPtr](../exceptionptr/)\&) | Κατασκευάζει μια παρουσία της κλάσης [ExceptionWrapper](./) που περιέχει τον δοσμένο δείκτη. |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionWrapper](./)\&) | Κατασκευαστής αντιγραφής. |
|  [ExceptionWrapper](./exceptionwrapper/)([ExceptionWrapper](./)\&&) | Κατασκευαστής μετακίνησης. |
| explicit  [ExceptionWrapper](./exceptionwrapper/)(Args\&&...) | Κατασκευαστής που προωθεί τις παραμέτρους στους κατασκευαστές της κλάσης Exception και δημιουργεί smart pointer που κρατά μια νέα παρουσία της κλάσης Exception. |
| static void * [operator new](./operator_new/)(std::size_t) |  |
| static void * [operator new[]](./operator_new[]/)(std::size_t) |  |
|  [operator SharedPtr< Object >](./operator_sharedptr_less_object__greater/)() | Ανώνυμος τελεστής μετατροπής σε SharedPtr<Object> |
| T * [operator->](./operator_minus_greater/)() const | Επιτρέπει την πρόσβαση στα μέλη του αντικειμένου Exception. |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)(const [ExceptionWrapper](./)\&) | Τελεστής ανάθεσης. |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)([ExceptionWrapper](./)\&&) | Τελεστής ανάθεσης μετακίνησης. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() | Συντόμευση για λήψη του αντικειμένου [System::TypeInfo](../typeinfo/) για τον τύπο Exception. |

## Ορισμοί τύπων

| Ορισμός τύπου | Περιγραφή |
| --- | --- |
| [ExceptionType](./exceptiontype/) | Χρησιμοποιείται για συναρτήσεις μετατροπής. |

## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)