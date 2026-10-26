---
title: ISlideText
second_title: Aspose.Slides for Java API Reference
description: Represents the text extracted from the slide
type: docs
url: /fr/com.aspose.slides/islidetext/
---```
public interface ISlideText
```

Représente le texte extrait de la diapositive
## Méthodes

| Méthode | Description |
| --- | --- |
| [getText()](#getText--) | Le texte des formes de la diapositive |
| [getMasterText()](#getMasterText--) | Le texte des formes de la page maître pour cette diapositive |
| [getLayoutText()](#getLayoutText--) | Le texte des formes de la page de mise en page pour cette diapositive |
| [getNotesText()](#getNotesText--) | Le texte des formes de la page de notes pour cette diapositive |
| [getCommentsText()](#getCommentsText--) | Le texte des commentaires de la diapositive |
### getText() {#getText--}
```
public abstract String getText()
```


Le texte des formes de la diapositive

**Renvoie :**
java.lang.String
### getMasterText() {#getMasterText--}
```
public abstract String getMasterText()
```


Le texte des formes de la page maître pour cette diapositive

**Renvoie :**
java.lang.String
### getLayoutText() {#getLayoutText--}
```
public abstract String getLayoutText()
```


Le texte des formes de la page de mise en page pour cette diapositive

**Renvoie :**
java.lang.String
### getNotesText() {#getNotesText--}
```
public abstract String getNotesText()
```


Le texte des formes de la page de notes pour cette diapositive

**Renvoie :**
java.lang.String
### getCommentsText() {#getCommentsText--}
```
public abstract String getCommentsText()
```


Le texte des commentaires de la diapositive

--------------------

Ce champ est vide lorsque le texte est extrait en utilisant le mode Arranged.

**Renvoie :**
java.lang.String