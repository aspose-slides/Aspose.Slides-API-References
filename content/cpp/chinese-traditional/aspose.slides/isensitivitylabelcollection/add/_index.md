---
title: Add()
second_title: Aspose.Slides for C++ API 參考
description: 在集合的末端加入靈敏度標籤。
type: docs
weight: 27
url: /zh-hant/aspose.slides/isensitivitylabelcollection/add/
---
## ISensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) 方法

在集合的末端加入靈敏度標籤。

```cpp
virtual System::SharedPtr<ISensitivityLabel> Aspose::Slides::ISensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | 靈敏度標籤的 ID。 |
| siteId | [System::Guid](../../../system/guid/) | Azure Active Directory (Azure AD) 站點識別碼。 |
| isEnabled | **bool** | 表示此靈敏度標籤是否已啟用的旗標。 |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | 靈敏度標籤的指派方法。 |

## ISensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) 方法

將 [SensitivityLabel](../../sensitivitylabel/) 新增至集合。

```cpp
virtual int32_t Aspose::Slides::ISensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| label | [System::SharedPtr](../../../system/sharedptr/)\<[ISensitivityLabel](../../isensitivitylabel/)\> | 要在集合末端新增的 [SensitivityLabel](../../sensitivitylabel/) 物件。 |

### 回傳值

已加入 [SensitivityLabel](../../sensitivitylabel/) 的索引位置。

## 另請參閱

* 列舉 [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [ISensitivityLabel](../../isensitivitylabel/)
* 類別 [String](../../../system/string/)
* 類別 [Guid](../../../system/guid/)
* 類別 [ISensitivityLabelCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)