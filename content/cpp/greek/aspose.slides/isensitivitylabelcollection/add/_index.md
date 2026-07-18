---
title: Add()
second_title: Aspose.Slides για την τεκμηρίωση API C++
description: Προσθέτει την ετικέτα ευαισθησίας στο τέλος της συλλογής.
type: docs
weight: 27
url: /el/aspose.slides/isensitivitylabelcollection/add/
---
## ISensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) method

Προσθέτει την ετικέτα ευαισθησίας στο τέλος της συλλογής.

```cpp
virtual System::SharedPtr<ISensitivityLabel> Aspose::Slides::ISensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType)=0
```

### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | Το αναγνωριστικό της ετικέτας ευαισθησίας. |
| siteId | [System::Guid](../../../system/guid/) | Το αναγνωριστικό του ιστότοπου Azure Active Directory (Azure AD). |
| isEnabled | **bool** | Σημαία που υποδεικνύει αν η ετικέτα ευαισθησίας είναι ενεργοποιημένη. |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | Η μέθοδος ανάθεσης για την ετικέτα ευαισθησίας. |

## ISensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) method

Προσθέτει ένα [SensitivityLabel](../../sensitivitylabel/) στη συλλογή.

```cpp
virtual int32_t Aspose::Slides::ISensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label)=0
```

### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| label | [System::SharedPtr](../../../system/sharedptr/)\<[ISensitivityLabel](../../isensitivitylabel/)\> | Το αντικείμενο [SensitivityLabel](../../sensitivitylabel/) που θα προστεθεί στο τέλος της συλλογής. |

### Return Value

Ο δείκτης στον οποίο προστέθηκε το [SensitivityLabel](../../sensitivitylabel/).

## See Also

* Enum [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ISensitivityLabel](../../isensitivitylabel/)
* Κλάση [String](../../../system/string/)
* Κλάση [Guid](../../../system/guid/)
* Κλάση [ISensitivityLabelCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)