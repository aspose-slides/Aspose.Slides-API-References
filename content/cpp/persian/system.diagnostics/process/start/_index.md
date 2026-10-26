---
title: Start()
second_title: مرجع API Aspose.Slides برای C++
description: فرآیند را با پارامترهای از پیش تعریف‌شده آغاز می‌کند.
type: docs
weight: 14
url: /fa/system.diagnostics/process/start/
---
## Process::Start() متد

فرآیند را با پارامترهای از پیش تعریف‌شده آغاز می‌کند.

```cpp
bool System::Diagnostics::Process::Start()
```

## Process::Start(const String\&, const String\&) متد

فرآیند را با مسیر و آرگومان‌های مشخص آغاز می‌کند.

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const String &filename, const String &arguments=String::Empty)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | [Process](../) مسیر. |
| arguments | const [String](../../../system/string/)\& | [Process](../) پارامترها. |

### مقدار بازگشتی

[Object](../../../system/object/) متصل به فرآیند تازه شروع‌شده.

## Process::Start(const SharedPtr\<ProcessStartInfo\>\&) متد

فرآیند را با مسیر و آرگومان‌های مشخص آغاز می‌کند.

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const SharedPtr<ProcessStartInfo> &start_info)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| start_info | const [SharedPtr](../../../system/sharedptr/)\<[ProcessStartInfo](../../processstartinfo/)\>\& | اطلاعات درباره فرآیندی که باید شروع شود. |

### مقدار بازگشتی

[Object](../../../system/object/) متصل به فرآیند تازه شروع‌شده.

## مراجعه کنید

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [Process](../)
* کلاس [String](../../../system/string/)
* کلاس [ProcessStartInfo](../../processstartinfo/)
* فضای‌نام [System::Diagnostics](../../)
* کتابخانه [Aspose.Slides](../../../)