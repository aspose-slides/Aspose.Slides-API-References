---
title: InsertTable()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새 테이블을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다.
type: docs
weight: 482
url: /ko/aspose.slides/shapecollection/inserttable/
---
## ShapeCollection::InsertTable(int32_t, float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) method

새 테이블을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다.

```cpp
System::SharedPtr<ITable> Aspose::Slides::ShapeCollection::InsertTable(int32_t index, float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 테이블을 삽입할 0부터 시작하는 인덱스입니다. |
| x | **float** | 포인트 단위의 테이블 x 좌표입니다. |
| y | **float** | 포인트 단위의 테이블 y 좌표입니다. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | 테이블 열의 너비를 포인트 단위로 나타내는 double 배열입니다. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | 테이블 행의 높이를 포인트 단위로 나타내는 double 배열입니다. |

### 반환값

새로 생성된 [ITable](../../itable/).

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [ITable](../../itable/)
* 클래스 [ShapeCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)