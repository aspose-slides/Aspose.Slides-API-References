---
title: SmartPtrInfo
second_title: Aspose.Slides για C++ - Αναφορά API
description: Κλάση υπηρεσίας για δοκιμή και τροποποίηση των περιεχομένων του SmartPtr χωρίς γνώση του τελικού τύπου. Χρησιμοποιείται για συλλογή απορριμμάτων και ανίχνευση αναφορών βρόχου, κ.λπ. Σκεφτείτε το ως 'δείκτη σε δείκτη'. Δεν μπορούμε να χρησιμοποιήσουμε τον βασικό τύπο του SmartPtr καθώς δεν υπάρχει· αντί αυτού, χρησιμοποιούμε αυτήν την κλάση 'info'.
type: docs
weight: 1223
url: /el/system/smartptrinfo/
---
## SmartPtrInfo κλάση

Service class to test and alter [SmartPtr](../smartptr/)'s contents without knowing final type. Used for garbage collection and loop references detection, etc. Think of it as of 'pointer to pointer'. We can't use [SmartPtr](../smartptr/)'s basetype as it doesn't have any; instead, we use this 'info' class.

```cpp
class SmartPtrInfo
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| const void * [getInternalPtr](./getinternalptr/)() const | Λαμβάνει τον ακατέργαστο δείκτη αντικειμένου στον οποίο δείχνει ο αναφορικός δείκτης. |
| [Object](../object/) * [getObject](./getobject/)() const | Λαμβάνει το αντικείμενο στο οποίο δείχνει ο αναφορικός δείκτης. |
| [Object](../object/) * [getOwned](./getowned/)() const | Λαμβάνει τον ιδιόκτητο δείκτη αντικειμένου. |
|  [operator bool](./operator_bool/)() const | Ελέγχει αν το αντικείμενο info δείχνει σε μη μηδενικό δείκτη. |
| **bool** [operator!](./operator_not/)() const | Ελέγχει αν το αντικείμενο info δεν δείχνει σε μη μηδενικό δείκτη. |
| [Object](../object/) * [operator->](./operator_minus_greater/)() const | Επιτρέπει την κλήση μεθόδων του [Object](../object/) που δείχνει ο αναφορικός δείκτης. |
| **bool** [operator<](./operator_less/)(const [SmartPtrInfo](./)\&) const | Συγκρίνει με μικρότερο τρόπο τις τιμές των δεικτών που αναφέρονται από δύο αντικείμενα info. |
|  [SmartPtrInfo](./smartptrinfo/)() | Δημιουργεί κενό αντικείμενο [SmartPtrInfo](./). |
| explicit  [SmartPtrInfo](./smartptrinfo/)(const [SmartPtr](../smartptr/)\<T\>\&) | Δημιουργεί αντικείμενο [SmartPtrInfo](./) με πληροφορίες για συγκεκριμένο έξυπνο δείκτη. |

## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)