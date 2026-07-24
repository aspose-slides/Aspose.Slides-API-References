---
title: StringWriter()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen StringBuilder ve IFormatProvider kullanılarak yeni bir StringWriter örneği oluşturur.
type: docs
weight: 1
url: /tr/system.io/stringwriter/stringwriter/
---
## StringWriter::StringWriter(const System::SharedPtr\<Text::StringBuilder\>\&, const IFormatProviderPtr\&) yapıcı


Belirtilen StringBuilder ve [IFormatProvider](../../../system/iformatprovider/) kullanılarak yeni bir [StringWriter](../) örneği oluşturur.

```cpp
System::IO::StringWriter::StringWriter(const System::SharedPtr<Text::StringBuilder> &sb, const IFormatProviderPtr &formatProvider)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sb | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | Oluşturulan [StringWriter](../) tarafından kullanılacak StringBuilder nesnesi |
| formatProvider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | Oluşturulan nesne tarafından kullanılacak bir [IFormatProvider](../../../system/iformatprovider/) nesnesi |

## StringWriter::StringWriter(const System::SharedPtr\<Text::StringBuilder\>\&) yapıcı


Mevcut kültürden alınan belirtilen StringBuilder ve [IFormatProvider](../../../system/iformatprovider/) kullanılarak yeni bir [StringWriter](../) örneği oluşturur.

```cpp
System::IO::StringWriter::StringWriter(const System::SharedPtr<Text::StringBuilder> &sb)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sb | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | Oluşturulan [StringWriter](../) tarafından kullanılacak StringBuilder nesnesi |

## StringWriter::StringWriter(const IFormatProviderPtr\&) yapıcı


Belirtilen [IFormatProvider](../../../system/iformatprovider/) kullanılarak yeni bir [StringWriter](../) örneği oluşturur.

```cpp
System::IO::StringWriter::StringWriter(const IFormatProviderPtr &formatProvider)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| formatProvider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | Oluşturulan nesne tarafından kullanılacak bir [IFormatProvider](../../../system/iformatprovider/) nesnesi |

## StringWriter::StringWriter() yapıcı


Mevcut kültürden alınan [IFormatProvider](../../../system/iformatprovider/) kullanılarak yeni bir [StringWriter](../) örneği oluşturur.

```cpp
System::IO::StringWriter::StringWriter()
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [IFormatProviderPtr](../../../system/iformatproviderptr/)
* Class [StringBuilder](../../../system.text/stringbuilder/)
* Class [StringWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)