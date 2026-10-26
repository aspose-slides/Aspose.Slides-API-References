---
title: InsertClone()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 템플릿 열의 복사본을 생성하고 표의 지정된 위치에 삽입합니다.
type: docs
weight: 66
url: /ko/aspose.slides/columncollection/insertclone/
---
## ColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) 메서드

지정된 템플릿 열의 복사본을 생성하고 표의 지정된 위치에 삽입합니다.

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 새 열의 인덱스. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) 템플릿으로 사용됩니다. |
| withAttachedColumns | **bool** | 템플릿 열에 연결된 모든 열도 복사하려면 True. |

### 반환값

삽입된 열.

## 참조

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IColumn](../../icolumn/)
* Class [ColumnCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)