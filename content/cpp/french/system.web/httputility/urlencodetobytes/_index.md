---
title: UrlEncodeToBytes()
second_title: Référence API Aspose.Slides for C++
description: Encode le fragment d'URI.
type: docs
weight: 66
url: /fr/system.web/httputility/urlencodetobytes/
---
## HttpUtility::UrlEncodeToBytes(const String\&) méthode

Encode le fragment d'URI.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const String &str)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Fragment d'URI à encoder. |

### Valeur de retour

Fragment d'URI encodé.

## HttpUtility::UrlEncodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) méthode

Encode le fragment d'URI.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Fragment d'URI à encoder. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Encodage à utiliser. |

### Valeur de retour

Fragment d'URI encodé.

## HttpUtility::UrlEncodeToBytes(const System::ArrayPtr\<uint8_t\>\&) méthode

Encode le fragment d'URI.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Fragment d'URI à encoder. |

### Valeur de retour

Fragment d'URI encodé.

## HttpUtility::UrlEncodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) méthode

Encode le fragment d'URI.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Fragment d'URI à encoder. |
| offset | **int32_t** | Décalage dans le tableau d'octets donné. |
| count | **int32_t** | Nombre d'octets à lire. |

### Valeur de retour

Fragment d'URI encodé.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [String](../../../system/string/)
* classe [HttpUtility](../)
* classe [Encoding](../../../system.text/encoding/)
* espace de noms [System::Web](../../)
* Library [Aspose.Slides](../../../)