---
title: ITabEffectiveData
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: Megváltoztathatatlan objektum, amely a szövegek tényleges tabulátorállomás tulajdonságait tartalmazza.
type: docs
url: /hu/com.aspose.slides/itabeffectivedata/
---
**Az összes megvalósított interfész:**
java.lang.Comparable
```
public interface ITabEffectiveData extends Comparable
```

Megváltoztathatatlan objektum, amely a szöveg tényleges tabulátorállomás tulajdonságait tartalmazza.

--------------------

Ez az interfész a [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) részeként használatos.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [getPosition()](#getPosition--) | Visszaadja egy tabulátor pozícióját. |
| [getAlignment()](#getAlignment--) | Visszaadja egy tabulátor igazítási stílusát. |
### getPosition() {#getPosition--}
```
public abstract double getPosition()
```


Visszaadja egy tabulátor pozícióját. Ennek a tulajdonságnak az értékadása megváltoztathatja a tabulátor indexét a gyűjteményben, és érvénytelenítheti az Enumerator-t. Csak olvasható double.

**Visszatérési érték:**  
double
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```


Visszaadja egy tabulátor igazítási stílusát. Csak olvasható [TabAlignment](../../com.aspose.slides/tabalignment).

**Visszatérési érték:**  
int