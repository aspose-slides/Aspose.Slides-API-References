---
title: Enter()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 개체에 대한 배타적 잠금을 획득합니다.
type: docs
weight: 1
url: /ko/system.threading/monitor/enter/
---
## Monitor::Enter(const SharedPtr\<Object\>\&) 메서드


지정된 개체에 대한 배타적 잠금을 획득합니다.

```cpp
static void System::Threading::Monitor::Enter(const SharedPtr<Object> &obj)
```


### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 모니터 잠금을 획득할 객체입니다. |

## Monitor::Enter(const System::SharedPtr\<Object\>\&, bool\&) 메서드


지정된 개체에 대한 배타적 잠금을 획득하고, 잠금이 획득되었는지를 나타내는 값을 원자적으로 설정합니다.

```cpp
static void System::Threading::Monitor::Enter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Monitor](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)