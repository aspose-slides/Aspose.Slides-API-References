---
title: ITextStyle
second_title: Aspose.Slides for Android via Java API Reference
description: Proprietà di formattazione dello stile del testo.
type: docs
url: /it/com.aspose.slides/itextstyle/
---```
public interface ITextStyle
```

Proprietà di formattazione dello stile del testo.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Se il livello di stile esiste lo restituisce, altrimenti restituisce null. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Proprietà predefinite del paragrafo. |
| [getEffective()](#getEffective--) | Ottiene i dati di formattazione dello stile del testo effettivo con l'ereditarietà applicata. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormat getLevel(int index)
```

Se il livello di stile esiste lo restituisce, altrimenti restituisce null.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice basato su zero del livello. Deve trovarsi nell'intervallo 0..8. |

**Restituisce:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Formattazione del livello [IParagraphFormat](../../com.aspose.slides/iparagraphformat).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormat getDefaultParagraphFormat()
```

Proprietà predefinite del paragrafo. Solo lettura [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Restituisce:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public abstract ITextStyleEffectiveData getEffective()
```

Ottiene i dati di formattazione dello stile del testo effettivo con l'ereditarietà applicata.

**Restituisce:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - Un [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).