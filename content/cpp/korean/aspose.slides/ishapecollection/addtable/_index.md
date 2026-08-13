---
title: AddTable()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새 테이블을 만들고 이를 shape 컬렉션의 끝에 추가합니다.
type: docs
weight: 430
url: /ko/aspose.slides/ishapecollection/addtable/
---
## IShapeCollection::AddTable(float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) 메서드

새 테이블을 만들고 이를 shape 컬렉션의 끝에 추가합니다.

```cpp
virtual System::SharedPtr<ITable> Aspose::Slides::IShapeCollection::AddTable(float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | **float** | 테이블의 x 좌표(포인트 단위). |
| y | **float** | 테이블의 y 좌표(포인트 단위). |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | 테이블 열의 너비를 나타내는 double 배열(포인트 단위). |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | 테이블 행의 높이를 나타내는 double 배열(포인트 단위). |

### 반환값

새로 만든 [ITable](../../itable/).

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ITable](../../itable/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)