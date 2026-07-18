---
title: "System::TestPredicates::Details"
second_title: Aspose.Slides για C++ API Αναφορά
description: 
type: docs
weight: 937
url: /el/system.testpredicates.details/
---
## Συναρτήσεις

| Συνάρτηση | Περιγραφή |
| --- | --- |
| std::enable_if_t<\![TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\> [PrintToString](./printtostring/)(const T\&) | Εκτυπώνει το αντικείμενο σε συμβολοσειρά επιλέγοντας τη σωστή συνάρτηση σειριοποίησης. |
| std::enable_if_t\<[TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\> [PrintToString](./printtostring/)(const T\&) | Εκτυπώνει δοχεία τύπου ICollection σε συμβολοσειρά εκτυπώνοντας τα στοιχεία τους (όχι πάνω από 32). |
| std::string [PrintToString](./printtostring/)(std::nullptr_t) | Εκτυπώνει το nullptr σε συμβολοσειρά. |
| std::string [PrintToString](./printtostring/)(const [Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<**bool**\>\&) | Εκτυπώνει τις συλλογές [IEnumerable<bool>](../system.collections.generic/ienumerable/) σε συμβολοσειρά εκτυπώνοντας τα στοιχεία τους (όχι πάνω από 32). |
| std::enable_if\<System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const [SharedPtr](../system/sharedptr/)\<T\>\&, long long) | Εκτυπώνει την υποκλάση [System::Object](../system/object/) σε συμβολοσειρά χρησιμοποιώντας τη μέθοδο ToString(). |
| std::enable_if\<System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const [WeakPtr](../system/weakptr/)\<T\>\&, long long) | Εκτυπώνει την υποκλάση [System::Object](../system/object/) σε συμβολοσειρά χρησιμοποιώντας τη μέθοδο ToString(). |
| std::enable_if<\![TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Εκτυπώνει το αντικείμενο σε συμβολοσειρά χρησιμοποιώντας τη μέθοδο ToString(). |
| std::enable_if\<[TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&\![TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Εκτυπώνει το αντικείμενο σε συμβολοσειρά χρησιμοποιώντας τη μέθοδο PrintTo. |
| std::enable_if\<[TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&[TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Εκτυπώνει το αντικείμενο σε συμβολοσειρά χρησιμοποιώντας τη μέθοδο PrintTo. |
| std::string [PrintToStringImpl](./printtostringimpl/)(const std::pair\<T1, T2\>\&, long long) | Εκτυπώνει το ζεύγος σε συμβολοσειρά. |
| std::string [PrintToStringImpl](./printtostringimpl/)(const [Collections::Generic::KeyValuePair](../system.collections.generic/keyvaluepair/)\<T1, T2\>\&, long long) | Εκτυπώνει το ζεύγος σε συμβολοσειρά. |
| std::enable_if\<[TypeTraits::IsCppContainer](../system.testpredicates.typetraits/iscppcontainer/)\<T\>::value\&&\!std::is_base_of\<[Object](../system/object/), T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Εκτυπώνει δοχεία τύπου STL σε συμβολοσειρά εκτυπώνοντας τα στοιχεία τους (όχι πάνω από 32). |
| std::string [PrintToStringImpl](./printtostringimpl/)(const T\&, int) | Εκτυπώνει άλλους τύπους σε συμβολοσειρά χρησιμοποιώντας τις συναρτήσεις που παρέχει το gtest. |
| testing::AssertionResult [EqFailure](./eqfailure/)(const char *, const char *, T1\&, T2\&) | Μορφοποιεί αποτυχία ισότητας (==) για έξοδο. |
| testing::AssertionResult [NotEqFailure](./noteqfailure/)(const char *, const char *, T1\&, T2\&) | Μορφοποιεί αποτυχία ανισότητας (!=) για έξοδο. |
| testing::AssertionResult [SameFailure](./samefailure/)(const char *, const char *, T1\&, T2\&) | Μορφοποιεί την αποτυχία του ελέγχου 'same' για έξοδο. |
| testing::AssertionResult [NotSameFailure](./notsamefailure/)(const char *, const char *, T1\&, T2\&) | Μορφοποιεί την αποτυχία του ελέγχου 'not same' για έξοδο. |