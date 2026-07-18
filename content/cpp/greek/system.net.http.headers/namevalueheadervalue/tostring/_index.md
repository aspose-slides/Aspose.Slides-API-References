---
title: ToString()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αναλογία της μεθόδου C# Object.ToString(). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά.
type: docs
weight: 79
url: /el/system.net.http.headers/namevalueheadervalue/tostring/
---
## NameValueHeaderValue::ToString() const μέθοδος

Αναλογία της μεθόδου C# [Object.ToString()](../../../system/object/tostring/). Επιτρέπει τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά.

```cpp
String System::Net::Http::Headers::NameValueHeaderValue::ToString() const override
```

### Τιμή Επιστροφής

[String](../../../system/string/) αναπαράσταση όπως παρέχεται από την τελική κλάση.

## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool, System::SharedPtr\<Text::StringBuilder\>) μέθοδος

Επιστρέφει μια συμβολοσειρά αναπαράστασης της συλλογής των NameValueHeaderValue-class παραδειγμάτων.

```cpp
static void System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator, System::SharedPtr<Text::StringBuilder> destination)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | Η συλλογή των NameValueHeaderValue-class παραδειγμάτων. |
| separator | char16_t | Διαχωριστής συμβολοσειράς. |
| leadingSeparator | **bool** | Η τιμή που υποδεικνύει αν το διαχωριστικό συμβολοσειράς πρέπει να προστεθεί πριν από το πρώτο στοιχείο της συλλογής. |
| destination | [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\> | Μία παρουσία στην οποία θα εκχωρηθεί μια αναπαράσταση συμβολοσειράς. |

## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool) μέθοδος

Επιστρέφει μια συμβολοσειρά αναπαράστασης της συλλογής των NameValueHeaderValue-class παραδειγμάτων.

```cpp
static String System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | Η συλλογή των NameValueHeaderValue-class παραδειγμάτων. |
| separator | char16_t | Διαχωριστής συμβολοσειράς. |
| leadingSeparator | **bool** | Η τιμή που υποδεικνύει αν το διαχωριστικό συμβολοσειράς πρέπει να προστεθεί πριν από το πρώτο στοιχείο της συλλογής. |

### Τιμή Επιστροφής

Μια αναπαράσταση συμβολοσυρρακής της συλλογής των NameValueHeaderValue-class παραδειγμάτων.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [NameValueHeaderValue](../)
* Κλάση [ObjectCollection](../../objectcollection/)
* Κλάση [StringBuilder](../../../system.text/stringbuilder/)
* Χώρος ονομάτων [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)