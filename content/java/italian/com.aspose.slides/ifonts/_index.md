---
title: IFonts
second_title: Aspose.Slides for Java API Reference
description: Represents fonts collection.
type: docs
url: /it/com.aspose.slides/ifonts/
---```
public interface IFonts
```

Rappresenta la raccolta di font.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getLatinFont()](#getLatinFont--) | Restituisce o imposta il font Latin. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Restituisce o imposta il font Latin. |
| [getEastAsianFont()](#getEastAsianFont--) | Restituisce o imposta il font dell'Asia orientale. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Restituisce o imposta il font dell'Asia orientale. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Restituisce o imposta il font del script complesso. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Restituisce o imposta il font del script complesso. |
| [getScriptFontMap()](#getScriptFontMap--) | Restituisce un dizionario di tutte le definizioni di font per script nella presentazione. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | Ottiene il nome del font associato a un tag script specifico dal tema della presentazione. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Assegna un nome di font a un tag script specifico, definendo come il testo di quello script verrà renderizzato nella presentazione. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Rimuove l'impostazione del font associata a un tag script specifico dalla collezione di font del tema. |
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Restituisce o imposta il font Latin. Lettura/Scrittura [IFontData](../../com.aspose.slides/ifontdata).

**Restituisce:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

Restituisce o imposta il font Latin. Lettura/Scrittura [IFontData](../../com.aspose.slides/ifontdata).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

Restituisce o imposta il font dell'Asia orientale. Lettura/Scrittura [IFontData](../../com.aspose.slides/ifontdata).

**Restituisce:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

Restituisce o imposta il font dell'Asia orientale. Lettura/Scrittura [IFontData](../../com.aspose.slides/ifontdata).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Restituisce o imposta il font del script complesso. Lettura/Scrittura [IFontData](../../com.aspose.slides/ifontdata).

**Restituisce:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

Restituisce o imposta il font del script complesso. Lettura/Scrittura [IFontData](../../com.aspose.slides/ifontdata).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getScriptFontMap() {#getScriptFontMap--}
```
public abstract System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```

Restituisce un dizionario di tutte le definizioni di font per script nella presentazione.

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
public abstract String getScriptFont(String script)
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
| script | java.lang.String | Il codice script BCP-47 (ad es., "Latn", "Cyrl", "Jpan") usato per identificare un sistema di scrittura. |

**Restituisce:**
java.lang.String - Il nome del font usato per lo script specificato, o  null  se lo script non è definito.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public abstract void setScriptFont(String script, String fontName)
```

Assegna un nome di font a un tag script specifico, definendo come il testo di quello script verrà renderizzato nella presentazione.

--------------------

> ```
> Questo esempio mostra come impostare il font per lo script arabo su "Segoe UI":
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
public abstract void removeScriptFont(String script)
```

Rimuove l'impostazione del font associata a un tag script specifico dalla collezione di font del tema.

--------------------

> ```
> Questo esempio dimostra come rimuovere l'associazione del font per lo script ebraico:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| script | java.lang.String | Il codice script BCP-47 la cui impostazione del font deve essere rimossa. |