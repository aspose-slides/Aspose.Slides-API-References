---
title: FontFallBackRulesCollection
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje kolekci pravidel FontFallBack definovaných uživatelem
type: docs
url: /cs/com.aspose.slides/fontfallbackrulescollection/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)
```
public class FontFallBackRulesCollection implements IFontFallBackRulesCollection
```

Reprezentuje kolekci pravidel FontFallBack definovaných uživatelem
## Konstruktory

| Constructor | Popis |
| --- | --- |
| [FontFallBackRulesCollection()](#FontFallBackRulesCollection--) |  |
## Metody

| Method | Popis |
| --- | --- |
| [size()](#size--) | Získá počet pravidel skutečně obsažených v kolekci. |
| [add(IFontFallBackRule sourceRule)](#add-com.aspose.slides.IFontFallBackRule-) | Přidá zadané pravidlo FallBack na konec kolekce. |
| [remove(IFontFallBackRule targetRule)](#remove-com.aspose.slides.IFontFallBackRule-) | Odstraní první výskyt konkrétního pravidla FallBack z kolekce. |
| [get_Item(int index)](#get-Item-int-) | Získá pravidlo na zadaném indexu. |
| [iterator()](#iterator--) | Vrátí enumerátor, který prochází kolekcí. |
| [iteratorJava()](#iteratorJava--) | Vrátí java iterátor pro celou kolekci. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Zkopíruje všechny prvky z kolekce do zadaného pole. |
| [isSynchronized()](#isSynchronized--) | Vrátí hodnotu indikující, zda je přístup ke kolekci synchronizován (vláknově bezpečný). |
| [getSyncRoot()](#getSyncRoot--) | Vrátí kořen synchronizace. |
### FontFallBackRulesCollection() {#FontFallBackRulesCollection--}
```
public FontFallBackRulesCollection()
```


### size() {#size--}
```
public final int size()
```


Získá počet pravidel skutečně obsažených v kolekci. Pouze pro čtení int.

**Vrací:**
int
### add(IFontFallBackRule sourceRule) {#add-com.aspose.slides.IFontFallBackRule-}
```
public final void add(IFontFallBackRule sourceRule)
```


Přidá zadané pravidlo FallBack na konec kolekce.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //Získání prázdné nebo předinicializované kolekce pravidel z FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //Přidání nového pravidla do kolekce
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parameter | Type | Popis |
| --- | --- | --- |
| sourceRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | Zadané pravidlo pro přidání |

### remove(IFontFallBackRule targetRule) {#remove-com.aspose.slides.IFontFallBackRule-}
```
public final void remove(IFontFallBackRule targetRule)
```


Odstraní první výskyt konkrétního pravidla FallBack z kolekce.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //Získání prázdné nebo předinicializované kolekce pravidel z FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //Přidání několika pravidel do kolekce
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //Získání objektu prvního pravidla v kolekci
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>      //Odstranění
>      rulesList.remove(firstRule);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parameter | Type | Popis |
| --- | --- | --- |
| targetRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | Pravidlo, které má být odebráno z kolekce. |

### get_Item(int index) {#get-Item-int-}
```
public final IFontFallBackRule get_Item(int index)
```


Získá pravidlo na zadaném indexu. Pouze pro čtení [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //Získání prázdné nebo předinicializované kolekce pravidel z FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //Přidání několika pravidel do kolekce
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //Získání objektu prvního pravidla v kolekci
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parameter | Type | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontFallBackRule> iterator()
```


Vrátí enumerátor, který prochází kolekcí.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontFallBackRule> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontFallBackRule> iteratorJava()
```


Vrátí java iterátor pro celou kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontFallBackRule> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Zkopíruje všechny prvky z kolekce do zadaného pole.

**Parametry:**
| Parameter | Type | Popis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cílové pole. |
| index | int | Počáteční index v cílovém poli. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Vrátí hodnotu indikující, zda je přístup ke kolekci synchronizován (vláknově bezpečný). Pouze pro čtení boolean.

**Vrací:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Vrátí kořen synchronizace. Pouze pro čtení Object.

**Vrací:**
java.lang.Object