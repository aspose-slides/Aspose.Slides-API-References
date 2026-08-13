---
title: InsertClone()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 템플릿 열의 복사본을 생성하고 테이블의 지정된 위치에 삽입합니다.
type: docs
weight: 27
url: /ko/aspose.slides/icolumncollection/insertclone/
---
## IColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) method


지정된 템플릿 열의 복사본을 생성하고 테이블의 지정된 위치에 삽입합니다.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 새 열의 인덱스. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) 템플릿으로 사용됩니다. |
| withAttachedColumns | **bool** | True를 지정하면 템플릿 열에 연결된 모든 열도 복사합니다. |

### 반환 값

삽입된 열.

## 관련 항목

* 타입 정의 [ArrayPtr](../../../system/arrayptr/)
* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IColumn](../../icolumn/)
* 클래스 [IColumnCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)