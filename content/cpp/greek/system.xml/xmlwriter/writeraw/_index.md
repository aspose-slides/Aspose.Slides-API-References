---
title: WriteRaw()
second_title: Aspose.Slides για C++ Αναφορά API
description: Όταν παρακάμπτεται σε μια παράγωγη κλάση, γράφει ακατέργαστο σήμανση χειροκίνητα από ένα buffer χαρακτήρων.
type: docs
weight: 287
url: /el/system.xml/xmlwriter/writeraw/
---
## XmlWriter::WriteRaw(ArrayPtr\<char16_t\>, int32_t, int32_t) μέθοδος

Όταν παρακάμπτεται σε μια παράγωγη κλάση, γράφει ακατέργαστο σήμανση χειροκίνητα από ένα buffer χαρακτήρων.

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | Πίνακας χαρακτήρων που περιέχει το κείμενο προς εγγραφή. |
| index | **int32_t** | Η θέση μέσα στο buffer που υποδεικνύει την έναρξη του κειμένου προς εγγραφή. |
| count | **int32_t** | Ο αριθμός των χαρακτήρων προς εγγραφή. |

## XmlWriter::WriteRaw(const String\&) μέθοδος

Όταν παρακάμπτεται σε μια παράγωγη κλάση, γράφει ακατέργαστο σήμανση χειροκίνητα από μια συμβολοσειρά.

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(const String &data)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | const [String](../../../system/string/)\& | [String](../../../system/string/) που περιέχει το κείμενο προς εγγραφή. |

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlWriter](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)