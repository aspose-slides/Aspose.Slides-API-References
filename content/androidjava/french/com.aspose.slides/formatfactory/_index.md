---
title: FormatFactory
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Permet de créer des formats via l'interface COM.
type: docs
url: /fr/com.aspose.slides/formatfactory/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IFormatFactory](../../com.aspose.slides/iformatfactory)
```
public class FormatFactory implements IFormatFactory
```

Permet de créer des formats via l'interface COM.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FormatFactory()](#FormatFactory--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getInstance()](#getInstance--) | Instance statique du fabrique de formats. |
| [createPortionFormat()](#createPortionFormat--) | Crée un nouveau [IPortionFormat](../../com.aspose.slides/iportionformat). |
| [createParagraphFormat()](#createParagraphFormat--) | Crée un nouveau [IParagraphFormat](../../com.aspose.slides/iparagraphformat). |
| [createTextFrameFormat()](#createTextFrameFormat--) | Crée un nouveau [ITextFrameFormat](../../com.aspose.slides/itextframeformat). |
### FormatFactory() {#FormatFactory--}
```
public FormatFactory()
```


### getInstance() {#getInstance--}
```
public static FormatFactory getInstance()
```


Instance statique du fabrique de formats. Lecture seule [FormatFactory](../../com.aspose.slides/formatfactory).

**Renvoie :**
[FormatFactory](../../com.aspose.slides/formatfactory)
### createPortionFormat() {#createPortionFormat--}
```
public final IPortionFormat createPortionFormat()
```


Crée un nouveau [IPortionFormat](../../com.aspose.slides/iportionformat).

**Renvoie :**
[IPortionFormat](../../com.aspose.slides/iportionformat) - Nouveau format de portion.
### createParagraphFormat() {#createParagraphFormat--}
```
public final IParagraphFormat createParagraphFormat()
```


Crée un nouveau [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Renvoie :**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Nouveau format de paragraphe.
### createTextFrameFormat() {#createTextFrameFormat--}
```
public final ITextFrameFormat createTextFrameFormat()
```


Crée un nouveau [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**Renvoie :**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat) - Nouveau format de cadre de texte.