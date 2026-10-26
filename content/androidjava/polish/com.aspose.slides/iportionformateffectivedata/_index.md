---
title: IPortionFormatEffectiveData
second_title: Aspose.Slides dla Androida – odniesienie API Java
description: Niezmienny obiekt, który zawiera właściwości formatowania efektywnej części tekstu.
type: docs
url: /pl/com.aspose.slides/iportionformateffectivedata/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IBasePortionFormatEffectiveData](../../com.aspose.slides/ibaseportionformateffectivedata)
```
public interface IPortionFormatEffectiveData extends IBasePortionFormatEffectiveData
```

Niezmienny obiekt, który zawiera właściwości formatowania efektywnej części tekstu.

--------------------

Ten interfejs jest używany razem z interfejsem [IPortionFormat](../../com.aspose.slides/iportionformat), aby zwrócić efektywne wartości formatowania z zastosowanym dziedziczeniem.
## Metody

| Metoda | Opis |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Zwraca identyfikator zakładki. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Zwraca hiperłącze określone dla kliknięcia myszy. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Zwraca hiperłącze określone dla najazdu kursorem. |
### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```

Zwraca identyfikator zakładki. Tylko do odczytu String.

**Zwraca:**
java.lang.String
### getHyperlinkClick() {#getHyperlinkClick--}
```
public abstract IHyperlink getHyperlinkClick()
```

Zwraca hiperłącze określone dla kliknięcia myszy. Tylko do odczytu [IHyperlink](../../com.aspose.slides/ihyperlink).

**Zwraca:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public abstract IHyperlink getHyperlinkMouseOver()
```

Zwraca hiperłącze określone dla najazdu kursorem. Tylko do odczytu [IHyperlink](../../com.aspose.slides/ihyperlink).

**Zwraca:**
[IHyperlink](../../com.aspose.slides/ihyperlink)