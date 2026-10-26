---
title: UrlEncode()
second_title: Référence de l'API Aspose.Slides pour C++
description: Encode le fragment d'URI.
type: docs
weight: 53
url: /fr/system.web/httputility/urlencode/
---
## HttpUtility::UrlEncode(String) méthode

Encode le fragment d'URI.

```cpp
static String System::Web::HttpUtility::UrlEncode(String str)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| str | [String](../../../system/string/) | Fragment d'URI à encoder. |

### Valeur de retour

Fragment d'URI encodé.

## HttpUtility::UrlEncode(String, const System::SharedPtr\<Text::Encoding\>\&) méthode

Encode le fragment d'URI.

```cpp
static String System::Web::HttpUtility::UrlEncode(String str, const System::SharedPtr<Text::Encoding> &e)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| str | [String](../../../system/string/) | Fragment d'URI à encoder. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Encodage à utiliser. |

### Valeur de retour

Fragment d'URI encodé.

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&) méthode

Encode le fragment d'URI.

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Fragment d'URI à encoder. |

### Valeur de retour

Fragment d'URI encodé.

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) méthode

Encode le fragment d'URI.

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Fragment d'URI à encoder. |
| offset | **int32_t** | Décalage dans le tableau d'octets donné. |
| count | **int32_t** | Nombre d'octets à lire. |

### Valeur de retour

Fragment d'URI encodé.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [HttpUtility](../)
* Class [Encoding](../../../system.text/encoding/)
* Namespace [System::Web](../../)
* Library [Aspose.Slides](../../../)