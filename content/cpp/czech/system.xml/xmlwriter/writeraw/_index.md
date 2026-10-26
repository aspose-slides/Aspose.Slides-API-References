---
title: WriteRaw()
second_title: Aspose.Slides pro C++ – reference API
description: Když je v odvozené třídě přepsána, zapisuje surový značkovací kód ručně z bufferu znaků.
type: docs
weight: 287
url: /cs/system.xml/xmlwriter/writeraw/
---
## XmlWriter::WriteRaw(ArrayPtr\<char16_t\>, int32_t, int32_t) metoda

Když je v odvozené třídě přepsána, zapisuje surový značkovací kód ručně z bufferu znaků.

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | Pole znaků obsahující text k zápisu. |
| index | **int32_t** | Pozice v bufferu označující začátek textu k zápisu. |
| count | **int32_t** | Počet znaků k zápisu. |

## XmlWriter::WriteRaw(const String\&) metoda

Když je v odvozené třídě přepsána, zapisuje surový značkovací kód ručně ze řetězce.

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(const String &data)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| data | const [String](../../../system/string/)\& | [String](../../../system/string/) obsahující text k zápisu. |

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [XmlWriter](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)