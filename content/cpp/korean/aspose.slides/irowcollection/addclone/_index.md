---
title: AddClone()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 템플릿 행의 복사본을 생성하고 표의 맨 아래에 삽입합니다.
type: docs
weight: 14
url: /ko/aspose.slides/irowcollection/addclone/
---
## IRowCollection::AddClone(System::SharedPtr\<IRow\>, bool) 메서드


지정된 템플릿 행의 복사본을 생성하고 표의 맨 아래에 삽입합니다.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::IRowCollection::AddClone(System::SharedPtr<IRow> templ, bool withAttachedRows)=0
```


### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) 템플릿으로 사용됩니다. |
| withAttachedRows | **bool** | 템플릿 행에 연결된 모든 행을 복사하려면 True. |

### Return Value

추가된 행.

## See Also

* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IRow](../../irow/)
* 클래스 [IRowCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)