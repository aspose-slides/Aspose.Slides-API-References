---
title: TryEnter()
second_title: Aspose.Slides för C++ API-referens
description: Försöker att erhålla ett exklusivt lås på det angivna objektet Inte implementerad.
type: docs
weight: 27
url: /sv/system.threading/monitor/tryenter/
---
## Monitor::TryEnter(const SharedPtr\<Object\>\&) metod


Försöker att erhålla ett exklusivt lås på det angivna objektet Inte implementerad.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj)
```


## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, bool\&) metod


Försöker att erhålla ett exklusivt lås på det angivna objektet och atomärt ställer in ett värde som indikerar om låset togs.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```

## Monitor::TryEnter(const SharedPtr\<Object\>\&, int32_t) metod


Försöker, under det angivna antalet millisekunder, att erhålla ett exklusivt lås på det angivna objektet Inte implementerad.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```


## Monitor::TryEnter(const SharedPtr\<Object\>\&, TimeSpan) metod


Försöker, under den angivna tidsperioden, att erhålla ett exklusivt lås på det angivna objektet Inte implementerad.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, TimeSpan timeout)
```


## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, int32_t, bool\&) metod


Försöker, under den angivna tidsperioden, att erhålla ett exklusivt lås på det angivna objektet och atomärt ställer in ett värde som indikerar om låset togs.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool &lockTaken)
```

## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, TimeSpan, bool\&) metod


Försöker, under den angivna tidsperioden, att erhålla ett exklusivt lås på det angivna objektet och atomärt ställer in ett värde som indikerar om låset togs.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, TimeSpan timeout, bool &lockTaken)
```

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Object](../../../system/object/)
* Klass [Monitor](../)
* Klass [TimeSpan](../../../system/timespan/)
* Namnrymd [System::Threading](../../)
* Bibliotek [Aspose.Slides](../../../)