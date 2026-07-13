---
title: ITextStyleEffectiveData
second_title: Aspose.Slides per Android tramite riferimento API Java
description: Oggetto immutabile che contiene le proprietà di stile del testo effettivo.
type: docs
url: /it/com.aspose.slides/itextstyleeffectivedata/
---```
public interface ITextStyleEffectiveData
```

Oggetto immutabile che contiene le proprietà di stile del testo effettivo.

--------------------

Questa interfaccia è usata insieme all'interfaccia [ITextStyle](../../com.aspose.slides/itextstyle) per restituire i valori di formattazione effettivi con l'ereditarietà applicata.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Restituisce il livello dello stile effettivo. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Restituisce le proprietà del paragrafo predefinito effettive. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormatEffectiveData getLevel(int index)
```

Restituisce il livello dello stile effettivo.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice basato su zero del livello. Deve trovarsi nell'intervallo 0..8. |

**Restituisce:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - Formattazione effettiva del livello [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormatEffectiveData getDefaultParagraphFormat()
```

Restituisce le proprietà del paragrafo predefinito effettive. Solo lettura [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

**Restituisce:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)