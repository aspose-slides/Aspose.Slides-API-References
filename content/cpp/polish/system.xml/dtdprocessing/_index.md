---
title: DtdProcessing
second_title: Odwołanie do API Aspose.Slides dla C++
description: Określa opcje przetwarzania DTD. Enumeracja DtdProcessing jest używana przez klasę XmlReaderSettings.
type: docs
weight: 638
url: /pl/system.xml/dtdprocessing/
---
## DtdProcessing enum

Określa opcje przetwarzania DTD. Enumeracja DtdProcessing jest używana przez klasę [XmlReaderSettings](../xmlreadersettings/).

```cpp
enum class DtdProcessing
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Prohibit | 0 | Określa, że po napotkaniu DTD zostaje wyrzucony XmlException z komunikatem informującym, że DTD są zabronione. Jest to zachowanie domyślne. |
| Ignore | 1 | Powoduje zignorowanie elementu DOCTYPE. Nie odbywa się żadne przetwarzanie DTD, a DTD/DOCTYPE zostaje utracone w wyjściu. |
| Parse | 2 | Używane do parsowania DTD. |

## Zobacz także

* Przestrzeń nazw [System::Xml](../)
* Biblioteka [Aspose.Slides](../../)