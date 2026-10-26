---
title: ToString()
second_title: Aspose.Slides για C++ API Αναφορά
description: Μετατρέπει το GUID που αντιπροσωπεύεται από το τρέχον αντικείμενο σε μορφή συμβολοσειράς.
type: docs
weight: 79
url: /el/system/guid/tostring/
---
## Guid::ToString() const μέθοδος

Μετατρέπει το GUID που αντιπροσωπεύεται από το τρέχον αντικείμενο σε μορφή συμβολοσειράς.

```cpp
String System::Guid::ToString() const
```

## Guid::ToString(const String\&) const μέθοδος

Μετατρέπει το GUID που αντιπροσωπεύεται από το τρέχον αντικείμενο σε μορφή συμβολοσειράς χρησιμοποιώντας τη συγκεκριμένη μορφή συμβολοσειράς.

```cpp
String System::Guid::ToString(const String &format) const
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| format | const [String](../../string/)\& | Η μορφή προς χρήση |

### Return Value

Η αναπαράσταση συμβολοσειράς της τιμής GUID που αντιπροσωπεύεται από το τρέχον αντικείμενο

## Guid::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const μέθοδος

Μετατρέπει το GUID που αντιπροσωπεύεται από το τρέχον αντικείμενο σε μορφή συμβολοσειράς χρησιμοποιώντας τη συγκεκριμένη μορφή συμβολοσειράς και Πολιτισμό.

```cpp
String System::Guid::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| format | const [String](../../string/)\& | Η μορφή προς χρήση |
| culture | const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Πολιτισμός προς χρήση |

### Return Value

Η αναπαράσταση συμβολοσειράς της τιμής GUID που αντιπροσωπεύεται από το τρέχον αντικείμενο

## Δείτε επίσης

* Typedef [SharedPtr](../../sharedptr/)
* Κλάση [String](../../string/)
* Κλάση [Guid](../)
* Κλάση [CultureInfo](../../../system.globalization/cultureinfo/)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)