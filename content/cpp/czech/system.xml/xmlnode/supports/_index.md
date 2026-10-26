---
title: Supports()
second_title: Aspose.Slides pro C++ API Reference
description: Testuje, zda implementace DOM podporuje konkrétní funkci.
type: docs
weight: 482
url: /cs/system.xml/xmlnode/supports/
---
## XmlNode::Supports(String, String) metoda

Testuje, zda implementace DOM podporuje konkrétní funkci.

```cpp
virtual bool System::Xml::XmlNode::Supports(String feature, String version)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| feature | [String](../../../system/string/) | Název balíčku funkce, kterou testovat. Tento název nerozlišuje velikost písmen. |
| version | [String](../../../system/string/) | Číslo verze balíčku, který se testuje. Pokud není verze uvedena (null), podpora jakékoli verze funkce způsobí, že metoda vrátí **true**. |

### Návratová hodnota

**true** pokud je funkce implementována ve specifikované verzi; jinak **false**.

## Poznámky

Následující tabulka popisuje kombinace, které vracejí **true**.

| Funkce | [Version](../../../system/version/) |
| --- | --- |
| XML | 1.0 |
| XML | 2.0 |

## Viz také

* třída [String](../../../system/string/)
* třída [XmlNode](../)
* jmenný prostor [System::Xml](../../)
* knihovna [Aspose.Slides](../../../)