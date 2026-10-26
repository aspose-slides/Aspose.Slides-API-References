---
title: HashAlgorithmName
second_title: Αναφορά API για Aspose.Slides για C++
description: "Συμβολοσειρά που αντιπροσωπεύει το όνομα ενός αλγορίθμου κατακερματισμού. Αυτός ο τύπος θα πρέπει να κατανεμηθεί στη στοίβα και να περάσει σε συναρτήσεις με τιμή ή με αναφορά. Ποτέ μην χρησιμοποιείτε την κλάση System::SmartPtr για τη διαχείριση αντικειμένων αυτού του τύπου."
type: docs
weight: 755
url: /el/system.security.cryptography/hashalgorithmname/
---
## HashAlgorithmName struct

[String](../../system/string/) που αντιπροσωπεύει το όνομα ενός αλγορίθμου κατακερματισμού. Αυτός ο τύπος θα πρέπει να κατανεμηθεί στη στοίβα και να περνιέται σε συναρτήσεις με τιμή ή με αναφορά. Ποτέ μην χρησιμοποιείτε την κλάση [System::SmartPtr](../../system/smartptr/) για τη διαχείριση αντικειμένων αυτού του τύπου.

```cpp
class HashAlgorithmName
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| **bool** [Equals](./equals/)(const [HashAlgorithmName](./)\&) const |  |
| static [HashAlgorithmName](./) [FromOid](./fromoid/)(const [String](../../system/string/)\&) | Δημιουργήστε το [HashAlgorithmName](./) από τιμή OID. |
| static [HashAlgorithmName](./) [get_MD5](./get_md5/)() | Λαμβάνει ένα [HashAlgorithmName](./) που αντιπροσωπεύει το [MD5](../md5/). |
| [String](../../system/string/) [get_Name](./get_name/)() const | Λαμβάνει τη συμβολοσειρά αναπαράστασης του ονόματος του αλγορίθμου. |
| static [HashAlgorithmName](./) [get_SHA1](./get_sha1/)() | Λαμβάνει ένα [HashAlgorithmName](./) που αντιπροσωπεύει το [SHA1](../sha1/). |
| static [HashAlgorithmName](./) [get_SHA256](./get_sha256/)() | Λαμβάνει ένα [HashAlgorithmName](./) που αντιπροσωπεύει το [SHA256](../sha256/). |
| static [HashAlgorithmName](./) [get_SHA384](./get_sha384/)() | Λαμβάνει ένα [HashAlgorithmName](./) που αντιπροσωπεύει το [SHA384](../sha384/). |
| static [HashAlgorithmName](./) [get_SHA512](./get_sha512/)() | Λαμβάνει ένα [HashAlgorithmName](./) που αντιπροσωπεύει το [SHA512](../sha512/). |
| int [GetHashCode](./gethashcode/)() const |  |
|  [HashAlgorithmName](./hashalgorithmname/)() |  |
|  [HashAlgorithmName](./hashalgorithmname/)(const [String](../../system/string/)\&) | Κατασκευαστής. |
| **bool** [IsNull](./isnull/)() const |  |
| **bool** [operator!=](./operator_not_equal/)(const [HashAlgorithmName](./)\&) const |  |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| [HashAlgorithmName](./)\& [operator=](./operator_equal/)(const [HashAlgorithmName](./)\&) |  |
| **bool** [operator==](./operator_equal_equal/)(const [HashAlgorithmName](./)\&) const |  |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| [String](../../system/string/) [ToString](./tostring/)() const | Λαμβάνει τη συμβολοσειρά αναπαράστασης του ονόματος του αλγορίθμου. |
| static **bool** [TryFromOid](./tryfromoid/)(const [String](../../system/string/)\&, [HashAlgorithmName](./)\&) | Προσπαθήστε να δημιουργήσετε το [HashAlgorithmName](./) από τιμή OID. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](./type/)() | Επιστρέφει ένα αντικείμενο [TypeInfo](../../system/typeinfo/) που αντιπροσωπεύει τη δομή [TimeSpan](../../system/timespan/). |

## Δείτε επίσης

* Χώρος ονομάτων [System::Security::Cryptography](../)
* Βιβλιοθήκη [Aspose.Slides](../../)