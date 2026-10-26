---
title: Start()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يبدأ العملية بمعلمات معرفة مسبقًا.
type: docs
weight: 14
url: /ar/system.diagnostics/process/start/
---
## Process::Start() طريقة

يبدأ العملية بمعلمات محددة مسبقًا.

```cpp
bool System::Diagnostics::Process::Start()
```

## Process::Start(const String\&, const String\&) طريقة

يبدأ العملية بالمسار المحدد والوسائط.

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const String &filename, const String &arguments=String::Empty)
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | [Process](../) مسار. |
| arguments | const [String](../../../system/string/)\& | [Process](../) معلمات. |

### قيمة الإرجاع

[Object](../../../system/object/) مرفق بالعملية التي بدأت حديثًا.

## Process::Start(const SharedPtr\<ProcessStartInfo\>\&) طريقة

يبدأ العملية بالمسار المحدد والوسائط.

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const SharedPtr<ProcessStartInfo> &start_info)
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| start_info | const [SharedPtr](../../../system/sharedptr/)\<[ProcessStartInfo](../../processstartinfo/)\>\& | معلومات عن العملية التي يجب بدءها. |

### قيمة الإرجاع

[Object](../../../system/object/) مرفق بالعملية التي بدأت حديثًا.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [Process](../)
* فئة [String](../../../system/string/)
* فئة [ProcessStartInfo](../../processstartinfo/)
* مساحة الاسم [System::Diagnostics](../../)
* مكتبة [Aspose.Slides](../../../)