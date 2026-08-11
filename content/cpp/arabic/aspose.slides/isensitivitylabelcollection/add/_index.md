---
title: Add()
second_title: Aspose.Slides لمرجع API C++
description: يضيف علامة الحساسية في نهاية المجموعة.
type: docs
weight: 27
url: /ar/aspose.slides/isensitivitylabelcollection/add/
---
## ISensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) طريقة

يضيف علامة الحساسية في نهاية المجموعة.

```cpp
virtual System::SharedPtr<ISensitivityLabel> Aspose::Slides::ISensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType)=0
```

### الوسائط

| معلمة | نوع | الوصف |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | معرف علامة الحساسية. |
| siteId | [System::Guid](../../../system/guid/) | معرف موقع Azure Active Directory (Azure AD). |
| isEnabled | **bool** | علامة تشير إلى ما إذا كانت علامة الحساسية مفعلة. |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | طريقة التعيين لعلامة الحساسية. |

## ISensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) طريقة

يضيف [SensitivityLabel](../../sensitivitylabel/) إلى المجموعة.

```cpp
virtual int32_t Aspose::Slides::ISensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label)=0
```

### الوسائط

| معلمة | نوع | الوصف |
| --- | --- | --- |
| label | [System::SharedPtr](../../../system/sharedptr/)\<[ISensitivityLabel](../../isensitivitylabel/)\> | الكائن [SensitivityLabel](../../sensitivitylabel/) الذي سيُضاف في نهاية المجموعة. |

### قيمة الإرجاع

الفهرس الذي تم إضافة [SensitivityLabel](../../sensitivitylabel/) فيه.

## انظر أيضًا

* Enum [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISensitivityLabel](../../isensitivitylabel/)
* Class [String](../../../system/string/)
* Class [Guid](../../../system/guid/)
* Class [ISensitivityLabelCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)