---
title: Add()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクションの末尾に感度ラベルを追加します。
type: docs
weight: 27
url: /ja/aspose.slides/isensitivitylabelcollection/add/
---
## ISensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) メソッド

コレクションの末尾に感度ラベルを追加します。

```cpp
virtual System::SharedPtr<ISensitivityLabel> Aspose::Slides::ISensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | 感度ラベルの ID。 |
| siteId | [System::Guid](../../../system/guid/) | Azure Active Directory (Azure AD) サイト識別子。 |
| isEnabled | **bool** | 感度ラベルが有効かどうかを示すフラグ。 |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | 感度ラベルの割り当て方法。 |

## ISensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) メソッド

コレクションに [SensitivityLabel](../../sensitivitylabel/) を追加します。

```cpp
virtual int32_t Aspose::Slides::ISensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label)=0
```

### 引数

| パラメーター | 型 | 説明 |
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
* クラス [ISensitivityLabelCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)