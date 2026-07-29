---
title: Wait()
second_title: Aspose.Slides för C++ API-referens
description: Frigör låset på ett objekt och blockerar den aktuella tråden tills den återfår låset. Om det specificerade timeout-intervallet löper ut, går tråden in i körkön. Valfritt lämnar den synkroniseringsdomän för det synkroniserade sammanhanget innan väntan och återfår domänen efteråt. Inte implementerad.
type: docs
weight: 53
url: /sv/system.threading/monitor/wait/
---
## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t, bool) metod

Frigör låset på ett objekt och blockerar den aktuella tråden tills den återfår låset. Om det specificerade timeout-intervallet löper ut, går tråden in i körkön. Valfritt lämnar den synkroniseringsdomän för det synkroniserade sammanhanget innan väntan och återfår domänen efteråt. Inte implementerad.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool exitContext)
```
## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan, bool) metod

Frigör låset på ett objekt och blockerar den aktuella tråden tills den återfår låset. Om det specificerade timeout-intervallet löper ut, går tråden in i körkön. Valfritt lämnar den synkroniseringsdomän för det synkroniserade sammanhanget innan väntan och återfår domänen efteråt. Inte implementerad.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout, bool exitContext)
```
## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t) metod

Frigör låset på ett objekt och blockerar den aktuella tråden tills den återfår låset. Om det specificerade timeout-intervallet löper ut, går tråden in i körkön. Inte implementerad.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```
## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan) metod

Frigör låset på ett objekt och blockerar den aktuella tråden tills den återfår låset. Om det specificerade timeout-intervallet löper ut, går tråden in i körkön. Inte implementerad.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout)
```
## Monitor::Wait(const SharedPtr\<Object\>\&) metod

Frigör låset på ett objekt och blockerar den aktuella tråden tills den återfår låset Inte implementerad.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj)
```
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Object](../../../system/object/)
* Klass [Monitor](../)
* Klass [TimeSpan](../../../system/timespan/)
* Namnrymd [System::Threading](../../)
* Library [Aspose.Slides](../../../)