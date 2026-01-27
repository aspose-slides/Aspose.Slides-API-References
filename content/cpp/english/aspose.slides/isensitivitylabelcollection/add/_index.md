---
title: Add()
second_title: Aspose.Slides for C++ API Reference
description: Adds the sensitivity label at the end of the collection.
type: docs
weight: 27
url: /aspose.slides/isensitivitylabelcollection/add/
---
## ISensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) method


Adds the sensitivity label at the end of the collection.

```cpp
virtual System::SharedPtr<ISensitivityLabel> Aspose::Slides::ISensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | The id of sensitivity label. |
| siteId | [System::Guid](../../../system/guid/) | The Azure Active Directory (Azure AD) site identifier. |
| isEnabled | **bool** | Flag indicates whether the sensitivity label is enabled. |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | The assignment method for the sensitivity label. |

## ISensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) method


Adds a [SensitivityLabel](../../sensitivitylabel/) to the collection.

```cpp
virtual int32_t Aspose::Slides::ISensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| label | [System::SharedPtr](../../../system/sharedptr/)\<[ISensitivityLabel](../../isensitivitylabel/)\> | The [SensitivityLabel](../../sensitivitylabel/) object to be added at the end of the collection. |

### Return Value

The index at which the [SensitivityLabel](../../sensitivitylabel/) was added.

## See Also

* Enum [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISensitivityLabel](../../isensitivitylabel/)
* Class [String](../../../system/string/)
* Class [Guid](../../../system/guid/)
* Class [ISensitivityLabelCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)