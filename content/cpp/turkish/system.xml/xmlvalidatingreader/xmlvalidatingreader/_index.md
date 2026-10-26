---
title: XmlValidatingReader()
second_title: Aspose.Slides for C++ API Referansı
description: Verilen XmlReader tarafından döndürülen içeriği doğrulayan XmlValidatingReader sınıfının yeni bir örneğini başlatır.
type: docs
weight: 430
url: /tr/system.xml/xmlvalidatingreader/xmlvalidatingreader/
---
## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<XmlReader\>\&) kurucu

Verilen [XmlReader](../../xmlreader/) tarafından döndürülen içeriği doğrulayan [XmlValidatingReader](../) sınıfının yeni bir örneğini başlatır.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<XmlReader> &reader)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\>\& | [XmlReader](../../xmlreader/) doğrulama sırasında okunacak. Mevcut uygulama yalnızca [XmlTextReader](../../xmltextreader/) destekler. |

## XmlValidatingReader::XmlValidatingReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) kurucu

Belirtilen değerlerle [XmlValidatingReader](../) sınıfının yeni bir örneğini başlatır.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | Ayrıştırılacak XML parçacığını içeren dize. |
| fragType | [XmlNodeType](../../xmlnodetype/) | XML parçacığının XmlNodeType'ı. Bu ayrıca parçacık dizesinin ne içerebileceğini belirler (aşağıdaki tabloya bakın). |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | [XmlParserContext](../../xmlparsercontext/) XML parçacığının ayrıştırılacağı yer. Bu, kullanılacak [NameTable](../../nametable/), kodlama, ad alanı kapsamı, geçerli **xml:lang**, ve **xml:space** kapsamını içerir. |

## Açıklamalar

Aşağıdaki tablo, **fragType** için geçerli değerleri ve okuyucunun farklı düğüm türlerini nasıl ayrıştırdığını listeler.

| XmlNodeType | Parçacık İçerebilir |
| --- | --- |
| Element| Geçerli herhangi bir element içeriği (örneğin, elementlerin, yorumların, işleme talimatlarının, cdata, metnin ve varlık referanslarının herhangi bir kombinasyonu). |
| [Attribute](../../../system/attribute/)| Özniteliğin değeri (tırnak işaretleri içindeki kısım). |
| Document| Tam bir XML belgesinin içeriği; bu, belge düzeyindeki kuralları uygular. |

## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) kurucu

[XmlValidatingReader](../) sınıfının belirtilen değerlerle yeni bir örneğini başlatır.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Ayrıştırılacak XML parçacığını içeren akış. |
| fragType | [XmlNodeType](../../xmlnodetype/) | XML parçacığının XmlNodeType'ı. Bu, parçacığın ne içerebileceğini belirler (aşağıdaki tabloya bakın). |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | [XmlParserContext](../../xmlparsercontext/) XML parçacığının ayrıştırılacağı yer. Bu, kullanılacak [XmlNameTable](../../xmlnametable/), kodlama, ad alanı kapsamı, geçerli **xml:lang**, ve **xml:space** kapsamını içerir. |

## Açıklamalar

Aşağıdaki tablo, **fragType** için geçerli değerleri ve okuyucunun farklı düğüm türlerini nasıl ayrıştırdığını listeler.

| XmlNodeType | Parçacık İçerebilir |
| --- | --- |
| Element| Geçerli herhangi bir element içeriği (örneğin, elementlerin, yorumların, işleme talimatlarının, cdata, metnin ve varlık referanslarının herhangi bir kombinasyonu). |
| [Attribute](../../../system/attribute/)| Özniteliğin değeri (tırnak işaretleri içindeki kısım). |
| Document| Tam bir XML belgesinin içeriği; bu, belge düzeyindeki kuralları uygular. |

## İlgili

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlReader](../../xmlreader/)
* Sınıf [XmlValidatingReader](../)
* Sınıf [String](../../../system/string/)
* Sınıf [XmlParserContext](../../xmlparsercontext/)
* Sınıf [Stream](../../../system.io/stream/)
* AdAlanı [System::Xml](../../)
* Library [Aspose.Slides](../../../)