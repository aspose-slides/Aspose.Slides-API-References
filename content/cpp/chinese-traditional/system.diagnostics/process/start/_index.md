---
title: Start()
second_title: Aspose.Slides for C++ API 參考
description: 使用預先定義的參數啟動程序。
type: docs
weight: 14
url: /zh-hant/system.diagnostics/process/start/
---
## Process::Start() 方法

使用預先定義的參數啟動程序。

```cpp
bool System::Diagnostics::Process::Start()
```

## Process::Start(const String\&, const String\&) 方法

使用指定的路徑和參數啟動程序。

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const String &filename, const String &arguments=String::Empty)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | [Process](../) 路徑。 |
| arguments | const [String](../../../system/string/)\& | [Process](../) 參數。 |

### 返回值

[Object](../../../system/object/) 已附加至新啟動的程序。

## Process::Start(const SharedPtr\<ProcessStartInfo\>\&) 方法

使用指定的路徑和參數啟動程序。

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const SharedPtr<ProcessStartInfo> &start_info)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| start_info | const [SharedPtr](../../../system/sharedptr/)\<[ProcessStartInfo](../../processstartinfo/)\>\& | 關於要啟動的程序的資訊。 |

### 返回值

[Object](../../../system/object/) 已附加至新啟動的程序。

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [Process](../)
* 類別 [String](../../../system/string/)
* 類別 [ProcessStartInfo](../../processstartinfo/)
* 命名空間 [System::Diagnostics](../../)
* Library [Aspose.Slides](../../../)