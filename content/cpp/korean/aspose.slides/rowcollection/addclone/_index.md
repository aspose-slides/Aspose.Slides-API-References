---
title: AddClone()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 템플릿 행의 복사본을 생성하고 이를 테이블 하단에 삽입합니다.
type: docs
weight: 53
url: /ko/aspose.slides/rowcollection/addclone/
---
## RowCollection::AddClone(System::SharedPtr\<IRow\>, bool) 메서드

지정된 템플릿 행의 복사본을 생성하고 이를 테이블 하단에 삽입합니다.

```cpp
System::ArrayPtr<System::SharedPtr<IRrow>> Aspose::Slides::RowCollection::AddClone(System::SharedPtr<IRow> templ, bool withAttachedRows) override
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) 은 템플릿으로 사용됩니다. |
| withAttachedRows | **bool** | 템플릿 행에 연결된 모든 행도 복사하려면 True. |

### 반환값

추가된 행.

## 관련 항목

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IRow](../../irow/)
* 클래스 [RowCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)