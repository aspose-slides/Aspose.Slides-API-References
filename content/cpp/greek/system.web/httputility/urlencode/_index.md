---
title: UrlEncode()
second_title: Αναφορά API Aspose.Slides για C++
description: Κωδικοποιεί τμήμα URI.
type: docs
weight: 53
url: /el/system.web/httputility/urlencode/
---
## HttpUtility::UrlEncode(String) μέθοδος


Κωδικοποιεί το τμήμα URI.

```cpp
static String System::Web::HttpUtility::UrlEncode(String str)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| str | [String](../../../system/string/) | Τμήμα URI προς κωδικοποίηση. |

### Τιμή Επιστροφής

Κωδικοποιημένο τμήμα URI.

## HttpUtility::UrlEncode(String, const System::SharedPtr\<Text::Encoding\>\&) μέθοδος


Κωδικοποιεί το τμήμα URI.

```cpp
static String System::Web::HttpUtility::UrlEncode(String str, const System::SharedPtr<Text::Encoding> &e)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| str | [String](../../../system/string/) | Τμήμα URI προς κωδικοποίηση. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Κωδικοποίηση προς χρήση. |

### Τιμή Επιστροφής

Κωδικοποιημένο τμήμα URI.

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&) μέθοδος


Κωδικοποιεί το τμήμα URI.

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Τμήμα URI προς κωδικοποίηση. |

### Τιμή Επιστροφής

Κωδικοποιημένο τμήμα URI.

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) μέθοδος


Κωδικοποιεί το τμήμα URI.

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Τμήμα URI προς κωδικοποίηση. |
| offset | **int32_t** | Μετατόπιση στον δεδομένο πίνακα byte. |
| count | **int32_t** | Αριθμός byte προς ανάγνωση. |

### Τιμή Επιστροφής

Κωδικοποιημένο τμήμα URI.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [HttpUtility](../)
* Κλάση [Encoding](../../../system.text/encoding/)
* Χώρος ονομάτων [System::Web](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)