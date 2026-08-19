---
title: FontFallBackRulesCollection
second_title: Riferimento API Aspose.Slides per Java
description: Rappresenta una collezione di regole FontFallBack definite dall'utente
type: docs
url: /it/com.aspose.slides/fontfallbackrulescollection/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)
```
public class FontFallBackRulesCollection implements IFontFallBackRulesCollection
```

Rappresenta una collezione di regole FontFallBack, definite dall'utente
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FontFallBackRulesCollection()](#FontFallBackRulesCollection--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [size()](#size--) | Ottiene il numero di regole effettivamente contenute nella collezione. |
| [add(IFontFallBackRule sourceRule)](#add-com.aspose.slides.IFontFallBackRule-) | Aggiunge una regola FallBack specificata alla fine della collezione. |
| [remove(IFontFallBackRule targetRule)](#remove-com.aspose.slides.IFontFallBackRule-) | Rimuove la prima occorrenza di una regola FallBack specifica dalla collezione. |
| [get_Item(int index)](#get-Item-int-) | Ottiene la regola all'indice specificato. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la collezione. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore java per l'intera collezione. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia tutti gli elementi dalla collezione nell'array specificato. |
| [isSynchronized()](#isSynchronized--) | Restituisce un valore che indica se l'accesso alla collezione è sincronizzato (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Restituisce una radice di sincronizzazione. |
### FontFallBackRulesCollection() {#FontFallBackRulesCollection--}
```
public FontFallBackRulesCollection()
```


### size() {#size--}
```
public final int size()
```


Ottiene il numero di regole effettivamente contenute nella collezione. Solo lettura int.

**Restituisce:**
int
### add(IFontFallBackRule sourceRule) {#add-com.aspose.slides.IFontFallBackRule-}
```
public final void add(IFontFallBackRule sourceRule)
```


Aggiunge una regola FallBack specificata alla fine della collezione.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | Regola specificata da aggiungere |

### remove(IFontFallBackRule targetRule) {#remove-com.aspose.slides.IFontFallBackRule-}
```
public final void remove(IFontFallBackRule targetRule)
```


Rimuove la prima occorrenza di una regola FallBack specifica dalla collezione.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| targetRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | La regola da rimuovere dalla collezione. |

### get_Item(int index) {#get-Item-int-}
```
public final IFontFallBackRule get_Item(int index)
```


Ottiene la regola all'indice specificato. Solo lettura [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontFallBackRule> iterator()
```


Restituisce un enumeratore che itera attraverso la collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontFallBackRule> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontFallBackRule> iteratorJava()
```


Restituisce un iteratore java per l'intera collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontFallBackRule> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copia tutti gli elementi dalla collezione nell'array specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array di destinazione. |
| index | int | Indice iniziale nell'array di destinazione. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Restituisce un valore che indica se l'accesso alla collezione è sincronizzato (thread-safe). Solo lettura boolean.

**Restituisce:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Restituisce una radice di sincronizzazione. Solo lettura Object.

**Restituisce:**
java.lang.Object