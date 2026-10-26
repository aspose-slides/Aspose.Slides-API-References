---
title: Deserialize()
second_title: Aspose.Slides C++ API referencia
description: Deszerializálja az XML dokumentumot egy objektummá.
type: docs
weight: 14
url: /hu/system.xml.serialization/xmlserializer/deserialize/
---
## XmlSerializer::Deserialize(System::SharedPtr\<IO::Stream\>) metódus


Deszerializálja az XML dokumentumot egy objektummá.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<IO::Stream> stream)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Az adatfolyam, amelyből a dokumentumot olvassa. |

### Visszatérési érték

[Object](../../../system/object/) amely korábban sorosítva lett a megadott dokumentumba.

## XmlSerializer::Deserialize(System::SharedPtr\<IO::TextReader\>) metódus


Deszerializálja az XML dokumentumot egy objektummá.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<IO::TextReader> textReader)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| textReader | [System::SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | Olvasó a dokumentum olvasásához. |

### Visszatérési érték

[Object](../../../system/object/) amely korábban sorosítva lett a megadott dokumentumba.

## XmlSerializer::Deserialize(System::SharedPtr\<XmlReader\>) metódus


Deszerializálja az XML dokumentumot egy objektummá.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<XmlReader> xmlReader)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Olvasó a dokumentum olvasásához. |

### Visszatérési érték

[Object](../../../system/object/) amely korábban sorosítva lett a megadott dokumentumba.

## XmlSerializer::Deserialize(System::SharedPtr\<XmlReader\>, String) metódus


Deszerializálja az XML dokumentumot egy objektummá.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<XmlReader> xmlReader, String encodingStyle)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Olvasó a dokumentum olvasásához. |
| encodingStyle | [String](../../../system/string/) | Az objektum sorosításához használt stílus. |

### Visszatérési érték

[Object](../../../system/object/) amely korábban sorosítva lett a megadott dokumentumba.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Object](../../../system/object/)
* Osztály [Stream](../../../system.io/stream/)
* Osztály [XmlSerializer](../)
* Osztály [TextReader](../../../system.io/textreader/)
* Osztály [XmlReader](../../../system.xml/xmlreader/)
* Osztály [String](../../../system/string/)
* Névtér [System::Xml::Serialization](../../)
* Könyvtár [Aspose.Slides](../../../)