---
title: SetUpperLimit()
second_title: Aspose.Slides για την αναφορά API C++
description: Λαμβάνει το άνω όριο
type: docs
weight: 144
url: /el/aspose.slides.mathtext/imathelement/setupperlimit/
---
## IMathElement::SetUpperLimit(System::SharedPtr\<IMathElement\>) μέθοδος


Λαμβάνει το άνω όριο

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetUpperLimit(System::SharedPtr<IMathElement> limit)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | όριο |

### Τιμή Επιστροφής

Νέα παρουσία του τύπου [IMathLimit](../../imathlimit/)
## Σχόλια



Παράδειγμα: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitValue = System::MakeObject<MathematicalText>(u"y?>1");
auto limitElement = baseElement->SetUpperLimit(limitValue);
```

## IMathElement::SetUpperLimit(System::String) μέθοδος


Λαμβάνει το άνω όριο

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetUpperLimit(System::String limit)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | όριο |

### Τιμή Επιστροφής

Νέα παρουσία του τύπου [IMathLimit](../../imathlimit/)
## Σχόλια



Παράδειγμα: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitElement = baseElement->SetUpperLimit(u"y?>1");
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathLimit](../../imathlimit/)
* Κλάση [IMathElement](../)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)