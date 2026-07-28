---
title: Supports()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Sprawdza, czy implementacja DOM obsługuje określoną funkcję.
type: docs
weight: 482
url: /pl/system.xml/xmlnode/supports/
---
## XmlNode::Supports(String, String) metoda

Sprawdza, czy implementacja DOM obsługuje określoną funkcję.

```cpp
virtual bool System::Xml::XmlNode::Supports(String feature, String version)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| feature | [String](../../../system/string/) | Nazwa pakietu funkcji do przetestowania. Ta nazwa nie jest rozróżniana pod względem wielkości liter. |
| version | [String](../../../system/string/) | Numer wersji nazwy pakietu do przetestowania. Jeśli wersja nie jest określona (null), obsługa dowolnej wersji funkcji powoduje, że metoda zwraca true. |

### Wartość zwracana

**true** jeśli funkcja jest zaimplementowana w określonej wersji; w przeciwnym razie **false**.

## Uwagi

Poniższa tabela opisuje kombinacje, które zwracają **true**. 

| Funkcja | [Version](../../../system/version/)|
| --- | --- |
| XML | 1.0 |
| XML | 2.0 |

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlNode](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)