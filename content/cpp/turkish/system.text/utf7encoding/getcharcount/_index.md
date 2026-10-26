---
title: GetCharCount()
second_title: Aspose.Slides için C++ API Referansı
description: Bir bayt arabelleğini çözümlemek için gereken karakter sayısını alır.
type: docs
weight: 79
url: /tr/system.text/utf7encoding/getcharcount/
---
## UTF7Encoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) method

Bir bayt arabelleğini çözümlemek için gereken karakter sayısını alır.

```cpp
int System::Text::UTF7Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Çözümleyecek baytlar. |
| index | int | Dilim başlangıcı. |
| count | int | Dilim boyutu. |

### Return Value

Karakter sayısı.

## UTF7Encoding::GetCharCount(const uint8_t *, int) method

Bir bayt arabelleğini çözümlemek için gereken karakter sayısını alır.

```cpp
int System::Text::UTF7Encoding::GetCharCount(const uint8_t *bytes, int count) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | Çözümleyecek baytlar. |
| count | int | Bayt sayısı. |

### Return Value

Karakter sayısı.

## UTF7Encoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) method

Bir bayt arabelleğini çözümlemek için gereken karakter sayısını alır.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Çözümleyecek baytlar. |
| index | int | Dilim başlangıcı. |
| count | int | Dilim boyutu. |

### Return Value

Karakter sayısı.

## UTF7Encoding::GetCharCount(ArrayPtr\<uint8_t\>) method

Bir bayt arabelleğini çözümlemek için gereken karakter sayısını alır.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Çözümleyecek baytlar. |

### Return Value

Karakter sayısı.

## UTF7Encoding::GetCharCount(const uint8_t *, int) method

Bir bayt arabelleğini çözümlemek için gereken karakter sayısını alır.

```cpp
virtual int System::Text::Encoding::GetCharCount(const uint8_t *bytes, int count)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | Çözümleyecek baytlar. |
| count | int | Bayt sayısı. |

### Return Value

Karakter sayısı.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [UTF7Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)