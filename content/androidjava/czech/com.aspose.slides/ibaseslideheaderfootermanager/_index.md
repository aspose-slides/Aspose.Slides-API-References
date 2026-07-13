---
title: IBaseSlideHeaderFooterManager
second_title: Aspose.Slides pro Android přes Java API
description: Reprezentuje manažera, který obsahuje chování placeholderů zápatí, data-času a čísla stránky pro všechny typy snímků.
type: docs
url: /cs/com.aspose.slides/ibaseslideheaderfootermanager/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IBaseSlideHeaderFooterManager extends IBaseHeaderFooterManager
```

Reprezentuje manažera, který obsahuje chování placeholderů zápatí, data-času a čísla stránky pro všechny typy snímků.
## Metody

| Metoda | Popis |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | Gets value indicating that a footer placeholder is present. |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | Gets value indicating that a page number placeholder is present. |
| [isDateTimeVisible()](#isDateTimeVisible--) | Gets value indicating that a date-time placeholder is present. |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | Changes slide footer placeholder visibility. |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | Changes slide page number placeholder visibility. |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | Changes slide date-time placeholder visibility. |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | Sets text to slide footer placeholder. |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | Sets text to slide date-time placeholder. |
### isFooterVisible() {#isFooterVisible--}
```
public abstract boolean isFooterVisible()
```

Vrací hodnotu indikující, že placeholder zápatí je přítomen. Čte boolean.

**Vrací:**
boolean
### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public abstract boolean isSlideNumberVisible()
```

Vrací hodnotu indikující, že placeholder čísla stránky je přítomen. Čte boolean.

**Vrací:**
boolean
### isDateTimeVisible() {#isDateTimeVisible--}
```
public abstract boolean isDateTimeVisible()
```

Vrací hodnotu indikující, že placeholder data-času je přítomen. Čte boolean.

**Vrací:**
boolean
### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public abstract void setFooterVisibility(boolean isVisible)
```

Mění viditelnost placeholderu zápatí snímku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| isVisible | boolean | true - zobrazí placeholder zápatí, jinak jej skryje. |
### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public abstract void setSlideNumberVisibility(boolean isVisible)
```

Mění viditelnost placeholderu čísla stránky snímku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| isVisible | boolean | true - zobrazí placeholder čísla stránky, jinak jej skryje. |
### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public abstract void setDateTimeVisibility(boolean isVisible)
```

Mění viditelnost placeholderu data-času snímku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| isVisible | boolean | true - zobrazí placeholder data-času, jinak jej skryje. |
### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public abstract void setFooterText(String text)
```

Nastaví text do placeholderu zápatí snímku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Text k nastavení. |
### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public abstract void setDateTimeText(String text)
```

Nastaví text do placeholderu data-času snímku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Text k nastavení. |