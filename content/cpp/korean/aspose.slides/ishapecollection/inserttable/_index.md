---
title: InsertTable()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새로운 테이블을 생성하고 지정된 인덱스에 shape 컬렉션에 삽입합니다.
type: docs
weight: 443
url: /ko/aspose.slides/ishapecollection/inserttable/
---
## IShapeCollection::InsertTable(int32_t, float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) 메서드

새로운 테이블을 생성하고 지정된 인덱스에 shape 컬렉션에 삽입합니다.

```cpp
virtual System::SharedPtr<ITable> Aspose::Slides::IShapeCollection::InsertTable(int32_t index, float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 테이블을 삽입할 0부터 시작하는 인덱스. |
| x | **float** | 테이블의 x좌표(포인트 단위). |
| y | **float** | 테이블의 y좌표(포인트 단위). |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | 테이블 열의 너비를 포인트 단위로 나타내는 double 배열. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | 테이블 행의 높이를 포인트 단위로 나타내는 double 배열. |

### 반환값

새로 생성된 [ITable](../../itable/).

## 또 보기

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [ITable](../../itable/)
* 클래스 [IShapeCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)