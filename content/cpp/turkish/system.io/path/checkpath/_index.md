---
title: CheckPath()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen yolun geçerli olup olmadığını, geçersiz karakter içerip içermediğini kontrol ederek belirler. Yol geçersiz karakter içeriyorsa bir istisna fırlatılır.
type: docs
weight: 209
url: /tr/system.io/path/checkpath/
---
## Path::CheckPath(const String\&, const String\&, bool) metod

Belirtilen yolun geçerli olup olmadığını, geçersiz karakter içerip içermediğini kontrol ederek belirler. Yol geçersiz karakter içeriyorsa bir istisna fırlatılır.

```cpp
static void System::IO::Path::CheckPath(const String &path, const String &msg=s_msg_path, bool allow_empty=1)
```

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Kontrol edilecek yol |
| msg | const [String](../../../system/string/)\& | İstisna nesnesinin yapıcısına geçirilecek mesaj |
| allow_empty | **bool** | Boş veya null bir dizgenin doğru bir yol olarak kabul edilip edilmeyeceğini belirtir (true) veya (false); bu parametre false olduğunda ve **path** boş ise bir ArgumentException fırlatılır; bu parametre false olduğunda ve **path** null ise bir ArgumentNullException fırlatılır |

## Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [Path](../)
* Ad alanı [System::IO](../../)
* Kütüphane [Aspose.Slides](../../../)