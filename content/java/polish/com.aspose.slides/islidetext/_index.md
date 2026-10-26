---
title: ISlideText
second_title: Aspose.Slides for Java API Reference
description: Reprezentuje tekst wyodrębniony ze slajdu
type: docs
url: /pl/com.aspose.slides/islidetext/
---```
public interface ISlideText
```

Reprezentuje tekst wyodrębniony ze slajdu
## Metody

| Metoda | Opis |
| --- | --- |
| [getText()](#getText--) | Tekst na kształtach slajdu |
| [getMasterText()](#getMasterText--) | Tekst na kształtach strony głównej dla tego slajdu |
| [getLayoutText()](#getLayoutText--) | Tekst na kształtach strony układu dla tego slajdu |
| [getNotesText()](#getNotesText--) | Tekst na kształtach strony notatek dla tego slajdu |
| [getCommentsText()](#getCommentsText--) | Tekst komentarzy slajdu |
### getText() {#getText--}
```
public abstract String getText()
```


Tekst na kształtach slajdu

**Zwraca:**
java.lang.String
### getMasterText() {#getMasterText--}
```
public abstract String getMasterText()
```


Tekst na kształtach strony głównej dla tego slajdu

**Zwraca:**
java.lang.String
### getLayoutText() {#getLayoutText--}
```
public abstract String getLayoutText()
```


Tekst na kształtach strony układu dla tego slajdu

**Zwraca:**
java.lang.String
### getNotesText() {#getNotesText--}
```
public abstract String getNotesText()
```


Tekst na kształtach strony notatek dla tego slajdu

**Zwraca:**
java.lang.String
### getCommentsText() {#getCommentsText--}
```
public abstract String getCommentsText()
```


Tekst komentarzy slajdu

--------------------

To pole jest puste, gdy tekst jest wyodrębniany przy użyciu trybu Arranged.

**Zwraca:**
java.lang.String