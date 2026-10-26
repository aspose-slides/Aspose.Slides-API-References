---
title: ISlideText
second_title: Aspose.Slides for Android via Java API Reference
description: Represents the text extracted from the slide
type: docs
url: /it/com.aspose.slides/islidetext/
---```
public interface ISlideText
```

Rappresenta il testo estratto dalla diapositiva
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getText()](#getText--) | Il testo sulle forme della diapositiva |
| [getMasterText()](#getMasterText--) | Il testo sulle forme della pagina master per questa diapositiva |
| [getLayoutText()](#getLayoutText--) | Il testo sulle forme della pagina layout per questa diapositiva |
| [getNotesText()](#getNotesText--) | Il testo sulle forme della pagina delle note per questa diapositiva |
| [getCommentsText()](#getCommentsText--) | Il testo dei commenti della diapositiva |
### getText() {#getText--}
```
public abstract String getText()
```

Il testo sulle forme della diapositiva

**Restituisce:**
java.lang.String
### getMasterText() {#getMasterText--}
```
public abstract String getMasterText()
```

Il testo sulle forme della pagina master per questa diapositiva

**Restituisce:**
java.lang.String
### getLayoutText() {#getLayoutText--}
```
public abstract String getLayoutText()
```

Il testo sulle forme della pagina layout per questa diapositiva

**Restituisce:**
java.lang.String
### getNotesText() {#getNotesText--}
```
public abstract String getNotesText()
```

Il testo sulle forme della pagina delle note per questa diapositiva

**Restituisce:**
java.lang.String
### getCommentsText() {#getCommentsText--}
```
public abstract String getCommentsText()
```

Il testo dei commenti della diapositiva

--------------------

Questo campo è vuoto quando il testo è estratto utilizzando la modalità Arranged.

**Restituisce:**
java.lang.String