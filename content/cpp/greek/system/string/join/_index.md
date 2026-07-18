---
title: Join()
second_title: Aspose.Slides για C++ Αναφορά API
description: Συνενώνει τον πίνακα χρησιμοποιώντας τη συμβολοσειρά ως διαχωριστικό.
type: docs
weight: 846
url: /el/system/string/join/
---
## String::Join(const String\&, const ArrayPtr\<String\>\&, int, int) μέθοδος

Συνενώνει τον πίνακα χρησιμοποιώντας τη συμβολοσειρά ως διαχωριστικό.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<String> &parts, int startIndex=0, int count=-1)
```

### Επιχειρήματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) για τοποθέτηση μεταξύ των στοιχείων του πίνακα κατά τη συνένωση. |
| parts | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) των τμημάτων για συνένωση. |
| startIndex | int | Πρώτος δείκτης στον πίνακα από όπου ξεκινά η συνένωση. |
| count | int | Αριθμός στοιχείων του πίνακα που θα συνενωθούν. -1 σημαίνει 'μέχρι το τέλος του πίνακα'. |

### Τιμή Επιστροφής

[String](../) που αντιπροσωπεύει τα ενωμένα στοιχεία του πίνακα.

## String::Join(const String\&, const System::Details::ArrayView\<String\>\&, int, int) μέθοδος

Συνενώνει τον πίνακα χρησιμοποιώντας τη συμβολοσειρά ως διαχωριστικό.

```cpp
static String System::String::Join(const String &separator, const System::Details::ArrayView<String> &parts, int startIndex=0, int count=-1)
```

### Επιχειρήματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) για τοποθέτηση μεταξύ των στοιχείων του πίνακα κατά τη συνένωση. |
| parts | const System::Details::ArrayView\<[String](../)\>\& | ArrayView των τμημάτων για συνένωση. |
| startIndex | int | Πρώτος δείκτης στον πίνακα από όπου ξεκινά η συνένωση. |
| count | int | Αριθμός στοιχείων του πίνακα που θα συνενωθούν. -1 σημαίνει 'μέχρι το τέλος του πίνακα'. |

### Τιμή Επιστροφής

[String](../) που αντιπροσωπεύει τα ενωμένα στοιχεία του πίνακα.

## String::Join(const String\&, const SharedPtr\<System::Collections::Generic::IEnumerable\<String\>\>\&) μέθοδος

Συνενώνει τον πίνακα χρησιμοποιώντας τη συμβολοσειρά ως διαχωριστικό.

```cpp
static String System::String::Join(const String &separator, const SharedPtr<System::Collections::Generic::IEnumerable<String>> &parts)
```

### Επιχειρήματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) για τοποθέτηση μεταξύ των στοιχείων του πίνακα κατά τη συνένωση. |
| parts | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../)\>\>\& | - αντικείμενο enumerable τμημάτων |

### Τιμή Επιστροφής

[String](../) που αντιπροσωπεύει τα ενωμένα στοιχεία.

## String::Join(const String\&, const ArrayPtr\<SharedPtr\<Object\>\>\&) μέθοδος

Συνενώνει τον πίνακα χρησιμοποιώντας τη συμβολοσειρά ως διαχωριστικό.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<SharedPtr<Object>> &parts)
```

### Επιχειρήματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) για τοποθέτηση μεταξύ των στοιχείων του πίνακα κατά τη συνένωση. |
| parts | const [ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\>\& | [Array](../../array/) των τμημάτων για συνένωση. |

### Τιμή Επιστροφής

[String](../) που αντιπροσωπεύει τα ενωμένα στοιχεία.

## Δείτε επίσης

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Κλάση [String](../)
* Κλάση [IEnumerable](../../../system.collections.generic/ienumerable/)
* Κλάση [Object](../../object/)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)