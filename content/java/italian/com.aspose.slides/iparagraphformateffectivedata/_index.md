---
title: IParagraphFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Oggetto immutabile che contiene le proprietà di formattazione effettiva del paragrafo.
type: docs
url: /it/com.aspose.slides/iparagraphformateffectivedata/
---```
public interface IParagraphFormatEffectiveData
```

Oggetto immutabile che contiene le proprietà di formattazione effettiva del paragrafo.

--------------------

Questa interfaccia è usata insieme all'interfaccia [IParagraphFormat](../../com.aspose.slides/iparagraphformat) per restituire i valori di formattazione effettiva con l'ereditarietà applicata.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBullet()](#getBullet--) | Restituisce un formato bullet di un paragrafo. |
| [getDepth()](#getDepth--) | Restituisce la profondità di un paragrafo. |
| [getAlignment()](#getAlignment--) | Restituisce l'allineamento del testo in un paragrafo. |
| [getSpaceWithin()](#getSpaceWithin--) | Restituisce la quantità di spazio tra le linee di base in un paragrafo. |
| [getSpaceBefore()](#getSpaceBefore--) | Restituisce la quantità di spazio prima della prima riga in un paragrafo. |
| [getSpaceAfter()](#getSpaceAfter--) | Restituisce la quantità di spazio dopo l'ultima riga in un paragrafo. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Determina se il ritorno a capo asiatico è usato in un paragrafo. |
| [getRightToLeft()](#getRightToLeft--) | Determina se la scrittura da destra a sinistra è usata in un paragrafo. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Determina se il ritorno a capo latino è usato in un paragrafo. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Determina se la punteggiatura sospesa è usata in un paragrafo. |
| [getMarginLeft()](#getMarginLeft--) | Restituisce il margine sinistro in un paragrafo. |
| [getMarginRight()](#getMarginRight--) | Restituisce il margine destro in un paragrafo. |
| [getIndent()](#getIndent--) | Restituisce l'Indentazione della Prima Riga/Indentazione Sospesa del paragrafo. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Restituisce la dimensione predefinita della tabulazione. |
| [getTabs()](#getTabs--) | Restituisce le tabulazioni di un paragrafo. |
| [getFontAlignment()](#getFontAlignment--) | Restituisce l'allineamento del carattere in un paragrafo. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Restituisce il formato porzione predefinito di un paragrafo. |
### getBullet() {#getBullet--}
```
public abstract IBulletFormatEffectiveData getBullet()
```

Restituisce un formato bullet di un paragrafo. Solo lettura [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).

**Restituisce:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)
### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

Restituisce la profondità di un paragrafo. Solo lettura short.

**Restituisce:**
short
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

Restituisce l'allineamento del testo in un paragrafo. Solo lettura [TextAlignment](../../com.aspose.slides/textalignment).

**Restituisce:**
int
### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

Restituisce la quantità di spazio tra le linee di base in un paragrafo. Solo lettura float.

**Restituisce:**
float
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

Restituisce la quantità di spazio prima della prima riga in un paragrafo. Solo lettura float.

**Restituisce:**
float
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

Restituisce la quantità di spazio dopo l'ultima riga in un paragrafo. Solo lettura float.

**Restituisce:**
float
### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract boolean getEastAsianLineBreak()
```

Determina se il ritorno a capo asiatico è usato in un paragrafo. Solo lettura boolean.

**Restituisce:**
boolean
### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

Determina se la scrittura da destra a sinistra è usata in un paragrafo. Solo lettura boolean.

**Restituisce:**
boolean
### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract boolean getLatinLineBreak()
```

Determina se il ritorno a capo latino è usato in un paragrafo. Solo lettura boolean.

**Restituisce:**
boolean
### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract boolean getHangingPunctuation()
```

Determina se la punteggiatura sospesa è usata in un paragrafo. Solo lettura boolean.

**Restituisce:**
boolean
### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

Restituisce il margine sinistro in un paragrafo. Solo lettura float.

**Restituisce:**
float
### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

Restituisce il margine destro in un paragrafo. Solo lettura float.

**Restituisce:**
float
### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

Restituisce l'Indentazione della Prima Riga/Indentazione Sospesa del paragrafo. L'Indentazione sospesa può essere definita con valori negativi. Solo lettura float.

**Restituisce:**
float
### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

Restituisce la dimensione predefinita della tabulazione. Solo lettura float.

**Restituisce:**
float
### getTabs() {#getTabs--}
```
public abstract ITabEffectiveData[] getTabs()
```

Restituisce le tabulazioni di un paragrafo. Solo lettura ITabEffectiveData[].

**Restituisce:**
com.aspose.slides.ITabEffectiveData[]
### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

Restituisce l'allineamento del carattere in un paragrafo. Solo lettura [FontAlignment](../../com.aspose.slides/fontalignment).

**Restituisce:**
int
### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormatEffectiveData getDefaultPortionFormat()
```

Restituisce il formato porzione predefinito di un paragrafo. Solo lettura [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

**Restituisce:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)