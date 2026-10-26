---
title: SetRange()
second_title: Aspose.Slides for C++ API 참조
description: 차트 데이터 범위를 설정합니다. 새 데이터 범위를 기반으로 시리즈와 카테고리가 업데이트됩니다. 데이터 범위의 시리즈 수가 차트 데이터의 시리즈 수보다 많으면 현재 컬렉션의 마지막 시리즈와 동일한 유형의 추가 시리즈가 컬렉션 끝에 추가됩니다.
type: docs
weight: 170
url: /ko/aspose.slides.charts/chartdata/setrange/
---
## ChartData::SetRange(System::String) 메서드


차트 데이터 범위를 설정합니다. 새 데이터 범위를 기준으로 시리즈와 카테고리가 업데이트됩니다. 데이터 범위의 시리즈 수가 차트 데이터의 시리즈 수보다 많으면 현재 컬렉션의 마지막 시리즈와 동일한 유형의 추가 시리즈가 컬렉션 끝에 추가됩니다.

```cpp
void Aspose::Slides::Charts::ChartData::SetRange(System::String formula) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | 셀 데이터 범위 수식입니다. E.g: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [ChartData](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)