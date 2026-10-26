---
title: Add()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 컬렉션 끝에 민감도 레이블을 추가합니다.
type: docs
weight: 27
url: /ko/aspose.slides/isensitivitylabelcollection/add/
---
## ISensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) method


컬렉션 끝에 민감도 레이블을 추가합니다.

```cpp
virtual System::SharedPtr<ISensitivityLabel> Aspose::Slides::ISensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType)=0
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | 민감도 레이블의 ID. |
| siteId | [System::Guid](../../../system/guid/) | Azure Active Directory(Azure AD) 사이트 식별자. |
| isEnabled | **bool** | 민감도 레이블이 활성화되어 있는지 나타내는 플래그. |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | 민감도 레이블에 대한 할당 방법. |

## ISensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) method


컬렉션에 [SensitivityLabel](../../sensitivitylabel/)를 추가합니다.

```cpp
virtual int32_t Aspose::Slides::ISensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label)=0
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| label | [System::SharedPtr](../../../system/sharedptr/)\<[ISensitivityLabel](../../isensitivitylabel/)\> | 컬렉션 끝에 추가될 [SensitivityLabel](../../sensitivitylabel/) 객체. |

### 반환 값

[SensitivityLabel](../../sensitivitylabel/)이(가) 추가된 인덱스.

## 참고

* Enum [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISensitivityLabel](../../isensitivitylabel/)
* Class [String](../../../system/string/)
* Class [Guid](../../../system/guid/)
* Class [ISensitivityLabelCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)