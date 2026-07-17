---
title: ResultTask()
second_title: Aspose.Slides for C++ API 参考
description: 使用返回值的函数构造一个 ResultTask。
type: docs
weight: 1
url: /zh/system.threading.tasks/resulttask/resulttask/
---
## ResultTask::ResultTask(const Func\<T\>\&) 构造函数


使用返回值的函数构造一个 [ResultTask](../)。

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const Func<T> &function)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| function | const [Func](../../../system/func/)\<T\>\& | 要异步执行并返回结果的函数 |

## ResultTask::ResultTask() 构造函数


内部实现。不供用户代码使用。

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask()
```

## 备注


内部构造函数，用于创建未初始化的结果任务

## ResultTask::ResultTask(const T\&) 构造函数


内部构造函数，用于创建具有指定结果的结果任务。

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const T &result)
```

## 另请参见

* 类 [Func](../../../system/func/)
* 类 [ResultTask](../)
* 命名空间 [System::Threading::Tasks](../../)
* 库 [Aspose.Slides](../../../)