---
title: FontsLoader
second_title: Riferimento API di Aspose.Slides per Java
description: Classe per caricare i font personalizzati definiti dall'utente.
type: docs
url: /it/com.aspose.slides/fontsloader/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IFontsLoader](../../com.aspose.slides/ifontsloader)
```
public final class FontsLoader implements IFontsLoader
```

Classe per caricare i font personalizzati definiti dall'utente. Deve essere utilizzata prima di creare qualsiasi oggetto di presentazione.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [loadExternalFonts(String[] directories)](#loadExternalFonts-java.lang.String---) | Aggiunge cartelle aggiuntive per cercare i font. |
| [loadExternalFont(byte[] data)](#loadExternalFont-byte---) | Aggiunge il font dai dati binari |
| [getFontFolders()](#getFontFolders--) | Ottiene le cartelle dei font. |
| [clearCache()](#clearCache--) | Rilascia tutti i font personalizzati definiti dall'utente |
### loadExternalFonts(String[] directories) {#loadExternalFonts-java.lang.String---}
```
public static void loadExternalFonts(String[] directories)
```


Aggiunge cartelle aggiuntive per cercare i font.

--------------------

> ```
> The follow examples shows how to load custom fonts from .TTF
>  
>  String dataDir = "C:/Fonts";
>  // cartelle per cercare i font
>  String[] folders = new String[] { dataDir };
>  // Carica i font della cartella dei font personalizzati
>  FontsLoader.loadExternalFonts(folders);
>  // Esegui qualche operazione e rendi la presentazione/diapositive
>  Presentation pres = new Presentation("DefaultFonts.pptx");
>  try {
>      pres.save("NewFonts_out.pptx", SaveFormat.Pptx);
>      // Cancella la cache dei font
>      FontsLoader.clearCache();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| directories | java.lang.String[] | Cartelle da leggere per font aggiuntivi. |

### loadExternalFont(byte[] data) {#loadExternalFont-byte---}
```
public static void loadExternalFont(byte[] data)
```


Aggiunge il font dai dati binari

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | byte[] | Dati del font |

### getFontFolders() {#getFontFolders--}
```
public static String[] getFontFolders()
```


Ottiene le cartelle dei font. Restituisce le cartelle aggiunte con il metodo LoadExternalFonts così come le cartelle dei font di sistema

**Restituisce:**
java.lang.String[] - array contenente i nomi delle cartelle
### clearCache() {#clearCache--}
```
public static void clearCache()
```


Rilascia tutti i font personalizzati definiti dall'utente

--------------------

Questo metodo deve cancellare la cache con i font personalizzati definiti dall'utente.