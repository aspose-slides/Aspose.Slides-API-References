---
title: Trace
second_title: Aspose.Slides for C++ API 레퍼런스
description: 디버거 트레이스(있는 경우)에 접근하기 위한 인터페이스를 제공합니다. 디버그 모드에서만 작동합니다. 이는 인스턴스 서비스를 제공하지 않는 정적 타입입니다. 어떠한 방법으로도 해당 타입의 인스턴스를 생성해서는 안 됩니다.
type: docs
weight: 131
url: /ko/system.diagnostics/trace/
---
## Trace struct


디버거 트레이스에 접근하기 위한 인터페이스를 제공합니다(있는 경우). [Debug](../debug/) 모드에서만 동작합니다. 이는 인스턴스 서비스를 제공하지 않는 정적 타입입니다. 어떠한 방법으로도 해당 타입의 인스턴스를 생성해서는 안 됩니다.

```cpp
class Trace
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| static void [Flush](./flush/)() | 출력 버퍼를 플러시하고, 버퍼링된 데이터가 리스너에게 기록되도록 합니다. |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | 디버거 트레이스에 라인을 씁니다. |
## 참고

* 네임스페이스 [System::Diagnostics](../)
* 라이브러리 [Aspose.Slides](../../)