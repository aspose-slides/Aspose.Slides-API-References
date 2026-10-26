---
title: XmlNodeType
second_title: Aspose.Slides için C++ API Referansı
description: Düğüm tipini belirtir.
type: docs
weight: 833
url: /tr/system.xml/xmlnodetype/
---
## XmlNodeType enum

Düğüm tipini belirtir.

```cpp
enum class XmlNodeType
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| None | 0 | Bu, **Read** metodu çağrılmadıysa [XmlReader](../xmlreader/) tarafından döndürülür. |
| Element | 1 | Bir öğe (örnek, **<item>**). |
| Attribute | 2 | Bir nitelik (örnek, **id='123'**). |
| Text | 3 | Bir düğümün metin içeriği. [XmlNodeType::Text](./) düğümü hiçbir alt düğüm içeremez. [XmlNodeType::Attribute](./), [XmlNodeType::DocumentFragment](./), [XmlNodeType::Element](./) ve [XmlNodeType::EntityReference](./) düğümlerinin alt düğümü olarak görünebilir. |
| CDATA | 4 | Bir CDATA bölümü (örnek, **my escaped text**). |
| EntityReference | 5 | Bir varlığa referans (örnek, **&num;**). |
| Entity | 6 | Bir varlık bildirimi (örnek, **<!ENTITY...>**). |
| ProcessingInstruction | 7 | Bir işlem talimatı (örnek, **<?pi test?>**). |
| Comment | 8 | Bir yorum (örnek, ****). |
| Document | 9 | Bir belge nesnesi, belge ağacının kökü olarak, tüm XML belgesine erişim sağlar. |
| DocumentType | 10 | Belge türü bildirimi, aşağıdaki etiketle gösterilir (örnek, **<!DOCTYPE...>**). |
| DocumentFragment | 11 | Bir belge parçası. |
| Notation | 12 | Belge türü bildirimindeki bir gösterim (örnek, **<!NOTATION...>**). |
| Whitespace | 13 | İşaretlemeler arasındaki boşluk. |
| SignificantWhitespace | 14 | Karışık içerik modelinde işaretlemeler arasındaki boşluk veya **xml:space=\"preserve\"** kapsamı içindeki boşluk. |
| EndElement | 15 | Bir kapanış öğe etiketi (örnek, ****). |
| EndEntity | 16 | [XmlReader](../xmlreader/), [XmlReader::ResolveEntity](../xmlreader/resolveentity/) çağrısı sonucunda varlık değiştirme sonuna geldiğinde döndürülür. |
| XmlDeclaration | 17 | XML bildirimi (örnek, **<?xml version='1.0'?>**). [XmlNodeType::XmlDeclaration](./) düğümü belgenin ilk düğümü olmalıdır. Çocuk düğüm içeremez. [XmlNodeType::Document](./) düğümünün çocuğudur. Sürüm ve kodlama bilgilerini sağlayan niteliklere sahip olabilir. |

## İlgili

* Ad alanı [System::Xml](../)
* Kütüphane [Aspose.Slides](../../)