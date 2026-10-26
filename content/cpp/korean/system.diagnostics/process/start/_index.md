---
title: Start()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 미리 정의된 매개변수로 프로세스를 시작합니다.
type: docs
weight: 14
url: /ko/system.diagnostics/process/start/
---
## Process::Start() 메서드

미리 정의된 매개변수로 프로세스를 시작합니다.

```cpp
bool System::Diagnostics::Process::Start()
```

## Process::Start(const String\&, const String\&) 메서드

지정된 경로와 인수로 프로세스를 시작합니다.

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const String &filename, const String &arguments=String::Empty)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | [Process](../) 경로. |
| arguments | const [String](../../../system/string/)\& | [Process](../) 매개변수. |

### 반환 값

[Object](../../../system/object/) 새로 시작된 프로세스에 연결된.

## Process::Start(const SharedPtr\<ProcessStartInfo\>\&) 메서드

지정된 경로와 인수로 프로세스를 시작합니다.

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const SharedPtr<ProcessStartInfo> &start_info)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| start_info | const [SharedPtr](../../../system/sharedptr/)\<[ProcessStartInfo](../../processstartinfo/)\>\& | 시작할 프로세스에 대한 정보. |

### 반환 값

[Object](../../../system/object/) 새로 시작된 프로세스에 연결된.

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Process](../)
* 클래스 [String](../../../system/string/)
* 클래스 [ProcessStartInfo](../../processstartinfo/)
* 네임스페이스 [System::Diagnostics](../../)
* Library [Aspose.Slides](../../../)