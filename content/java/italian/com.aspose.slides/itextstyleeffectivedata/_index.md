---
title: ITextStyleEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective text style properties.
type: docs
url: /it/com.aspose.slides/itextstyleeffectivedata/
---```
public interface ITextStyleEffectiveData
```

Oggetto immutabile che contiene le proprietà effettive dello stile del testo.

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
| index | int | Indice a base zero del livello. Deve trovarsi nell'intervallo 0..8. |

**Restituisce:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - Formattazione effettiva del livello [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormatEffectiveData getDefaultParagraphFormat()
```


Restituisce le proprietà predefinite del paragrafo effettive. Sola lettura [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

**Restituisce:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)