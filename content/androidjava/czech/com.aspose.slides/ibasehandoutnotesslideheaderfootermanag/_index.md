---
title: IBaseHandoutNotesSlideHeaderFooterManag
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Reprezentuje správce, který obsahuje chování zástupných prvků, včetně záhlaví zástupného prvku pro všechny typy handout a notes snímků.
type: docs
url: /cs/com.aspose.slides/ibasehandoutnotesslideheaderfootermanag/
---
**Všechna implementovaná rozhraní:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IBaseHandoutNotesSlideHeaderFooterManag extends IBaseSlideHeaderFooterManager
```

Reprezentuje správce, který obsahuje chování zástupných prvků, včetně záhlaví zástupného prvku pro všechny typy rozdílových a poznámkových snímků.

--------------------

Původní název rozhraní "IBaseHandoutNotesSlideHeaderFooterManager" je zkrácen na "IBaseHandoutNotesSlideHeaderFooterManag" pro kompatibilitu s COM (délka názvu typu nesmí být delší než 39).
## Metody

| Metoda | Popis |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | Získá hodnotu indikující, že záhlaví zástupného prvku je přítomno. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | Mění viditelnost záhlaví zástupného prvku snímku. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | Nastaví text do záhlaví zástupného prvku snímku. |
### isHeaderVisible() {#isHeaderVisible--}
```
public abstract boolean isHeaderVisible()
```


Získá hodnotu indikující, že záhlaví zástupného prvku je přítomno. Read boolean.

**Vrací:**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public abstract void setHeaderVisibility(boolean isVisible)
```


Mění viditelnost záhlaví zástupného prvku snímku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| isVisible | boolean | true - zobrazí záhlaví zástupného prvku, jinak jej skryje. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public abstract void setHeaderText(String text)
```


Nastaví text do záhlaví zástupného prvku snímku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Text, který se má nastavit. |