---
title: Add()
second_title: Aspose.Slides για την αναφορά API C++
description: Προσθέτει έναν πίνακα byte στο αποθήκη XmlPreloadedResolver και τον αντιστοιχίζει σε ένα URI. Εάν η αποθήκη περιέχει ήδη μια αντιστοίχηση για το ίδιο URI, η υπάρχουσα αντιστοίχηση αντικαθίσταται.
type: docs
weight: 79
url: /el/system.xml.resolvers/xmlpreloadedresolver/add/
---
## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&) μέθοδος

Προσθέτει έναν πίνακα byte στο [XmlPreloadedResolver](../) store και τον αντιστοιχίζει σε ένα URI. Εάν το store ήδη περιέχει μια αντιστοίχηση για το ίδιο URI, η υπάρχουσα αντιστοίχηση αντικαθίσταται.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | The URI of the data that is being added to the [XmlPreloadedResolver](../) store. |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | A byte array with the data that corresponds to the provided URI. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) μέθοδος

Προσθέτει έναν πίνακα byte στο [XmlPreloadedResolver](../) store και τον αντιστοιχίζει σε ένα URI. Εάν το store ήδη περιέχει μια αντιστοίχηση για το ίδιο URI, η υπάρχουσα αντιστοίχηση αντικαθίσταται.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value, int32_t offset, int32_t count)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | The URI of the data that is being added to the [XmlPreloadedResolver](../) store. |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | A byte array with the data that corresponds to the provided URI. |
| offset | **int32_t** | The offset in the provided byte array where the data starts. |
| count | **int32_t** | The number of bytes to read from the byte array, starting at the provided offset. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const SharedPtr\<IO::Stream\>\&) μέθοδος

Προσθέτει ένα Stream στο [XmlPreloadedResolver](../) store και το αντιστοιχίζει σε ένα URI. Εάν το store ήδη περιέχει μια αντιστοίχηση για το ίδιο URI, η υπάρχουσα αντιστοίχηση αντικαθίσταται.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const SharedPtr<IO::Stream> &value)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | The URI of the data that is being added to the [XmlPreloadedResolver](../) store. |
| value | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | A Stream with the data that corresponds to the provided URI. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const String\&) μέθοδος

Προσθέτει μια συμβολοσειρά με προφορτωμένα δεδομένα στο [XmlPreloadedResolver](../) store και την αντιστοιχίζει σε ένα URI. Εάν το store ήδη περιέχει μια αντιστοίχηση για το ίδιο URI, η υπάρχουσα αντιστοίχηση αντικαθίσταται.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const String &value)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | The URI of the data that is being added to the [XmlPreloadedResolver](../) store. |
| value | const [String](../../../system/string/)\& | A [String](../../../system/string/) with the data that corresponds to the provided URI. |

## Δείτε επίσης

* typedef [SharedPtr](../../../system/sharedptr/)
* typedef [ArrayPtr](../../../system/arrayptr/)
* κλάση [Uri](../../../system/uri/)
* κλάση [XmlPreloadedResolver](../)
* κλάση [Stream](../../../system.io/stream/)
* κλάση [String](../../../system/string/)
* ονομαχώρος [System::Xml::Resolvers](../../)
* βιβλιοθήκη [Aspose.Slides](../../../)