---
title: Uri()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί ένα αντικείμενο Uri που αντιπροσωπεύει το καθορισμένο URI.
type: docs
weight: 287
url: /el/system/uri/uri/
---
## Uri::Uri(const String\&) κατασκευαστής

Δημιουργεί ένα [Uri](../) αντικείμενο που αντιπροσωπεύει το καθορισμένο URI.

```cpp
System::Uri::Uri(const String &uriString)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | Η συμβολοσειρά URI που θα αντιπροσωπεύεται από το αντικείμενο που κατασκευάζεται |

## Uri::Uri(const String\&, bool) κατασκευαστής

Δημιουργεί ένα [Uri](../) αντικείμενο που αντιπροσωπεύει το καθορισμένο URI· ένα όρισμα καθορίζει αν το URI πρέπει να κωδικοποιηθεί.

```cpp
System::Uri::Uri(const String &uriString, bool dontEscape)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | Η συμβολοσειρά URI που θα αντιπροσωπεύεται από το αντικείμενο που κατασκευάζεται |
| dontEscape | **bool** | Καθορίζει αν το URI δεν πρέπει να κωδικοποιηθεί |

## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&, bool) κατασκευαστής

Δημιουργεί ένα [Uri](../) abject από το καθορισμένο [Uri](../) αντικείμενο που αντιπροσωπεύει το βασικό URI και την αναπαράσταση κειμένου του σχετικού URI· ένα όρισμα καθορίζει αν το URI πρέπει να κωδικοποιηθεί.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri, bool dontEscape)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Το βασικό URI |
| relativeUri | const [String](../../string/)\& | Το σχετικό URI που προστίθεται στο βασικό URI |
| dontEscape | **bool** | Καθορίζει αν το URI δεν πρέπει να κωδικοποιηθεί |

## Uri::Uri(const String\&, UriKind) κατασκευαστής

Δημιουργεί ένα [Uri](../) αντικείμενο που αντιπροσωπεύει το καθορισμένο URI· ένα όρισμα καθορίζει τον τύπο του URI.

```cpp
System::Uri::Uri(const String &uriString, UriKind uriKind)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | Η συμβολοσειρά URI που θα αντιπροσωπεύεται από το αντικείμενο που κατασκευάζεται |
| uriKind | [UriKind](../../urikind/) | Καθορίζει τον τύπο του URI |

## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&) κατασκευαστής

Δημιουργεί ένα [Uri](../) abject από τα καθορισμένα βασικά και σχετικά URIs.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Το βασικό URI |
| relativeUri | const [String](../../string/)\& | Το σχετικό URI που προστίθεται στο βασικό URI |

## Uri::Uri(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) κατασκευαστής

Δημιουργεί ένα [Uri](../) abject από τα καθορισμένα βασικά και σχετικά URIs.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Το βασικό URI |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Το σχετικό URI που προστίθεται στο βασικό URI |

## Δείτε επίσης

* Enum [UriKind](../../urikind/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)