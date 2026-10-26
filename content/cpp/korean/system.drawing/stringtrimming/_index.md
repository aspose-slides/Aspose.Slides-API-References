---
title: StringTrimming
second_title: Aspose.Slides for C++ API 레퍼런스
description: 레이아웃 모양에 맞지 않는 문자열에서 문자를 어떻게 잘라낼지 지정합니다.
type: docs
weight: 495
url: /ko/system.drawing/stringtrimming/
---
## StringTrimming 열거형

문자열이 레이아웃 모양에 맞지 않을 경우 문자들을 어떻게 잘라낼지 지정합니다.

```cpp
enum class StringTrimming
```

### 값

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | 트리밍 없음. |
| Character | 1 | 가장 가까운 문자까지 잘라냅니다. |
| Word | 2 | 가장 가까운 단어까지 잘라냅니다. |
| EllipsisCharacter | 3 | 가장 가까운 문자까지 잘라내고 문자열 끝에 줄임표를 삽입합니다. |
| EllipsisWord | 4 | 가장 가까운 단어까지 잘라내고 문자열 끝에 줄임표를 삽입합니다. |
| EllipsisPath | 5 | 잘라낸 라인의 중간 부분을 제거하고 줄임표로 대체합니다. 가능한 한 마지막 슬래시 구분 구간을 많이 유지합니다. |

## 참고

* 네임스페이스 [System::Drawing](../)
* 라이브러리 [Aspose.Slides](../../)