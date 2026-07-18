---
title: DoTryFinally()
second_title: Aspose.Slides για την Αναφορά API του C++
description: Η μοναδική συνάρτηση που προσομοιώνει τη συμπεριφορά της δήλωσης try[-catch]-finally της C#. Κατά τη μετάφραση της δήλωσης try[-catch]-finally της C# με την επιλογή του μεταφραστή finally_statement_as_lambda ορισμένη σε true, η δήλωση μετατρέπεται στην κλήση αυτής της μεθόδου.
type: docs
weight: 2406
url: /el/system/dotryfinally/
---
## System::DoTryFinally(T\&&, F\&&) συνάρτηση


Η μοναδική συνάρτηση που προσομοιώνει τη συμπεριφορά της δήλωσης try[-catch]-finally της C#. Κατά τη μετάφραση της δήλωσης try[-catch]-finally της C# με την επιλογή του μεταφραστή finally_statement_as_lambda ορισμένη σε true, η δήλωση μετατρέπεται στην κλήση αυτής της μεθόδου.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_void<T>::value> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος του αντικειμένου συνάρτησης που υλοποιεί το τμήμα try[-catch] της δήλωσης try[-catch]-finally που προσομοιώνεται |
| F | Ο τύπος του αντικειμένου συνάρτησης που υλοποιεί το τμήμα finally της δήλωσης try[-catch]-finally που προσομοιώνεται |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| tryBlock | T\&& | Το αντικείμενο συνάρτησης του οποίου το σώμα περιέχει την υλοποίηση του τμήματος try[-catch] της δήλωσης try[-catch]-finally που προσομοιώνεται |
| finallyBlock | F\&& | Το αντικείμενο συνάρτησης του οποίου το σώμα περιέχει την υλοποίηση του τμήματος finally της δήσης try[-catch]-finally που προσομοιώνεται |

## System::DoTryFinally(T\&&, F\&&) συνάρτηση


Η μοναδική συνάρτηση που προσομοιώνει τη συμπεριφορά της δήλωσης try[-catch]-finally της C#. Κατά τη μετάφραση της δήλωσης try[-catch]-finally της C# με την επιλογή του μεταφραστή finally_statement_as_lambda ορισμένη σε true, η δήλωση μετατρέπεται στην κλήση αυτής της μεθόδου. Αυτή η υπερφόρτωση χειρίζεται την περίπτωση όπου η τιμή επιστροφής του αντικειμένου συνάρτησης που υλοποιεί το τμήμα try[-catch] της δήλωσης try[-catch]-finally είναι bool.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_boolref<T>::value, bool> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος του αντικειμένου συνάρτησης που υλοποιεί το τμήμα try[-catch] της δήλωσης try[-catch]-finally που προσομοιώνεται |
| F | Ο τύπος του αντικειμένου συνάρτησης που υλοποιεί το τμήμα finally της δήλωσης try[-catch]-finally που προσομοιώνεται |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| tryBlock | T\&& | Το αντικείμενο συνάρτησης του οποίου το σώμα περιέχει την υλοποίηση του τμήματος try[-catch] της δήλωσης try[-catch]-finally που προσομοιώνεται |
| finallyBlock | F\&& | Το αντικείμενο συνάρτησης του οποίου το σώμα περιέχει την υλοποίηση του τμήματος finally της δήσης try[-catch]-finally που προσομοιώνεται |

## System::DoTryFinally(T\&&, F\&&) συνάρτηση


Η μοναδική συνάρτηση που προσομοιώνει τη συμπεριφορά της δήλωσης try[-catch]-finally της C#. Κατά τη μετάφραση της δήλωσης try[-catch]-finally της C# με την επιλογή του μεταφραστή finally_statement_as_lambda ορισμένη σε true, η δήλωση μετατρέπεται στην κλήση αυτής της μεθόδου. Αυτή η υπερφόρτωση χειρίζεται την περίπτωση όπου η τιμή επιστροφής του αντικειμένου συνάρτησης που υλοποιεί το τμήμα try[-catch] της δήλωσης try[-catch]-finally είναι bool&.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_nonovoid_boolref<T>::value, std::optional<Details::ResultOf<T, bool &>>> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος του αντικειμένου συνάρτησης που υλοποιεί το τμήμα try[-catch] της δήλωσης try[-catch]-finally που προσομοιώνεται |
| F | Ο τύπος του αντικειμένου συνάρτησης που υλοποιεί το τμήμα finally της δήλωσης try[-catch]-finally που προσομοιώνεται |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| tryBlock | T\&& | Το αντικείμενο συνάρτησης του οποίου το σώμα περιέχει την υλοποίηση του τμήματος try[-catch] της δήλωσης try[-catch]-finally που προσομοιώνεται |
| finallyBlock | F\&& | Το αντικείμενο συνάρτησης του οποίου το σώμα περιέχει την υλοποίηση του τμήματος finally της δήσης try[-catch]-finally που προσομοιώνεται |

## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)