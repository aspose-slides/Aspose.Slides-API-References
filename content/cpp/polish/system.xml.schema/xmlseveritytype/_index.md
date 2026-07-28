---
title: XmlSeverityType
second_title: Aspose.Slides dla C++ - Referencja API
description: Reprezentuje poziom powagi zdarzenia walidacji.
type: docs
weight: 1080
url: /pl/system.xml.schema/xmlseveritytype/
---
## XmlSeverityType enum

Represents the severity of the validation event.

```cpp
enum class XmlSeverityType
```

### Wartości

| Nazwa | Wartość | Opis |
| --- | --- | --- |
| Error | 0 | Wskazuje, że podczas walidacji dokumentu wystąpił błąd walidacji. Dotyczy to definicji typów dokumentów (DTDs) oraz XML [Schema](../) język definicji (XSD) schematów. Ograniczenia ważności World Wide [Web](../../system.web/) Consortium (W3C) są uznawane za błędy. Jeśli nie został utworzony obsługiwacz zdarzeń walidacji, błędy generują wyjątek. |
| Warning | 1 | Wskazuje, że wystąpiło zdarzenie walidacji, które nie jest błędem. Ostrzeżenie jest zazwyczaj zgłaszane, gdy nie ma DTD ani XML [Schema](../) do walidacji konkretnego elementu lub atrybutu. W przeciwieństwie do błędów, ostrzeżenia nie generują wyjątku, jeśli nie ma obsługiwacza zdarzeń walidacji. |

## Zobacz także

* Przestrzeń nazw [System::Xml::Schema](../)
* Biblioteka [Aspose.Slides](../../)