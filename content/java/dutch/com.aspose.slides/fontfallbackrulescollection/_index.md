---
title: FontFallBackRulesCollection
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een door de gebruiker gedefinieerde verzameling FontFallBack-regels voor
type: docs
url: /nl/com.aspose.slides/fontfallbackrulescollection/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)
```
public class FontFallBackRulesCollection implements IFontFallBackRulesCollection
```

Stelt een collectie van FontFallBack-regels voor, gedefinieerd door de gebruiker
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [FontFallBackRulesCollection()](#FontFallBackRulesCollection--) |  |
## Methods

| Methode | Beschrijving |
| --- | --- |
| [size()](#size--) | Haalt het aantal regels op dat daadwerkelijk in de collectie aanwezig is. |
| [add(IFontFallBackRule sourceRule)](#add-com.aspose.slides.IFontFallBackRule-) | Voeg een opgegeven FallBack-regel toe aan het einde van de collectie. |
| [remove(IFontFallBackRule targetRule)](#remove-com.aspose.slides.IFontFallBackRule-) | Verwijdert de eerste instantie van een specifieke FallBack-regel uit de collectie. |
| [get_Item(int index)](#get-Item-int-) | Haalt de regel op op de opgegeven index. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie itereren. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java-iterator voor de volledige collectie. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopieert alle elementen uit de collectie naar de opgegeven array. |
| [isSynchronized()](#isSynchronized--) | Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retourneert de synchronisatiewortel. |
### FontFallBackRulesCollection() {#FontFallBackRulesCollection--}
```
public FontFallBackRulesCollection()
```


### size() {#size--}
```
public final int size()
```


Haalt het aantal regels op dat daadwerkelijk in de collectie aanwezig is. Alleen-lezen int.

**Retour:**
int
### add(IFontFallBackRule sourceRule) {#add-com.aspose.slides.IFontFallBackRule-}
```
public final void add(IFontFallBackRule sourceRule)
```


Voeg een opgegeven FallBack-regel toe aan het einde van de collectie.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //Getting of empty or preinitialized rules collection from FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //Adding of new rule to collection
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | Opgegeven regel voor toevoegen |

### remove(IFontFallBackRule targetRule) {#remove-com.aspose.slides.IFontFallBackRule-}
```
public final void remove(IFontFallBackRule targetRule)
```


Verwijdert de eerste instantie van een specifieke FallBack-regel uit de collectie.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //Getting of empty or preinitialized rules collection from FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //Adding of several rules to collection
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //Retrieving of object of the first rule in collection
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>      //Removing 
>      rulesList.remove(firstRule);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| targetRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | De regel die uit de collectie moet worden verwijderd. |

### get_Item(int index) {#get-Item-int-}
```
public final IFontFallBackRule get_Item(int index)
```


Haalt de regel op op de opgegeven index. Alleen-lezen [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //Getting of empty or preinitialized rules collection from FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //Adding of several rules to collection
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //Retrieving of object of the first rule in collection
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retour:**
[IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontFallBackRule> iterator()
```


Retourneert een enumerator die door de collectie itereren.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontFallBackRule> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontFallBackRule> iteratorJava()
```


Retourneert een java-iterator voor de volledige collectie.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontFallBackRule> - Een java.util.Iterator voor de volledige collectie.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Kopieert alle elementen uit de collectie naar de opgegeven array.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Doelarrray. |
| index | int | Startindex in de doelarray. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-safe). Alleen-lezen boolean.

**Retour:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Retourneert de synchronisatiewortel. Alleen-lezen Object.

**Retour:**
java.lang.Object