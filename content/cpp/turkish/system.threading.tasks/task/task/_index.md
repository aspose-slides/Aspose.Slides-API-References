---
title: Task()
second_title: Aspose.Slides for C++ API Referansı
description: Bir eylemle yürütülecek bir Task oluşturur.
type: docs
weight: 1
url: /tr/system.threading.tasks/task/task/
---
## Task::Task(const Action<>\&) constructor

Bir [Task](../) oluşturur ve yürütülecek bir eylem alır.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | Asenkron olarak yürütülecek eylem |

## Task::Task(const Action<>\&, const CancellationToken\&) constructor

Bir [Task](../) oluşturur ve bir eylem ile iptal belirteci alır.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action, const CancellationToken &cancellationToken)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | Asenkron olarak yürütülecek eylem |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | İptal isteklerini izlemek için kullanılan belirteç |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&) constructor

Bir [Task](../) oluşturur ve durumlu bir eylem ile durum nesnesi alır.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | Durum nesnesi kabul eden eylem |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Eyleme geçirilen kullanıcı tanımlı durum nesnesi |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&, const CancellationToken\&) constructor

Bir [Task](../) oluşturur ve durumlu eylem, durum ve iptal belirteci alır.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state, const CancellationToken &cancellationToken)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | Durum nesnesi kabul eden eylem |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Eyleme geçirilen kullanıcı tanımlı durum nesnesi |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | İptal isteklerini izlemek için kullanılan belirteç |

## Task::Task() constructor

Başlatılmamış görevler oluşturmak için dahili kurucu.

```cpp
System::Threading::Tasks::Task::Task()
```

## Bkz

* Typedef [Action](../../../system/action/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Task](../)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [Object](../../../system/object/)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)