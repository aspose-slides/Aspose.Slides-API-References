---
title: Add()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Přidá pole bajtů do úložiště XmlPreloadedResolver a přiřadí jej k URI. Pokud úložiště již obsahuje mapování pro stejné URI, existující mapování je přepsáno.
type: docs
weight: 79
url: /cs/system.xml.resolvers/xmlpreloadedresolver/add/
---
## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&) metoda

Přidá pole bajtů do úložiště [XmlPreloadedResolver](../) a přiřadí jej k URI. Pokud úložiště již obsahuje mapování pro stejné URI, existující mapování je přepsáno.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | URI dat, která jsou přidávána do úložiště [XmlPreloadedResolver](../). |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Pole bajtů s daty, která odpovídají zadanému URI. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda

Přidá pole bajtů do úložiště [XmlPreloadedResolver](../) a přiřadí jej k URI. Pokud úložiště již obsahuje mapování pro stejné URI, existující mapování je přepsáno.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value, int32_t offset, int32_t count)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | URI dat, která jsou přidávána do úložiště [XmlPreloadedResolver](../). |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Pole bajtů s daty, která odpovídají zadanému URI. |
| offset | **int32_t** | Posun v poskytnutém poli bajtů, kde data začínají. |
| count | **int32_t** | Počet bajtů, které se mají načíst z pole bajtů, počínaje zadaným posunem. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const SharedPtr\<IO::Stream\>\&) metoda

Přidá Stream do úložiště [XmlPreloadedResolver](../) a přiřadí jej k URI. Pokud úložiště již obsahuje mapování pro stejné URI, existující mapování je přepsáno.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const SharedPtr<IO::Stream> &value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | URI dat, která jsou přidávána do úložiště [XmlPreloadedResolver](../). |
| value | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Stream s daty, která odpovídají zadanému URI. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const String\&) metoda

Přidá řetězec s přednačtenými daty do úložiště [XmlPreloadedResolver](../) a přiřadí jej k URI. Pokud úložiště již obsahuje mapování pro stejné URI, existující mapování je přepsáno.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const String &value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | URI dat, která jsou přidávána do úložiště [XmlPreloadedResolver](../). |
| value | const [String](../../../system/string/)\& | Instanci [String](../../../system/string/) s daty, která odpovídají zadanému URI. |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [Uri](../../../system/uri/)
* Třída [XmlPreloadedResolver](../)
* Třída [Stream](../../../system.io/stream/)
* Třída [String](../../../system/string/)
* Jmenný prostor [System::Xml::Resolvers](../../)
* Knihovna [Aspose.Slides](../../../)