---
title: Add()
second_title: Aspose.Slides για C++ API Αναφορά
description: Προσθέτει την ετικέτα ευαισθησίας στο τέλος της συλλογής.
type: docs
weight: 27
url: /el/aspose.slides/sensitivitylabelcollection/add/
---
## SensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) method

Προσθέτει την ετικέτα ευαισθησίας στο τέλος της συλλογής.

```cpp
System::SharedPtr<ISensitivityLabel> Aspose::Slides::SensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | Το αναγνωριστικό της ετικέτας ευαισθησίας. |
| siteId | [System::Guid](../../../system/guid/) | Το αναγνωριστικό του ιστότοπου Azure Active Directory (Azure AD). |
| isEnabled | **bool** | Σημαία που υποδεικνύει αν η ετικέτα ευαισθησίας είναι ενεργοποιημένη. |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | Η μέθοδος ανάθεσης για την ετικέτα ευαισθησίας. |

## SensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) method

Προσθέτει ένα [SensitivityLabel](../../sensitivitylabel/) στη συλλογή.

```cpp
int32_t Aspose::Slides::SensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| label | [System::SharedPtr](../../../system/sharedptr/)\<[ISensitivityLabel](../../isensitivitylabel/)\> | Το αντικείμενο [SensitivityLabel](../../sensitivitylabel/) που θα προστεθεί στο τέλος της συλλογής. |

### Τιμή Επιστροφής

Ο δείκτης στον οποίο προστέθηκε το [SensitivityLabel](../../sensitivitylabel/).

## Δείτε επίσης

* Enum [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ISensitivityLabel](../../isensitivitylabel/)
* Κλάση [String](../../../system/string/)
* Κλάση [Guid](../../../system/guid/)
* Κλάση [SensitivityLabelCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)