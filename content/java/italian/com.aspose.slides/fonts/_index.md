---
title: Fonts
second_title: Riferimento API di Aspose.Slides per Java
description: Raccolta di font.
type: docs
url: /it/com.aspose.slides/fonts/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IFonts](../../com.aspose.slides/ifonts)
```
public class Fonts implements IFonts
```

Raccolta di font.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getScriptFontMap()](#getScriptFontMap--) | Restituisce un dizionario di tutte le definizioni di font script nella presentazione. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | Ottiene il nome del font associato a un tag script specifico dal tema della presentazione. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Assegna un nome di font a un tag script specifico, che definisce come il testo di quel script verrà visualizzato nella presentazione. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Rimuove l'impostazione del font associata a un tag script specifico dalla collezione di font del tema. |
| [getLatinFont()](#getLatinFont--) | Restituisce o imposta il font latino. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Restituisce o imposta il font latino. |
| [getEastAsianFont()](#getEastAsianFont--) | Restituisce o imposta il font dell'Est asiatico. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Restituisce o imposta il font dell'Est asiatico. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Restituisce o imposta il font script complesso. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Restituisce o imposta il font script complesso. |
### getScriptFontMap() {#getScriptFontMap--}
```
public final System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```

Restituisce un dizionario di tutte le definizioni di font script nella presentazione.

--------------------

> ```
> Dictionary.Enumerator<String, String> map = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFontMap().iterator();
>  while (map.hasNext())
>  {
>      KeyValuePair<String, String> kvp = map.next();
>      System.out.println(kvp.getKey() + " ? " + kvp.getValue());
>  }
> ```

**Restituisce:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - A dictionary mapping script codes to font names.
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public final String getScriptFont(String script)
```

Ottiene il nome del font associato a un tag script specifico dal tema della presentazione.

--------------------

> ```
> This example demonstrates how to retrieve the font assigned to the Cyrillic script in the presentation theme.
>  
>  String font = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFont("Cyrl");
>  System.out.println("Font for Cyrillic script: " + font);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| script | java.lang.String | Il codice script BCP-47 (ad es., "Latn", "Cyrl", "Jpan") usato per identificare un sistema di scrittura. |

**Restituisce:**
java.lang.String - Il nome del font usato per lo script specificato, o  null  se lo script non è definito.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public final void setScriptFont(String script, String fontName)
```

Assegna un nome di font a un tag script specifico, che definisce come il testo di quello script verrà visualizzato nella presentazione.

--------------------

> ```
> Questo esempio mostra come impostare il font per lo script Arabo a "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segue UI");
```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| script | java.lang.String | Il codice script BCP-47 (ad es., "Arab", "Hebr", "Hans") identificante il sistema di scrittura. |
| fontName | java.lang.String | Il nome del font da assegnare allo script specificato. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public final void removeScriptFont(String script)
```

Rimuove l'impostazione del font associata a un tag script specifico dalla collezione di font del tema.

--------------------

> ```
> This example demonstrates how to remove the font mapping for the Hebrew script:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| script | java.lang.String | Il codice script BCP-47 la cui impostazione del font deve essere rimossa. |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

Restituisce o imposta il font latino. Lettura/scrittura [IFontData](../../com.aspose.slides/ifontdata).

**Restituisce:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

Restituisce o imposta il font latino. Lettura/scrittura [IFontData](../../com.aspose.slides/ifontdata).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

Restituisce o imposta il font dell'Est asiatico. Lettura/scrittura [IFontData](../../com.aspose.slides/ifontdata).

**Restituisce:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

Restituisce o imposta il font dell'Est asiatico. Lettura/scrittura [IFontData](../../com.aspose.slides/ifontdata).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

Restituisce o imposta il font script complesso. Lettura/scrittura [IFontData](../../com.aspose.slides/ifontdata).

**Restituisce:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

Restituisce o imposta il font script complesso. Lettura/scrittura [IFontData](../../com.aspose.slides/ifontdata).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |