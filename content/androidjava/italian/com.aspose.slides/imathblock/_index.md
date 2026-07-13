---
title: IMathBlock
second_title: Riferimento API Java di Aspose.Slides per Android
description: Specifica un'istanza di testo matematico contenuta in un MathParagraph e che inizia su una sua riga.
type: docs
url: /it/com.aspose.slides/imathblock/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IMathElementCollection](../../com.aspose.slides/imathelementcollection), [com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBlock extends IMathElementCollection, IMathElement
```

Specifica un'istanza di testo matematico contenuto in un MathParagraph e che inizia su una sua riga. Tutte le zone matematiche, incluse equazioni, espressioni, array di equazioni o espressioni e formule, sono rappresentate da un blocco matematico.

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathBlock();
> ```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [delimit(char separatorCharacter)](#delimit-char-) | Delimita tutti gli elementi figli con il carattere separatore (senza le parentesi) |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | Include gli elementi figli di questo blocco nei caratteri specificati, come parentesi o altri come cornice, e delimita con un carattere separatore |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | Unisce un altro blocco matematico a questo |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Salva il contenuto di questo [IMathBlock](../../com.aspose.slides/imathblock) come MathML |
### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```

Delimita tutti gli elementi figli con il carattere separatore (senza le parentesi)

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| separatorCharacter | char | Carattere usato come separatore |

**Restituisce:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Istanza dell'elemento IMathDelimiter
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

Include gli elementi figli di questo blocco nei caratteri specificati, come parentesi o altri come cornice, e delimita con un carattere separatore

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| beginningCharacter | char | Carattere d'inizio (solitamente parentesi sinistra) |
| endingCharacter | char | Carattere di chiusura (solitamente parentesi destra) |
| separatorCharacter | char | Carattere separatore |

**Restituisce:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - L'elemento matematico di tipo [IMathDelimiter](../../com.aspose.slides/imathdelimiter) che include i caratteri specificati come cornice e delimitatore
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public abstract IMathBlock joinBlock(IMathBlock other)
```

Unisce un altro blocco matematico a questo

--------------------

> ```
> Example:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | Il blocco da unire |

**Restituisce:**
[IMathBlock](../../com.aspose.slides/imathblock) - questo blocco matematico dopo l'unione
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```

Salva il contenuto di questo [IMathBlock](../../com.aspose.slides/imathblock) come MathML

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | Flusso di destinazione |