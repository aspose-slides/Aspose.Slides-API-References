---
title: Start()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ξεκινά τη διαδικασία με προκαθορισμένες παραμέτρους.
type: docs
weight: 14
url: /el/system.diagnostics/process/start/
---
## Process::Start() μέθοδος


Ξεκινά τη διαδικασία με προκαθορισμένες παραμέτρους.

```cpp
bool System::Diagnostics::Process::Start()
```

## Process::Start(const String\&, const String\&) μέθοδος


Ξεκινά τη διαδικασία με καθορισμένη διαδρομή και ορίσματα.

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const String &filename, const String &arguments=String::Empty)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | [Process](../) διαδρομή. |
| arguments | const [String](../../../system/string/)\& | [Process](../) παραμέτρους. |

### Τιμή Επιστροφής

[Object](../../../system/object/) επισυνάπτεται στη νεοαρχιζόμενη διαδικασία.

## Process::Start(const SharedPtr\<ProcessStartInfo\>\&) μέθοδος


Ξεκινά τη διαδικασία με καθορισμένη διαδρομή και ορίσματα.

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const SharedPtr<ProcessStartInfo> &start_info)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| start_info | const [SharedPtr](../../../system/sharedptr/)\<[ProcessStartInfo](../../processstartinfo/)\>\& | Πληροφορίες για τη διαδικασία που θα ξεκινήσει. |

### Τιμή Επιστροφής

[Object](../../../system/object/) επισυνάπτεται στη νεοαρχιζόμενη διαδικασία.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Process](../)
* Κλάση [String](../../../system/string/)
* Κλάση [ProcessStartInfo](../../processstartinfo/)
* Χώρος ονομάτων [System::Diagnostics](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)