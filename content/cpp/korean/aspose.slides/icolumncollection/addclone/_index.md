---
title: AddClone()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 템플릿 행의 복사본을 생성하고 테이블 하단에 삽입합니다.
type: docs
weight: 14
url: /ko/aspose.slides/icolumncollection/addclone/
---
## IColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) 메서드

지정된 템플릿 행의 복사본을 생성하고 테이블 하단에 삽입합니다.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/)는 템플릿으로 사용됩니다. |
| withAttachedColumns | **bool** | 템플릿 행에 연결된 모든 열도 복사하려면 true를 지정합니다. |

### 반환값

추가된 열.

## 참조

* 타입 정의 [ArrayPtr](../../../system/arrayptr/)
* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IColumn](../../icolumn/)
* 클래스 [IColumnCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)