---
title: Add()
second_title: Aspose.Slides for C++ – Dokumentacja API
description: Dodaje tablicę bajtów do magazynu XmlPreloadedResolver i mapuje ją na URI. Jeśli magazyn już zawiera mapowanie dla tego samego URI, istniejące mapowanie zostaje nadpisane.
type: docs
weight: 79
url: /pl/system.xml.resolvers/xmlpreloadedresolver/add/
---
## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&) metoda

Dodaje tablicę bajtów do magazynu [XmlPreloadedResolver](../) i mapuje ją na URI. Jeśli magazyn już zawiera mapowanie dla tego samego URI, istniejące mapowanie zostaje nadpisane.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | URI danych, które są dodawane do magazynu [XmlPreloadedResolver](../). |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Tablica bajtów z danymi odpowiadającymi podanemu URI. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda

Dodaje tablicę bajtów do magazynu [XmlPreloadedResolver](../) i mapuje ją na URI. Jeśli magazyn już zawiera mapowanie dla tego samego URI, istniejące mapowanie zostaje nadpisane.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value, int32_t offset, int32_t count)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | URI danych, które są dodawane do magazynu [XmlPreloadedResolver](../). |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Tablica bajtów z danymi odpowiadającymi podanemu URI. |
| offset | **int32_t** | Przesunięcie w podanej tablicy bajtów, w którym zaczynają się dane. |
| count | **int32_t** | Liczba bajtów do odczytania z tablicy bajtów, zaczynając od podanego przesunięcia. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const SharedPtr\<IO::Stream\>\&) metoda

Dodaje strumień do magazynu [XmlPreloadedResolver](../) i mapuje go na URI. Jeśli magazyn już zawiera mapowanie dla tego samego URI, istniejące mapowanie zostaje nadpisane.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const SharedPtr<IO::Stream> &value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | URI danych, które są dodawane do magazynu [XmlPreloadedResolver](../). |
| value | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Strumień z danymi odpowiadającymi podanemu URI. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const String\&) metoda

Dodaje ciąg znaków z wstępnie załadowanymi danymi do magazynu [XmlPreloadedResolver](../) i mapuje go na URI. Jeśli magazyn już zawiera mapowanie dla tego samego URI, istniejące mapowanie zostaje nadpisane.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const String &value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | URI danych, które są dodawane do magazynu [XmlPreloadedResolver](../). |
| value | const [String](../../../system/string/)\& | Obiekt [String](../../../system/string/) z danymi, które odpowiadają podanemu URI. |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [Uri](../../../system/uri/)
* Klasa [XmlPreloadedResolver](../)
* Klasa [Stream](../../../system.io/stream/)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [System::Xml::Resolvers](../../)
* Biblioteka [Aspose.Slides](../../../)