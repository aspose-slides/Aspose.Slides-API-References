---
title: XmlSchemaContentProcessing
second_title: Aspose.Slides dla C++ – Referencja API
description: Udostępnia informacje o trybie walidacji zastąpień elementów any i anyAttribute.
type: docs
weight: 976
url: /pl/system.xml.schema/xmlschemacontentprocessing/
---
## XmlSchemaContentProcessing enum

Udostępnia informacje o trybie walidacji zastąpień elementów **any** i **anyAttribute**.

```cpp
enum class XmlSchemaContentProcessing
```

### Wartości

| Nazwa | Wartość | Opis |
| --- | --- | --- |
| None | 0 | Elementy dokumentu nie są walidowane. |
| Skip | 1 | Elementy dokumentu muszą być poprawnym XML i nie są walidowane przez schemat. |
| Lax | 2 | Jeśli zostanie znaleziony powiązany schemat, elementy dokumentu zostaną zwalidowane. W przeciwnym razie nie zostaną zgłoszone żadne błędy. |
| Strict | 3 | Procesor schematu musi znaleźć schemat powiązany z wskazaną przestrzenią nazw, aby zwalidować elementy dokumentu. |

## Zobacz także

* Namespace [System::Xml::Schema](../)
* Library [Aspose.Slides](../../)