---
title: ConvertAll()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί ένα νέο αντικείμενο Array και το γεμίζει με στοιχεία του καθορισμένου πίνακα που μετατρέπονται σε τύπο OutputType χρησιμοποιώντας το καθορισμένο delegate μετατροπέα.
type: docs
weight: 625
url: /el/system/array/convertall/
---
## Array::ConvertAll(ArrayPtr\<InputType\>, Converter\<InputType, OutputType\>) μέθοδος

Δημιουργεί ένα νέο αντικείμενο [Array](../) και το γεμίζει με στοιχεία του καθορισμένου πίνακα που μετατρέπονται σε τύπο **OutputType** χρησιμοποιώντας το καθορισμένο delegate μετατροπέα.

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, Converter<InputType, OutputType> converter)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| InputType | Ο τύπος των στοιχείων του πίνακα εισόδου |
| OutputType | Ο τύπος των στοιχείων του προκύπτοντος πίνακα |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | Ένα αντικείμενο [Array](../) |
| converter | [Converter](../../converter/)\<InputType, OutputType\> | Ένα αντικείμενο Converter που χρησιμοποιείται για τη μετατροπή κάθε στοιχείου του πίνακα εισόδου σε ισοδύναμες τιμές τύπου **OutputType** |

### Τιμή Επιστροφής

Ένας νέος πίνακας που περιέχει τιμές τύπου **OutputType** ισοδύναμες με τις τιμές του **input_array**

## Array::ConvertAll(ArrayPtr\<InputType\>, std::function\<OutputType(InputType)>) μέθοδος

Δημιουργεί ένα νέο αντικείμενο [Array](../) και το γεμίζει με στοιχεία του καθορισμένου πίνακα που μετατρέπονται σε τύπο **OutputType** χρησιμοποιώντας το καθορισμένο αντικείμενο συνάρτησης μετατροπέα.

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, std::function<OutputType(InputType)> converter)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| InputType | Ο τύπος των στοιχείων του πίνακα εισόδου |
| OutputType | Ο τύπος των στοιχείων του προκύπτοντος πίνακα |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | Ένα αντικείμενο [Array](../) |
| converter | std::function\<OutputType(InputType)> | Ένα αντικείμενο συνάρτησης που χρησιμοποιείται για τη μετατροπή κάθε στοιχείου του πίνακα εισόδου σε ισοδύναμες τιμές τύπου **OutputType** |

### Τιμή Επιστροφής

Ένας νέος πίνακας που περιέχει τιμές τύπου **OutputType** ισοδύναμες με τις τιμές του **input_array**

## Δείτε επίσης

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Converter](../../converter/)
* Κλάση [Array](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)