---
title: Uri()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen URI'yi temsil eden bir Uri nesnesi oluşturur.
type: docs
weight: 287
url: /tr/system/uri/uri/
---
## Uri::Uri(const String\&) constructor


[Uri](../) nesnesini oluşturur; bu nesne belirtilen URI'yi temsil eder.

```cpp
System::Uri::Uri(const String &uriString)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | Oluşturulan nesne tarafından temsil edilecek dize URI |

## Uri::Uri(const String\&, bool) constructor


[Uri](../) nesnesini oluşturur; bu nesne belirtilen URI'yi temsil eder; bir argüman URI'nın kaçırılıp kaçırılmayacağını belirler.

```cpp
System::Uri::Uri(const String &uriString, bool dontEscape)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | Oluşturulan nesne tarafından temsil edilecek dize URI |
| dontEscape | **bool** | URI'nın kaçırılmaması gerektiğini belirtir |

## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&, bool) constructor


[Uri](../) nesnesini, temel URI'yi temsil eden belirtilen [Uri](../) nesnesi ve göreli URI'nın dize temsili üzerinden oluşturur; bir argüman URI'nın kaçırılıp kaçırılmayacağını belirler.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri, bool dontEscape)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Temel URI |
| relativeUri | const [String](../../string/)\& | Temel URI'ya eklenen göreli URI |
| dontEscape | **bool** | URI'nın kaçırılmaması gerektiğini belirtir |

## Uri::Uri(const String\&, UriKind) constructor


[Uri](../) nesnesini oluşturur; bu nesne belirtilen URI'yi temsil eder; bir argüman URI türünü belirler.

```cpp
System::Uri::Uri(const String &uriString, UriKind uriKind)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | Oluşturulan nesne tarafından temsil edilecek dize URI |
| uriKind | [UriKind](../../urikind/) | URI türünü belirler |

## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&) constructor


[Uri](../) nesnesini belirtilen temel ve göreli URI'lardan oluşturur.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Temel URI |
| relativeUri | const [String](../../string/)\& | Temel URI'ya eklenen göreli URI |

## Uri::Uri(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) constructor


[Uri](../) nesnesini belirtilen temel ve göreli URI'lardan oluşturur.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Temel URI |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Temel URI'ya eklenen göreli URI |

## İlgili

* Enum [UriKind](../../urikind/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)