---
title: Add()
second_title: Aspose.Slides for C++ API Reference
description: Adds the sensitivity label at the end of the collection.
type: docs
weight: 27
url: /aspose.slides/sensitivitylabelcollection/add/
---
## SensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) method


Adds the sensitivity label at the end of the collection.

```cpp
System::SharedPtr<ISensitivityLabel> Aspose::Slides::SensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | The id of sensitivity label. |
| siteId | [System::Guid](../../../system/guid/) | The Azure Active Directory (Azure AD) site identifier. |
| isEnabled | **bool** | Flag indicates whether the sensitivity label is enabled. |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | The assignment method for the sensitivity label. |

## SensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) method


Adds a [SensitivityLabel](../../sensitivitylabel/) to the collection.

```cpp
int32_t Aspose::Slides::SensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label) override
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
* Class [SensitivityLabelCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)