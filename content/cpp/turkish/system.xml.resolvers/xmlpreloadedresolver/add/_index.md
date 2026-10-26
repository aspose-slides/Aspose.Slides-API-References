---
title: Add()
second_title: Aspose.Slides for C++ API Referansı
description: Bir bayt dizisini XmlPreloadedResolver deposuna ekler ve onu bir URI'ye eşler. Depo aynı URI için zaten bir eşleme içeriyorsa, mevcut eşleme üzerine yazılır.
type: docs
weight: 79
url: /tr/system.xml.resolvers/xmlpreloadedresolver/add/
---
## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&) metodu

[XmlPreloadedResolver](../) deposuna bir bayt dizisi ekler ve onu bir URI’ye eşler. Depo aynı URI için zaten bir eşleme içeriyorsa, mevcut eşleme üzerine yazılır.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | Verinin [XmlPreloadedResolver](../) deposuna eklenmekte olduğu URI. |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Sağlanan URI’ye karşılık gelen veriyi içeren bir bayt dizisi. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metodu

[XmlPreloadedResolver](../) deposuna bir bayt dizisi ekler ve onu bir URI’ye eşler. Depo aynı URI için zaten bir eşleme içeriyorsa, mevcut eşleme üzerine yazılır.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value, int32_t offset, int32_t count)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | Verinin [XmlPreloadedResolver](../) deposuna eklenmekte olduğu URI. |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Sağlanan URI’ye karşılık gelen veriyi içeren bir bayt dizisi. |
| offset | **int32_t** | Verinin başladığı bayt dizisindeki ofset. |
| count | **int32_t** | Sağlanan ofsetten başlayarak bayt dizisinden okunacak bayt sayısı. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const SharedPtr\<IO::Stream\>\&) metodu

[XmlPreloadedResolver](../) deposuna bir Stream ekler ve onu bir URI’ye eşler. Depo aynı URI için zaten bir eşleme içeriyorsa, mevcut eşleme üzerine yazılır.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const SharedPtr<IO::Stream> &value)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | Verinin [XmlPreloadedResolver](../) deposuna eklenmekte olduğu URI. |
| value | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Sağlanan URI’ye karşılık gelen veriyi içeren bir Stream. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const String\&) metodu

[XmlPreloadedResolver](../) deposuna önceden yüklenmiş veri içeren bir dize ekler ve onu bir URI’ye eşler. Depo aynı URI için zaten bir eşleme içeriyorsa, mevcut eşleme üzerine yazılır.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const String &value)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | Verinin [XmlPreloadedResolver](../) deposuna eklenmekte olduğu URI. |
| value | const [String](../../../system/string/)\& | [String](../../../system/string/) içinde sağlanan URI’ye karşılık gelen veri. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Uri](../../../system/uri/)
* Class [XmlPreloadedResolver](../)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)