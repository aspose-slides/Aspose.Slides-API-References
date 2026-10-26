---
title: UrlDecodeToBytes()
second_title: Référence de l'API Aspose.Slides pour C++
description: Décode le fragment URI à partir d'un tableau d'octets.
type: docs
weight: 14
url: /fr/system.web/httputility/urldecodetobytes/
---
## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&) méthode

Décode le fragment URI à partir d'un tableau d'octets.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Fragment URI encodé. |

### Valeur de retour

Fragment d'URI décodé.

## HttpUtility::UrlDecodeToBytes(const String\&) méthode

Décode le fragment URI à partir d'une chaîne d'octets.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Fragment URI encodé. |

### Valeur de retour

Fragment d'URI décodé.

## HttpUtility::UrlDecodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) méthode

Décode le fragment URI à partir d'une chaîne.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Fragment URI encodé. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Encodage à utiliser. |

### Valeur de retour

Fragment d'URI décodé.

## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) méthode

Décode le fragment URI à partir d'un tableau d'octets.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Fragment URI encodé. |
| offset | **int32_t** | Décalage dans le tableau d'octets fourni. |
| count | **int32_t** | Nombre d'octets à lire. |

### Valeur de retour

Fragment d'URI décodé.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [HttpUtility](../)
* Classe [String](../../../system/string/)
* Classe [Encoding](../../../system.text/encoding/)
* Espace de noms [System::Web](../../)
* Bibliothèque [Aspose.Slides](../../../)