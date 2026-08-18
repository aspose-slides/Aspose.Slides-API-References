---
title: ITabEffectiveData
second_title: Aspose.Slides for Java API referenciája
description: Megváltoztathatatlan objektum, amely a hatékony szövegek táblázatállomás tulajdonságait tartalmazza.
type: docs
url: /hu/com.aspose.slides/itabeffectivedata/
---
**Az összes megvalósított interfész:**
java.lang.Comparable
```
public interface ITabEffectiveData extends Comparable
```

Megváltoztathatatlan objektum, amely a hatékony szöveg táblázatállomás tulajdonságait tartalmazza.

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


Visszaadja egy tabulátor pozícióját. Ennek a tulajdonságnak az értékadásával megváltoztatható a tabulátor indexe a gyűjteményben, és érvényteleníthető az Enumerator. Csak olvasható double.

**Visszatér:**
double
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```


Visszaadja egy tabulátor igazítási stílusát. Csak olvasható [TabAlignment](../../com.aspose.slides/tabalignment).

**Visszatér:**
int