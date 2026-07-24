---
title: Create()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen URI ile yeni bir XmlReader örneği oluşturur.
type: docs
weight: 1015
url: /tr/system.xml/xmlreader/create/
---
## XmlReader::Create(const String\&) method

Belirtilen URI ile yeni bir [XmlReader](../) örneği oluşturur.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | XML verilerini içeren dosyanın URI'si. [XmlUrlResolver](../../xmlurlresolver/) sınıfı, yolu kanonik bir veri temsiline dönüştürmek için kullanılır. |

### Dönüş Değeri

Akıştaki XML verilerini okumak için kullanılan bir nesne.

## XmlReader::Create(const String\&, const SharedPtr\<XmlReaderSettings\>\&) method

Belirtilen URI ve ayarları kullanarak yeni bir [XmlReader](../) örneği oluşturur.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, const SharedPtr<XmlReaderSettings> &settings)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | XML verilerini içeren dosyanın URI'si. [XmlResolver](../../xmlresolver/) nesnesi, [XmlReaderSettings](../../xmlreadersettings/) nesnesi üzerinde, yolu kanonik bir veri temsiline dönüştürmek için kullanılır. XmlReaderSettings::get_XmlResolver değeri **nullptr** ise yeni bir [XmlUrlResolver](../../xmlurlresolver/) nesnesi kullanılır. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | Yeni [XmlReader](../) örneği için ayarlar. Bu değer **nullptr** olabilir. |

### Dönüş Değeri

Akıştaki XML verilerini okumak için kullanılan bir nesne.

## XmlReader::Create(const String\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) method

Belirtilen URI, ayarlar ve ayrıştırma için bağlam bilgilerini kullanarak yeni bir [XmlReader](../) örneği oluşturur.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | XML verilerini içeren dosyanın URI'si. [XmlResolver](../../xmlresolver/) nesnesi, [XmlReaderSettings](../../xmlreadersettings/) nesnesi üzerinde, yolu kanonik bir veri temsiline dönüştürmek için kullanılır. XmlReaderSettings::get_XmlResolver değeri **nullptr** ise yeni bir [XmlUrlResolver](../../xmlurlresolver/) nesnesi kullanılır. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Yeni [XmlReader](../) örneği için ayarlar. Bu değer **nullptr** olabilir. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | XML parçacığını ayrıştırmak için gerekli bağlam bilgisi. Bağlam bilgisi, kullanılacak [XmlNameTable](../../xmlnametable/), kodlama, ad alanı kapsamı, geçerli **xml:lang** ve **xml:space** kapsamı, temel URI ve belge türü tanımını içerebilir. Bu değer **nullptr** olabilir. |

### Dönüş Değeri

Akıştaki XML verilerini okumak için kullanılan bir nesne.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&) method

Varsayılan ayarlarla belirtilen akışı kullanarak yeni bir [XmlReader](../) örneği oluşturur.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | XML verilerini içeren akış. [XmlReader](../) akışın ilk baytlarını bir bayt sırası işareti ya da diğer kodlama işaretleri için tarar. Kodlama belirlendiğinde, akışı okumaya devam etmek için kodlama kullanılır ve işleme, girdiyi (Unicode) karakter akışı olarak ayrıştırmaya devam eder. |

### Dönüş Değeri

Akıştaki XML verilerini okumak için kullanılan bir nesne.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlReaderSettings\>\&) method

Belirtilen akış ve ayarlarla yeni bir [XmlReader](../) örneği oluşturur.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlReaderSettings> &settings)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | XML verilerini içeren akış. [XmlReader](../) akışın ilk baytlarını bir bayt sırası işareti ya da diğer kodlama işaretleri için tarar. Kodlama belirlendiğinde, akışı okumaya devam etmek için kodlama kullanılır ve işleme, girdiyi (Unicode) karakter akışı olarak ayrıştırmaya devam eder. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | Yeni [XmlReader](../) örneği için ayarlar. Bu değer **nullptr** olabilir. |

### Dönüş Değeri

Akıştaki XML verilerini okumak için kullanılan bir nesne.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) method

Belirtilen akış, temel URI ve ayarları kullanarak yeni bir [XmlReader](../) örneği oluşturur.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | XML verilerini içeren akış. [XmlReader](../) akışın ilk baytlarını bir bayt sırası işareti ya da diğer kodlama işaretleri için tarar. Kodlama belirlendiğinde, akışı okumaya devam etmek için kodlama kullanılır ve işleme, girdiyi (Unicode) karakter akışı olarak ayrıştırmaya devam eder. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Yeni [XmlReader](../) örneği için ayarlar. Bu değer **nullptr** olabilir. |
| baseUri | const [String](../../../system/string/)\& | Okunan varlık veya belge için temel URI. Bu değer **nullptr** olabilir. **[Security](../../../system.security/) Not** Temel URI, XML belgesinin göreli URI'sini çözmek için kullanılır. Güvenilmeyen bir kaynaktan temel URI kullanmayın. |

### Dönüş Değeri

Akıştaki XML verilerini okumak için kullanılan bir nesne.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) method

