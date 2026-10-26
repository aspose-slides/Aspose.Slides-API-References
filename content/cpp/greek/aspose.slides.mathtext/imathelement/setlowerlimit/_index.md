---
title: SetLowerLimit()
second_title: Aspose.Slides για C++ API Αναφορά
description: Παίρνει το κατώτερο όριο
type: docs
weight: 157
url: /el/aspose.slides.mathtext/imathelement/setlowerlimit/
---
## IMathElement::SetLowerLimit(System::SharedPtr\<IMathElement\>) μέθοδος

Παίρνει το κατώτερο όριο

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetLowerLimit(System::SharedPtr<IMathElement> limit)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | όριο |

### Τιμή Επιστροφής

Νέα παρουσία τύπου [IMathLimit](../../imathlimit/)
## Σχόλια



Παράδειγμα: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitValue = System::MakeObject<MathematicalText>(u"\U0001d45b→∞");
auto limitElement = baseElement->SetLowerLimit(limitValue);
```

## IMathElement::SetLowerLimit(System::String) μέθοδος

Παίρνει το κατώτερο όριο

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetLowerLimit(System::String limit)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | όριο |

### Τιμή Επιστροφής

Νέα παρουσία τύπου [IMathLimit](../../imathlimit/)
## Σχόλια



Παράδειγμα: 
```cpp
System::SharedPtr<IMathElement> baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitElement = baseElement->SetLowerLimit(u"\U0001d45b→∞");
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathLimit](../../imathlimit/)
* Κλάση [IMathElement](../)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)