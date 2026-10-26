---
title: Warning()
second_title: Referensi API Aspose.Slides untuk C++
description: Metode callback yang menerima peringatan dan memutuskan apakah operasi harus dibatalkan.
type: docs
weight: 1
url: /id/aspose.slides.warnings/iwarningcallback/warning/
---
## IWarningCallback::Warning(System::SharedPtr\<IWarningInfo\>) metode

Metode callback yang menerima peringatan dan memutuskan apakah operasi harus dibatalkan.

```cpp
virtual ReturnAction Aspose::Slides::Warnings::IWarningCallback::Warning(System::SharedPtr<IWarningInfo> warning)=0
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| warning | [System::SharedPtr](../../../system/sharedptr/)\<[IWarningInfo](../../iwarninginfo/)\> | Peringatan untuk diproses. |

### Nilai Kembali

Keputusan penghentian [ReturnAction](../../returnaction/).

## Lihat Juga

* Enum [ReturnAction](../../returnaction/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IWarningInfo](../../iwarninginfo/)
* Kelas [IWarningCallback](../)
* Namespace [Aspose::Slides::Warnings](../../)
* Library [Aspose.Slides](../../../)