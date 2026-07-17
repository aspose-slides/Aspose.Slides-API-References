---
title: Add()
second_title: Aspose.Slides for C++ API 参考
description: 在集合的末尾添加敏感度标签。
type: docs
weight: 27
url: /zh/aspose.slides/isensitivitylabelcollection/add/
---
## ISensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) 方法

在集合的末尾添加敏感度标签。

```cpp
virtual System::SharedPtr<ISensitivityLabel> Aspose::Slides::ISensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | 敏感度标签的 ID。 |
| siteId | [System::Guid](../../../system/guid/) | Azure Active Directory (Azure AD) 站点标识符。 |
| isEnabled | **bool** | 指示是否启用敏感度标签的标志。 |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | 敏感度标签的分配方法。 |

## ISensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) 方法

将 [SensitivityLabel](../../sensitivitylabel/) 添加到集合中。

```cpp
virtual int32_t Aspose::Slides::ISensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| label | [System::SharedPtr](../../../system/sharedptr/)\<[ISensitivityLabel](../../isensitivitylabel/)\> | 要在集合末尾添加的 [SensitivityLabel](../../sensitivitylabel/) 对象。 |

### 返回值

添加 [SensitivityLabel](../../sensitivitylabel/) 时的索引。

## 另见

* Enum [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [ISensitivityLabel](../../isensitivitylabel/)
* 类 [String](../../../system/string/)
* 类 [Guid](../../../system/guid/)
* 类 [ISensitivityLabelCollection](../)
* 命名空间 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)