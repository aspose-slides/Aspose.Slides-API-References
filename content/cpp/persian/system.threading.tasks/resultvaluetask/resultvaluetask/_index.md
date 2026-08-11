---
title: ResultValueTask()
second_title: Aspose.Slides برای مرجع API C++
description: یک ResultValueTask خالی و بدون مقدار اولیه می‌سازد.
type: docs
weight: 1
url: /fa/system.threading.tasks/resultvaluetask/resultvaluetask/
---
## ResultValueTask::ResultValueTask() سازنده

یک [ResultValueTask](../) خالی و بدون مقدار اولیه می‌سازد.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask()
```

## توضیحات

وظیفه تکمیل نشده است و هیچ نتیجی ندارد. تلاش برای دریافت نتیجه باعث پرتاب یک استثنا خواهد شد. 

## ResultValueTask::ResultValueTask(const T\&) سازنده

یک [ResultValueTask](../) تکمیل شده با نتیجه مشخص‌شده می‌سازد.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const T &result)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| result | const T\& | مقدار نتیجه برای بسته‌بندی در یک وظیفهٔ تکمیل‌شده. |
## توضیحات

این یک وظیفه با موفقیت تکمیل‌شده ایجاد می‌کند که بلافاصله مقدار را برمی‌گرداند. 

## ResultValueTask::ResultValueTask(const RTaskPtr\<T\>\&) سازنده

یک [ResultValueTask](../) را از یک اشاره‌گر مشترک به ResultTask<T> می‌سازد.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const RTaskPtr<T> &task)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| task | const [RTaskPtr](../../../system/rtaskptr/)\<T\>\& | وظیفه‌ای که باید بسته‌بندی شود. می‌تواند برای یک وظیفهٔ خالی مقدار null داشته باشد. |
## توضیحات

[ResultValueTask](../) وضعیت و نتیجهٔ وظیفهٔ ارائه‌شده را نشان می‌دهد. 

## موارد مرتبط

* نوع‌تعریف [RTaskPtr](../../../system/rtaskptr/)
* کلاس [ResultValueTask](../)
* فضای‌نام [System::Threading::Tasks](../../)
* کتابخانه [Aspose.Slides](../../../)