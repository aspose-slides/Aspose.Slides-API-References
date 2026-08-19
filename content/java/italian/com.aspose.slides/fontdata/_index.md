---
title: FontData
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta una definizione di carattere.
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

Rappresenta una definizione di carattere. Immutabile.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FontData(String fontName)](#FontData-java.lang.String-) | Crea un nuovo oggetto FontData con il nome del carattere specificato. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFontName()](#getFontName--) | Restituisce il nome del carattere. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Restituisce il nome del carattere, sostituendo il riferimento al tema con un carattere effettivamente utilizzato. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se due istanze di FontData sono uguali. |
| [hashCode()](#hashCode--) | Funziona come funzione hash per un tipo specifico, adatta all'uso in algoritmi di hashing e strutture dati come una tabella hash. |
| [toString()](#toString--) | Restituisce la rappresentazione stringa. |
### FontData(String fontName) {#FontData-java.lang.String-}
```
public FontData(String fontName)
```

Crea un nuovo oggetto FontData con il nome del carattere specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | java.lang.String | Nome del carattere. |

### getFontName() {#getFontName--}
```
public final String getFontName()
```

Restituisce il nome del carattere. Lettura/scrittura String.

**Restituisce:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public final String getFontName(IThemeEffectiveData theme)
```

Restituisce il nome del carattere, sostituendo il riferimento al tema con un carattere effettivamente utilizzato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Tema da cui prendere il nome del carattere tematico. Spetta al chiamante fornire un valore corretto. Vedi [IThemeable.createThemeEffective](../../com.aspose.slides/ithemeable\#createThemeEffective) |

**Restituisce:**
java.lang.String - Nome del carattere.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Determina se due istanze di FontData sono uguali.

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

Funziona come funzione hash per un tipo specifico, adatta all'uso in algoritmi di hashing e strutture dati come una tabella hash.

**Restituisce:**
int - Codice hash del FontData.
### toString() {#toString--}
```
public String toString()
```

Restituisce la rappresentazione stringa.

**Restituisce:**
java.lang.String - Rappresentazione stringa.