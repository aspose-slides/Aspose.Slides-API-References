---
title: Fonts
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Collezione di font.
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
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Assegna un nome di font a un tag script specifico, definendo come il testo di quello script verrà visualizzato nella presentazione. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Rimuove l'impostazione del font associata a un tag script specifico dalla raccolta di font del tema. |
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
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - Un dizionario che mappa i codici script ai nomi dei font.

### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public final String getScriptFont(String script)
```


Ottiene il nome del font associato a un tag script specifico dal tema della presentazione.

--------------------

> ```
> Questo esempio dimostra come recuperare il font assegnato allo script cirillico nel tema della presentazione.
>  
>  String font = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFont("Cyrl");
>  System.out.println("Font for Cyrillic script: " + font);
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| script | java.lang.String | Il codice script BCP-47 (ad es., "Latn", "Cyrl", "Jpan") utilizzato per identificare un sistema di scrittura. |

**Restituisce:**
java.lang.String - Il nome del font usato per lo script specificato, oppure  null  se lo script non è definito.

### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public final void setScriptFont(String script, String fontName)
```


Assegna un nome di font a un tag script specifico, definendo come il testo di quello script verrà visualizzato nella presentazione.

--------------------

> ```
> Questo esempio mostra come impostare il font per lo script arabo a "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| script | java.lang.String | Il codice script BCP-47 (ad es., "Arab", "Hebr", "Hans") che identifica il sistema di scrittura. |
| fontName | java.lang.String | Il nome del font da assegnare allo script specificato. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public final void removeScriptFont(String script)
```


Rimuove l'impostazione del font associata a un tag script specifico dalla raccolta di font del tema.

--------------------

> ```
> Questo esempio dimostra come rimuovere l'associazione del font per lo script ebraico:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| script | java.lang.String | Il codice script BCP-47 del quale rimuovere l'impostazione del font. |

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