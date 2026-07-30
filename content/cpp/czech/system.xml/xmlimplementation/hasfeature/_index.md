---
title: HasFeature()
second_title: Aspose.Slides pro C++ API dokumentaci
description: Testuje, zda implementace Document Object Model (DOM) implementuje konkrétní funkci.
type: docs
weight: 14
url: /cs/system.xml/xmlimplementation/hasfeature/
---
## XmlImplementation::HasFeature(const String\&, const String\&) metoda


Testuje, zda implementace Document [Object](../../../system/object/) Model (DOM) implementuje konkrétní funkci.

```cpp
bool System::Xml::XmlImplementation::HasFeature(const String &strFeature, const String &strVersion)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| strFeature | const [String](../../../system/string/)\& | Název balíčku funkce, kterou testujete. Tento název nerozlišuje velikost písmen. |
| strVersion | const [String](../../../system/string/)\& | Jedná se o číslo verze balíčku, který se testuje. Pokud není verze specifikována (**nullptr**), podpora libovolné verze funkce způsobí, že metoda vrátí **true**. |

### Návratová hodnota

**true** pokud je funkce implementována ve zadané verzi; jinak **false**.
## Poznámky



Následující tabulka ukazuje kombinace, které způsobí, že **HasFeature** vrátí **true**. 

| strFeature | strVersion |
| --- | --- |
| XML | 1.0 |
| XML | 2.0 |


## Viz také

* Třída [String](../../../system/string/)
* Třída [XmlImplementation](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)