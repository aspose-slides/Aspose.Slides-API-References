---
title: MathGroupingCharacterFactory
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mengizinkan pembuatan karakter pengelompokkan matematika
type: docs
url: /id/com.aspose.slides/mathgroupingcharacterfactory/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathGroupingCharacterFactory](../../com.aspose.slides/imathgroupingcharacterfactory)
```
public class MathGroupingCharacterFactory implements IMathGroupingCharacterFactory
```

Mengizinkan pembuatan karakter pengelompokkan matematika

--------------------

Untuk kompatibilitas COM
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MathGroupingCharacterFactory()](#MathGroupingCharacterFactory--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Creates a math grouping character |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | Creates a math grouping character |
### MathGroupingCharacterFactory() {#MathGroupingCharacterFactory--}
```
public MathGroupingCharacterFactory()
```

### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public final IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

Membuat karakter pengelompokkan matematika

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemen matematika untuk menerapkan karakter pengelompokkan |
| character | char | karakter pengelompokkan |
| position | int | posisi karakter pengelompokkan |
| verticalJustification | int | justifikasi vertikal |

**Mengembalikan:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - elemen karakter pengelompokkan baru
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public final IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```

Membuat karakter pengelompokkan matematika

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemen matematika untuk menerapkan karakter pengelompokkan |

**Mengembalikan:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - elemen karakter pengelompokkan baru