---
title: Create()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen dosya adını kullanarak yeni bir XmlWriter örneği oluşturur.
type: docs
weight: 469
url: /tr/system.xml/xmlwriter/create/
---
## XmlWriter::Create(const String\&) metot


Belirtilen dosya adını kullanarak yeni bir [XmlWriter](../) örneği oluşturur.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | Yazmak istediğiniz dosya. [XmlWriter](../) belirtilen yolda bir dosya oluşturur ve XML 1.0 metin sözdiziminde ona yazar. **outputFileName** bir dosya sistemi yolu olmalıdır. |

### Dönüş Değeri

Bir [XmlWriter](../) nesnesi.

## XmlWriter::Create(const String\&, SharedPtr\<XmlWriterSettings\>) metot


Dosya adı ve [XmlWriterSettings](../../xmlwritersettings/) nesnesini kullanarak yeni bir [XmlWriter](../) örneği oluşturur.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName, SharedPtr<XmlWriterSettings> settings)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | Yazmak istediğiniz dosya. [XmlWriter](../) belirtilen yolda bir dosya oluşturur ve XML 1.0 metin sözdiziminde ona yazar. **outputFileName** bir dosya sistemi yolu olmalıdır. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | Yeni [XmlWriter](../) örneğini yapılandırmak için kullanılan [XmlWriterSettings](../../xmlwritersettings/) nesnesi. Bu **nullptr** ise, varsayılan ayarlarla bir [XmlWriterSettings](../../xmlwritersettings/) kullanılır. Eğer [XmlWriter](../) XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) metodu ile kullanılıyorsa, doğru ayarlarla bir [XmlWriterSettings](../../xmlwritersettings/) nesnesi elde etmek için XslCompiledTransform::get_OutputSettings değerini kullanmalısınız. Bu, oluşturulan [XmlWriter](../) nesnesinin doğru çıktı ayarlarına sahip olmasını sağlar. |

### Dönüş Değeri

Bir [XmlWriter](../) nesnesi.

## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&) metot


Belirtilen akışı kullanarak yeni bir [XmlWriter](../) örneği oluşturur.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Yazmak istediğiniz akış. [XmlWriter](../) XML 1.0 metin sözdiziminde yazar ve belirtilen akışa ekler. |

### Dönüş Değeri

Bir [XmlWriter](../) nesnesi.

## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlWriterSettings\>) metot


Akış ve [XmlWriterSettings](../../xmlwritersettings/) nesnesini kullanarak yeni bir [XmlWriter](../) örneği oluşturur.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output, SharedPtr<XmlWriterSettings> settings)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Yazmak istediğiniz akış. [XmlWriter](../) XML 1.0 metin sözdiziminde yazar ve belirtilen akışa ekler. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | Yeni [XmlWriter](../) örneğini yapılandırmak için kullanılan [XmlWriterSettings](../../xmlwritersettings/) nesnesi. Bu **nullptr** ise, varsayılan ayarlarla bir [XmlWriterSettings](../../xmlwritersettings/) kullanılır. Eğer [XmlWriter](../) XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) metodu ile kullanılıyorsa, doğru ayarlarla bir [XmlWriterSettings](../../xmlwritersettings/) nesnesi elde etmek için XslCompiledTransform::get_OutputSettings değerini kullanmalısınız. Bu, oluşturulan [XmlWriter](../) nesnesinin doğru çıktı ayarlarına sahip olmasını sağlar. |

### Dönüş Değeri

Bir [XmlWriter](../) nesnesi.

## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&) metot


Belirtilen TextWriter'ı kullanarak yeni bir [XmlWriter](../) örneği oluşturur.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Yazmak istediğiniz TextWriter. [XmlWriter](../) XML 1.0 metin sözdiziminde yazar ve belirtilen TextWriter'a ekler. |

### Dönüş Değeri

Bir [XmlWriter](../) nesnesi.

## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&, SharedPtr\<XmlWriterSettings\>) metot


TextWriter ve [XmlWriterSettings](../../xmlwritersettings/) nesnelerini kullanarak yeni bir [XmlWriter](../) örneği oluşturur.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output, SharedPtr<XmlWriterSettings> settings)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Yazmak istediğiniz TextWriter. [XmlWriter](../) XML 1.0 metin sözdiziminde yazar ve belirtilen TextWriter'a ekler. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | Yeni [XmlWriter](../) örneğini yapılandırmak için kullanılan [XmlWriterSettings](../../xmlwritersettings/) nesnesi. Bu **nullptr** ise, varsayılan ayarlarla bir [XmlWriterSettings](../../xmlwritersettings/) kullanılır. Eğer [XmlWriter](../) XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) metodu ile kullanılıyorsa, doğru ayarlarla bir [XmlWriterSettings](../../xmlwritersettings/) nesnesi elde etmek için XslCompiledTransform::get_OutputSettings değerini kullanmalısınız. Bu, oluşturulan [XmlWriter](../) nesnesinin doğru çıktı ayarlarına sahip olmasını sağlar. |

