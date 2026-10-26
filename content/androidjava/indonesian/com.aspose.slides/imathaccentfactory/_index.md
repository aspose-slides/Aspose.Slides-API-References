---
title: IMathAccentFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Mengizinkan membuat aksen matematika
type: docs
url: /id/com.aspose.slides/imathaccentfactory/
---```
public interface IMathAccentFactory
```

Mengizinkan membuat aksen matematika

--------------------

Untuk kompatibilitas COM
## Metode

| Metode | Deskripsi |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Membuat aksen matematika yang diterapkan pada elemen matematika tertentu dengan nilai karakter aksen default |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Membuat aksen matematika yang diterapkan pada elemen matematika tertentu |
### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public abstract IMathAccent createMathAccent(IMathElement element)
```

Membuat aksen matematika yang diterapkan pada elemen matematika tertentu dengan nilai karakter aksen default

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemen matematika untuk menerapkan aksen |

**Mengembalikan:**
[IMathAccent](../../com.aspose.slides/imathaccent) - aksen matematika baru
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public abstract IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```

Membuat aksen matematika yang diterapkan pada elemen matematika tertentu

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemen matematika untuk menerapkan aksen |
| accentCharacter | char | karakter aksen |

**Mengembalikan:**
[IMathAccent](../../com.aspose.slides/imathaccent) - aksen matematika baru