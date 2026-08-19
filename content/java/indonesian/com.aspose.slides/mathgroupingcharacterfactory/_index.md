---
title: MathGroupingCharacterFactory
second_title: Referensi API Aspose.Slides untuk Java
description: Mengizinkan membuat karakter pengelompokan matematika
type: docs
url: /id/com.aspose.slides/mathgroupingcharacterfactory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IMathGroupingCharacterFactory](../../com.aspose.slides/imathgroupingcharacterfactory)
```
public class MathGroupingCharacterFactory implements IMathGroupingCharacterFactory
```

Mengizinkan membuat karakter pengelompokan matematika

--------------------

Untuk kompatibilitas COM
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MathGroupingCharacterFactory()](#MathGroupingCharacterFactory--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Membuat karakter pengelompokan matematika |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | Membuat karakter pengelompokan matematika |
### MathGroupingCharacterFactory() {#MathGroupingCharacterFactory--}
```
public MathGroupingCharacterFactory()
```

### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public final IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

Membuat karakter pengelompokan matematika

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemen matematika untuk menerapkan karakter pengelompokan |
| character | char | karakter pengelompokan |
| position | int | posisi karakter pengelompokan |
| verticalJustification | int | justifikasi vertikal |

**Mengembalikan:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - elemen karakter pengelompokan baru
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public final IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```

Membuat karakter pengelompokan matematika

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemen matematika untuk menerapkan karakter pengelompokan |

**Mengembalikan:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - elemen karakter pengelompokan baru