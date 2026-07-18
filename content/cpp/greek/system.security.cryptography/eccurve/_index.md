---
title: ECCurve
second_title: Αναφορά API του Aspose.Slides για C++
description: Μία ελλειπτική καμπύλη.
type: docs
weight: 716
url: /el/system.security.cryptography/eccurve/
---
## ECCurve struct

Μία ελλειπτική καμπύλη.

```cpp
class ECCurve
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| static [ECCurve](./) [CreateFromFriendlyName](./createfromfriendlyname/)(const [String](../../system/string/)\&) | Δημιουργεί μια καμπύλη από το καθορισμένο φιλικό όνομα OID. |
| static [ECCurve](./) [CreateFromOid](./createfromoid/)(const [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\>\&) | Δημιουργεί μια καμπύλη από το καθορισμένο oid. |
| static [ECCurve](./) [CreateFromValue](./createfromvalue/)(const [String](../../system/string/)\&) | Δημιουργεί μια καμπύλη από την καθορισμένη τιμή OID. |
| **bool** [get_IsCharacteristic2](./get_ischaracteristic2/)() const |  |
| **bool** [get_IsExplicit](./get_isexplicit/)() const |  |
| **bool** [get_IsNamed](./get_isnamed/)() const |  |
| **bool** [get_IsPrime](./get_isprime/)() const |  |
| [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\> [get_Oid](./get_oid/)() const | Λαμβάνει [Oid](../oid/) που αντιπροσωπεύει την ονομαστική καμπύλη. |
| void [Validate](./validate/)() const | Επικυρώνει την τρέχουσα καμπύλη. |
## Απαριθμήσεις

| Απαριθμήση | Περιγραφή |
| --- | --- |
| [ECCurveType](./eccurvetype/) | Τύπος ελλειπτικής καμπύλης. |
## Δείτε επίσης

* Namespace [System::Security::Cryptography](../)
* Library [Aspose.Slides](../../)