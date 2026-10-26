---
title: ToType()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Μετατρέπει την τιμή αυτού του αντικειμένου σε ένα System::Object του καθορισμένου System::Type που έχει ισοδύναμη τιμή, χρησιμοποιώντας τις καθορισμένες πληροφορίες μορφοποίησης ειδικές για τον πολιτισμό."
type: docs
weight: 209
url: /el/system/iconvertible/totype/
---
## IConvertible::ToType(const TypeInfo\&, System::SharedPtr\<System::IFormatProvider\>) μέθοδος

Μετατρέπει την τιμή αυτού του αντικειμένου σε ένα [System::Object](../../object/) του καθορισμένου System::Type που έχει ισοδύναμη τιμή, χρησιμοποιώντας τις καθορισμένες πληροφορίες μορφοποίησης που είναι ειδικές για τον πολιτισμό.

```cpp
virtual System::SharedPtr<System::Object> System::IConvertible::ToType(const TypeInfo &conversionType, System::SharedPtr<System::IFormatProvider> provider)=0
```

### Παραμέτρους

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| conversionType | const [TypeInfo](../../typeinfo/)\& | Το System::Type στο οποίο μετατρέπεται η τιμή αυτού του αντικειμένου. |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | Μια υλοποίηση διεπαφής [System::IFormatProvider](../../iformatprovider/) που παρέχει πληροφορίες μορφοποίησης ειδικές για τον πολιτισμό. |

### Τιμή Επιστροφής

Ένα αντικείμενο [System::Object](../../object/) τύπου conversionType του οποίου η τιμή είναι ισοδύναμη με την τιμή αυτού του αντικειμένου.

## Δείτε επίσης

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [TypeInfo](../../typeinfo/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [IConvertible](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)