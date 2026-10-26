---
title: IOControl()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 소켓에 대한 저수준 운영 모드를 설정합니다.
type: docs
weight: 703
url: /ko/system.net.sockets/socket/iocontrol/
---
## Socket::IOControl(int32_t, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) 메서드

소켓에 대한 저수준 운영 모드를 설정합니다.

```cpp
int32_t System::Net::Sockets::Socket::IOControl(int32_t ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ioControlCode | **int32_t** | 수행할 작업의 제어 코드입니다. |
| optionInValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 입력 데이터를 포함하는 바이트 배열입니다. |
| optionOutValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 출력 데이터를 포함하는 바이트 배열입니다. |

### 반환 값

**optionOutValue** 매개변수에 있는 바이트 수.

## Socket::IOControl(IOControlCode, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) 메서드

소켓에 대한 저수준 운영 모드를 설정합니다.

```cpp
int32_t System::Net::Sockets::Socket::IOControl(IOControlCode ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ioControlCode | [IOControlCode](../../iocontrolcode/) | 수행할 작업의 제어 코드입니다. |
| optionInValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 입력 데이터를 포함하는 바이트 배열입니다. |
| optionOutValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 출력 데이터를 포함하는 바이트 배열입니다. |

### 반환 값

**optionOutValue** 매개변수에 있는 바이트 수.

## 또 보기

* 열거형 [IOControlCode](../../iocontrolcode/)
* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [Socket](../)
* 네임스페이스 [System::Net::Sockets](../../)
* 라이브러리 [Aspose.Slides](../../../)