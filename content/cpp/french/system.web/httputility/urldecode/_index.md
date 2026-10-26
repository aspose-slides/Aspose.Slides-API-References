---
title: UrlDecode()
second_title: Référence API Aspose.Slides pour C++
description: Décode le fragment d'URI à partir d'une chaîne.
type: docs
weight: 1
url: /fr/system.web/httputility/urldecode/
---
## HttpUtility::UrlDecode(String) méthode

Décode le fragment d'URI à partir d'une chaîne.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| str | [String](../../../system/string/) | Fragment d'URI encodé. |

### Valeur de retour

Fragment d'URI décodé.

## HttpUtility::UrlDecode(String, System::SharedPtr\<Text::Encoding\>) méthode

Décode le fragment d'URI à partir d'une chaîne.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str, System::SharedPtr<Text::Encoding> e)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| str | [String](../../../system/string/) | Fragment d'URI encodé. |
| e | [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\> | Encodage à utiliser. |

### Valeur de retour

Fragment d'URI décodé.

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, const System::SharedPtr\<Text::Encoding\>\&) méthode

Décode le fragment d'URI à partir d'un tableau d'octets.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, const System::SharedPtr<Text::Encoding> &e)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Fragment d'URI encodé. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Encodage à utiliser. |

### Valeur de retour

Fragment d'URI décodé.

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const System::SharedPtr\<Text::Encoding\>\&) méthode

Décode le fragment d'URI à partir d'un tableau d'octets.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count, const System::SharedPtr<Text::Encoding> &e)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Fragment d'URI encodé. |
| offset | **int32_t** | Décalage dans le tableau d'octets fourni. |
| count | **int32_t** | Nombre d'octets à lire. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Encodage à utiliser. |

### Valeur de retour

Fragment d'URI décodé.

## Voir également

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [HttpUtility](../)
* Classe [Encoding](../../../system.text/encoding/)
* Espace de noms [System::Web](../../)
* Bibliothèque [Aspose.Slides](../../../)