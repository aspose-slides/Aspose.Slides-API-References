---
title: ToUpper()
second_title: Référence API Aspose.Slides pour C++
description: Convertit les caractères en majuscules en utilisant la culture spécifiée.
type: docs
weight: 469
url: /fr/system.memoryextensions/toupper/
---
## System::MemoryExtensions::ToUpper(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&, const SharedPtr\<Globalization::CultureInfo\>\&) fonction

Convertit les caractères en majuscules en utilisant la culture spécifiée.

```cpp
int32_t System::MemoryExtensions::ToUpper(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination, const SharedPtr<Globalization::CultureInfo> &culture)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Le span de caractères source à convertir |
| destination | [Span](../../system/span/)\<char16_t\>\& | Le span de destination pour stocker les caractères convertis |
| culture | const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\& | La culture à utiliser pour la conversion (nullptr pour la culture actuelle) |

### Valeur de retour

Nombre de caractères convertis, ou -1 si la destination est trop petite

## Voir aussi

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Class [CultureInfo](../../system.globalization/cultureinfo/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)