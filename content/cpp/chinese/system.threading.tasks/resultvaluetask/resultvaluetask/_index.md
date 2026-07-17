---
title: ResultValueTask()
second_title: Aspose.Slides C++ API 参考
description: 构造一个空的、未初始化的 ResultValueTask。
type: docs
weight: 1
url: /zh/system.threading.tasks/resultvaluetask/resultvaluetask/
---
## ResultValueTask::ResultValueTask() 构造函数


构造一个空的、未初始化的 [ResultValueTask](../)。

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask()
```

## 备注



该任务未完成且不包含结果。尝试获取结果将抛出异常。 

## ResultValueTask::ResultValueTask(const T\&) 构造函数


构造一个已完成的 [ResultValueTask](../)，并使用指定的结果。

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const T &result)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| result | const T\& | 要包装在已完成任务中的结果值。 |
## 备注



此操作创建一个成功完成的任务，并立即返回该值。 

## ResultValueTask::ResultValueTask(const RTaskPtr\<T\>\&) 构造函数


从指向 ResultTask<T> 的共享指针构造一个 [ResultValueTask](../)。

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const RTaskPtr<T> &task)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| task | const [RTaskPtr](../../../system/rtaskptr/)\<T\>\& | 要包装的任务。为空时表示空任务。 |
## 备注



[ResultValueTask](../) 将表示提供的任务的状态和结果。 

## 另见

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* 类 [ResultValueTask](../)
* 命名空间 [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)