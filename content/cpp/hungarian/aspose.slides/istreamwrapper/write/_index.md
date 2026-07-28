---
title: Write()
second_title: Aspose.Slides C++ API referencia
description: bájtok sorozatát írja a jelenlegi streamba, és a stream aktuális pozícióját a leírt bájtok számával előre lépteti.
type: docs
weight: 144
url: /hu/aspose.slides/istreamwrapper/write/
---
## IStreamWrapper::Write(System::ArrayPtr\<uint8_t\>, int32_t, int32_t) metódus

bájtból álló sorozatot ír a jelenlegi streamba, és a stream aktuális pozícióját a leírt bájtok számával előre lépteti.

```cpp
virtual void Aspose::Slides::IStreamWrapper::Write(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | A **uint8_t**[] bájtok tömbje |
| offset | **int32_t** | Az a nullától kezdődő bájt eltolás a bufferben, ahol a bájtok másolását a jelenlegi streamba megkezdi **int32_t** |
| count | **int32_t** | A jelenlegi streamba írandó bájtok száma **int32_t** |

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IStreamWrapper](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)