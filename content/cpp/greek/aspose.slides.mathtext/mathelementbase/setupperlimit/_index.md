---
title: SetUpperLimit()
second_title: Aspose.Slides για C++ Αναφορά API
description: Λαμβάνει άνω όριο
type: docs
weight: 131
url: /el/aspose.slides.mathtext/mathelementbase/setupperlimit/
---
## MathElementBase::SetUpperLimit(System::SharedPtr\<IMathElement\>) μέθοδος

Λαμβάνει το άνω όριο

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetUpperLimit(System::SharedPtr<IMathElement> limit) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | όριο |

### Τιμή επιστροφής

Νέα παρουσία τύπου [IMathLimit](../../imathlimit/)
## Σχόλια



Παράδειγμα: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitValue = System::MakeObject<MathematicalText>(u"y?>1");
auto limitElement = baseElement->SetUpperLimit(limitValue);
```

## MathElementBase::SetUpperLimit(System::String) μέθοδος

Λαμβάνει το άνω όριο

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetUpperLimit(System::String limit) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | όριο |

### Τιμή επιστροφής

Νέα παρουσία τύπου [IMathLimit](../../imathlimit/)
## Σχόλια



Παράδειγμα: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitElement = baseElement->SetUpperLimit(u"y?>1");
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathLimit](../../imathlimit/)
* Κλάση [IMathElement](../../imathelement/)
* Κλάση [MathElementBase](../)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)