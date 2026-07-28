---
title: Add()
second_title: Aspose.Slides C++ API referenciája
description: Byte tömböt ad hozzá az XmlPreloadedResolver tárolóhoz, és egy URI-hez rendeli. Ha a tároló már tartalmaz egy leképezést ugyanarra az URI-ra, a meglévő leképezés felülíródik.
type: docs
weight: 79
url: /hu/system.xml.resolvers/xmlpreloadedresolver/add/
---
## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&) method

Byte tömböt ad hozzá a [XmlPreloadedResolver](../) tárolóhoz, és hozzárendeli egy URI-hez. Ha a tároló már tartalmaz egy leképezést ugyanarra az URI-ra, a meglévő leképezés felülíródik.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | Az URI, amelyhez az adat hozzáadódik a [XmlPreloadedResolver](../) tárolóhoz. |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Egy byte tömb, amely a megadott URI-hez tartozó adatokat tartalmazza. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

Byte tömböt ad hozzá a [XmlPreloadedResolver](../) tárolóhoz, és egy URI-hez rendeli. Ha a tároló már tartalmaz egy leképezést ugyanarra az URI-ra, a meglévő leképezés felülíródik.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value, int32_t offset, int32_t count)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | Az URI, amelyhez az adat hozzáadódik a [XmlPreloadedResolver](../) tárolóhoz. |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Egy byte tömb, amely a megadott URI-hez tartozó adatokat tartalmazza. |
| offset | **int32_t** | Az eltolás a megadott byte tömbön belül, ahol az adat kezdődik. |
| count | **int32_t** | A byte-ok száma, amelyet a megadott eltolástól kezdve a byte tömbből kell olvasni. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const SharedPtr\<IO::Stream\>\&) method

Stream-et ad hozzá a [XmlPreloadedResolver](../) tárolóhoz, és egy URI-hez rendeli. Ha a tároló már tartalmaz egy leképezést ugyanarra az URI-ra, a meglévő leképezés felülíródik.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const SharedPtr<IO::Stream> &value)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | Az URI, amelyhez az adat hozzáadódik a [XmlPreloadedResolver](../) tárolóhoz. |
| value | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Egy Stream, amely a megadott URI-hez tartozó adatokat tartalmazza. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const String\&) method

Előre betöltött adatokkal rendelkező karakterláncot ad hozzá a [XmlPreloadedResolver](../) tárolóhoz, és egy URI-hez rendeli. Ha a tároló már tartalmaz egy leképezést ugyanarra az URI-ra, a meglévő leképezés felülíródik.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const String &value)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | Az URI, amelyhez az adat hozzáadódik a [XmlPreloadedResolver](../) tárolóhoz. |
| value | const [String](../../../system/string/)\& | Egy [String](../../../system/string/) a megadott URI-hez tartozó adatokkal. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Uri](../../../system/uri/)
* Class [XmlPreloadedResolver](../)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)