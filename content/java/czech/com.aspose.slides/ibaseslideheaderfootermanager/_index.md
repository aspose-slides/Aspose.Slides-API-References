---
title: IBaseSlideHeaderFooterManager
second_title: Aspose.Slides pro Java - reference API
description: Reprezentuje manažer, který obsahuje chování placeholderů zápatí, datum-času a číslování stránek pro všechny typy snímků.
type: docs
url: /cs/com.aspose.slides/ibaseslideheaderfootermanager/
---
**Všechna implementovaná rozhraní:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IBaseSlideHeaderFooterManager extends IBaseHeaderFooterManager
```

Reprezentuje manažer, který obsahuje chování placeholderů zápatí, datum-času a číslování stránek pro všechny typy snímků.
## Metody

| Metoda | Popis |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | Získá hodnotu indikující, že placeholder zápatí je přítomen. |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | Získá hodnotu indikující, že placeholder čísla stránky je přítomen. |
| [isDateTimeVisible()](#isDateTimeVisible--) | Získá hodnotu indikující, že placeholder datum-času je přítomen. |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | Mění viditelnost placeholderu zápatí snímku. |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | Mění viditelnost placeholderu čísla stránky snímku. |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | Mění viditelnost placeholderu datum-času snímku. |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | Nastaví text do placeholderu zápatí snímku. |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | Nastaví text do placeholderu datum-času snímku. |
### isFooterVisible() {#isFooterVisible--}
```
public abstract boolean isFooterVisible()
```


Získá hodnotu indikující, že placeholder zápatí je přítomen. Čte boolean.

**Vrací:**
boolean
### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public abstract boolean isSlideNumberVisible()
```


Získá hodnotu indikující, že placeholder čísla stránky je přítomen. Čte boolean.

**Vrací:**
boolean
### isDateTimeVisible() {#isDateTimeVisible--}
```
public abstract boolean isDateTimeVisible()
```


Získá hodnotu indikující, že placeholder datum-času je přítomen. Čte boolean.

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


Mění viditelnost placeholderu datum-času snímku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| isVisible | boolean | true - zobrazí placeholder datum-času, jinak jej skryje. |

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


Nastaví text do placeholderu datum-času snímku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Text k nastavení. |