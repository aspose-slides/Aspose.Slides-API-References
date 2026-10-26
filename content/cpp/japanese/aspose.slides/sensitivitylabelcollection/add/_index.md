---
title: Add()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクションの末尾に機密ラベルを追加します。
type: docs
weight: 27
url: /ja/aspose.slides/sensitivitylabelcollection/add/
---
## SensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) メソッド

コレクションの末尾に機密ラベルを追加します。

```cpp
System::SharedPtr<ISensitivityLabel> Aspose::Slides::SensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | 機密ラベルの ID。 |
| siteId | [System::Guid](../../../system/guid/) | Azure Active Directory (Azure AD) のサイト識別子。 |
| isEnabled | **bool** | 機密ラベルが有効かどうかを示すフラグ。 |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | 機密ラベルの割り当て方法。 |

## SensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) メソッド

コレクションに [SensitivityLabel](../../sensitivitylabel/) を追加します。

```cpp
int32_t Aspose::Slides::SensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| label | [System::SharedPtr](../../../system/sharedptr/)\<[ISensitivityLabel](../../isensitivitylabel/)\> | コレクションの末尾に追加される [SensitivityLabel](../../sensitivitylabel/) オブジェクト。 |

### 戻り値

[SensitivityLabel](../../sensitivitylabel/) が追加されたインデックス。

## 参照

* 列挙型 [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [ISensitivityLabel](../../isensitivitylabel/)
* クラス [String](../../../system/string/)
* クラス [Guid](../../../system/guid/)
* クラス [SensitivityLabelCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)