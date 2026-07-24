---
title: Start()
second_title: Aspose.Slides için C++ API Referansı
description: Önceden tanımlı parametrelerle işlemi başlatır.
type: docs
weight: 14
url: /tr/system.diagnostics/process/start/
---
## Process::Start() yöntemi


Starts process with pre-defined parameters.

```cpp
bool System::Diagnostics::Process::Start()
```

## Process::Start(const String&, const String&) yöntemi


Starts process with specified path and arguments.

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const String &filename, const String &arguments=String::Empty)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | [Process](../) yol. |
| arguments | const [String](../../../system/string/)\& | [Process](../) parametreler. |

### Dönüş Değeri

[Object](../../../system/object/) yeni başlatılan işleme eklenir.

## Process::Start(const SharedPtr\<ProcessStartInfo\>\&) yöntemi


Starts process with specified path and arguments.

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const SharedPtr<ProcessStartInfo> &start_info)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| start_info | const [SharedPtr](../../../system/sharedptr/)\<[ProcessStartInfo](../../processstartinfo/)\>\& | Başlatılacak işlem hakkında bilgi. |

### Dönüş Değeri

[Object](../../../system/object/) yeni başlatılan işleme eklenir.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Process](../)
* Sınıf [String](../../../system/string/)
* Sınıf [ProcessStartInfo](../../processstartinfo/)
* Ad Alanı [System::Diagnostics](../../)
* Kütüphane [Aspose.Slides](../../../)