Belirtilen akış, ayarlar ve ayrıştırma için bağlam bilgilerini kullanarak yeni bir [XmlReader](../) örneği oluşturur.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | XML verilerini içeren akış. [XmlReader](../) akışın ilk baytlarını bir bayt sırası işareti ya da diğer kodlama işaretleri için tarar. Kodlama belirlendiğinde, akışı okumaya devam etmek için kodlama kullanılır ve işleme, girdiyi (Unicode) karakter akışı olarak ayrıştırmaya devam eder. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Yeni [XmlReader](../) örneği için ayarlar. Bu değer **nullptr** olabilir. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | XML parçacığını ayrıştırmak için gerekli bağlam bilgisi. Bağlam bilgisi, kullanılacak [XmlNameTable](../../xmlnametable/), kodlama, ad alanı kapsamı, geçerli **xml:lang** ve **xml:space** kapsamı, temel URI ve belge türü tanımını içerebilir. Bu değer **nullptr** olabilir. |

### Dönüş Değeri

Akıştaki XML verilerini okumak için kullanılan bir nesne.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&) method

Belirtilen metin okuyucuyu kullanarak yeni bir [XmlReader](../) örneği oluşturur.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | XML verilerini okumak için kullanılan metin okuyucu. Bir metin okuyucu Unicode karakter akışı döndürür, bu yüzden XML bildiriminde belirtilen kodlama, veri akışını çözmek için XML okuyucu tarafından kullanılmaz. |

### Dönüş Değeri

Akıştaki XML verilerini okumak için kullanılan bir nesne.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlReaderSettings\>\&) method

Belirtilen metin okuyucu ve ayarları kullanarak yeni bir [XmlReader](../) örneği oluşturur.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlReaderSettings> &settings)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | XML verlerini okumak için kullanılan metin okuyucu. Bir metin okuyucu Unicode karakter akışı döndürür, bu yüzden XML bildiriminde belirtilen kodlama XML okuyucu tarafından veri akışını çözmek için kullanılmaz. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | Yeni [XmlReader](../) örneği için ayarlar. Bu değer **nullptr** olabilir. |

### Dönüş Değeri

Akıştaki XML verilerini okumak için kullanılan bir nesne.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) method

Belirtilen metin okuyucu, ayarlar ve temel URI'yi kullanarak yeni bir [XmlReader](../) örneği oluşturur.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | XML verilerini okumak için kullanılan metin okuyucu. Bir metin okuyucu Unicode karakter akışı döndürür, bu yüzden XML bildiriminde belirtilen kodlama [XmlReader](../) tarafından veri akışını çözmek için kullanılmaz. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Yeni [XmlReader](../) örneği için ayarlar. Bu değer **nullptr** olabilir. |
| baseUri | const [String](../../../system/string/)\& | Okunan varlık veya belge için temel URI. Bu değer **nullptr** olabilir. **[Security](../../../system.security/) Not** Temel URI, XML belgesinin göreli URI'sini çözmek için kullanılır. Güvenilmeyen bir kaynaktan temel URI kullanmayın. |

### Dönüş Değeri

Akıştaki XML verilerini okumak için kullanılan bir nesne.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) method

Belirtilen metin okuyucu, ayarlar ve ayrıştırma için bağlam bilgilerini kullanarak yeni bir [XmlReader](../) örneği oluşturur.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | XML verilerini okumak için kullanılan metin okuyucu. Bir metin okuyucu Unicode karakter akışı döndürür, bu yüzden XML bildiriminde belirtilen kodlama XML okuyucu tarafından veri akışını çözmek için kullanılmaz. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Yeni [XmlReader](../) örneği için ayarlar. Bu değer **nullptr** olabilir. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | XML parçacığını ayrıştırmak için gerekli bağlam bilgisi. Bağlam bilgisi, kullanılacak [XmlNameTable](../../xmlnametable/), kodlama, ad alanı kapsamı, geçerli **xml:lang** ve **xml:space** kapsamı, temel URI ve belge türü tanımını içerebilir. Bu değer **nullptr** olabilir. |

### Dönüş Değeri

Akıştaki XML verilerini okumak için kullanılan bir nesne.

## XmlReader::Create(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlReaderSettings\>) method

Belirtilen XML okuyucu ve ayarları kullanarak yeni bir [XmlReader](../) örneği oluşturur.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<XmlReader> &reader, SharedPtr<XmlReaderSettings> settings)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../)\>\& | Alt XML okuyucu olarak kullanmak istediğiniz nesne. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Yeni [XmlReader](../) örneği için ayarlar. [XmlReaderSettings](../../xmlreadersettings/) nesnesinin uyumluluk seviyesi, alt okuyucunun uyumluluk seviyesiyle eşleşmelidir ya da [ConformanceLevel::Auto](../../conformancelevel/) olarak ayarlanmalıdır. |

### Dönüş Değeri

Belirtilen [XmlReader](../) nesnesinin etrafına sarılmış bir nesne.

## Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlReader](../)
* Sınıf [String](../../../system/string/)
* Sınıf [XmlReaderSettings](../../xmlreadersettings/)
* Sınıf [XmlParserContext](../../xmlparsercontext/)
* Sınıf [Stream](../../../system.io/stream/)
* Sınıf [TextReader](../../../system.io/textreader/)
* Ad alanı [System::Xml](../../)
* Library [Aspose.Slides](../../../)