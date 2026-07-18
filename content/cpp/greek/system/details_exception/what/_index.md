---
title: what()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Υλοποιεί τη μέθοδο what() που καλείται από την κλάση ExceptionWrapper. Παρά το γεγονός ότι αυτή η κλάση δεν κληρονομείται από τις κλάσεις που προέρχονται από std::exception, οι παράγωγες κλάσεις μπορούν να χρησιμοποιούν προστατευμένα/ιδιωτικά μέλη για να υλοποιήσουν τη λογική τους. Η μεταφορά της υλοποίησης αυτής της μεθόδου στην ExceptionWrapper μπορεί να διασπάσει αυτή τη λογική."
type: docs
weight: 105
url: /el/system/details_exception/what/
---
## Details_Exception::what() const μέθοδος

Implements [what()](./) μέθοδος which is called by [ExceptionWrapper](../../exceptionwrapper/) κλάση. Despite of the fact that this class is not inherited from std::exception derived classes can use protected/private members to implement their logic. Moving this method implementation to the [ExceptionWrapper](../../exceptionwrapper/) may broke that logic.

```cpp
virtual const char * System::Details_Exception::what() const noexcept
```

### Τιμή Επιστροφής

Η περιγραφή της εξαίρεσης.

## Δείτε επίσης

* Κλάση [Details_Exception](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)