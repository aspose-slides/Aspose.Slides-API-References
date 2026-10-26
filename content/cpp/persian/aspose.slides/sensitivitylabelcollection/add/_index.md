---
title: Add()
second_title: Aspose.Slides برای C++ - مرجع API
description: برچسب حساسیت را در انتهای مجموعه اضافه می‌کند.
type: docs
weight: 27
url: /fa/aspose.slides/sensitivitylabelcollection/add/
---
## SensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) method

برچسب حساسیت را در انتهای مجموعه اضافه می‌کند.

```cpp
System::SharedPtr<ISensitivityLabel> Aspose::Slides::SensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | شناسه برچسب حساسیت. |
| siteId | [System::Guid](../../../system/guid/) | شناسه سایت Azure Active Directory (Azure AD). |
| isEnabled | **bool** | پرچمی که نشان می‌دهد برچسب حساسیت فعال است یا نه. |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | روش اختصاص برچسب حساسیت. |

## SensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) method

یک [SensitivityLabel](../../sensitivitylabel/) را به مجموعه اضافه می‌کند.

```cpp
int32_t Aspose::Slides::SensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| label | [System::SharedPtr](../../../system/sharedptr/)\<[ISensitivityLabel](../../isensitivitylabel/)\> | شیء [SensitivityLabel](../../sensitivitylabel/) که در انتهای مجموعه افزوده می‌شود. |

### مقدار بازگشتی

اندیس‌ایی که [SensitivityLabel](../../sensitivitylabel/) در آن اضافه شده است.

## موارد مرتبط

* enum [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/)
* typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [ISensitivityLabel](../../isensitivitylabel/)
* کلاس [String](../../../system/string/)
* کلاس [Guid](../../../system/guid/)
* کلاس [SensitivityLabelCollection](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)