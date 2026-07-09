---
title: ISlideText
second_title: Aspose.Slides for Android via Java API Reference
description: Représente le texte extrait de la diapositive
type: docs
url: /fr/com.aspose.slides/islidetext/
---```
public interface ISlideText
```

Représente le texte extrait de la diapositive
## Méthodes

| Méthode | Description |
| --- | --- |
| [getText()](#getText--) | Le texte sur les formes de la diapositive |
| [getMasterText()](#getMasterText--) | Le texte sur les formes de la page maître pour cette diapositive |
| [getLayoutText()](#getLayoutText--) | Le texte sur les formes de la page de mise en page pour cette diapositive |
| [getNotesText()](#getNotesText--) | Le texte sur les formes de la page de notes pour cette diapositive |
| [getCommentsText()](#getCommentsText--) | Le texte des commentaires de la diapositive |
### getText() {#getText--}
```
public abstract String getText()
```

Le texte sur les formes de la diapositive

**Retour:**  
java.lang.String
### getMasterText() {#getMasterText--}
```
public abstract String getMasterText()
```

Le texte sur les formes de la page maître pour cette diapositive

**Retour:**  
java.lang.String
### getLayoutText() {#getLayoutText--}
```
public abstract String getLayoutText()
```

Le texte sur les formes de la page de mise en page pour cette diapositive

**Retour:**  
java.lang.String
### getNotesText() {#getNotesText--}
```
public abstract String getNotesText()
```

Le texte sur les formes de la page de notes pour cette diapositive

**Retour:**  
java.lang.String
### getCommentsText() {#getCommentsText--}
```
public abstract String getCommentsText()
```

Le texte des commentaires de la diapositive

--------------------

Ce champ est vide lorsque le texte est extrait en utilisant le mode Arranged.

**Retour:**  
java.lang.String