### Dönüş Değeri

Bir [XmlWriter](../) nesnesi.

## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&) metot


Belirtilen [Text::StringBuilder](../../../system.text/stringbuilder/)'i kullanarak yeni bir [XmlWriter](../) örneği oluşturur.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | Yazmak istediğiniz [Text::StringBuilder](../../../system.text/stringbuilder/). [XmlWriter](../) tarafından yazılan içerik [Text::StringBuilder](../../../system.text/stringbuilder/)'e eklenir. |

### Dönüş Değeri

Bir [XmlWriter](../) nesnesi.

## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&, SharedPtr\<XmlWriterSettings\>) metot


[Text::StringBuilder](../../../system.text/stringbuilder/) ve [XmlWriterSettings](../../xmlwritersettings/) nesnelerini kullanarak yeni bir [XmlWriter](../) örneği oluşturur.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output, SharedPtr<XmlWriterSettings> settings)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | Yazmak istediğiniz [Text::StringBuilder](../../../system.text/stringbuilder/). [XmlWriter](../) tarafından yazılan içerik [Text::StringBuilder](../../../system.text/stringbuilder/)'a eklenir. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | Yeni [XmlWriter](../) örneğini yapılandırmak için kullanılan [XmlWriterSettings](../../xmlwritersettings/) nesnesi. Bu **nullptr** ise, varsayılan ayarlarla bir [XmlWriterSettings](../../xmlwritersettings/) kullanılır. Eğer [XmlWriter](../) XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) metodu ile kullanılıyorsa, doğru ayarlarla bir [XmlWriterSettings](../../xmlwritersettings/) nesnesi elde etmek için XslCompiledTransform::get_OutputSettings değerini kullanmalısınız. Bu, oluşturulan [XmlWriter](../) nesnesinin doğru çıktı ayarlarına sahip olmasını sağlar. |

### Dönüş Değeri

Bir [XmlWriter](../) nesnesi.

## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&) metot


Belirtilen [XmlWriter](../) nesnesini kullanarak yeni bir [XmlWriter](../) örneği oluşturur.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | Alt yazıcı olarak kullanmak istediğiniz [XmlWriter](../) nesnesi. |

### Dönüş Değeri

Belirtilen [XmlWriter](../) nesnesi etrafında sarılmış bir [XmlWriter](../) nesnesi.

## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&, SharedPtr\<XmlWriterSettings\>) metot


Belirtilen [XmlWriter](../) ve [XmlWriterSettings](../../xmlwritersettings/) nesnelerini kullanarak yeni bir [XmlWriter](../) örneği oluşturur.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output, SharedPtr<XmlWriterSettings> settings)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | Alt yazıcı olarak kullanmak istediğiniz [XmlWriter](../) nesnesi. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | Yeni [XmlWriter](../) örneğini yapılandırmak için kullanılan [XmlWriterSettings](../../xmlwritersettings/) nesnesi. Bu **nullptr** ise, varsayılan ayarlarla bir [XmlWriterSettings](../../xmlwritersettings/) kullanılır. Eğer [XmlWriter](../) XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) metodu ile kullanılıyorsa, doğru ayarlarla bir [XmlWriterSettings](../../xmlwritersettings/) nesnesi elde etmek için XslCompiledTransform::get_OutputSettings değerini kullanmalısınız. Bu, oluşturulan [XmlWriter](../) nesnesinin doğru çıktı ayarlarına sahip olmasını sağlar. |

### Dönüş Değeri

Belirtilen [XmlWriter](../) nesnesi etrafında sarılmış bir [XmlWriter](../) nesnesi.

## Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlWriter](../)
* Sınıf [String](../../../system/string/)
* Sınıf [XmlWriterSettings](../../xmlwritersettings/)
* Sınıf [Stream](../../../system.io/stream/)
* Sınıf [TextWriter](../../../system.io/textwriter/)
* Sınıf [StringBuilder](../../../system.text/stringbuilder/)
* Ad Alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)