---
title: UrlDecode()
second_title: Αναφορά API Aspose.Slides για C++
description: Αποκωδικοποιεί το τμήμα URI από συμβολοσειρά.
type: docs
weight: 1
url: /el/system.web/httputility/urldecode/
---
## HttpUtility::UrlDecode(String) μέθοδος


Αποκωδικοποιεί το τμήμα URI από συμβολοσειρά.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| str | [String](../../../system/string/) | Κωδικοποιημένο τμήμα URI. |

### Τιμή Επιστροφής

Αποκωδικοποιημένο τμήμα URI.

## HttpUtility::UrlDecode(String, System::SharedPtr\<Text::Encoding\>) μέθοδος


Αποκωδικοποιεί το τμήμα URI από συμβολοσειρά.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str, System::SharedPtr<Text::Encoding> e)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| str | [String](../../../system/string/) | Κωδικοποιημένο τμήμα URI. |
| e | [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\> | Κωδικοποίηση προς χρήση. |

### Τιμή Επιστροφής

Αποκωδικοποιημένο τμήμα URI.

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, const System::SharedPtr\<Text::Encoding\>\&) μέθοδος


Αποκωδικοποιεί το τμήμα URI από πίνακα bytes.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, const System::SharedPtr<Text::Encoding> &e)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Κωδικοποιημένο τμήμα URI. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Κωδικοποίηση προς χρήση. |

### Τιμή Επιστροφής

Αποκωδικοποιημένο τμήμα URI.

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const System::SharedPtr\<Text::Encoding\>\&) μέθοδος


Αποκωδικοποιεί το τμήμα URI από πίνακα bytes.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count, const System::SharedPtr<Text::Encoding> &e)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Κωδικοποιημένο τμήμα URI. |
| offset | **int32_t** | Μετατόπιση στον δεδομένο πίνακα bytes. |
| count | **int32_t** | Αριθμός bytes προς ανάγνωση. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Κωδικοποίηση προς χρήση. |

### Τιμή Επιστροφής

Αποκωδικοποιημένο τμήμα URI.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [HttpUtility](../)
* Κλάση [Encoding](../../../system.text/encoding/)
* Χώρος ονομάτων [System::Web](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)