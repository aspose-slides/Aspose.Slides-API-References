---
title: AddClone()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 템플릿 행의 복사본을 생성하고 테이블 하단에 삽입합니다.
type: docs
weight: 53
url: /ko/aspose.slides/columncollection/addclone/
---
## ColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) method


지정된 템플릿 행의 복사본을 만들어 테이블 하단에 삽입합니다.

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) 템플릿으로 사용됩니다. |
| withAttachedColumns | **bool** | 템플릿 행에 연결된 모든 열을 복사하려면 true. |

### 반환 값

추가된 열.

## 참조

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IColumn](../../icolumn/)
* 클래스 [ColumnCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)