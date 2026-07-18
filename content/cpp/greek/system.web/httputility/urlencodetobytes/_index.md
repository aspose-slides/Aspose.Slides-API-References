---
title: UrlEncodeToBytes()
second_title: Aspose.Slides για C++ API Αναφορά
description: Κωδικοποιεί τμήμα URI.
type: docs
weight: 66
url: /el/system.web/httputility/urlencodetobytes/
---
## HttpUtility::UrlEncodeToBytes(const String\&) μέθοδος

Κωδικοποιεί το τμήμα URI.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const String &str)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Τμήμα URI για κωδικοποίηση. |

### Τιμή Επιστροφής

Κωδικοποιημένο τμήμα URI.

## HttpUtility::UrlEncodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) μέθοδος

Κωδικοποιεί το τμήμα URI.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Τμήμα URI για κωδικοποίηση. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Κωδικοποίηση προς χρήση. |

### Τιμή Επιστροφής

Κωδικοποιημένο τμήμα URI.

## HttpUtility::UrlEncodeToBytes(const System::ArrayPtr\<uint8_t\>\&) μέθοδος

Κωδικοποιεί το τμήμα URI.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Τμήμα URI για κωδικοποίηση. |

### Τιμή Επιστροφής

Κωδικοποιημένο τμήμα URI.

## HttpUtility::UrlEncodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) μέθοδος

Κωδικοποιεί το τμήμα URI.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Τμήμα URI για κωδικοποίηση. |
| offset | **int32_t** | Μετατόπιση στον δοσμένο πίνακα byte. |
| count | **int32_t** | Αριθμός byte προς ανάγνωση. |

### Τιμή Επιστροφής

Κωδικοποιημένο τμήμα URI.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [HttpUtility](../)
* Class [Encoding](../../../system.text/encoding/)
* Namespace [System::Web](../../)
* Library [Aspose.Slides](../../../)