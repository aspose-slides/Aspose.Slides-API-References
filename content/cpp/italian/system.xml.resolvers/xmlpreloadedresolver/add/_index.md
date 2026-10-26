---
title: Add()
second_title: Riferimento API Aspose.Slides per C++
description: Aggiunge un array di byte al negozio XmlPreloadedResolver e lo associa a un URI. Se il negozio contiene già una mappatura per lo stesso URI, la mappatura esistente viene sovrascritta.
type: docs
weight: 79
url: /it/system.xml.resolvers/xmlpreloadedresolver/add/
---
## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&) metodo

Aggiunge un array di byte al negozio [XmlPreloadedResolver](../) e lo associa a un URI. Se il negozio contiene già una mappatura per lo stesso URI, la mappatura esistente viene sovrascritta.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | L'URI dei dati che vengono aggiunti al negozio [XmlPreloadedResolver](../). |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Un array di byte con i dati corrispondenti all'URI fornito. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metodo

Aggiunge un array di byte al negozio [XmlPreloadedResolver](../) e lo associa a un URI. Se il negozio contiene già una mappatura per lo stesso URI, la mappatura esistente viene sovrascritta.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value, int32_t offset, int32_t count)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | L'URI dei dati che vengono aggiunti al negozio [XmlPreloadedResolver](../). |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Un array di byte con i dati corrispondenti all'URI fornito. |
| offset | **int32_t** | L'offset nell'array di byte fornito dove iniziano i dati. |
| count | **int32_t** | Il numero di byte da leggere dall'array di byte, a partire dall'offset fornito. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const SharedPtr\<IO::Stream\>\&) metodo

Aggiunge uno Stream al negozio [XmlPreloadedResolver](../) e lo associa a un URI. Se il negozio contiene già una mappatura per lo stesso URI, la mappatura esistente viene sovrascritta.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const SharedPtr<IO::Stream> &value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | L'URI dei dati che vengono aggiunti al negozio [XmlPreloadedResolver](../). |
| value | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Uno Stream con i dati corrispondenti all'URI fornito. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const String\&) metodo

Aggiunge una stringa con dati precaricati al negozio [XmlPreloadedResolver](../) e la associa a un URI. Se il negozio contiene già una mappatura per lo stesso URI, la mappatura esistente viene sovrascritta.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const String &value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | L'URI dei dati che vengono aggiunti al negozio [XmlPreloadedResolver](../). |
| value | const [String](../../../system/string/)\& | Un [String](../../../system/string/) con i dati corrispondenti all'URI fornito. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Uri](../../../system/uri/)
* Class [XmlPreloadedResolver](../)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)