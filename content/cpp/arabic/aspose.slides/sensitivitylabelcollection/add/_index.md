---
title: Add()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يضيف تصنيف الحساسية في نهاية المجموعة.
type: docs
weight: 27
url: /ar/aspose.slides/sensitivitylabelcollection/add/
---
## SensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) طريقة


يضيف تصنيف الحساسية في نهاية المجموعة.

```cpp
System::SharedPtr<ISensitivityLabel> Aspose::Slides::SensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType) override
```


### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | معرّف تصنيف الحساسية. |
| siteId | [System::Guid](../../../system/guid/) | معرّف موقع Azure Active Directory (Azure AD). |
| isEnabled | **bool** | علامة تشير إلى ما إذا كان تصنيف الحساسية مفعلاً. |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | طريقة تعيين تصنيف الحساسية. |

## SensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) طريقة


يضيف [SensitivityLabel](../../sensitivitylabel/) إلى المجموعة.

```cpp
int32_t Aspose::Slides::SensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label) override
```


### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| label | [System::SharedPtr](../../../system/sharedptr/)\<[ISensitivityLabel](../../isensitivitylabel/)\> | الكائن [SensitivityLabel](../../sensitivitylabel/) المراد إضافته في نهاية المجموعة. |

### قيمة الإرجاع

الفهرس الذي أضيف فيه [SensitivityLabel](../../sensitivitylabel/).

## انظر أيضًا

* تعداد [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [ISensitivityLabel](../../isensitivitylabel/)
* فئة [String](../../../system/string/)
* فئة [Guid](../../../system/guid/)
* فئة [SensitivityLabelCollection](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)