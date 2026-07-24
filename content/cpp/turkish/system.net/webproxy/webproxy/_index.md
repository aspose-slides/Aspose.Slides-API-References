---
title: WebProxy()
second_title: Aspose.Slides için C++ API Referansı
description: Yeni bir örnek oluşturur.
type: docs
weight: 131
url: /tr/system.net/webproxy/webproxy/
---
## WebProxy::WebProxy() yapıcı

Yeni bir örnek oluşturur.

```cpp
System::Net::WebProxy::WebProxy()
```

## WebProxy::WebProxy(System::SharedPtr\<Uri\>) yapıcı

Yeni bir örnek oluşturur.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Proxy sunucu adresi. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool) yapıcı

Yeni bir örnek oluşturur.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Proxy sunucu adresi. |
| BypassOnLocal | **bool** | Proxy sunucusunun yerel adresler için kullanılıp kullanılmayacağını belirten bir değer. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>) yapıcı

Yeni bir örnek oluşturur.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Proxy sunucu adresi. |
| BypassOnLocal | **bool** | Proxy sunucusunun yerel adresler için kullanılıp kullanılmayacağını belirten bir değer. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | Proxy sunucusunu kullanmayan adreslerin listesi. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) yapıcı

Yeni bir örnek oluşturur.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList, System::SharedPtr<ICredentials> Credentials)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Proxy sunucu adresi. |
| BypassOnLocal | **bool** | Proxy sunucusunun yerel adresler için kullanılıp kullanılmayacağını belirten bir değer. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | Proxy sunucusunu kullanmayan adreslerin listesi. |
| Credentials | [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\> | Kimlik doğrulama için proxy sunucusuna gönderilen kimlik bilgileri. |

## WebProxy::WebProxy(String, int32_t) yapıcı

Yeni bir örnek oluşturur.

```cpp
System::Net::WebProxy::WebProxy(String Host, int32_t Port)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| Host | [String](../../../system/string/) | Ana bilgisayar adı. |
| Port | **int32_t** | Bağlantı noktası numarası. |

## WebProxy::WebProxy(String) yapıcı

Yeni bir örnek oluşturur.

```cpp
System::Net::WebProxy::WebProxy(String Address)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| Address | [String](../../../system/string/) | Proxy sunucu adresi. |

## WebProxy::WebProxy(String, bool) yapıcı

Yeni bir örnek oluşturur.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| Address | [String](../../../system/string/) | Proxy sunucu adresi. |
| BypassOnLocal | **bool** | Proxy sunucusunun yerel adresler için kullanılıp kullanılmayacağını belirten bir değer. |

## WebProxy::WebProxy(String, bool, System::ArrayPtr\<String\>) yapıcı

Yeni bir örnek oluşturur.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| Address | [String](../../../system/string/) | Proxy sunucu adresi. |
| BypassOnLocal | **bool** | Proxy sunucusunun yerel adresler için kullanılıp kullanılmayacağını belirten bir değer. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | Proxy sunucusunu kullanmayan adreslerin listesi. |

## WebProxy::WebProxy(String, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) yapıcı

Yeni bir örnek oluşturur.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList, System::SharedPtr<ICredentials> Credentials)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| Address | [String](../../../system/string/) | Proxy sunucu adresi. |
| BypassOnLocal | **bool** | Proxy sunucusunun yerel adresler için kullanılıp kullanılmayacağını belirten bir değer. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | Proxy sunucusunu kullanmayan adreslerin listesi. |
| Credentials | [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\> | Kimlik doğrulama için proxy sunucusuna gönderilen kimlik bilgileri. |

## Başvurular

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [WebProxy](../)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [ICredentials](../../icredentials/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)