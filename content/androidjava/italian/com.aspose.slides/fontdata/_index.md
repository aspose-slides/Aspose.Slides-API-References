---
title: FontData
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta una definizione di font.
type: docs
url: /it/com.aspose.slides/fontdata/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IFontData](../../com.aspose.slides/ifontdata)
```
public final class FontData implements IFontData
```

Rappresenta una definizione di font. Immutabile.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FontData(String fontName)](#FontData-java.lang.String-) | Crea un nuovo oggetto FontData con il nome del font specificato. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFontName()](#getFontName--) | Restituisce il nome del font. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Restituisce il nome del font, sostituendo il riferimento al tema con un font effettivo utilizzato. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se due istanze FontData sono uguali. |
| [hashCode()](#hashCode--) | Funziona come funzione hash per un tipo particolare, adatta all'uso in algoritmi di hashing e strutture dati come una tabella hash. |
| [toString()](#toString--) | Restituisce la rappresentazione stringa. |
### FontData(String fontName) {#FontData-java.lang.String-}
```
public FontData(String fontName)
```

Crea un nuovo oggetto FontData con il nome del font specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | java.lang.String | Nome del font. |

### getFontName() {#getFontName--}
```
public final String getFontName()
```

Restituisce il nome del font. Lettura/Scrittura String.

**Restituisce:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public final String getFontName(IThemeEffectiveData theme)
```

Restituisce il nome del font, sostituendo il riferimento al tema con un font effettivo utilizzato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Tema da cui dovrebbe essere preso il nome del font tematico. Spetta al chiamante fornire un valore corretto. Vedi [IThemeable.createThemeEffective](../../com.aspose.slides/ithemeable\#createThemeEffective) |

**Restituisce:**
java.lang.String - Nome del font.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Determina se due istanze FontData sono uguali.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | Il FontData da confrontare con il FontData corrente. |

**Restituisce:**
boolean - **true** se il FontData specificato è uguale al FontData corrente; altrimenti, **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Funziona come funzione hash per un tipo particolare, adatta all'uso in algoritmi di hashing e strutture dati come una tabella hash.

**Restituisce:**
int - Codice hash del FontData.
### toString() {#toString--}
```
public String toString()
```

Restituisce la rappresentazione stringa.

**Restituisce:**
java.lang.String - Rappresentazione stringa.