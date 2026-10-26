---
title: Create()
second_title: Aspose.Slides för C++ API-referens
description: Skapar kulturspecifik jämförare.
type: docs
weight: 79
url: /sv/system/stringcomparer/create/
---
## StringComparer::Create(const System::SharedPtr\<System::Globalization::CultureInfo\>\&, bool) method


Skapar kulturspecifik jämförare.

```cpp
static StringComparerPtr System::StringComparer::Create(const System::SharedPtr<System::Globalization::CultureInfo> &culture, bool ignoreCase)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| culture | const [System::SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Kultur att skapa jämförare för. |
| ignoreCase | **bool** | Om jämförare ska ignorera skiftläge. |

### Returvärde

Pekare till det nyss skapade jämförareobjektet.

## Se även

* Typedef [StringComparerPtr](../../stringcomparerptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Klass [CultureInfo](../../../system.globalization/cultureinfo/)
* Klass [StringComparer](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)