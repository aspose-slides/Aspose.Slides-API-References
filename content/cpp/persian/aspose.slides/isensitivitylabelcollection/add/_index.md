---
title: Add()
second_title: مرجع API Aspose.Slides برای C++
description: برچسب حساسیت را در انتهای مجموعه اضافه می‌کند.
type: docs
weight: 27
url: /fa/aspose.slides/isensitivitylabelcollection/add/
---
## ISensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) متد

برچسب حساسیت را در انتهای مجموعه اضافه می‌کند.

```cpp
virtual System::SharedPtr<ISensitivityLabel> Aspose::Slides::ISensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType)=0
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | شناسه برچسب حساسیت. |
| siteId | [System::Guid](../../../system/guid/) | شناسه سایت Azure Active Directory (Azure AD). |
| isEnabled | **bool** | پرچمی که نشان می‌دهد برچسب حساسیت فعال است. |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | روش انتساب برچسب حساسیت. |

## ISensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) متد

یک [SensitivityLabel](../../sensitivitylabel/) را به مجموعه اضافه می‌کند.

```cpp
virtual int32_t Aspose::Slides::ISensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label)=0
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| label | [System::SharedPtr](../../../system/sharedptr/)\<[ISensitivityLabel](../../isensitivitylabel/)\> | شیء [SensitivityLabel](../../sensitivitylabel/) که در انتهای مجموعه اضافه می‌شود. |

### مقدار بازگشتی

شاخصی که [SensitivityLabel](../../sensitivitylabel/) در آن اضافه شد.

## موارد مرتبط

* Enum [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISensitivityLabel](../../isensitivitylabel/)
* Class [String](../../../system/string/)
* Class [Guid](../../../system/guid/)
* Class [ISensitivityLabelCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)