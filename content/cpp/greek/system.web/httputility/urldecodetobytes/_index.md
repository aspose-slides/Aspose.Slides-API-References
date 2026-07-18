---
title: UrlDecodeToBytes()
second_title: Αναφορά API του Aspose.Slides για C++
description: Αποκωδικοποιεί το τμήμα URI από πίνακα byte.
type: docs
weight: 14
url: /el/system.web/httputility/urldecodetobytes/
---
## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&) μέθοδος

Αποκωδικοποιεί το τμήμα URI από πίνακα byte.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Κωδικοποιημένο τμήμα URI. |

### Τιμή Επιστροφής

Αποκωδικοποιημένο τμήμα URI.

## HttpUtility::UrlDecodeToBytes(const String\&) μέθοδος

Αποκωδικοποιεί το τμήμα URI από συμβολοσειρά byte.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Κωδικοποιημένο τμήμα URI. |

### Τιμή Επιστροφής

Αποκωδικοποιημένο τμήμα URI.

## HttpUtility::UrlDecodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) μέθοδος

Αποκωδικοποιεί το τμήμα URI από συμβολοσειρά.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Κωδικοποιημένο τμήμα URI. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Κωδικοποίηση προς χρήση. |

### Τιμή Επιστροφής

Αποκωδικοποιημένο τμήμα URI.

## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) μέθοδος

Αποκωδικοποιεί το τμήμα URI από πίνακα byte.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Κωδικοποιημένο τμήμα URI. |
| offset | **int32_t** | Μετατόπιση στον δεδομένο πίνακα byte. |
| count | **int32_t** | Αριθμός bytes προς ανάγνωση. |

### Τιμή Επιστροφής

Αποκωδικοποιημένο τμήμα URI.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [HttpUtility](../)
* Κλάση [String](../../../system/string/)
* Κλάση [Encoding](../../../system.text/encoding/)
* Χώρος ονομάτων [System::Web](../../)
* Library [Aspose.Slides](../../../)