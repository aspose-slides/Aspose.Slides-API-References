---
title: HasFeature()
second_title: Aspose.Slides för C++ API-referens
description: Testar om Document Object Model (DOM)-implementeringen implementerar en specifik funktion.
type: docs
weight: 14
url: /sv/system.xml/xmlimplementation/hasfeature/
---
## XmlImplementation::HasFeature(const String\&, const String\&) method


Testar om Document [Object](../../../system/object/) Model (DOM)-implementeringen implementerar en specifik funktion.

```cpp
bool System::Xml::XmlImplementation::HasFeature(const String &strFeature, const String &strVersion)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| strFeature | const [String](../../../system/string/)\& | Funktionspaketets namn som ska testas. Detta namn är inte skiftlägeskänsligt. |
| strVersion | const [String](../../../system/string/)\& | Detta är versionsnumret för paketnamnet som ska testas. Om versionen inte anges (**nullptr**) gör stöd för någon version av funktionen att metoden returnerar **true**. |

### Returvärde

**true** om funktionen är implementerad i den angivna versionen; annars **false**.
## Anmärkningar



Följande tabell visar kombinationerna som får **HasFeature** att returnera **true**. 

| strFeature | strVersion |
| --- | --- |
| XML | 1.0 |
| XML | 2.0 |


## Se även

* Klass [String](../../../system/string/)
* Klass [XmlImplementation](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)