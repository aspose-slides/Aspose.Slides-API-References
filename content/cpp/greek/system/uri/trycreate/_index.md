---
title: TryCreate()
second_title: Αναφορά API του Aspose.Slides για C++
description: Δημιουργεί ένα αντικείμενο Uri που αντιπροσωπεύει το καθορισμένο URI· ένα όρισμα καθορίζει τον τύπο του URI.
type: docs
weight: 508
url: /el/system/uri/trycreate/
---
## Uri::TryCreate(const String\&, UriKind, SharedPtr\<Uri\>\&) method

Δημιουργεί ένα [Uri](../) αντικείμενο που αντιπροσωπεύει το καθορισμένο URI· ένα όρισμα καθορίζει τον τύπο του URI.

```cpp
static bool System::Uri::TryCreate(const String &uriString, UriKind uriKind, SharedPtr<Uri> &result)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | Το κείμενο URI για να αναπαρασταθεί από το αντικείμενο που κατασκευάζεται |
| uriKind | [UriKind](../../urikind/) | Καθορίζει τον τύπο του URI |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Το όρισμα εξόδου που, εάν η κατασκευή επιτύχει, δείχνει στο νεοκατασκευασμένο [Uri](../) αντικείμενο στην επιστροφή της μεθόδου |

### Τιμή Επιστροφής

True εάν η κατασκευή πέτυχε, διαφορετικά - false

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const String\&, SharedPtr\<Uri\>\&) method

Δημιουργεί ένα [Uri](../) αντικείμενο από το καθορισμένο [Uri](../) αντικείμενο που αντιπροσωπεύει το βασικό URI και την αλφαριθμητική αναπαράσταση του σχετικού URI.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const String &relativeUri, SharedPtr<Uri> &result)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Το βασικό URI |
| relativeUri | const [String](../../string/)\& | Το σχετικό URI που προστίθεται στο βασικό URI |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Το όρισμα εξόδου που, εάν η κατασκευή επιτύχει, δείχνει στο νεοκατασκευασμένο [Uri](../) αντικείμενο στην επιστροφή της μεθόδου |

### Τιμή Επιστροφής

True εάν η κατασκευή πέτυχε, διαφορετικά - false

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, SharedPtr\<Uri\>\&) method

Δημιουργεί ένα [Uri](../) αντικείμενο από τα καθορισμένα βασικά και σχετικά URIs.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri, SharedPtr<Uri> &result)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Το βασικό URI |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Το σχετικό URI που προστίθεται στο βασικό URI |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Το όρισμα εξόδου που, εάν η κατασκευή επιτύχει, δείχνει στο νεοκατασκευασμένο [Uri](../) αντικείμενο στην επιστροφή της μεθόδου |

### Τιμή Επιστροφής

True εάν η κατασκευή πέτυχε, διαφορετικά - false

## Δείτε επίσης

* Enum [UriKind](../../urikind/)
* Typedef [SharedPtr](../../sharedptr/)
* Κλάση [String](../../string/)
* Κλάση [Uri](../)
* Χώρος ονομάτων [System](../../)
* Library [Aspose.Slides](../../../)