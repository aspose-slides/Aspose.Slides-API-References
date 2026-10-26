---
title: InsertClone()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 템플릿 행의 복사본을 생성하고 테이블의 지정된 위치에 삽입합니다.
type: docs
weight: 27
url: /ko/aspose.slides/irowcollection/insertclone/
---
## IRowCollection::InsertClone(int32_t, System::SharedPtr\<IRow\>, bool) 메서드

지정된 템플릿 행의 복사본을 생성하고 테이블의 지정된 위치에 삽입합니다.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::IRowCollection::InsertClone(int32_t index, System::SharedPtr<IRow> templ, bool withAttachedRows)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 새 행의 인덱스입니다. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/)는 템플릿으로 사용됩니다. |
| withAttachedRows | **bool** | 템플릿 행에 연결된 모든 행도 복사하려면 True. |

### 반환값

삽입된 행들.

## 참조

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IRow](../../irow/)
* 클래스 [IRowCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)