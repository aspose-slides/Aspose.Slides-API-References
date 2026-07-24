---
title: Create()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt kulturspezifischen Comparer.
type: docs
weight: 79
url: /de/system/stringcomparer/create/
---
## StringComparer::Create(const System::SharedPtr\<System::Globalization::CultureInfo\>\&, bool) Methode

Erstellt kulturspezifischen Comparer.

```cpp
static StringComparerPtr System::StringComparer::Create(const System::SharedPtr<System::Globalization::CultureInfo> &culture, bool ignoreCase)
```

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| culture | const [System::SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Kultur, für die ein Comparer erstellt werden soll. |
| ignoreCase | **bool** | Gibt an, ob der Comparer die Groß-/Kleinschreibung ignorieren soll. |

### Return Value

Zeiger auf das neu erstellte Comparer-Objekt.

## See Also

* Typedef [StringComparerPtr](../../stringcomparerptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasse [StringComparer](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)