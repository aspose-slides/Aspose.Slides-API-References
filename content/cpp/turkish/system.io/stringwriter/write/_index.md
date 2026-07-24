---
title: Write()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen karakteri akışa yazar.
type: docs
weight: 40
url: /tr/system.io/stringwriter/write/
---
## StringWriter::Write(char_t) metodu

Belirtilen karakteri akışa yazar.

```cpp
virtual void System::IO::StringWriter::Write(char_t value) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | char_t | Yazılacak değer |

## StringWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) metodu

Belirtilen karakter dizisinden belirtilen karakter alt aralığını akışa yazar.

```cpp
virtual void System::IO::StringWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Yazılacak karakterleri içeren dizi |
| index | **int32_t** | Yazılacak alt aralığın başladığı **buffer** içindeki 0 tabanlı indeks |
| count | **int32_t** | Yazılacak alt aralıktaki karakter sayısı |

## StringWriter::Write(const String\&) metodu

Belirtilen metni akışa yazar.

```cpp
virtual void System::IO::StringWriter::Write(const String &value) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Yazılacak metin |

## İlgili

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [StringWriter](../)
* Sınıf [String](../../../system/string/)
* Ad alanı [System::IO](../../)
* Kütüphane [Aspose.Slides](../../../)