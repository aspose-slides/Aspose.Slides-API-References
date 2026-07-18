---
title: StringWriter()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί ένα νέο αντικείμενο StringWriter χρησιμοποιώντας το καθορισμένο StringBuilder και το IFormatProvider.
type: docs
weight: 1
url: /el/system.io/stringwriter/stringwriter/
---
## StringWriter::StringWriter(const System::SharedPtr\<Text::StringBuilder\>\&, const IFormatProviderPtr\&) κατασκευαστής

Δημιουργεί ένα νέο αντίγραφο του [StringWriter](../) χρησιμοποιώντας το καθορισμένο StringBuilder και [IFormatProvider](../../../system/iformatprovider/).

```cpp
System::IO::StringWriter::StringWriter(const System::SharedPtr<Text::StringBuilder> &sb, const IFormatProviderPtr &formatProvider)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sb | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | Το StringBuilder αντικείμενο που θα χρησιμοποιηθεί από το [StringWriter](../) που κατασκευάζεται |
| formatProvider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | Ένα [IFormatProvider](../../../system/iformatprovider/) αντικείμενο που θα χρησιμοποιηθεί από το αντικείμενο που κατασκευάζεται |

## StringWriter::StringWriter(const System::SharedPtr\<Text::StringBuilder\>\&) κατασκευαστής

Δημιουργεί ένα νέο αντίγραφο του [StringWriter](../) χρησιμοποιώντας το καθορισμένο StringBuilder και [IFormatProvider](../../../system/iformatprovider/) από την τρέχουσα πολιτιστική ρύθμιση.

```cpp
System::IO::StringWriter::StringWriter(const System::SharedPtr<Text::StringBuilder> &sb)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sb | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | Το StringBuilder αντικείμενο που θα χρησιμοποιηθεί από το [StringWriter](../) που κατασκευάζεται |

## StringWriter::StringWriter(const IFormatProviderPtr\&) κατασκευαστής

Δημιουργεί ένα νέο αντίγραφο του [StringWriter](../) χρησιμοποιώντας το καθορισμένο [IFormatProvider](../../../system/iformatprovider/).

```cpp
System::IO::StringWriter::StringWriter(const IFormatProviderPtr &formatProvider)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| formatProvider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | Ένα [IFormatProvider](../../../system/iformatprovider/) αντικείμενο που θα χρησιμοποιηθεί από το αντικείμενο που κατασκευάζεται |

## StringWriter::StringWriter() κατασκευαστής

Δημιουργεί ένα νέο αντίγραφο του [StringWriter](../) χρησιμοποιώντας [IFormatProvider](../../../system/iformatprovider/) από την τρέχουσα πολιτιστική ρύθμιση.

```cpp
System::IO::StringWriter::StringWriter()
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [IFormatProviderPtr](../../../system/iformatproviderptr/)
* Κλάση [StringBuilder](../../../system.text/stringbuilder/)
* Κλάση [StringWriter](../)
* Ονομαχώρος [System::IO](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)