---
title: HasFeature()
second_title: Aspose.Slides dla C++ – odwołanie do API
description: Sprawdza, czy implementacja Document Object Model (DOM) obsługuje określoną funkcję.
type: docs
weight: 14
url: /pl/system.xml/xmlimplementation/hasfeature/
---
## XmlImplementation::HasFeature(const String\&, const String\&) metoda

Sprawdza, czy implementacja Document [Object](../../../system/object/) Model (DOM) implementuje określoną funkcję.

```cpp
bool System::Xml::XmlImplementation::HasFeature(const String &strFeature, const String &strVersion)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| strFeature | const [String](../../../system/string/)\& | Nazwa pakietu funkcji do przetestowania. Ta nazwa nie rozróżnia wielkości liter. |
| strVersion | const [String](../../../system/string/)\& | Jest to numer wersji nazwy pakietu do przetestowania. Jeśli wersja nie jest określona (**nullptr**), obsługa dowolnej wersji funkcji powoduje, że metoda zwraca **true**. |

### Wartość zwracana

**true** jeśli funkcja jest zaimplementowana w określonej wersji; w przeciwnym razie, **false**.

## Uwagi

Poniższa tabela pokazuje kombinacje, które powodują, że **HasFeature** zwraca **true**.

| strFeature | strVersion |
| --- | --- |
| XML | 1.0 |
| XML | 2.0 |

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlImplementation](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)