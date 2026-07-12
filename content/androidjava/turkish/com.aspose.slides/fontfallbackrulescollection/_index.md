---
title: FontFallBackRulesCollection
second_title: Aspose.Slides for Android için Java API Referansı
description: Kullanıcı tarafından tanımlanan FontFallBack kurallarının bir koleksiyonunu temsil eder
type: docs
url: /tr/com.aspose.slides/fontfallbackrulescollection/
---
**Miras:**
java.lang.Object

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)
```
public class FontFallBackRulesCollection implements IFontFallBackRulesCollection
```

Kullanıcı tarafından tanımlanan FontFallBack kurallarının bir koleksiyonunu temsil eder
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FontFallBackRulesCollection()](#FontFallBackRulesCollection--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [size()](#size--) | Koleksiyonda gerçekte bulunan kural sayısını alır. |
| [add(IFontFallBackRule sourceRule)](#add-com.aspose.slides.IFontFallBackRule-) | Belirtilen FallBack kuralını koleksiyonun sonuna ekler. |
| [remove(IFontFallBackRule targetRule)](#remove-com.aspose.slides.IFontFallBackRule-) | Belirli bir FallBack kuralının koleksiyondaki ilk görünümünü kaldırır. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki kuralı alır. |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Tüm öğeleri koleksiyondan belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (thread-safe) olup olmadığını gösteren bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |
### FontFallBackRulesCollection() {#FontFallBackRulesCollection--}
```
public FontFallBackRulesCollection()
```


### size() {#size--}
```
public final int size()
```


Koleksiyonda gerçekte bulunan kural sayısını alır. Salt-okunur int.

**Döndürür:**
int
### add(IFontFallBackRule sourceRule) {#add-com.aspose.slides.IFontFallBackRule-}
```
public final void add(IFontFallBackRule sourceRule)
```


Belirtilen FallBack kuralını koleksiyonun sonuna ekler.

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | Ekleme için belirtilen kural |

### remove(IFontFallBackRule targetRule) {#remove-com.aspose.slides.IFontFallBackRule-}
```
public final void remove(IFontFallBackRule targetRule)
```


Koleksiyondan belirli bir FallBack kuralının ilk görünümünü kaldırır.

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| targetRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | Koleksiyondan kaldırılacak kural. |

### get_Item(int index) {#get-Item-int-}
```
public final IFontFallBackRule get_Item(int index)
```


Belirtilen indeksteki kuralı alır. Salt-okunur [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontFallBackRule> iterator()
```


Koleksiyon içinde yineleme yapan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontFallBackRule> - Koleksiyon içinde yineleme yapmak için kullanılabilecek bir IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontFallBackRule> iteratorJava()
```


Tüm koleksiyon için bir java iterator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontFallBackRule> - Tüm koleksiyon için bir java.util.Iterator.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Hedef dizi. |
| index | int | Hedef dizideki başlangıç indeksi. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Koleksiyona erişimin senkronize (thread-safe) olup olmadığını gösteren bir değer döndürür. Salt-okunur boolean.

**Döndürür:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Bir senkronizasyon kökü döndürür. Salt-okunur Object.

**Döndürür:**
java.lang.Object