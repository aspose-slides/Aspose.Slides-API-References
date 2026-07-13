---
title: IMathBlock
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Menentukan sebuah instance teks matematika yang berada dalam MathParagraph dan dimulai pada baris terpisah.
type: docs
url: /id/com.aspose.slides/imathblock/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathElementCollection](../../com.aspose.slides/imathelementcollection), [com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBlock extends IMathElementCollection, IMathElement
```

Menentukan sebuah instance teks matematika yang berada di dalam MathParagraph dan dimulai pada baris terpisah. Semua zona matematika, termasuk persamaan, ekspresi, array persamaan atau ekspresi, dan formula direpresentasikan oleh blok matematika.

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathBlock();
> ```
## Metode

| Metode | Deskripsi |
| --- | --- |
| [delimit(char separatorCharacter)](#delimit-char-) | Membatasi semua elemen anak dengan karakter pemisah (tanpa tanda kurung) |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | Menyertakan elemen anak dari blok ini dalam karakter yang ditentukan seperti tanda kurung atau karakter lain sebagai bingkai dan membatasi dengan karakter pemisah |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | Menggabungkan blok matematika lain dengan yang ini |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Menyimpan konten [IMathBlock](../../com.aspose.slides/imathblock) ini sebagai MathML |

### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```

Membatasi semua elemen anak dengan karakter pemisah (tanpa tanda kurung)

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| separatorCharacter | char | Karakter yang digunakan sebagai pemisah |

**Mengembalikan:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Instance dari elemen IMathDelimiter

### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

Menyertakan elemen anak dari blok ini dalam karakter yang ditentukan seperti tanda kurung atau karakter lain sebagai bingkai dan membatasi dengan karakter pemisah

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| beginningCharacter | char | Karakter awal (biasanya kurung kiri) |
| endingCharacter | char | Karakter akhir (biasanya kurung kanan) |
| separatorCharacter | char | Karakter pemisah |

**Mengembalikan:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Elemen matematika tipe [IMathDelimiter](../../com.aspose.slides/imathdelimiter) yang mencakup karakter yang ditentukan sebagai bingkai dan delimiter

### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public abstract IMathBlock joinBlock(IMathBlock other)
```

Menggabungkan blok matematika lain dengan yang ini

--------------------

> ```
> Example:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | Blok yang akan digabung |

**Mengembalikan:**
[IMathBlock](../../com.aspose.slides/imathblock) - blok matematika ini setelah digabung

### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```

Menyimpan konten [IMathBlock](../../com.aspose.slides/imathblock) ini sebagai MathML

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.OutputStream | Aliran target |