---
title: IBaseHandoutNotesSlideHeaderFooterManag
second_title: Aspose.Slides pro Java – referenční dokumentace
description: Reprezentuje správce, který obsahuje chování zástupných objektů, včetně zástupného objektu záhlaví pro všechny typy slidů s výtisky a poznámkami.
type: docs
url: /cs/com.aspose.slides/ibasehandoutnotesslideheaderfootermanag/
---
**Všechna implementovaná rozhraní:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IBaseHandoutNotesSlideHeaderFooterManag extends IBaseSlideHeaderFooterManager
```

Reprezentuje správce, který obsahuje chování zástupných objektů, včetně zástupného objektu záhlaví pro všechny typy slidů s výtisky a poznámkami.

--------------------

Původní název rozhraní "IBaseHandoutNotesSlideHeaderFooterManager" je zkrácen na "IBaseHandoutNotesSlideHeaderFooterManag" pro kompatibilitu s COM (délka názvu typu nesmí být větší než 39).
## Metody

| Metoda | Popis |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | Získá hodnotu indikující, že je přítomen zástupný objekt záhlaví. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | Mění viditelnost zástupného objektu záhlaví slidu. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | Nastaví text do zástupného objektu záhlaví slidu. |
### isHeaderVisible() {#isHeaderVisible--}
```
public abstract boolean isHeaderVisible()
```


Získá hodnotu indikující, že je přítomen zástupný objekt záhlaví. Čte boolean.

**Vrací:**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public abstract void setHeaderVisibility(boolean isVisible)
```


Mění viditelnost zástupného objektu záhlaví slidu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| isVisible | boolean | true – zobrazí zástupný objekt záhlaví, jinak jej skryje. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public abstract void setHeaderText(String text)
```


Nastaví text do zástupného objektu záhlaví slidu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Text, který se má nastavit. |