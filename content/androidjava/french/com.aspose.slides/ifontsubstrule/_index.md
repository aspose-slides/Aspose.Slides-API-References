---
title: IFontSubstRule
second_title: Aspose.Slides for Android via Java API Reference
description: Représente les informations de substitution de police
type: docs
url: /fr/com.aspose.slides/ifontsubstrule/
---```
public interface IFontSubstRule
```

Représente les informations de substitution de police
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | Police à substituer Lecture seule [IFontData](../../com.aspose.slides/ifontdata). |
| [getDestFont()](#getDestFont--) | Police à utiliser pour la substitution Lecture seule [IFontData](../../com.aspose.slides/ifontdata). |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | Règle à appliquer pour la substitution Lecture seule [FontSubstCondition](../../com.aspose.slides/fontsubstcondition). |
### getSourceFont() {#getSourceFont--}
```
public abstract IFontData getSourceFont()
```


Police à substituer Lecture seule [IFontData](../../com.aspose.slides/ifontdata).

**Renvoie :**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public abstract IFontData getDestFont()
```


Police à utiliser pour la substitution Lecture seule [IFontData](../../com.aspose.slides/ifontdata).

**Renvoie :**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public abstract int getReplaceFontCondition()
```


Règle à appliquer pour la substitution Lecture seule [FontSubstCondition](../../com.aspose.slides/fontsubstcondition).

**Renvoie :**
int