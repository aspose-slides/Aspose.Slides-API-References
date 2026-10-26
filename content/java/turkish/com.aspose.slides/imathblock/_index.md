---
title: IMathBlock
second_title: Aspose.Slides for Java API Referansı
description: Bir MathParagraph içinde bulunan ve kendi satırında başlayan matematik metni örneğini belirtir.
type: docs
url: /tr/com.aspose.slides/imathblock/
---
**Tüm Gerçekleştirilen Arabirimler:**
[com.aspose.slides.IMathElementCollection](../../com.aspose.slides/imathelementcollection), [com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBlock extends IMathElementCollection, IMathElement
```

MathParagraph içinde bulunan ve kendi satırında başlayan matematik metni örneğini belirtir. Denklemler, ifadeler, denklem veya ifade dizileri ve formüller dahil olmak üzere tüm matematik bölgeleri, matematik bloğu tarafından temsil edilir.

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathBlock();
> ```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [delimit(char separatorCharacter)](#delimit-char-) | Tüm alt öğeleri ayırıcı karakterle (köşeli parantezler olmadan) sınırlamaktadır. |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | Bu bloğun alt öğelerini parantez gibi belirtilen karakterlerle çerçeveleyerek ve bir ayırıcı karakterle sınırlayarak kapsar. |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | Başka bir matematik bloğunu bu bloğa ekler. |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Bu [IMathBlock](../../com.aspose.slides/imathblock) içeriğini MathML olarak kaydeder. |
### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```

Tüm alt öğeleri ayırıcı karakterle (köşeli parantezler olmadan) sınırlamaktadır.

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| separatorCharacter | char | Ayırıcı olarak kullanılan karakter |

**Döndürür:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - IMathDelimiter öğesinin bir örneği
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

Bu bloğun alt öğelerini parantez gibi belirtilen karakterlerle çerçeveleyerek ve bir ayırıcı karakterle sınırlayarak kapsar.

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| beginningCharacter | char | Başlangıç karakteri (genellikle sol parantez) |
| endingCharacter | char | Bitiş karakteri (genellikle sağ parantez) |
| separatorCharacter | char | Ayırıcı karakter |

**Döndürür:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - [IMathDelimiter](../../com.aspose.slides/imathdelimiter) tipinde, belirtilen karakterleri çerçeve ve ayırıcı olarak içeren matematik öğesi
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public abstract IMathBlock joinBlock(IMathBlock other)
```

Başka bir matematik bloğunu bu bloğa ekler.

--------------------

> ```
> Example:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | Birleştirilen blok |

**Döndürür:**
[IMathBlock](../../com.aspose.slides/imathblock) - birleştirme sonrası bu matematik bloğu
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```

Bu [IMathBlock](../../com.aspose.slides/imathblock) içeriğini MathML olarak kaydeder

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.OutputStream | Hedef akış |
