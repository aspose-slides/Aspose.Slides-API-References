---
title: ReadChars()
second_title: Aspose.Slides C++ API referencia
description: Beolvassa egy elem szövegtartalmát egy karakterpufferbe. Ez a metódus arra van tervezve, hogy beágyazott szöveg nagy folyamatait sorozatosan hívással olvassa.
type: docs
weight: 755
url: /hu/system.xml/xmltextreader/readchars/
---
## XmlTextReader::ReadChars(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) metódus


Beolvassa egy elem szövegtartalmát egy karakterpufferbe. Ez a metódus arra van tervezve, hogy beágyazott szöveg nagy folyamatait sorozatosan hívással olvassa.

```cpp
int32_t System::Xml::XmlTextReader::ReadChars(const ArrayPtr<char16_t> &buffer, int32_t index, int32_t count)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | A karakterek tömbje, amely a puffert szolgálja, ahová a szövegtartalom íródik. |
| index | **int32_t** | A **buffer**-ben lévő pozíció, ahol a metódus elkezdheti a szövegtartalom írását. |
| count | **int32_t** | A **buffer**-be írandó karakterek száma. |

### Visszatérési érték

A beolvasott karakterek száma. Ez 0 is lehet, ha az olvasó nincs egy elemre pozicionálva, vagy ha a jelenlegi kontextusban nincs több szövegtartalom visszaadandó.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [XmlTextReader](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)