---
title: Add()
second_title: Aspose.Slides for C++ API 參考
description: 在集合的末端新增敏感度標籤。
type: docs
weight: 27
url: /zh-hant/aspose.slides/sensitivitylabelcollection/add/
---
## SensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) method


在集合的末端新增敏感度標籤。

```cpp
System::SharedPtr<ISensitivityLabel> Aspose::Slides::SensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | 敏感度標籤的 id。 |
| siteId | [System::Guid](../../../system/guid/) | Azure Active Directory (Azure AD) 網站識別碼。 |
| isEnabled | **bool** | 指示是否已啟用敏感度標籤的旗標。 |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | 敏感度標籤的指派方法。 |

## SensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) method


將 [SensitivityLabel](../../sensitivitylabel/) 新增至集合。

```cpp
int32_t Aspose::Slides::SensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| label | [System::SharedPtr](../../../system/sharedptr/)\<[ISensitivityLabel](../../isensitivitylabel/)\> | 要在集合末端新增的 [SensitivityLabel](../../sensitivitylabel/) 物件。 |

### 傳回值

[SensitivityLabel](../../sensitivitylabel/) 被新增的索引位置。

## 另請參閱

* 列舉 [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [ISensitivityLabel](../../isensitivitylabel/)
* 類別 [String](../../../system/string/)
* 類別 [Guid](../../../system/guid/)
* 類別 [SensitivityLabelCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)