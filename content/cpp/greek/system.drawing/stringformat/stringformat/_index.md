---
title: StringFormat()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί ένα νέο αντικείμενο της κλάσης StringFormat.
type: docs
weight: 1
url: /el/system.drawing/stringformat/stringformat/
---
## StringFormat::StringFormat() κατασκευαστής

Δημιουργεί ένα νέο αντικείμενο της κλάσης [StringFormat](../).

```cpp
System::Drawing::StringFormat::StringFormat()
```

## StringFormat::StringFormat(StringFormatFlags, int32_t) κατασκευαστής

Δημιουργεί ένα νέο αντικείμενο της κλάσης [StringFormat](../) με τις καθορισμένες σημαίες μορφής και τη γλώσσα.

```cpp
System::Drawing::StringFormat::StringFormat(StringFormatFlags options, int32_t language=0)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| options | [StringFormatFlags](../../stringformatflags/) | Ένας συνδυασμός bitwise των τιμών της απαριθμητικής StringFormatFlags που καθορίζουν τη μορφή του κειμένου που θα αντιπροσωπεύει το αντικείμενο που δημιουργείται |
| language | **int32_t** | Η γλώσσα του κειμένου |

## StringFormat::StringFormat(const SharedPtr\<StringFormat\>\&) κατασκευαστής

Κατασκευαστής αντιγραφής.

```cpp
System::Drawing::StringFormat::StringFormat(const SharedPtr<StringFormat> &format)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| format | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../)\>\& | Ένα αντικείμενο [StringFormat](../) για αντιγραφή |

## Δείτε επίσης

* Απαρίθμηση [StringFormatFlags](../../stringformatflags/)
* Ορισμός τύπου [SharedPtr](../../../system/sharedptr/)
* Κλάση [StringFormat](../)
* Χώρος ονομάτων [System::Drawing](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)