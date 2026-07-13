---
title: FontFallBackRulesCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av FontFallBack-regler definierade av användaren
type: docs
url: /sv/com.aspose.slides/fontfallbackrulescollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)
```
public class FontFallBackRulesCollection implements IFontFallBackRulesCollection
```

Representerar en samling av FontFallBack-regler, definierade av användaren
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [FontFallBackRulesCollection()](#FontFallBackRulesCollection--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [size()](#size--) | Hämtar antalet regler som faktiskt finns i samlingen. |
| [add(IFontFallBackRule sourceRule)](#add-com.aspose.slides.IFontFallBackRule-) | Lägger till en specificerad FallBack-regel i slutet av samlingen. |
| [remove(IFontFallBackRule targetRule)](#remove-com.aspose.slides.IFontFallBackRule-) | Tar bort den första förekomsten av en specifik FallBack-regel från samlingen. |
| [get_Item(int index)](#get-Item-int-) | Hämtar regeln på angivet index. |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [iteratorJava()](#iteratorJava--) | Returnerar en java-iterator för hela samlingen. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopierar alla element från samlingen till den angivna arrayen. |
| [isSynchronized()](#isSynchronized--) | Returnerar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). |
| [getSyncRoot()](#getSyncRoot--) | Returnerar ett synkroniseringsrot. |
### FontFallBackRulesCollection() {#FontFallBackRulesCollection--}
```
public FontFallBackRulesCollection()
```


### size() {#size--}
```
public final int size()
```

Hämtar antalet regler som faktiskt finns i samlingen. Skrivskyddad int.

**Returnerar:**
int
### add(IFontFallBackRule sourceRule) {#add-com.aspose.slides.IFontFallBackRule-}
```
public final void add(IFontFallBackRule sourceRule)
```

Lägger till en specificerad FallBack-regel i slutet av samlingen.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //Hämtar en tom eller förinitierad regelssamling från FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //Lägger till en ny regel i samlingen
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | Specificerad regel för tillägg |

### remove(IFontFallBackRule targetRule) {#remove-com.aspose.slides.IFontFallBackRule-}
```
public final void remove(IFontFallBackRule targetRule)
```

Tar bort den första förekomsten av en specifik FallBack-regel från samlingen.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| targetRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | Reglen som ska tas bort från samlingen. |

### get_Item(int index) {#get-Item-int-}
```
public final IFontFallBackRule get_Item(int index)
```

Hämtar regeln på angivet index. Skrivskyddad [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //Hämtar en tom eller förinitierad regelssamling från FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //Lägger till flera regler i samlingen
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //Hämtar objektet för den första regeln i samlingen
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontFallBackRule> iterator()
```

Returnerar en enumerator som itererar genom samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontFallBackRule> - En IGenericEnumerator som kan användas för att iterera genom samlingen.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontFallBackRule> iteratorJava()
```

Returnerar en java-iterator för hela samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontFallBackRule> - En java.util.Iterator för hela samlingen.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopierar alla element från samlingen till den angivna arrayen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Målarray. |
| index | int | Startindex i målarry. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Returnerar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). Skrivskyddad boolean.

**Returnerar:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Returnerar ett synkroniseringsrot. Skrivskyddad Object.

**Returnerar:**
java.lang.Object