---
title: MergeCells()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 인접 셀을 병합합니다.
type: docs
weight: 261
url: /ko/aspose.slides/itable/mergecells/
---
## ITable::MergeCells(System::SharedPtr\<ICell\>, System::SharedPtr\<ICell\>, bool) method

인접 셀을 병합합니다.

```cpp
virtual System::SharedPtr<ICell> Aspose::Slides::ITable::MergeCells(System::SharedPtr<ICell> cell1, System::SharedPtr<ICell> cell2, bool allowSplitting)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| cell1 | [System::SharedPtr](../../../system/sharedptr/)\<[ICell](../../icell/)\> | [Cell](../../cell/) 병합할. |
| cell2 | [System::SharedPtr](../../../system/sharedptr/)\<[ICell](../../icell/)\> | [Cell](../../cell/) 병합할. |
| allowSplitting | **bool** | 셀 분할을 허용하려면 True. |

### 반환 값

병합된 셀.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICell](../../icell/)
* Class [ITable](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)