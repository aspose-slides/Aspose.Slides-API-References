---
title: AppendFormat()
second_title: Aspose.Slides για C++ API Αναφορά
description: Προσθέτει μορφοποιημένη συμβολοσειρά στο builder.
type: docs
weight: 131
url: /el/system.text/stringbuilder/appendformat/
---
## StringBuilder::AppendFormat(const String&, const TArgs&...) method


Προσθέτει μορφοποιημένη συμβολοσειρά στο builder.

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const String &format, const TArgs &... args)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TArgs | Τύπος ορισμάτων. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| format | const [String](../../../system/string/)& | Συμβολοσειρά μορφοποίησης. |
| args | const TArgs&... | Ορίσματα που θα εισαχθούν στις θέσεις της συμβολοσειράς μορφοποίησης. |

### Τιμή επιστροφής

Αυτόν τον δείκτη.

## StringBuilder::AppendFormat(const SharedPtr\<IFormatProvider\>&, const String&, const TArgs&...) method


Προσθέτει μορφοποιημένη συμβολοσειρά στο builder.

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const SharedPtr<IFormatProvider> &fp, const String &format, const TArgs &... args)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TArgs | Τύπος ορισμάτων. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fp | const [SharedPtr](../../../system/sharedptr/)<[IFormatProvider](../../../system/iformatprovider/)>& | Παροχέας μορφοποίησης· αγνοείται. |
| format | const [String](../../../system/string/)& | Συμβολοσειρά μορφοποίησης. |
| args | const TArgs&... | Ορίσματα που θα εισαχθούν στις θέσεις της συμβολοσειράς μορφοποίησης. |

### Τιμή επιστροφής

Αυτόν τον δείκτη.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [StringBuilder](../)
* Κλάση [String](../../../system/string/)
* Κλάση [IFormatProvider](../../../system/iformatprovider/)
* Χώρος ονομάτων [System::Text](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)