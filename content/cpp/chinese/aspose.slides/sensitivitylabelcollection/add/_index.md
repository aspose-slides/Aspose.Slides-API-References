---
title: Add()
second_title: Aspose.Slides C++ API 参考
description: 在集合的末尾添加敏感标签。
type: docs
weight: 27
url: /zh/aspose.slides/sensitivitylabelcollection/add/
---
## SensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) 方法


在集合的末尾添加敏感标签。

```cpp
System::SharedPtr<ISensitivityLabel> Aspose::Slides::SensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | 敏感标签的标识。 |
| siteId | [System::Guid](../../../system/guid/) | Azure Active Directory (Azure AD) 站点标识符。 |
| isEnabled | **bool** | 标志指示是否启用敏感标签。 |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | 敏感标签的分配方法。 |

## SensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) 方法


向集合中添加一个 [SensitivityLabel](../../sensitivitylabel/)。

```cpp
int32_t Aspose::Slides::SensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| label | [System::SharedPtr](../../../system/sharedptr/)\<[ISensitivityLabel](../../isensitivitylabel/)\> | 要在集合末尾添加的 [SensitivityLabel](../../sensitivitylabel/) 对象。 |

### 返回值

[SensitivityLabel](../../sensitivitylabel/) 被添加的位置索引。

## 另请参见

* Enum [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISensitivityLabel](../../isensitivitylabel/)
* Class [String](../../../system/string/)
* Class [Guid](../../../system/guid/)
* Class [SensitivityLabelCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)