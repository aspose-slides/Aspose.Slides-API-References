---
title: InsertClone()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 템플릿 행의 복사본을 생성하고 테이블의 지정된 위치에 삽입합니다.
type: docs
weight: 66
url: /ko/aspose.slides/rowcollection/insertclone/
---
## RowCollection::InsertClone(int32_t, System::SharedPtr\<IRow\>, bool) 메서드

지정된 템플릿 행의 복사본을 생성하고 테이블의 지정된 위치에 삽입합니다.

```cpp
System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::RowCollection::InsertClone(int32_t index, System::SharedPtr<IRow> templ, bool withAttachedRows) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 새 행의 인덱스입니다. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/)는 템플릿으로 사용됩니다. |
| withAttachedRows | **bool** | 템플릿 행에 연결된 모든 행도 복사하려면 true를 설정합니다. |

### 반환 값

삽입된 행.

## 참조

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IRow](../../irow/)
* 클래스 [RowCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)