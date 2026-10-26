---
title: ReadString()
second_title: Aspose.Slides for C++ API-referencia
description: Kiolvassa egy elem vagy szövegcsomópont tartalmát karakterláncként.
type: docs
weight: 391
url: /hu/system.xml/xmlnodereader/readstring/
---
## XmlNodeReader::ReadString() metódus

Kiolvassa egy elem vagy szövegcsomópont tartalmát karakterláncként.

```cpp
String System::Xml::XmlNodeReader::ReadString() override
```

### Visszatérési érték

Az elem vagy szövegszerű csomópont tartalma (Ez magában foglalhat CDATA, [Text](../../../system.text/) csomópontokat stb.). Ez lehet üres karakterlánc, ha az olvasó olyan helyen áll, amely nem elem vagy szövegcsomópont, vagy ha a jelenlegi kontextusban nincs több visszaadható szövegtartalom. Megjegyzés: A szövegcsomópont lehet elem vagy attribútum szövegcsomópont.

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlNodeReader](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)